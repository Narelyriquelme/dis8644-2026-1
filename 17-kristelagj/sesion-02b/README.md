# sesion-02b

## clase 200326

### pre-clase (teloneo Aaron)

Referentes:
1. Hainbach
2. Cocoquantus
3. Zizifo
4. Texas instruments

**Bob Widlar:** Wilarización es cuando algo te traiciona y lo rompes para que nunca más lo haga

¿Qué es 8 bits?

Ocupar tinkercad si no me funciona el sistema original

### clase

- Primera parte: Aaron

- Segunda parte: Misaa


### imagenes de proceso

### post-clase

Comencé a realizar de nuevo el ejercicio número 3, ahora logré encender la D1, pero no D2. No me puede ganar. 

Compre unas bolsas para ordenar por piezas entregadas, ya que así tengo un orden y sé que tengo de cada cosa (no tendré que comenzar la búsqueda del tesoro)

Por otro lado, se reconoce cada elemento que se nos entregó de manera visual, pero nombres y que hacen, no muy bien, entonces me dedique a revisar los apuntes de mis compañeros para poder encontrar nuevas cosas y hacer una guía de que es cada cosa agregando mis apuntes (quiero agregar datos que quizás yo no tengo o encontré y que me ayuden a entender)Quiero encontrar una manera de hacer algún manual que yo entienda de lo que hemos visto y de cada pieza de este puzzle. 

La corriente eléctrica es el flujo de cargas eléctricas (normalmente electrones) que se mueven a través de un material.

**Ley de Ohm:** Intensidad de la corriente (I) mientras más corriente, más electrones pasando, la diferencia de potencial (el voltaje (V)), y resistencia (R) que tán fácil o tan difícil es para mi conducto dejar pasar lo que quiera, la resistencia no tiene polaridad. El resultado de ésto queda en la ecuación I (ampere) = V (voltios) / R (ohm).

Esta establece que la corriente que circula por un conductor es directamente proporcional al voltaje e inversamente proporcional a la resistencia. Siguiendo la Ley de Ohm, deberíamos conectar el cable de alimentación a los buses positivo y negativo. Luego, conectar la resistencia en las entradas verticales y de ahí conectar al LED. Es vital fijarse en la polaridad. Si se sigue ese orden, el LED se encenderá.

Si el voltaje aumenta, la corriente aumenta.
Si la resistencia aumenta, la corriente disminuye.


Tipos de circuitos

**Circuito eléctrico:** Lazo cerrado que pasa por elementos resistivos

**Circuito paralelo:** es independiente. Es una configuración donde los componentes (resistencias, bombillas) comparten los mismos nodos de entrada y salida, creando caminos independientes para la corriente. El voltaje es igual en todos los componentes, mientras que la corriente total se divide entre las ramas. Si uno falla, los demás siguen funcionando.

**Circuito en serie:** circuito en serie: Es una configuración eléctrica donde los componentes (resistencias, bombillas, etc.) se conectan uno tras otro, creando un único camino para la corriente eléctrica. La intensidad de corriente es constante en todo el circuito, mientras que el voltaje total se distribuye entre los componentes y la resistencia total es la suma de las unidades individuales. 

Abreviaciones

GND = Ground (Negativo/0V)
Por la tierra (Grounding)
VCC/BT = Voltaje de alimentación
Batería
R = Resistor
D = LED
Diodo

Elementos para realizar el circuito

**Protoboard:** también conocida como o breadboard es una placa con muchos orificios interconectados internamente. Sirve para armar y probar circuitos de forma temporal: insertas los componentes y cables DuPont en ella sin usar soldadura.

La protoboard se divide en partes y polos:

Polos: Positivo y negativo, los cuales tienen buses metálicos de manera horizontal esto ayuda a que toda esa línea tenga un polo completamente + o - 
Nodos de conexión: Las entradas centrales están conectadas de manera vertical esto ayuda a que solo esa línea la cual se le está pasando la energía sea de un cierto polo.  

**Resistencia:** se mide en OHM y están realizadas de carbón por su nivel limitando así el paso de la corriente eléctrica las resistencias. No tienen polaridad entonces no importa en qué dirección se coloca. Controla el flujo de electrones.  Sirve para proteger otros materiales (como los LED) para que no se quemen al recibir demasiada energía. Depende de la resistividad del material, la longitud del conductor y su área transversal.A mayor resistencia, menor corriente pasa, generando calor como efecto secundario.

Para poder identificar la dirección nos guiamos por el dorado que irá al último. Los primeros dos colores son dígitos; el tercer color es la cantidad de ceros, por ejemplo, rojo-rojo-café-dorado es igual a 220 Ω, ya que el rojo equivale a 2, y el café a 1, indicando que solo hay un cero. 

Resistencia eléctrica
Un material se opone al paso de la electricidad

Cable más largo → más resistencia
Más chico el área → más resistencia
Más grande el área → menos resistencia

Ejemplo para entender

Electricidad = agua
Material = tubo

Tubo ancho → pasa fácil → poca resistencia
Tubo angosto → cuesta → mucha resistencia
Siempre hay algo de resistencia

**LEDs (Light Emitting Diode):** Es un diodo que emite luz cuando la electricidad pasa a través de él. Sirve como indicador visual (encendido/apagado) o para iluminación básica, consumiendo muy poca energía. Dienen un lado positivo ánodo (+) y cátodo (-). Tiene polaridad.

Diodo es un componente electrónico semiconductor que actúa como un interruptor unidireccional, permitiendo que la corriente eléctrica fluya en una sola dirección (polarización directa) y bloqueándola en la contraria (polarización inversa). Tiene dos terminales: ánodo (+) y cátodo (-), y es esencial para rectificar, regular y proteger circuitos
¿Cómo reconocerlas?

Terminal largo es positivo y terminal corto es negativo
En la parte superior del LED se encuentran 2 triángulos, en donde e grande es el negativo, mientras que el pequeño es el positivo
Tocar la cabeza del LED, y cuando sientas una parte plana, significa que ese lado es el negativo, mientras que el redondo es el positivo.

**Cables dupont:** Son cables flexibles con conectores en los extremos que sirven para unir componentes en una placa de pruebas sin necesidad de soldar. Son el "pegamento" que comunica todas las piezas de tu proyecto.
No existe un material conductor absoluto.. Los de cobre son los conductores por excelencia.

**Batería:** ​Es un dispositivo que convierte energía química en eléctrica. Sirve como la fuente de energía (el "alimento") para que tu circuito pueda funcionar sin estar conectado a un enchufe.

**potenciómetro B100k:** Es una resistencia variable. Sirve para que tú puedas controlar manualmente la intensidad de algo, como subir el volumen de un parlante o variar el brillo de una luz LED al girar su perilla. Mide la potencia. Tiene un comportamiento lineal.
La letra "B" indica que el cambio de resistencia es constante y proporcional al giro de la perilla, controla la intensidad de luz o tono. Resistencia variable de 100kΩ 

**chip ic:**  Es una pastilla de silicio que contiene miles de componentes diminutos en su interior . Sirve para realizar funciones complejas (como procesar datos o amplificar sonido) en un espacio muy reducido. Contador de secuencialidad. Se coloca entorno al eje céntrico de la proto (tiene transistores dentro)

**un broche de batería:** conecta la batería al circuito Rojo: Poder (arriba) Negro: Tierra (abajo) 

### Reflexiones
