# sesion-05b
La clase empezó a las 11 y aun asi me quede dormido y casi llego muy tarde pero solo me atrase un poco por lo menos
## apuntes Viernes 10 de Abril

### referencias de la clase
* Push turn move = libro de referencia aclamado sobre el diseño de interfaces en instrumentos musicales electrónicos.
* Pedalboard = permite cambiar efectos de la guitarra sin necesidad de tocar la guitarra o algun boton cerca de este, asi se puede tocar y cambiar los efectos en tiempo real
* David bryrne = Lo caracteriza que nadie esta sentado ni enfrente de uno ya que todos los de la banda importan lo mismo, por lo tanto tambien deben de tener las mismas prendas, ademas de tener un estilo experimental y un acercamiento a la electronica, de hecho tiene una version de "the model" de Kraftwerk
* St. Vincent = Usa una guitarra personalizada para las personas de genero femenino ya que se adaptan usualmente a su cuerpo y tambien las distribuye.
* Banda marinero = Dúo chileno que usa guitarras de St. Vicent.

### significado o funcionamiento de cosas
**Secuenciador** = reproduce eventos musicales en orden, controlando sintetizadores, cajas de ritmos o sampler. Actua como un cerebro. La diferencia con un sintetizador es que no genera sonido por si mismo sino que envía señales a otros equipos para que ellos toquen.
* Se puede hacer un reloj con un 555 y un 4093 (ambos chips)
* funciona de 0 a 9 y reproduce diferentes notas en base a eso, es un contador de decada
**4017** = de Q0 a Q3 toca notas y vuelve a 0 si conectamos el final con 14 rst.
* Cuenta tambien con 16 patitas a diferencia del 555 que solo tiene 8.

---

### Experimentacion
* Hicimos un experimento junto ami compañero Angel Sabogal, en donde unimos un 555 y un 4093:
![Prueba](./imagenes/prueba.gif)

Gracias al 555 es posible hacer que los led conectados al 4093 empieces a prenderse en secuencia, al aumentar el potenciometro la secuencia sera mas rapida.

