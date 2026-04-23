# grupo-01

## integrantes

- Vanessa Garcia (vanessagarciaM)
- Ariel Orozco (arielorozco024)
- Narely Riquelme (Narelyriquelme)

## descripción del sintetizador realizado

El proyecto consiste en un sintetizador secuencial de cuatro pasos, construido con componentes electrónicos básicos. Utiliza los integrados NE555, CD4017, CD4093 y LM386, junto con potenciómetros, resistencias, capacitores cerámicos y electrolíticos, un parlante y una fuente de alimentación mediante batería de 9 V. Está montado sobre una protoboard con cables Dupont.

El circuito utiliza un temporizador NE555 configurado como oscilador para generar una señal de reloj, la cual determina el ritmo del sistema. Esta señal se envía al CD4017, que activa de forma secuencial distintas salidas en respuesta a los pulsos del reloj. Estas se conectan a las entradas de las compuertas del CD4093, permitiendo activar cada oscilador uno por uno. De este modo se generan distintas frecuencias, que varían según los capacitores, produciendo sonidos electrónicos tipo onda cuadrada.

Finalmente, la señal generada es enviada a un amplificador de audio basado en el integrado LM386, que permite aumentar la potencia de la señal para que pueda ser reproducida por el parlante. En conjunto, el circuito permite generar secuencias de sonidos rítmicos y melódicos mediante la coordinación entre la señal de reloj y los osciladores.

![sintetizador](./imagenes/img-sintetizador.jpeg)


https://github.com/user-attachments/assets/905e3b0a-8652-41ce-81cf-a35a47ac748d



## proceso y resultados del reloj y secuenciador

Logramos comprender y ensamblar el circuito de reloj y secuenciador que transforma pulsos eléctricos en un ciclo visual continuo, dividiendo el trabajo en dos etapas principales. Por la parte izquierda del diagrama armamos el generador de reloj utilizando un temporizador 555 configurado en modo astable, el cual emite un pulso constante de voltaje por su pin 3; comprobamos que el ritmo de estos pulsos lo podemos controlar y hacer más rápido o más lento simplemente ajustando el condensador C1 y la perilla del potenciómetro. Luego, conectamos esta señal a la parte derecha del circuito, donde usamos un chip contador de décadas CD4017 como secuenciador. Al hacer que el pulso del 555 entre al pin 14 del 4017, logramos sincronizar ambos componentes: cada latido le indica al 4017 que avance un paso, activando en orden las salidas Q0 a Q3 (pines 3, 2, 4 y 7).  Como resultado final, conseguimos que los 4 LEDs conectados a estas salidas se enciendan uno por uno en fila, creando un ciclo visual infinito!.

**Imagenes del proceso**
![Esquematico](./imagenes/esquematico555-4017.png)
![Resultados](./imagenes/img555-4017.jpeg)
![Resultados](./imagenes/gif555-4017.gif)

## proceso y resultados de osciladores y amplificador

Código de colores propuesto para facilitar la organización y comprensión del circuito.
+ STEP 1: Amarillo  
+ STEP 2: Verde  
+ STEP 3: Azul 
+ STEP 4: Morado

**Pruebas realizadas**

En el primer intento de realizar el circuito, las dos primeras etapas funcionaron correctamente. Sin embargo, surgieron problemas en las conexiones entre el chip 4093 y los potenciómetros, ya que solo se generaba una señal de onda cuadrada de frecuencia constante y no coincidía con el movimiento de las luces. Además, al ajustar los potenciómetros no se producía ningún cambio en la frecuencia del sonido, lo que indicaba un funcionamiento incorrecto del circuito. Durante el proceso, el chip 4093 se dañó. 

En un segundo intento, se volvieron a realizar las dos últimas etapas del circuito. Sin embargo, el comportamiento fue similar al de la prueba anterior. Con el tiempo, se observó que el circuito solo generaba señal de audio al hacer contacto con algún cable o componente, lo que indicaba un funcionamiento inestable en las conexiones. 
En la tercera prueba, se evaluó cada STEP de forma individual. Sin embargo, en todos los casos se observó la misma situación, ya que la frecuencia se mantenía constante y no presentaba relación con las variaciones observadas en los LED. 

Al conectar todo el circuito, se observa una variación en la frecuencia, por lo que deja de ser constante. Esta se mantiene sincronizada con los tres primeros LED; sin embargo, al pasar al cuarto se produce un desfase, y a partir de ese punto dejan de estar coordinados.  
Se sustituyó el chip 4093 y, al encender el dispositivo con el nuevo componente, se observaron variaciones en la frecuencia del sonido. Al manipular los potenciómetros, fue posible generar distintos tonos. Se aprecia una relación entre la frecuencia y los LED en STEP 1 y STEP 2, pero a partir de ese punto el funcionamiento pasa a ser continuo. 
Sin embargo, dejó de funcionar la primera etapa. Se revisaron las conexiones, pero el problema persistía, ya que el circuito quedaba fijo y no había secuencia en las luces, a menos que se desconectara y volviera a conectar el cable negativo. Por lo tanto, se reemplazó el chip 555 y el circuito volvió a oscilar.

**Resultados obtenidos**

Después de realizar múltiples pruebas, hicimos funcionar el circuito guiándonos exactamente por el esquemático original. Conseguimos que los cuatro steps se activaran con sus sonidos correspondientes y logramos sincronizarlos a la perfección con el ritmo del reloj. Una vez que el circuito estaba funcionando, comenzamos a experimentar con él, descubriendo una amplia gama de sonidos y múltiples posibilidades creativas.

## modificaciones realizadas a los circuitos originales

Se realizaron primeras pruebas y cambios de capacitores de forma individual, colocando resistencias en los LED para activar solo el STEP deseado y así poder definir el sonido ideal.
+ STEP 1: de 1 µF a 10 µF, el tono es más bajo y grave.
+ STEP 2: de 1 µF a 100 µF, el tono es aún más grave que con 10 µF.
+ STEP 3: de 1 µF a 100 nF, el tono es más agudo.
+ STEP 4: de 1 µF a 0,47 nF, el tono es más lento.
+ STEP 4: de 0,47 nF a 10 nF, el tono es mucho más agudo.

Se realizó una prueba con un fotoresistor, donde el sonido se generaba solo por un momento, aproximadamente 2 segundos. Para que volviera a sonar, era necesario ajustar el volumen.

**Modificaciones finales** 

Agregamos un nuevo capacitor de 100 uf en la patita 5 donde estaba conectada el primer capacitor, para poder así conectar un nuevo parlante, los cual funcionó correctamente

Se definió el sonido y los capacitores a utilizar:
+ STEP 1: 1 µF
+ STEP 2: 100 nF
+ STEP 3: 100 nF
+ STEP 4: 1 µF

## carcasas de cartón

La construcción se plantea como un sistema modular, formando la figura de un “robot” llamado Rodolfo, en el cual se organiza el circuito de una forma fácil de comprender y manipular.

Rodolfo se compone de cuatro módulos que almacenan distintas partes del circuito. En la cabeza se ubican el reloj y el secuenciador. Esta sección es la encargada de generar y organizar los impulsos eléctricos que determinan el ritmo y la activación del resto de los componentes.

El torso concentra los osciladores, que son responsables de generar las señales sonoras. Su ubicación en el centro permite una distribución más eficiente de las conexiones hacia las otras partes.

Los brazos, ubicados a ambos lados, contienen los amplificadores. Estos módulos toman la señal generada en el torso y la potencian, permitiendo que el sonido sea audible y tenga mayor presencia.

## interconexión entre módulos

textos, imágenes, diagramas de interconexión

## resultados finales

texto

imagen

video / audio

## aprendizajes y errores

A lo largo del proyecto se cometieron diversos errores que afectaron el desarrollo y funcionamiento del circuito. En primer lugar, las baterías no siempre estaban bien cargadas, lo que dificultó la identificación de otras fallas. Además, se presentaron confusiones con los nombres de los chips, por lo que en un inicio se utilizaron componentes equivocados. Específicamente, se confundió el chip 386 con el 555, lo que provocó que este último se quemara. A esto se suma que uno de los chips fue instalado en una posición incorrecta, lo que obligó a revisar nuevamente el circuito.

A partir de estos errores, se logró comprender la importancia de organizar de forma adecuada las conexiones entre los componentes, con el fin de facilitar la lectura del circuito. Asimismo, fue necesario verificar el estado de las baterías y aislarlas para evitar el contacto con otros componentes y su descarga, previniendo así diagnósticos erróneos. Por último, también se volvió fundamental comprobar que cada componente sea el correcto y que esté funcionando adecuadamente antes de integrarlo al sistema.

## conclusiones

En conclusión, el desarrollo del proyecto nos permitió construir un circuito funcional y modular, comprendiendo de mejor manera su funcionamiento a lo largo del proceso. La división del sistema en módulos facilitó tanto la comprensión como la manipulación del circuito, permitiendo realizar correcciones de forma independiente en cada etapa. Las pruebas y errores fueron fundamentales, ya que nos entregaron aprendizaje constante y nos ayudaron a avanzar hasta lograr un resultado correcto.

Comprender el funcionamiento y la correcta disposición de los componentes electrónicos facilitó la lectura del circuito y la resolución de problemas. Además, mantener un orden en el uso de colores en las conexiones aportó claridad durante la construcción, permitiendo identificar errores de forma más rápida.

Por otra parte, la materialidad del proyecto, representada en la forma de un robot, ayudó a visualizar la relación entre las distintas etapas del circuito, favoreciendo una mejor organización de los componentes y su distribución.

Finalmente, el trabajo en equipo fue fundamental durante todo el proceso. Trabajar de manera conjunta en cada etapa permitió compartir ideas, detectar errores y proponer soluciones de forma colaborativa, donde el apoyo mutuo fue clave para el desarrollo y finalización del proyecto.
