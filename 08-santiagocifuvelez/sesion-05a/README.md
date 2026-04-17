# sesion-05a
07 de Abril del 2026

Hola Profe Aron, Misa y Emi. Espero que se encuentren bien el día en el que estén leyendo estos textos.
El día de hoy vamos a ver:  

1.	Simulador de Eurorack.  
2.	Abreviaturas y sus significados.  
3.	Todo es un ritmo y hay diferentes tipos de Ondas que componen estos.  
4.	Lógica de Boole
    
So, let´s start c:

## 1. Simulador de Eurorack.

![vcvrackkkk](https://github.com/santiagocifuvelez/dis8644-2026-1/blob/main/08-santiagocifuvelez/sesion-05a/imagenes/vcvrack.jpeg)

VCV Rack es una app en la web de síntesis modular virtual, inspirado en los sistemas de sintetizadores analógicos físicos (como los modulares Eurorack).

En pocas palabras, es una plataforma donde puedes crear sonidos desde cero conectando módulos virtuales . Cada módulo cumple una función específica (osciladores, filtros, envolventes, secuenciadores, etc.), y tú decides cómo conectarlos mediante “cables”, igual que en un sistema real. Lo interesante es que: no hay una única forma de uso: es totalmente abierto y experimental, permite entender de manera práctica cómo funciona la síntesis de sonido, se utiliza tanto para música electrónica como para diseño sonoro más experimental. 

Agregando a lo anterior, VCV Rack es como un “laboratorio digital” donde construye tus propios sintetizadores pieza por pieza y exploras cómo se genera y transforma el sonido.

## 2.	Abreviaturas y sus significados.  

Aquí tenemos unas abreviaturas utilizadas en VCV RACK, que nos ayudarán a entender las funciones de los elementos que tengan estas “iniciales”. 

**VC (Voltage Controlled)**  
Significa “controlado por voltaje”.  
Indica que un módulo responde a señales eléctricas (voltajes) para modificar su comportamiento. Por ejemplo, un parámetro como volumen o frecuencia puede cambiar automáticamente según un voltaje externo.

**VCO (Oscilador controlado por voltaje)**  
Oscilador controlado por voltaje.  
Es el módulo que genera el sonido base (ondas como seno, cuadrado, diente de sierra, etc.), y su frecuencia (tono) se controla mediante voltaje.

**LFO (Oscilador de baja frecuencia)**  
Oscilador de baja frecuencia.  
No se usa directamente para escuchar sonido, sino para modular otros parámetros (como vibrato, trémolo o movimiento en filtros). Genera señales lentas que crean cambios en el tiempo.
