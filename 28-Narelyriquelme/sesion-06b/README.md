# sesion-06b
## Apuntes 17 abr
### Fe de erratas
Una fe de erratas es una lista de errores detectados en un texto después de que este ha sido impreso o publicado, la cual se añade al final o al inicio de la obra para indicar la corrección necesaria.

Es una herramienta común en el mundo editorial, académico y legal para mantener la integridad de la información sin tener que reimprimir todo el material.

En resumen, es la manera formal y transparente de decir: "Nos equivocamos en esta parte, lo correcto es esto".

"Por mi culpa, por mi culpa, por mi gran culpa".

### Correcciones al circuito
![Apuntes06b](./imagenes/apuntes-06b.jpg)

missa en clases nos enseño varias correcciones y datos utiles para hacer en los circuitos como se muestra en la imagen de arriba:

**Correcciones**
+ agregar una resistencia de 100k entre la conexion entre el chip 555 y 4017.
+ agregar capacitores ceramicos de 104 a cada chip en la salida a positivo $V+$ y luego conectarlo cada uno a GND, mientras mas cerca del chip mejor.
+  conectar un capacitor de 100 uf entre la patita 2 del potenciometro y la patita 3 del chip 386.

**Datos**
+ fuentes alternativas de energia como usar 5v de los cables usb tipo A y tambien hay chips sensibles a la cantidad de energía. Por ejemplo, con 9 V pueden sonar más fuerte.
+ se puede utilizar ambos lados de $v+$ y GND en la protoboard conectando ambos lados con un cable para mayor facilidad de conexión en los componentes.

### Bitacora avances
Seguimos avanzando en el sintetizador que ya traíamos todo armado. Le agregamos todas las correcciones que nos dio el profesor en la clase y, ya con todo listo, lo probamos y... no nos resultó. Antes de hacer las conexiones sí salía sonido, pero después de los cambios ya no. Lo primero que hicimos fue revisar si alguna conexión nueva era la que había fallado, pero al revisarlo todo vimos que estaba correcto. Después revisamos si era alguna otra conexión y, al analizar todo meticulosamente, no parecía estar nada mal, en ese momento entramos en desesperación y le pedimos ayuda a Missa, quien nos ayudó demasiado. ¡Gracias, Missa!

Missa nos enseñó a revisar cada parte del circuito por separado. Primero revisamos la conexión de los chips 555 y 4017 y funcionaba todo bien por separado, eso lo dejamos de lado y revisamos la otra parte de los chips 4093 y 386. Primero corroboramos que la salida de audio estuviera bien y armamos con otro chip 4093, en otra protoboard, un step para ver si salía sonido. Al principio no nos funcionó, aunque todo se veía bien conectado, entonces probamos cambiar el chip 386 y ahí sí nos funcionó. Estábamos felices, pero con otro chip quemado a la colección.

Después de corroborar que funcionaba, revisamos si estaba todo bien conectado en el chip 4093 y se veía correcto, entonces decidimos probar todo junto nuevamente y, al conectar todo, no salía sonido :( . Decidimos cambiar el chip 4093 por el que estábamos usando de prueba, ya que ese sabíamos que funcionaba, pero después de cambiarlo aún no sonaba. Ya no sabíamos qué más hacer.

Hasta que a Missa se le ocurrió sacar los LEDs del chip 4017 solo para probar y, ¡sorpresa!, por fin salía sonido. Descubrimos junto a él que los LEDs del secuenciador afectaban el paso de la energía a los steps del sintetizador. Sacando todos los LEDs de los steps, al fin nos funcionó correctamente todo el circuito y fuimos demasiado felices. También cabe destacar, entre paréntesis, que el profesor Aarón nos enseñó que debíamos cuidar la batería, ya que si uno la deja suelta en la cajita puede tocar algún otro componente y se puede descargar. Después de tener todo funcionando, quisimos probar distintos sonidos y fue muy entretenido. Aquí dejo algunos sonidos que obtuvimos.



https://github.com/user-attachments/assets/628148e3-b2c9-46cb-a3e6-df87f0b89ef4



https://github.com/user-attachments/assets/7744fd53-5cb1-4799-947a-01f492bf91d2




https://github.com/user-attachments/assets/e69baccd-dc3d-40e3-91de-44012a54202a


