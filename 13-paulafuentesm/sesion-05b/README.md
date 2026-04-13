# sesion-05b

## **Clock Generator**

" la gente escucha con la vista "

Ux: experiencia de usurario + resolver la necesidad de un nicho

Relojes:

+ 555: astable - igual lento
+ CD403: compuertas 0-1

![fases-clock](https://github.com/paulafuentesm/dis8644-2026-1/blob/12e54202c3d59e407ed2ef52f6bbfe5805762d5e/13-paulafuentesm/sesion-05b/imagenes/fases-clock.jpg)

Chip 4017: contador de decadas ( secuanciador) 

----

### Ejercicio en clases:

![clock-generator](https://github.com/paulafuentesm/dis8644-2026-1/blob/12e54202c3d59e407ed2ef52f6bbfe5805762d5e/13-paulafuentesm/sesion-05b/imagenes/clock-generator.png)

Ejecución:

![clock-proto](https://github.com/paulafuentesm/dis8644-2026-1/blob/12e54202c3d59e407ed2ef52f6bbfe5805762d5e/13-paulafuentesm/sesion-05b/imagenes/clock-proto.jpg)

Observaciones:
Los lED se encienden una por una en secuencia

+ 555: pulsos repetitivos.
+ CD4017: contador secuencial

Las luces van rotando una tras otra de forma automática por la secuencia de reloj y la rapidez de ese movimiento puede ajustarse con el potenciómetro.

### Extra:

+ Agregar un boton entre 3 - 14

Ejecución:

![reloj-boton-proto](https://github.com/paulafuentesm/dis8644-2026-1/blob/12e54202c3d59e407ed2ef52f6bbfe5805762d5e/13-paulafuentesm/sesion-05b/imagenes/reloj-boton-proto.jpg)

Observaciones:

+ Cuando se presiona el botón, la luz queda fija en el ultimo LED encendido, deteniendo momentáneamente el movimiento secuencial del circuito. Al soltar el botón, las luces reanudan su desplazamiento normal siguiendo nuevamente el ritmo del reloj.
