# Uipath
Arreglo con txt en uipath



String.Format(query,COLUMN04,COLUMN07,COLUMN09)


'String.Format("ARCHIVO EJEMPLO TXT URL",VARIABLES 0,VARIABLES 1,VARIBLES 2)'

'↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓

'EJEMPLO DEL ARCHIVO TXT 
'UPDATE [TMSTuria].[App].[Shipments]
SET PriceDatAvg = '{0}',
OriZipCode = {1}
where ShipmentId = {2}
