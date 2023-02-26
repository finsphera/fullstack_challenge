Con el archivo dbase.js realizar los siguientes dos calculos:

1. response = ((Efectivo en Caja y Depósitos en Instituciones de Crédito Nacionales + 
Efectivo en Caja y Depósitos en Instituciones de Crédito del Extranjero + 
Inversiones en Valores Instituciones Nacionales + 
Inversiones en Valores Instituciones Extranjeras + 
Cuentas y Documentos por Cobrar (Total) + 
Cuentas y Documentos por Cobrar del Extranjero (Total) + 
Contribuciones a Favor + 
Otros Activos Circulantes)
-
Inventarios) 
/ 
( Cuentas y Documentos por Pagar Nacionales (Total) + 
Cuentas y Documentos por Pagar del Extranjero (Total) + 
Contribuciones por Pagar + 
Anticipos de Clientes (Total) )

2. Creando una función ( o lo que consideres mejor) de la siguiente tabla 
definir a que valor del catalogo le corresponde response

  response >= 1.5 entonces es 10
  response >= 1.25 y response < 1.5 entonces es 9.75
  response >= 1 y response < 1.25 entonces es 9.5
  response >= 0.75 y response < 1 entonces es 9.25
  response >= 0.5 y response < 0.75 entonces es 9
  response < 0.5 entonces es 8.75
