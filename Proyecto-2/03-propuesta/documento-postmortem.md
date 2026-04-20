# Documento Post-Mortem

## 1. Resumen del incidente

Durante la implementación del sistema en la Farmacia del Ángel, se presentó un incidente relacionado con el módulo de apoyo informativo de medicamentos.

El sistema generó una recomendación incorrecta en la dosificación de un medicamento para un paciente infantil, debido a una mala interpretación de los datos ingresados (edad y peso).

Este incidente ocurrió durante la fase de pruebas del sistema y afectó la confiabilidad del módulo de apoyo.

---

## 2. Línea de tiempo (Timeline)

- **9:00 PM:** Inicio de pruebas del sistema por parte del equipo  
- **9:05 PM:** Se ingresa una consulta sobre dosificación de medicamento para un niño  
- **9:05 PM:** El sistema genera una recomendación automática  
- **9:08 PM:** Se detecta que la recomendación no coincide con valores esperados  
- **9:10 PM:** El equipo detiene las pruebas del módulo  
- **9:10 PM:** Se inicia revisión del error  
- **9:45 PM:** Se identifica la causa del problema  
- **10:20 PM:** Se implementa una solución temporal  
- **11:00PM:** Se encontro una solución fija

---

## 3. Impacto

El incidente tuvo los siguientes impactos:

- Generación de información incorrecta en el sistema  
- Pérdida de confianza en el módulo de apoyo informativo  
- Retraso en la fase de pruebas  
- Riesgo potencial en caso de uso en un entorno real  

No hubo impacto directo en clientes reales, ya que el incidente ocurrió en fase de pruebas.

---

## 4. Causa raíz

La causa principal del problema fue:

- Falta de validación adecuada de los datos de entrada (edad, peso)  
- Uso de lógica incompleta en el cálculo de dosificación  
- Dependencia excesiva en el módulo automatizado sin verificación adicional  

Aplicando el análisis de los “5 porqués”:

1. ¿Por qué ocurrió el error?  
   Porque el sistema generó una recomendación incorrecta  

2. ¿Por qué generó una recomendación incorrecta?  
   Porque los datos no fueron interpretados correctamente  

3. ¿Por qué no fueron interpretados correctamente?  
   Porque no existía validación suficiente en los datos  

4. ¿Por qué no había validación suficiente?  
   Porque el módulo fue desarrollado sin pruebas completas  

5. ¿Por qué no se realizaron pruebas completas?  
   Por presión de tiempo en la entrega del sistema  

---

## 5. Acciones tomadas para solucionarlo

Para corregir el incidente se realizaron las siguientes acciones:

- Se deshabilitó temporalmente el módulo de recomendación automática  
- Se implementaron validaciones en los datos de entrada  
- Se ajustó la lógica de cálculo de dosificación  
- Se agregó una advertencia indicando que el sistema es solo de apoyo  
- Se realizaron pruebas adicionales para verificar el correcto funcionamiento  

---

## 6. Acciones a futuro

Para evitar que este tipo de problemas vuelva a ocurrir, se proponen las siguientes mejoras:

- Implementar pruebas más rigurosas antes de liberar funcionalidades  
- Agregar validaciones obligatorias en todos los datos ingresados  
- Incorporar revisión manual en módulos críticos  
- Limitar el uso de inteligencia artificial a funciones informativas  
- Documentar claramente las limitaciones del sistema  
- Implementar monitoreo continuo del sistema  
- Capacitar al usuario sobre el uso correcto del sistema  

---

## Conclusión

El incidente permitió identificar debilidades en el desarrollo del sistema, especialmente en el uso de automatización para procesos críticos.

Gracias a este análisis, se lograron implementar mejoras que fortalecen la calidad, seguridad y confiabilidad de la solución propuesta.