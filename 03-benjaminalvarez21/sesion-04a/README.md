# sesion-04a

## 27 de marzo

Circuit simulator applet es un simulador de circuitos electrónicos se pueden guardar los archivos, modelar en falstad 

### link

<https://www-falstad-com.translate.goog/circuit/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es&_x_tr_pto=tc>

Si algo mide mil de algo es kilo

Si mide un millón de algo es MEGA

después el Giga tiene 6 ceros  y luego el tera que tiene 12 ceros

el uf que ponemos en la medida de los condensadores electrolítico es microfaradio y el nf que usamos en el condensador cerámico es nanofaradio

## pinout del chip

Pin 1 (GND): Tierra o negativo de la alimentación.

Pin 2 (Trigger/Disparo): Inicia la temporización cuando el voltaje cae por debajo de un tercio del vcc

Pin 3 (Output/Salida): Entrega la señal de salida (alto o bajo), capaz de suministrar hasta 200mA.

Pin 4 (Reset): Reinicia el temporizador. Si se conecta a negativo, el chip se reinicia; debe ir a vcc para funcionamiento normal.

Pin 5 (Control Voltage): Permite modificar los tiempos internos, usualmente conectado a un condensador a tierra para evitar ruido.

Pin 6 (Threshold/Umbral): Detiene la temporización cuando el voltaje supera.

Pin 7 (Discharge/Descarga): Descarga el condensador externo para reiniciar el ciclo de temporización.

Pin 8 : Alimentación positiva (4.5V - 15V)

## ejercicio en clase astable con monoestable

en este ejercicio unimos un circuito astable con un monoestable

![astable y monoestable](./imagenes/ejercicio-clase.png)

al inicio hicimos cada uno por separado, añadiendo parlante y con distintos resultados

![foto pizarra circuito con parlante](./imagenes/astable-monoestable-con-parlante.jpg)

https://github.com/user-attachments/assets/86e083c0-6bc7-4727-9de8-ffead0e39b0b

https://github.com/user-attachments/assets/5b5cb009-9445-4e97-b4d4-8eb0e591214b

al inicio no funciono pero teniamo un error que era que no teniamos conectados los protos entre si en la tierra (el positivo de la proto con la otra y el negativo de la proto con la otra), al conectarla obtuvimos este resultado

https://github.com/user-attachments/assets/7160ac8a-d62f-4c3d-a341-d12686352ad5

luego añadimos un potenciometro en el circuito astable que funcionaba para subir y bajar el volumen del sonido, aca este el resultado del astable solo y unido con el monoestable

https://github.com/user-attachments/assets/6e9d8837-71d4-41fa-8182-83874a938a13

https://github.com/user-attachments/assets/a0b89e35-d19b-4ca2-adda-2f31af42bfd0

## encargo

falta poner encargo
