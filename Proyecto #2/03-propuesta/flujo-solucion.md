# Flujo de la Solución Propuesta

## Introducción

El siguiente flujo describe el funcionamiento del sistema propuesto para la Farmacia del Ángel.  

La solución se basa en un sistema digital modular, accesible mediante un modelo tipo servicio (SaaS), el cual permite mejorar la gestión del negocio, reducir errores y optimizar la atención al cliente.

---

## Descripción general del sistema

El sistema estará compuesto por módulos que pueden implementarse progresivamente:

- Módulo de productos e inventario  
- Módulo de ventas  
- Módulo de clientes  
- Módulo de apoyo informativo sobre medicamentos  
- Módulo de contabilidad básica  

El sistema será accesible mediante una plataforma web, permitiendo al usuario gestionar su negocio de manera centralizada.

---

## Flujo del sistema

### 1. Inicio de sesión

El encargado accede al sistema mediante:
- Usuario  
- Contraseña  

Esto permite identificar al usuario y proteger la información del negocio.

---

### 2. Gestión de productos

El usuario puede:

- Registrar nuevos medicamentos  
- Agregar información (nombre, categoría, precio, descripción)  
- Registrar fecha de vencimiento  
- Actualizar stock  

El sistema almacena toda la información de forma digital.

---

### 3. Control de inventario

El sistema realiza automáticamente:

- Verificación de stock  
- Alertas de productos próximos a vencer  
- Alertas de bajo inventario  

Esto evita pérdidas y mejora la organización del negocio.

---

### 4. Atención al cliente

Cuando un cliente llega:

#### Caso 1: Cliente sabe qué necesita
- Se busca el producto en el sistema  
- Se verifica disponibilidad  
- Se realiza la venta  

#### Caso 2: Cliente necesita orientación
- Se consulta el sistema  
- Se muestra información del medicamento  
- Se brinda una recomendación básica  

---

### 5. Apoyo informativo (IA como asistencia)

El sistema incluye un módulo de apoyo que permite:

- Mostrar información simplificada de medicamentos  
- Brindar orientación básica  
- Apoyar en la dosificación para niños  

---

### 6. Registro de ventas

Cada venta:

- Se registra automáticamente  
- Se almacena en el sistema  
- Se actualiza el inventario  

Esto elimina el uso de registros manuales.

---

### 7. Gestión de clientes

El sistema permite:

- Registrar clientes  
- Consultar historial de compras  
- Mejorar el seguimiento de ventas  

---

### 8. Contabilidad básica

El sistema puede:

- Registrar ingresos  
- Registrar egresos  
- Mostrar resumen financiero  

---

## Representación del flujo (pseudodiagrama)

```text
INICIO
  ↓
Login usuario
  ↓
Menú principal
  ↓
¿Acción?
  ├── Gestionar productos
  ├── Registrar venta
  ├── Consultar cliente
  ├── Ver inventario
  └── Consultar medicamento
          ↓
     Mostrar información
          ↓
Realizar venta
  ↓
Actualizar inventario
  ↓
Guardar datos
  ↓
FIN
  ↓
FIN
