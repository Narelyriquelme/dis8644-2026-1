# sesion-06b

Viernes 17 de Abril, 2026. 

Nota del día: queda una semana para la entrega final, estoy muy feliz con los resultados que logramos hoy como grupo !! 

## Referentes (y otras cosas)

- **Gijs Gieskes** es un artista, diseñador industrial y músico neerlandés reconocido por crear instrumentos electrónicos audiovisuales y máquinas experimentales. Su trabajo se sitúa en la intersección del arte, la tecnología y el diseño, destacando por su enfoque radical hacia la electrónica y el uso de componentes básicos para reinventar soluciones tecnológicas. - <https://www.instagram.com/gijsgieskes/> / <https://gieskes.nl/>
- **Frei Otto** fue un arquitecto e ingeniero estructural alemán, ganador del Premio Pritzker 2015, conocido por ser el pionero en el uso de estructuras ligeras y tensadas. Sus proyectos en Múnich son los ejemplos más emblemáticos de su filosofía, que buscaba imitar formas naturales como telarañas o pompas de jabón para crear espacios amplios con el mínimo material posible.  
- **Fungi metro tokio** En 2010, un equipo de investigadores de la Universidad de Hokkaido, liderado por Atsushi Tero, realizó un experimento, utilizaron un moho mucilaginoso para replicar la red de metro de Tokio. Aunque a menudo se le llama "hongo", técnicamente es un protista unicelular llamado Physarum polycephalum. 
- **Nery oxman** (mala persona) es una diseñadora, arquitecta e inventora estadounidense-israelí, conocida por fundar el campo de la Ecología Material. Su trabajo fusiona el diseño computacional, la fabricación aditiva (impresión 3D), la ciencia de los materiales y la biología sintética para crear estructuras que no solo se inspiran en la naturaleza, sino que crecen con ella. 
- **Paradojas del Nihilismo - CAPÍTULO I: Desilusión** _"¿Cuál es el sentido de la universidad? ¿Cuán profunda es la crisis de sentido de la institución? ¿Cómo opera el nihilismo en las instituciones y qué relación tiene con el cinismo e hipocresía de quienes la componen? El capítulo 1 introduce las temáticas que se abordarán en los siguientes: capitalismo cognitivo, ejercicios de poder, lucro, la figura del intelectual precarizado y un mercado multimillonario que supedita la creación de conocimiento a la generación de papers, que nadie lee. Un sistema que se compone de códigos precapitalistas como la jerarquía, el honor y el status, que en los últimos 30 años ha tenido que acomodarse a procesos y códigos de burocratización y acreditación neoliberal, que supeditan el trabajo intelectual al mercado. El capitalismo académico, que convive con la misma desilusión actual del modelo educativo, abre la pregunta sobre las posibilidades de emancipación y cambio, de un sistema que está protegido incluso de la crítica y  sustentado en pequeños actos de hipocresía que lo mantienen. "_- <https://youtu.be/_3cYAsJClEg>

## Qué hice hoy 

(Trabajo grupal)

Hoy Misaa nos presentó una nueva versión de la secuencia de 4 pasos vista en la clase pasada, pero con algunas modificaciones:

- Paso 1: Clock.
- Paso 2: Secuenciador.
- Paso 3: Sintetizador.
- Paso 4: Salida (audio).

![4pasosnuevo](./imagenes/4pasosnuevo.png)

Sin embargo, tuvimos varios problemas. Dejamos armada la conexión de la clase anterior y, al conectarla nuevamente a la corriente, ya no funcionaba, el LED no parpadeaba y no se generaba la secuencia de pasos.

Decidimos desconectar todo y volver a armar el circuito desde cero (para así tenerlo más ordenado también), pero el problema persistía. Finalmente, optamos por reemplazar el chip 555 por uno nuevo (dos veces), y eso solucionó la falla y la secuencia volvió a funcionar correctamente.

Luego pasamos a trabajar en los sintetizadores. Notamos que cada potenciómetro estaba afectando toda la secuencia de sonido, en lugar de operar paso a paso como esperábamos. Mientras intentábamos resolver esto, Misa nos sugirió que retiráramos los LEDs y sus respectivas resistencias de la secuencia en el paso 02 (que ya estaba funcionando). Al hacerlo, el problema se solucionó y ahora casa "step" era modificado por su propio potenciometro y generaba un sonido más disparejo (no igual en todo momento).

Con el sistema ya operativo, comenzamos a experimentar con los sintetizadores y condensadores para lograr un sonido que nos gustara para presentar como proyecto 01. Buscábamos un sonido más agudo, por lo que utilizamos condensadores de menor capacidad (1 µF), y logramos el resultado deseado. El sonido obtenido nos gustó mucho, ya que al menos a mi me recuerda a los juegos arcade antiguos. Aarón comentó que esto probablemente se debe al uso de ondas cuadradas (y repetitivas) y que el audio se escucha algo distorsionado. Ahora, el siguiente paso es encontrar una forma más precisa de describir y explicar este sonido, ya que no basta con decir simplemente que nos gusta.

![trabajoenclase](./imagenes/trabajoenclase.png)

videos del avance: (reproducir con audio!!)

https://github.com/user-attachments/assets/18822ace-0a86-40e5-b8be-09264a99a16d

https://github.com/user-attachments/assets/04e532cc-fa6f-4008-9e11-089d3ce75ca7

### Ideas generales (carcasa)

- Caja con forma de caja (como las de envío de paquetes, que tiene 4 solapas; la idea es hacer una réplica en miniatura donde adentro está el circuito).
- Caja con cables afuera (en forma de cubo; los cables del circuito pasan por afuera de la caja y después vuelven a entrar. En la cara trasera del cubo va la salida del parlante y en la cara de arriba van las perillas para modificar el audio).
- Caja con grabado/recorte tipo píxeles (referentes: <https://cl.pinterest.com/pin/12455336471122664/>).

> Definimos como grupo que el nombre del proyecto es: "La caja"
