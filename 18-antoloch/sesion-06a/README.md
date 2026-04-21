# sesion-06a

## Schmitt Trigger


de nuevo se habló de schmitt trigger, ya lo habia investigado un poquitoooooo pero buenoo, un **Schmitt Trigger** es un comparador con histéresis.

### Función:
Convierte señales analógicas ruidosas en señales digitales limpias.

---

### Ejemplo real: CD4093

- 4 compuertass
- Entradas con histéresis

### Usos:
- botones
- Osciladores 
- Limpieza de señal

---

##  4. Comparador

- Si `A > B` → salida = 1
- Si `A < B` → salida = 0

###  Relación:
El Schmitt Trigger es un comparador mejorado:
- Añade memoria
- Mayor estabilidad

bueno mis notas estan un povo desordenadas pero de alguna forma entiendo perfectamente jijiji
  
![notas](./imagenes/notas.jpeg)
---

## Voltajes

- `Vcc` → alimentación
- `GND` → referencia
- `Vi` → entrada
- `Vo` → salida


## Memoria en circuitos

La histéresis implica que:
> El sistema recuerda su estado anterior

---

##  Puertas lógicas

| Puerta | Función |
|------|--------|
| AND | Todas deben ser 1 |
| OR | Al menos una es 1 |
| NOT | Invierte señal |
| NAND | AND negada |


### Componentes chips :)))
- NE555 
- CD4017 
- CD4093 
---

### Funcionamiento:

El **NE555** en modo astable genera:
- Señal cuadrada (clock)

El **CD4093**:
- Elimina ruido
- Estabiliza la señal

El **CD4017**:
- Cuenta pulsos
- Activa salidas secuenciales

---

## Familia CMOS 4000

### Características:
- Bajo consumo
- Amplio rango de voltaje
- Alta inmunidad al ruido

---

## Problemas comunes

Sin histéresis:
- Oscilaciones no deseadas .
- Señales inestables

---

##  Aplicaciones

- Botones 
- Sensores 
- Osciladores
- Sistemas secuenciales
- Interfaces electrónicas

---


## ejercicio en clases 
Bueno, el circuito no nos funcionó completamente. Solo logramos que encendieran las luces en las dos primeras partes del circuito, el resto no funcionó en absoluto.
![sesion06a](./imagenes/sesion06a.jpeg)
![sesion06aa](./imagenes/sesion06aa.jpeg)
 
controlar la frustración, seguir, seguir y seguir!! hasta lograrlo
No pensar constantemente en que repetí mil veces los pasos, solo mirar al futuro jiji 
