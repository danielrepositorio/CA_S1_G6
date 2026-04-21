<img width="1536" height="1024" alt="Diagrama del sistema de inventario" src="https://github.com/user-attachments/assets/10e1c60c-7a6b-42e0-8cf3-1c2e9027414d" />
# Tarea 5  
## Comunicación Asertiva y Análisis de Trade-Offs en un Proyecto de Software

---

# 1. Planteamiento del problema

## Contexto del proyecto
El equipo de desarrollo está trabajando en un sistema web para la **gestión de inventarios de una empresa de distribución**.  
El sistema permitirá registrar productos, controlar existencias, gestionar pedidos y generar reportes automáticos.

El cliente necesita que el sistema esté funcionando antes de una auditoría interna, por lo que el tiempo de desarrollo es limitado.

El equipo está conformado por **4 desarrolladores**, un **líder técnico** y un **representante del cliente** que supervisa el avance del proyecto.

---

## Descripción del problema

Durante el desarrollo del sistema, el equipo identificó que algunas funcionalidades solicitadas por el cliente requieren más tiempo del previsto inicialmente.

Esto genera un conflicto entre varios factores importantes del proyecto, como:

- cumplir con la **fecha de entrega**
- mantener una **alta calidad del software**
- implementar **todas las funcionalidades solicitadas**

Por lo tanto, el equipo debe tomar decisiones técnicas evaluando diferentes alternativas y considerando el impacto que cada decisión tendrá en el proyecto.

---

## Restricciones del proyecto

- **Tiempo:** 6 semanas para completar el desarrollo.
- **Equipo:** 4 desarrolladores.
- **Presupuesto:** no se pueden contratar más desarrolladores.
- **Alcance:** el cliente espera al menos las funcionalidades principales del sistema.

---

## Imagen sugerida

Aquí se puede colocar una imagen que represente el contexto del proyecto.

![Diagrama del sistema de inventario](imagenes/contexto_proyecto.png)

*Sugerencia de imagen:*  
Un diagrama simple del sistema mostrando módulos como inventario, pedidos y reportes.

---

# 2. Identificación de Trade-Offs

En los proyectos de software es común que las decisiones impliquen **trade-offs**, es decir, elegir entre diferentes opciones donde mejorar un aspecto puede afectar otro.

En este proyecto se identificaron los siguientes trade-offs:

| Trade-Off | Opción A | Opción B |
|-----------|-----------|-----------|
| Rapidez vs Calidad | Entregar rápido con menos pruebas | Entregar con pruebas completas |
| Costo vs Funcionalidad | Reducir funcionalidades | Implementar todas las funcionalidades |
| Simplicidad vs Escalabilidad | Arquitectura simple | Arquitectura escalable |

---

## Imagen sugerida

Se puede colocar un diagrama que explique visualmente los trade-offs.

![Diagrama trade-offs](imagenes/tradeoffs.png)

*Sugerencia de imagen:*  
Un triángulo de gestión de proyectos (tiempo, costo, calidad).

---

# 3. Análisis de alternativas

## 3.1 Rapidez vs Calidad

### Opción A: Entregar rápido con menos pruebas

**Ventajas**

- Permite cumplir con la fecha límite.
- El cliente recibe el sistema dentro del plazo esperado.

**Desventajas**

- Mayor probabilidad de errores en el sistema.
- Posibles fallos durante el uso del software.

**Impacto en el proyecto**

Puede afectar la estabilidad del sistema y generar costos adicionales de mantenimiento.

---

### Opción B: Entregar con pruebas completas

**Ventajas**

- Sistema más estable y confiable.
- Menor probabilidad de errores críticos.

**Desventajas**

- Posible retraso en la entrega.
- Necesidad de renegociar el cronograma con el cliente.

**Impacto en el proyecto**

Mejora la calidad del software pero afecta el tiempo de entrega.

---

## 3.2 Costo vs Funcionalidad

### Opción A: Reducir funcionalidades

**Ventajas**

- Se mantiene el presupuesto del proyecto.
- Facilita cumplir con el cronograma.

**Desventajas**

- El sistema tendrá menos características.
- Algunas funcionalidades deberán desarrollarse en una segunda fase.

**Impacto en el proyecto**

El sistema será funcional pero más limitado.

---

### Opción B: Implementar todas las funcionalidades

**Ventajas**

- Se cumplen todos los requerimientos del cliente.
- Mayor satisfacción del usuario final.

**Desventajas**

- Puede aumentar el costo del proyecto.
- Requiere más tiempo de desarrollo.

**Impacto en el proyecto**

Mayor complejidad técnica y posible retraso en la entrega.

---

## 3.3 Simplicidad vs Escalabilidad

### Opción A: Sistema simple

**Ventajas**

- Desarrollo más rápido.
- Menor complejidad técnica.

**Desventajas**

- Limitaciones para futuras mejoras.
- Puede ser difícil agregar nuevas funcionalidades.

**Impacto en el proyecto**

Adecuado para necesidades inmediatas, pero limitado a largo plazo.

---

### Opción B: Arquitectura escalable

**Ventajas**

- Facilita el crecimiento del sistema.
- Permite integrar nuevas funcionalidades en el futuro.

**Desventajas**

- Requiere más tiempo de diseño.
- Mayor complejidad técnica.

**Impacto en el proyecto**

Mejor preparación para el futuro del sistema.

---

## Imagen sugerida

Aquí se puede colocar un diagrama comparando arquitectura simple vs escalable.

![Arquitectura del sistema](imagenes/arquitectura.png)

---

# 4. Negociación técnica

Después de analizar las alternativas, el equipo realizó una discusión técnica utilizando principios de **comunicación asertiva**.

Durante la reunión:

- Cada integrante presentó sus argumentos de forma clara.
- Se analizaron los impactos de cada decisión.
- Se evaluaron los riesgos asociados a cada opción.

El equipo llegó a la conclusión de que lo más adecuado es **priorizar la estabilidad del sistema y las funcionalidades principales**.

Para respaldar la decisión se utilizaron los siguientes criterios:

**Uso de evidencia**

Experiencias previas en proyectos indican que los errores en producción generan costos mayores que el retraso en el desarrollo.

**Análisis de impacto**

Un sistema inestable podría afectar la operación del cliente durante la auditoría.

**Razonamiento lógico**

Es preferible entregar un sistema estable con funcionalidades esenciales que un sistema completo pero con errores.

---

## Imagen sugerida

Aquí se puede colocar una imagen de una reunión de equipo o diagrama de toma de decisiones.

![Reunión técnica](imagenes/negociacion.png)

---

# 5. Decisión final

## Solución elegida

El equipo decidió desarrollar primero las **funcionalidades principales del sistema** con un enfoque en calidad y estabilidad.

Las funcionalidades secundarias serán implementadas en una **segunda fase del proyecto**.

---

## Justificación

Esta decisión permite equilibrar los factores más importantes del proyecto:

- mantener la calidad del software
- cumplir con el tiempo disponible
- respetar el presupuesto establecido

---

## Consecuencias de la decisión

- El cliente recibirá un sistema funcional dentro del plazo.
- El software tendrá mayor estabilidad.
- Las funcionalidades adicionales se desarrollarán posteriormente.

---

# 6. Reflexión

## ¿Qué tan difícil fue tomar la decisión?

La decisión fue complicada porque cada alternativa presentaba ventajas y desventajas. Fue necesario analizar cuidadosamente cada opción y evaluar su impacto en el proyecto.

---

## ¿Qué aprendimos sobre los trade-offs?

Aprendimos que en los proyectos de software siempre existen decisiones donde no se puede optimizar todo al mismo tiempo. Los trade-offs permiten analizar las opciones disponibles y elegir la que mejor se adapte a las necesidades del proyecto.

---

## ¿Cómo aplicamos comunicación asertiva?

La comunicación asertiva se aplicó durante las discusiones del equipo, donde cada integrante expresó sus ideas de forma clara y respetuosa. Se utilizaron argumentos técnicos y evidencia para apoyar las decisiones tomadas.<img width="1536" height="1024" alt="Diagrama del sistema de inventario" src="https://github.com/user-attachments/assets/f53697d0-487f-459d-add7-ffc2bb6b7666" />
