# sesion-04a #

>***Recordatorio, Ingresar la información y aprendisajes del libro _Code As Creative Medium_***
>
> ***Joya de la animación recomendada para ver y que me recordé de su existencia [https://www.youtube.com/watch?v=DKk2q89LyrA]***
>> Favor de ver el capitulo completo, buenas referencias que entendí gracias a esta clase

## Apuntes ##

La clase inicio con un pequeño resumen / repaso sobre algunos términos y conceptos, donde lo que más destaco es la tabla con las potencias de 10 (la cual tengo en mi bitacora física pero no tan bonita como acá) 

|                           | Potencia de 10  | prefijo | abreviatura |
| ------------------------- | --------------- | ------- | ----------- |
| 1 000 000 000 000 000 000 | $10^{18}$       | Exa     | E           |
| 1 000 000 000 000 000     | $10^{15}$       | Peta    | P           |
| 1 000 000 000 000         | $10^{12}$       | Tera    | T           |
| 1 000 000 000             | $10^{9}$        | Giga    | G           |
| 1 000 000                 | $10^{6}$        | Mega    | M           |
| 1 000                     | $10^{3}$        | Kilo    | k           |
| 100                       | $10^{2}$        | Hecta   | h           |
| 10                        | $10^{1}$        | Deca    | da          |
| 1                         | $10^{0}$        |         |             |
| 0.1                       | $10^{-1}$       | deci    | d           |
| 0.01                      | $10^{-2}$       | centi   | c           |
| 0.001                     | $10^{-3}$       | mili    | m           |
| 0.000 001                 | $10^{-6}$       | micro   | µ           |
| 0.000 000 001             | $10^{-9}$       | nano    | n           |
| 0.000 000 000 001         | $10^{-12}$      | pico    | p           |
| 0.000 000 000 000 001     | $10^{-15}$      | femto   | f           |
| 0.00 000 000 000 000 001  | $10^{-18}$      | atto    | a           |

<br>

Lo siguiente que revisamos fue una variación del circuito anterior (Un Astable que se conectaba a un Monostable), donde se inicia con un Monostable que llega a un Astable.

![Esquematico](./imagenes/esquematico.jpg)

![Protoboard](./imagenes/proto1.jpg)

![Protoboard](./imagenes/proto2.jpg)

![Protoboard](./imagenes/proto3.jpg)


1. Lo primero que debemos entender para llevar a cabo este circuito, es que hace cada uno
  
  a)  El Astable : En el output recibimos una corriente que alterna entre _on_ y _off_
 
  b)  El Monostable: Al presionar el interruptor la energía sigue circulando un tiempo desde que se suelta el switch.

2. Entonces para conectar el circuito _B_ al _A_ vamos a tomar el pin 3 del Monostable y conectarlo al pin _Reset_, es decir al n°4

3. Ahora cada vez que pulsemos el switch, la energía circula por un tiempo determinado donde el Astable, para luego emitir la corriente en ondas cuadradas hasta el parlante

> Una pequeña acotación es la particularidad del sonido, muy similar a como suena una ambulancia

<br>

### Falstad ###

Se nos enseño la web <https://www.falstad.com/circuit/>. Utilizada para visualizar de mejor manera que TinkerCad, ya que podemos ver como circula la energía en estas carreteras llamadas cables.

![Captura de pantalla](./imagenes/captura-de-pantalla04.png)

> Acá podemos ver como es la interfaz del sitio.
>
>> Abajo se pueden ver graficamente las ondas, en Inductores, condensadores, etc..
>>
>> Al lado se puede manipular aspectos de representación
>>
>> Arriba se observa todas las opciones disponibles

<br>

![Captura de pantalla](./imagenes/captura-de-pantalla03.png)

> En este apartado tenemos ejemplos de circuitos, opción bastante útil para aprender

<br>

![Captura de pantalla](./imagenes/captura-de-pantalla02.png)

> Este circuito es un ejemplo de un circuito _Oscilador con bajo ciclo activo_
>
> También se aprecia al mismisimo 555, pero con una _skin_ diferente (en la sesión anterior pudimos aprender esto)

<br>

![Captura de pantalla](./imagenes/captura-de-pantalla01.png)

> Ahora podemos apreciar las opciones para _Archivos_, donde destacan:
>
>> Exportar / Importar como formato de texto: Esto significa que mediante un mensaje podemos compartir diversos circuitos, sin necesidad de descargar un archivo
>>
>> Exportar como enlace: Formato más popular para compartir algo, pero el más volátil en mi opinión (esperemos que no desaparezca el servidor donde está el blog que tengo guardado hace 12 años xd)
>>
>> Exportar como SVG: Me parece fenomenal que exista esta opción, en cualquier momento estampo mi polera con el circuito _Atari Punk Console_
>>
>>> (Scalable Vector Graphics) es un formato de imagen vectorial basado en XML que permite escalar gráficos sin perder calidad ni pixelarse al ampliarlos.

<br>

![Captura de pantalla](./imagenes/captura-de-pantalla00.png)

> Ejemplo de como se ve el formato de texto

<br>

### Elementos a Investigar ###

Como es costumbre, dentro del bombardeo de preguntas que me surgen en clase hubo elementos que considero importantes rescatar:

1. Vimos los elementos internos del 555 y entendiendo que todo lo que hay dentro existe como componente _normal_ (como los que tenemos para usar en una protoboard), significa que se puede recrear desde 0. Además de poder hacerlo en Minecraft

> Un referente que se nos enseñó fue Evil Mad Scientist (el nombre me recorde al grupo criminal de cientificos MAD, de One Piece), quienes vendian un kit donde se recreaba un chip 555 de manera _artesanal_ o de mayor escala que el que tenemos, que cae en un dedo

2. Otro punto importante fue la unidad de medida _henrio_ (de Henry Joseph Henry), utilizada para medir la capacidad de un componente (como una bobina) para almacenar energía en un campo magnético. Un henrio se define como la inductancia de un circuito que produce una FEM (fuerza electromotriz) de 1 voltio cuando la corriente varía a 1 amperio por segundo.

> En palabras menos GPT, el henrio (H) se usa para medir la inducción 

3. Finalmente está el libro que traía la Emi, el cual le tome una fotografía para revisarlo de manera completamente legal y para nada en formato .pdf

![Libro](./imagenes/libro-emi.jpg)

 <br>

<br>

 ## Encargo ##

 Se nos solicito realizar una carnicería electrónica, la idea es desarmar un equipo electrónico y observar, analizar y cuestionarnos el como podría funcionar

 1. El kit utilizado para la operación de nuestro paciente

![Herramientas](./imagenes/desarme07.jpg)

<br>

 2. Nuestro paciente, un _Pioneer Cassette Deck Model CT-1040W_. Este equipo fue desechado a la basura un dia antes que se nos encargara esta tarea (la suerte me sonrie), por lo que se encontraba bien sucio la verdad

> La primera imagen corresponde a una fotografía de internet, puesto que no le tome fotos antes de iniciar
 
![Pioneer Cassette Deck Model CT-1040W](./imagenes/pioneer.jpg)

<br>

3. Iniciamos con la operación, dejando al paciente con su cerebro expuesto

![Desarme](./imagenes/desarme02.jpg)

![Desarme](./imagenes/desarme00.jpg)

![Desarme](./imagenes/desarme03.jpg)

> Podre utilizar esta imagen de excusa cuando digan que mi circuito no está ordenado (?)

<br>

![Desarme](./imagenes/desarme04.jpg)

Acá observamos los primeros elementos o como se compone, observando de momento 2 placas PCB

<br>

4. Empezamos a ver componentes algo llamativos

![Desarme](./imagenes/desarme05.jpg)

![Desarme](./imagenes/desarme06.jpg)

> Realmente lo más _fome_ conectores _dupont_ y un transformador de voltaje

<br>

![Desarme](./imagenes/desarme08.jpg)

![Desarme](./imagenes/desarme09.jpg)

![Desarme](./imagenes/desarme10.jpg)

![Desarme](./imagenes/desarme11.jpg)

<br>

![Desarme](./imagenes/desarme12.jpg)

> Apreciación de como no todo es perfecto, ni debe estarlo

<br>

![Desarme](./imagenes/desarme13.jpg)

![Desarme](./imagenes/desarme14.jpg)

![Desarme](./imagenes/desarme16.jpg)

![Desarme](./imagenes/desarme19.jpg)

![Desarme](./imagenes/desarme20.jpg)

> Una resistencia de 100 000 000 $\Omega$ 😲

<br> 

![Desarme](./imagenes/desarme21.jpg)

>En efecto, no se medir resistencias en multímetros

<br>

![Desarme](./imagenes/desarme22.jpg)

<br>

6. Recien terminada la primera placa, la cual fue un mundo de posibilidades y cosas nuevas. Iniciamos la etapa 2

![Desarme](./imagenes/desarme23.jpg)

![Desarme](./imagenes/desarme24.jpg)

![Desarme](./imagenes/desarme26.jpg)

> Algo fascinante es ver el como se generan soluciones tan creativas a algunas problematicas, en este caso esas piezas plásticas sirven para hacer contacto con los switch integrados a la placa

<br>

![Desarme](./imagenes/desarme28.jpg)

> Acá tambien se aprecia una solución similar, la diferencia radica en la distancia que existe desde el botón de la carcasa hasta la placa. Es llamativo pensar en como se prioriza la ubicación de la PCB por sobre sus conexiones, por ejemplo, mientras compañerxs realizaban el ejercicio me pude percatar como en un parlante la placa estaba diseñada de tal manera que cada switch estuviera a mm de la carcasa

<br>

![Desarme](./imagenes/desarme27.jpg)

>La buena confiable amarra plástica

<br>

![Desarme](./imagenes/desarme29.jpg)

![Desarme](./imagenes/desarme30.jpg)

![Desarme](./imagenes/desarme31.jpg)

> Capacitores XL
>
>> No me atreví a sacarlo ni nada, igualmente considerar que el equipo llevaba más de 10 años guardando polvo. Por lo que espero estuviera descargado

<br>

![Desarme](./imagenes/desarme32.jpg)

![Desarme](./imagenes/desarme33.jpg)

> Curioso, un chip con el simbolo Dolby, posibilidad que funcione para el audio 99%

<br> 

![Desarme](./imagenes/desarme34.jpg)

![Desarme](./imagenes/desarme35.jpg)

![Desarme](./imagenes/desarme36.jpg)

<br>

7. Luego de tanto componente, inicio la operación para analizar el lector de cassette

![Desarme](./imagenes/desarme37.jpg)

![Desarme](./imagenes/desarme38.jpg)

> Apreciación de mi área de trabajo

<br>

![Desarme](./imagenes/desarme39.jpg)

![Desarme](./imagenes/desarme40.jpg)

![Desarme](./imagenes/desarme41.jpg)

> Encuentro algo maravilloso el como lo mecánico convive y crea un ecosistema con lo electrónico

<br>

![Desarme](./imagenes/desarme42.jpg)

> Al ver esto me sorprendí, en mi ingenuidad juraba que los insertos roscados eran algo diseñados exclusivamente para la impresión 3D, el ver uno en un equipo de los años 90 fue llamativo

![Desarme](./imagenes/desarme43.jpg)

![Desarme](./imagenes/desarme44.jpg)

<br>

<br>

### Funcionamiento ###

Dentro de todo lo que observe del equipo, asumo que su funcionamiento se divide en 3 partes, es decir 3 cerebros, donde 2 de ellos procesan parte de la información y se la transmiten al tercero. La PCB número 1, que se ubica al abrir carcasa me hace creer que se encarga del mecanismo de los lectores de cassette, es decir que reciben un input de algún lado (spoiler abajo) y le dan las instrucciónes a elementos como los motores, y creo esto debido a que gran parte de los cables conectaban con partes mecanicas de estos

La 2da PCB, se encuentra próxima a la Interfaz (donde están los botones, perillas y todos esos elementos llamativos), considerando la ubicación y el hecho que posee muchos switch asumo que esta placa / cerebro se encarga de mediar las instrucciones o _inputs_ que se reciben, para luego enviarlos a donde corresponden

Finalmente la última se encarga del procesamiento del sonido, esta afirmación se basa en 3 puntos principales
-  Posee un chip con el simbolo Dolby
-  Tiene un conector RCA incluido
-  Es la única opción considerando el funcionamiento de las otras 2

En conclusión este stereo no es más que MEGA circuito (si, un circuito x 1 000 000), ya que posee distintos centros de procesamiento que se conectan entre sí, una manera más refinada de la lógica detrás de conectar un Astable y un Monostable.

<br>

#### Definiciones más técnicas ####

Se realizó una tambla comparativa sobre tipos de chips vistos acá. Con ayuda de mi mejor amigx Gemini 

<br>

##### Prompt: #####

"Me encuentro desarmando un Stereo cassette Tape Deck Magnetophone a cassette Stereo Modelo No. Ct- 1040w



Dentro encontré los siguientes chips:

- PD4029
- D824HH
- D4069UBC
- D82435C
- HD14066BP
- HA11226 (Posee el simbolo Dolby)
- IR2C30
- M5218L (Posee simbolo Mitsubishi)



Quiero que hagas una tabla en la que se abarquen los siguiente puntos:



- Modelo: de que chip hablamos
- Que hace: explicación del funcionamiento
- Para que se usa: Que se especifique que funcion podria cumplir en este dispositivo"

<br>

##### Resultado #####

# Análisis de Componentes: Stereo Cassette Tape Deck CT-1040W

Este documento detalla la función técnica de los circuitos integrados encontrados en el Magnetophone a cassette **Modelo No. CT-1040W**.

---

## Tabla de Componentes

| Modelo | Descripción Técnica | Función en el Dispositivo |
| :--- | :--- | :--- |
| $PD4029$ | Contador binario/decimal preseteable de $4$ bits. | Control de la lógica del contador digital de cinta y gestión de estados de transporte. |
| $D824HH$ | Transistor de potencia / Regulador de voltaje. | Suministro de corriente estable para los motores $DC$ y el sistema de iluminación. |
| $D4069UBC$ | Seis inversores lógicos ($Hex Inverter$). | Procesamiento de señales de control y generación de la frecuencia de $Bias$ para grabación. |
| $D82435C$ | Microcontrolador de funciones lógicas de transporte. | Coordinación de solenoides y motores al activar $Play$, $Stop$ o $Rewind$. |
| $HD14066BP$ | Interruptor cuádruple bilateral ($Quad Analog Switch$). | Conmutación electrónica entre los modos de entrada ($Line In$) y salida ($Playback$). |
| $HA11226$ | Sistema de reducción de ruido $Dolby \ B$. | Procesamiento de la señal para reducir el siseo ($Hiss$) en altas frecuencias. |
| $IR2C30$ | Driver de escala logarítmica para visualización. | Procesamiento de la señal de audio para el movimiento de los $VU$ meters (Agujas/LEDs). |
| $M5218L$ | Amplificador operacional dual de bajo ruido. | Preamplificación de la señal analógica proveniente del cabezal magnético ($Head$). |

---

## Detalles Técnicos Relevantes

### 1. Procesamiento de Audio
El chip **$M5218L$** de Mitsubishi actúa como la primera etapa de ganancia. Es crucial para mantener una relación señal-ruido ($\frac{S}{N}$) óptima antes de pasar al sistema **$Dolby$**.

### 2. Sistema de Reducción de Ruido
El **$HA11226$** implementa el algoritmo de compresión/expansión de $Dolby \ B$. Durante la reproducción, actúa como un filtro dinámico que atenúa las frecuencias superiores a los $1 \ kHz$ donde el ruido de la cinta es más perceptible.

### 3. Conmutación y Lógica
El uso del **$HD14066BP$** permite que el dispositivo cambie de estado sin necesidad de interruptores mecánicos largos que podrían introducir interferencias electromagnéticas ($EMI$) en la ruta de audio.

---

> **Nota de mantenimiento:** Los integrados de la serie $4000$ ($PD4029$, $D4069$, $HD14066$) son tecnología $CMOS$ y presentan una alta impedancia de entrada, lo que los hace vulnerables a descargas electrostáticas ($ESD$).
