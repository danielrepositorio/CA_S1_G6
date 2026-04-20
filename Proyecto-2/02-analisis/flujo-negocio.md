# Flujo del Negocio Escogido (Farmacia del Ángel)

## Introducción

El siguiente flujo describe el funcionamiento actual de la Farmacia del Ángel, basado en la información obtenida durante la entrevista. Este flujo representa el proceso manual que se realiza diariamente en la atención al cliente y gestión del negocio.

---

## Descripción del flujo

### 1. Inicio de la jornada
El encargado abre la farmacia e inicia la atención al cliente.

---

### 2. Llegada del cliente
El cliente llega al establecimiento y realiza una de las siguientes acciones:

- Solicita un medicamento específico (la mayoría de los casos)
- Solicita recomendación sobre qué medicamento tomar

---

### 3. Atención del cliente

El encargado realiza las siguientes acciones:

- Escucha la necesidad del cliente
- Si el cliente solicita recomendación:
  - Intenta orientar según su conocimiento
  - En algunos casos consulta internet o recomienda acudir a un médico
- Busca el medicamento en el inventario físico

---

### 4. Verificación del producto

- Si el producto está disponible:
  - Se muestra al cliente
  - Se indica el precio
- Si el producto no está disponible:
  - Se informa al cliente
  - Se pierde la venta o se sugiere una alternativa

---

### 5. Venta del producto

- El cliente acepta el producto
- Se realiza la venta
- El registro de la venta se realiza de forma manual (papel o memoria)

---

### 6. Explicación del uso del medicamento

- El encargado explica cómo utilizar el medicamento
- En algunos casos:
  - Los clientes (especialmente adultos mayores) no comprenden bien las instrucciones
  - Se generan dudas o errores de interpretación

---

### 7. Control de inventario

- Se revisa el inventario de forma manual diariamente
- Se verifica qué productos hacen falta
- Se identifican productos próximos a vencer o vencidos
- Se realizan pedidos a proveedores cuando es necesario

---

### 8. Problemas en el proceso

Durante el flujo se presentan los siguientes problemas:

- Uso de registros manuales (ineficiencia y errores)
- Falta de información clara sobre medicamentos
- Dificultad en la dosificación de medicamentos para niños
- Errores cuando otra persona atiende el negocio
- Pérdida de tiempo en tareas repetitivas
- Falta de control automatizado del inventario
- Falta de registro de clientes

---

## Representación del flujo (pseudodiagrama)

```text
INICIO
  ↓
Cliente llega
  ↓
¿Sabe qué necesita?
  ├── Sí → Buscar producto
  └── No → Dar recomendación
             ↓
        Buscar producto
  ↓
¿Producto disponible?
  ├── Sí → Mostrar producto → Venta → Registro manual
  └── No → Informar → Fin
  ↓
Explicar uso del medicamento
  ↓
Actualizar inventario manualmente
  ↓
FIN
