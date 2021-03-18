# Extensión al OCDS para Contratos Marco
Extensión al OCD para incluir la información del tender referente a los contratos marco del gobierno federal mexicano.

## Ejemplo
```
{
  tender : {
    ...
    "frameworkAgreement" : true,
    "frameworkAgreementPlatform" : "Procura México, Tienda Digital del Gobierno Federal",
     "frameworkAgreementPlatform" : "The name of the base framework agreement"
    ...
  },
  
  contracts : [
    {
      ...
      "frameworkAgreementRequisitionNumber" : "REQ-2020-06-711-00000020"
      ...
    }
  ]
}
```

## Acerca de los contratos Marco
La Tienda Digital es el módulo de CompraNet a través del cual se llevan a cabo los procedimientos de contratación mediante el uso de catálogos electrónicos que contengan los bienes o servicios objeto de un contrato marco celebrado por la Secretaria de Hacienda y Crédito Público, con fundamento en los artículo 17 y 41 fracción XX de la Ley de Adquisiciones, Arrendamientos y Servicios del sector Publico (LAASSP) y 14 de su Reglamento.
 
Al tratarse de un contrato especifico derivado de un contrato marco no está sujeto al procedimiento de licitación pública.
 
Para mayor información respecto del módulo denominado “Tienda Digital del Gobierno Federal” visitar la página [https://compranet.hacienda.gob.mx/web/login.html](https://compranet.hacienda.gob.mx/web/login.html)