# finder
finder project

## DESCRIPCION

Descripcion del proyecto
 Proyecto para la creacion de un buscador de objetos, utilizando una Bosina


|Item|Respuesta|
|----|-------|
|Nombre de proyecto|Finder|
|Case|Sensor: tarjeta ESP32, con la utilzacion de una bosina |
|Solar o alimentación alternativa|Batería lipo, de carga normal para dispositivos de alerta|
|Entrada de datos por el usuario|Para activar la bosina, el usuario final debe habilitar un punto de acceso, con el ssid y el password indicado en el documento|
|Etapas: 1.|Prueba : Solo un finder que con la configuracion de acceso a intenert para que se active la bosina, un dispositivo de alerta. |
|2.|Producción : Agregar la funcionalidad de la bateria externa|
|3.|Futuro: Disminuir el tamano de los componentes a utilizar para que sea accesible y demas utilidad y con esto iniciar la produccion en masa
|Hardware: Dispositivo Sensor|TTGO-ESP32 con pantalla, batería lipo|
|Hardware: Dispositivo de Alerta|Bosina , batería, cargador inductivo. Alertas visuales y auditivas a definir.|
|Posibles problemas|Que se encuentre una red wireless y que se altere la bosina|


## COMO ENSAMBLAR

Se debe colocar el cable de corriente al ping de voltage de la ttgo y de tierra en el pin de tirra de la ttgo, ademas colocar el pin de la bosina en el pin 16 de la ttgo.


## COMO CARGAR EL SOFTWARE 

Se debe cargar la libreria  Tone-master y cargar el software finder a la tableta ttgo. 


##  Se documenta el uso general del proyecto

Para que se inicie el buscador se debe configurar un AP (Punto de acceso) en con el ssid p20 y la contrasena 123456789 para que el sensor se active. 


