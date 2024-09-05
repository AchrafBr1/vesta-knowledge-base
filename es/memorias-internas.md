---
icon: code-branch
---

# Memorias Internas

### ¿Qué son las Memorias Internas en VESTA?

Las **memorias internas** en el sistema de reglas de VESTA son una herramienta poderosa para la automatización avanzada. Son básicamente variables de estado (on/off) que se pueden usar para almacenar información temporal o de contexto. Hay 20 memorias internas disponibles, denominadas de `m00` a `m19`.

Estas memorias pueden ser utilizadas de tres formas en las reglas automáticas:

1. **Como desencadenante de una regla:** Puedes definir una regla que se active cuando una memoria interna cambie su estado (de verdadero a falso o viceversa).
2. **Como condicional de una regla:** Puedes configurar una regla para que se ejecute solo si una memoria interna está en un estado específico (verdadero o falso).
3. **Como acción de una regla:** Puedes hacer que una regla cambie el estado de una memoria interna a verdadero o falso, con opciones adicionales de temporización o alternancia (toggle).

### Ejemplo de Uso de Memorias Internas

Supongamos que quieres crear una automatización para mantener una luz encendida mientras haya movimiento en un área específica. Podrías usar una memoria interna para gestionar esta lógica:

1. **Desencadenante:** Un sensor de movimiento detecta actividad.
2. **Condicional:** NA
3. **Acción:**
   * Cambiar la memoria interna `m01` a "verdadero por 2 min" (indicando que se ha detectado movimiento).
   * Encender la luz.

Crear otra regla de apagado:&#x20;

* **Desencadenante:** memoria interna `m01` es Falsa
* **Condicional:** NA
* **Acción:**
  * Apagar la luz.

Con este flujo, la luz se mantendrá encendida mientras el sensor de movimiento continúe detectando movimiento. y cuando deje de detectar al cabo de 2 min apagará la luz.

### Opciones Avanzadas para Cambiar el Estado de las Memorias Internas

1. **Verdadero o Falso:** Cambia directamente el estado de una memoria interna.
2. **Verdadero durante un tiempo específico:** Activa el estado "verdadero" por un tiempo predefinido (por ejemplo, 1 minuto, 5 minutos, etc.).
3. **Verdadero hasta:** Mantiene el estado "verdadero" hasta que se cumpla una condición de tiempo específica.
4. **Toggle:** Alterna el estado de la memoria interna; si es "verdadero", lo cambia a "falso", y viceversa.

### Otros Ejemplos de Uso

1. **Generar una alarma por inactividad:** Usando una memoria interna, puedes configurar una regla que monitoree la actividad de un sensor (como una puerta o un sensor de movimiento) y active una alarma si no hay actividad durante un tiempo determinado.
2. **Automatizar un dispositivo con múltiples condiciones:** Las memorias internas pueden almacenar diferentes estados y condiciones, permitiendo crear automatizaciones complejas, como activar o desactivar dispositivos en función de varias entradas (sensores, horarios, estados previos, etc.).

### Conclusión

Las memorias internas en VESTA permiten crear automatizaciones más avanzadas, flexibles y dinámicas. Son especialmente útiles cuando necesitas manejar condiciones complejas o estados temporales que pueden influir en el comportamiento de otras reglas. Con su capacidad de actuar como desencadenantes, condicionales y acciones, estas memorias abren un abanico de posibilidades para mejorar y personalizar la automatización del sistema a tus necesidades específicas.

### Resumen

🧠 **Memorias internas**: Las memorias internas pueden ser utilizadas para disparar otras reglas así como para tenerlas como condicionales, dando una potencia muy importante a nivel de **lógicas de automatización más avanzadas**.

En el sistema tenemos 20 memorias internas, llamadas

* m00
* m01
* m02
* m03
* m04
* m05
* m06
* m07
* m08
* m09
* m10
* m11
* m12
* m13
* m14
* m15
* m16
* m17
* m18
* m19

Como **desencadenante** de la regla permiten cambiar su estado:

* Estado de (memoria interna) mxx –> <mark style="color:green;">Verdadero</mark> o <mark style="color:red;">falso</mark>

Como **condicional** de la regla permitirán:

* Estado de (memoria interna) mxx –>  <mark style="color:green;">Verdadero</mark> o <mark style="color:red;">falso</mark>

Como **acciones** de la regla deberán permitir:

* Cambio de estado de la memoria interna –> mxx –>  <mark style="color:green;">Verdadero,</mark> <mark style="color:red;">falso</mark>, <mark style="color:green;">Verdadero</mark> para (Elegir el tiempo 1min, 5min ….), <mark style="color:green;">Verdadero</mark> hasta (Dejar elegir el tiempo), **toggle** (Si es verdadero pasar a falso y si es falso volver a verdadero)

Ejemplo de uso:

* Mantener una luz encendida mintras haya movimiento en un detector
* Generar una alarma por inactividad
* Infinidad de posiblidades…
