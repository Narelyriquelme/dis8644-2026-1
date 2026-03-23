# sesion-02b

---

## Apuntes clase viernes 20 de Marzo

### <ins>Referentes</ins>

#### **Ángel Abusleme**
* Actualmente es un profesor asociado con la Universidad Católica, el cual tiene una especialidad en diseño electrónico, microelectrónica, microcontroladores y sistemas embebidos.
* Ángel llegó a hacer un doctorado en Stanford University, en donde participó en una defensa de tesis sobre el Bean: un procesador de pulsos para un experimento de física de partículas.
* En su doctorado falló su circuito, pero logró “operarlo quirúrgicamente” para que funcionara.
* A sus palabras, él no era más inteligente que sus alumnos, solo les gana en los años de experiencia y que cualquiera de ellos lo podría superar.

#### **Bob Widlar**
* Fue un ingeniero electrónico estadounidense y diseñador de circuitos integrados lineales
* Realizó una metodología que utilizaba transistores para reemplazar las resistencias, creando el primer circuito integrado lineal monolítico
* Él creía en el método Widlar, el cual consistía en romper los componentes que no funcionaran (terapéutico).

### <ins>Ley de Ohm</ins>

La fórmula que ya conocemos, que es *V = I * R* 
Un ejemplo seria:
9 V = I * 220 Ω

Para aislar I, dividimos 9/220

El resultado sería I = 0.04090909

Para expresar este valor en miliamperios, se multiplica el resultado por 1000

0.0409090 * 1000 = 40.91 mA

O simplificado sería 0.04 A * 1000 mA = 40 mA.

### <ins>Grafos topologicos</ins>
* Los nodos o imágenes usados para representar el circuito y los que mandaron de tarea no son más que grafos topológicos (representación visual de un sistema que utiliza nodos y aristas para mostrar relaciones y componentes).
* Por ejemplo, un cilindro pasaría como un círculo, haciendo una simplificación para que esto sea más fácil de leer o comprender.
* Los esquemas también se pueden realizar solo con letras, un ejemplo con circuitos sería A (bci | de).
* En nuestro caso usamos un esquema con conexiones cuadradas que terminan en tierra y empiezan por la alimentacion.
* Se podrían también hacer conexiones circulares y seguiría cumpliendo su propósito de simplificación y haciendo más fácil el entendimiento del camino de los circuitos.
* Me recuerda al sistema de nodos que usa TouchDesigner.

### <ins>Componentes entregados en clase y datos sobre estos</ins>

#### **Capacitor**
* Positivo/negativo, Negativo está en la parte negra gris del componente, además de tener el signo menos dibujado en esa parte.
* Entregaron 3 tipos: 1, 10 y 100 uF

#### **Condensador/Cerámica**
* 10 u / 10 nf
* La lenteja es capaz de estabilizar.

#### **Circuito integrado (IC)**
* Media luna 8 patas
* Originalmente es un timer o secuenciador
* Viene escrito 555 (específicamente es ne 555 e)
* Contar las patas en contra reloj, seria:

         1 8
          2 7  
           3 6
            4 5

#### **Resistores**
* Usaremos uno de 10K, los colores que contiene son 1 (café), 0 (negro) y 3 (naranja).


#### **Fotorresistor**
* Capaz de cambiar su resistencia eléctrica en base a la luz que le llega, al llegarle mucha luz, aumenta, y si le llega poca, reduce.

#### **Potenciometro**
* Puede cambiar la resistencia eléctrica dependiendo de qué tanto se gire la perilla que tiene.
* Tiene 3 patas, pero con solo 2 basta para que el potenciómetro funcione.

---

## Experimentación en el protoboard, luz LED parpadeante

### <ins>Uso de capacitadores</ins>
* Reemplace un resistor de 10 k por un capacitor de 10 uF, al hacer esto, la luz LED parpadea de manera más rápida.
* Remplace el capacitor de 10 uF a 100 uF, hizo que la luz parpadeara muy lento.
* Agregue un capacitor de 100 uF además del capacitor de 100 uF, esto hizo que la luz parpadeara mucho más lento que con solo uno de 100 uF.
* Removí los dos capacitores de 100 uF y agregué 2 capacitores de 50 uF para simular a un solo capacitor de 100 uF, el resultado no fue el mismo. Consulté con el profesor y nos dijo que nunca serán precisos los números entregados en los capacitores, por lo que dos de 50 uF tendrán el mismo resultado que uno de 100 uF.

### <ins>Uso de potenciometro</ins>
* Reemplacé la resistencia de 10 k por un potenciometro, al hacer esto, obtuve que, dependiendo de dónde se gire, hace que la luz LED parpadee más o simplemente deje de parpadear.
* Hay un punto preciso en donde la luz llega a parpadear muy rápido y, si la mueves un poco, simplemente ya no parpadea.

### <ins>Uso de fotorresistor</ins>
*Reemplacé la resistencia de 10 k por un fotorresistor, al hacerlo, la luz LED estaba parpadeando.
*Usé la linterna del celular en el fotorresistor y esto hizo que aumentara el parpadeo.
*Usé mi polerón para tapar la luz que le llegaba al fotorresistor y esto hizo que la luz parpadeara mucho más lento.

---

## Preguntas para la siguiente clase
* ¿Qué son los miliampereos?
* ¿Por qué el cambio de los capacitores hace que la luz LED parpadee más rápido o más lento?
* ¿Qué contiene el fotorresistor para que logre cambiar el parpadeo de la luz LED?
* ¿Qué son los uF?
* ¿Qué es un circuito integrado lineal monolítico?
* ¿Transistores pueden reemplazar la resistencia?
* ¿Se puede convertir el parpadeo LED en sonido en una protoboard?
* Si se le agrega algún botón, ¿se puede prender y apagar una luz LED?
* ¿Qué ocurre si el voltaje supera por mucho a un resistor?
* En el protoboard realizado con el circuito integrado, ¿qué ocurre si se reemplazan todos los resistores del grafo tipológico por un capacitor?
