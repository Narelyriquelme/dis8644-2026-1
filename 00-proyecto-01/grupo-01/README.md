# grupo-01

## integrantes

- Bruno Ferrari // chknngttts
- Martina Echavarría // martinaechavarria-stack
- Lucas Ortiz // ryukivol

## descripción del sintetizador realizado

Al hablar como grupo sobre lo que queríamos hacer, pensamos en distintos synths y nos interesó mucho hacer uno que lograra producír sonidos más parecidos al noise (como genero musical). Al buscar "Pink/Brown/Blue/Drone noise generator" en internet, encontramos uno en un forum de electronica y circuitos llamado "https://electro-music.com". El circuito utilizaba componentes que ya aprendímos en clase pero permitía hacer nuevos sonidos. 

El "NANDulator - PHOBoS" utiliza un 4093* para generar el sonido. Dentro del esquematico en la pagina no muestran como amplificar la señal para que se pueda escuchar, por lo que decidimos añadir un LM386, conectando el pin 4 del 4093 al pin 3 del LM386. Eso si al utilizar el synth, sentimos que faltaba algo para poder modular más el sonido, por lo que añadimos un filtro de "https://generalguitargadgets.com" entre la salida del 4093 y el AMP. Consiste en 2 filtros R/C y un linear pot (todo conectado a un potenciómetro) que permite controlar el Dry/Wet del filtro, actuando como un EQ. 

En cuanto a modificaciónes de los circuitos base, en el Schmitt Trigger del pin 4-5-6 cambiamos el potenciómetro de 500k a 100k **CORROBORAR!!! CREO QUE ESTOY MINTIENDO**. En el filtro, cambiamos la resistencia de 39k por una de 36k (o 33k)**CORROBORAR!!! CREO QUE ESTOY MINTIENDO**, más que nada por la accesibilidad a materiales en el laboratorio y porque la variación de la resistencia es muy baja y no impacta el sonido final. 

*4093
  - El creador del NANDulator actualizó en su forum que distintos 4093 creaban resultados variados. Dependiendo de la empresa del chip, el circuito podía o no funcionar a corde a lo que tenia pensado el creador. Uno de los IC's que no funcionaba supuestamente es el CD4093 de Texas Instruments, que es el que utilizamos para el synth. De igual manera estamos contentos con el resultado, nos interesaría averiguar las variabilidades en sonido intercambiando el chip con otros de distintas empresas.

imagen del sintetizador en su contexto

![Esquemático Original del NANDulator](./imagenes/nandulatorplanosoriginales.gif)

audio o video del sintetizador en acción

## proceso y resultados del reloj y secuenciador

con chips 555 y 4017

incluir texto e imágenes sobre cableado, pruebas, resultados obtenidos.

## proceso y resultados de osciladores y amplificador

con chips 4093 y 386

incluir texto e imágenes sobre cableado, pruebas, resultados obtenidos.

## modificaciones realizadas a los circuitos originales

incluir texto, imágenes sobre modificaciones realizadas a los circuitos originales, incluyendo el proceso de diseño, pruebas y resultados obtenidos.

incluir modificaciones en posición, chips, parámetros, valores, etc.

## carcasas de cartón

textos, imágenes

incluir origen de materiales, decisiones de posiciones de los componentes, decisiones estéticas, pruebas, resultados obtenidos.
**CARTON DE DESECHOS, CINTA GAFFER COMO FORMA DE ACERCARSE A LAS CARCASAS DE ALUMINIO EN LAS QUE SUELEN ESTAR LOS EFECTOS MODULARES Y PERILLAS A LO LOCO/PARLANTE COLGANDO PORQUE QUEREMOS SALIR UN POCO DE LO COMODO(?) O CONVENIENTE(???)**

## interconexión entre módulos

textos, imágenes, diagramas de interconexión

## resultados finales

texto

imagen

video / audio

## aprendizajes y errores

las mejores lecciones aprendidas y los errores más comunes y cómo los resolvieron

**NO LOGRAMOS HACER FUNCIONAR EL 4STEPSYNTH COMPLETAMENTE, PERO SI LOGRAMOS EL NANDULATOR, COSTO UNIR EL FILTRO/EFECTO DEL 4093 Y AL AMP, NOS COSTO ENTENDER COMO FUNCIONABA EL FILTRO, LA UNION DE CABLES ETC...**

## conclusiones

sobre modularidad, materialidad, trabajo en equipo, trabajo electrónico, trabajo maquinal.
