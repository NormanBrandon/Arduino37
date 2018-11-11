# **Motores**
## ¿Qué son los motores?
Una definicion formal es la siguiente
> Un motor es la parte sistemática de una máquina capaz de hacer funcionar el sistema, transformando algún tipo de energía 
(eléctrica, de combustibles fósiles, etc.), en energía mecánica capaz de realizar un trabajo. 

En otras palabras, una maquina que produce movimiento a partir de algún tipo energía para realizar cualquier tarea.
¿Poqué vemos motores en este curso?, porque una de las aplicaciones mas comunes de Arduino es el control, y como lo que queremos es tener control con sistemas fisicos y no solo virtuales necesitamos de estos elementos que tienen inumerables aplicaciones.

## Tipos de Motores
Se pueden clasificar por distintas caracteristicas como: Por el tipo de energía que convierten o Por el tipo de movimiento que generan.
Vamos a verlos por el tipo de energia que convierten
* ### Motores de Combustión Interna
Un motor de combustión interna es un tipo de máquina que obtiene energía mecánica directamente de la energía química de un combustible que arde dentro de una cámara de combustión. Su nombre se debe a que dicha combustión se produce dentro de la máquina en si misma, a diferencia de, por ejemplo, la máquina de vapor.
![Motor de Gasolina(ro-des.com)](https://img1.ro-des.com/wp-content/uploads/2014/11/mot-gasolina-ciclo_2.jpg)
* ### Motores Electricos
El motor eléctrico es un dispositivo que convierte la energía eléctrica en energía mecánica por medio de la acción de los campos magnéticos generados en sus bobinas. Son máquinas eléctricas rotatorias compuestas por un estator y un rotor.

![Motor electrico(areatecnologica.com)](https://images-na.ssl-images-amazon.com/images/I/61qyjtv0KkL._SX425_.jpg)
Se conforma de 5 principales partes
* Rotor : parte del motor que gira, aqui hay un bobinado(cables enrrollados) que producen un campo magnetico
* Estator : parte del motor que permanece estatica, en los motores DC tiene imanes con un campo magnetico fijo, y los AC tiene un segundo bobinado
* Eje : este esta unido al Rotor para girar con él, es el que transmite el movimiento al exterior
* Escobillas : Son las que conectan al Rotor y las terminales electricas para transmitir la energia electrica
* Carcasa : Es la que cubre al motor y sobre la que se montan todas las piezas
![Motor electrico(areatecnologica.com)](http://www.areatecnologia.com/electricidad/imagenes/partes-de-un-motor-electrico.jpg)

Los motores que usaremos en este curso son los motores DC, es decir aquellos que funcionan con corriente continua (el tipo de corriente que proporciona una pila, o el cargador de tu celular). ¿pero que tiene de especial el motor DC?, pues que es muy facil de usar y podemos controlar mas variables de las que podemos controlar usando alguno de los motores anteriores. 

## ¿Qué variables podemos controlar?
* Velocidad
* Dirección de giro
* Encendido/Apagado
* Posicion (solo Servomotores)
* Pasos (solo en Motores a Pasos)
Y como las controlamos? , pues con nuestro sistema de control Arduino. ¿Entonces lo podemos conectar al Arduino asi nada mas y ya funciona?¿Cómo un led?; pues no exactamente
