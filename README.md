# Generador de Qr - Etiquetas para equipos en Reparacion

Este código esta basado en https://medium.com/@facucarbonel_97514/how-to-create-a-qr-generator-using-javascript-4b5ce1b6ec27
Se customizo para cumplir con los requerimientos de las etiquetas. 
Las etiquetas debían contener dos qr. Se resolvió la medida mínima de aproximadamente 12,5cm x 8cm (segun la impresora podía variar el ancho). Este tamaño era limitado por el tamaño mínimo de impresión en impresoras laser comunes. Esta opción resolvia el problema de tener que adquirir una impresora especial para estas etiquetas, y se podía utilizar alguno de los equipos con los que ya contabamos. 
Se utilizaron etiquetas antiguas, de resma continua (para impresora de matriz de puntos), recortandose a las medidas que se necesitaban.
Para completar, se debía configurar en las propiedades de impresión de la impresora un tamaño especial de hoja, como el especificado anteriormente.

Habíendo terminado la implementación, concluyó en un ahorro de dinero, al no realizar la compra de un equipo nuevo, repuestos para el mismo, y etiquetas especiales.
