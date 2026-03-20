# sesion-02b
## Apuntes
hoy dia nos entregaron otros componentes como el condensador, el ceramico, el fotoresistor y un circuito integrado ic, aqui su definicion:
### 1. Capacitor (Condensador)
​Es un componente diseñado para almacenar energía en forma de un campo eléctrico. Actúa de forma similar a una pequeña batería temporal: se carga cuando recibe corriente y se descarga cuando el circuito lo requiere. Se utiliza comúnmente para filtrar señales, estabilizar voltajes o bloquear el paso de la corriente continua permitiendo solo la alterna. 
### 2. Capacitor Cerámico
Es un tipo específico de capacitor que utiliza materiales cerámicos como aislante (dieléctrico). A diferencia de los electrolíticos, no tiene polaridad (puedes conectarlo en cualquier dirección) y suele tener una capacidad de almacenamiento más pequeña. Son excelentes para trabajar a altas frecuencias y se usan mucho para eliminar el "ruido" eléctrico en los circuitos.
### ​3. Fotoresistor
​Es un componente cuya resistencia eléctrica varía según la intensidad de la luz que incide sobre él.  
+ Mucha luz: La resistencia baja, permitiendo que pase más corriente.
+ Oscuridad: La resistencia sube, dificultando el paso de la corriente.
### 4. Circuito Integrado 555 (IC Chip)
​Es un chip de 8 pines diseñado para funcionar como un reloj o temporizador. Su función principal es encender y apagar una señal eléctrica durante intervalos de tiempo específicos que tú mismo puedes configurar usando capacitores y resistencias externas.

Se utiliza principalmente en dos modos:
+ ​Modo Monoestable: Funciona como un temporizador de "un solo disparo" (por ejemplo, presionas un botón y una luz se queda encendida 10 segundos y luego se apaga).
+ ​Modo Astable: Funciona como un oscilador constante (por ejemplo, hace que un LED parpadee continuamente) 

Es la pieza fundamental en dispositivos que se activan automáticamente al anochecer, como las luces de los postes de la calle. 

### apuntes de la clase

![Ejercicio 1](./imagenes/apuntes_2b.jpg)

hisimos un circuito con el chip ic 555 en donde la luz led parpadeaba porque el chip 555 está "vigilando" constantemente cómo se llena y se vacía el condensador, encendiendo y apagando la luz cada vez que el condensador llega a sus límites de carga, despues realisamos diferentes pruebas cambiando algunos componentes.

hicimos mas pruebas cambiando el condensador de 10microF primero por el de 100 cambiando la velocidad del parpadeo del led mas lento y al cambiarlo al de 1 la velocidad aumentaba mucho casi sin que se note que estaba parpadeando 

despues cambiamos el R2 primero por un potenciometro que hacia que se pudiera controlar la velocidad del parpadeo de las luz led y despues lo cambiamos po un fotoresistor que hacia que la intencidad de la luz aumentara o disminuia segun cuanta luz le llegaba al fotoresistor.

**Resumen de las Pruebas Realizadas**

​Llevamos a cabo una serie de experimentos modificando los componentes del oscilador astable para observar cómo afectaban el comportamiento del LED.


