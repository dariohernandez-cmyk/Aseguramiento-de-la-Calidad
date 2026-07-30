# Casos de Prueba - Historia 5: Realizar pedido

## Caso de Prueba TC-009
**Título:** Pedido confirmado exitosamente  
**Objetivo:** Validar que el sistema genera número de orden único y confirma el pedido.  
**Precondiciones:** El usuario debe tener productos en el carrito.  
**Datos de prueba:**  
- Método de pago: Simulado (Tarjeta)  

**Pasos:**  
1. Acceder al carrito.  
2. Presionar botón "Confirmar pedido".  
3. Seleccionar método de pago válido.  

**Resultado esperado:** El sistema genera número de orden y muestra confirmación con detalles.  
**Resultado obtenido:** Pendiente  
**Estado:** Pendiente  

---

## Caso de Prueba TC-010
**Título:** Error al confirmar pedido sin productos  
**Objetivo:** Validar que el sistema no permite confirmar pedido vacío.  
**Precondiciones:** Carrito vacío.  
**Datos de prueba:** N/A  

**Pasos:**  
1. Acceder al carrito vacío.  
2. Presionar botón "Confirmar pedido".  

**Resultado esperado:** El sistema muestra mensaje de error “No hay productos en el carrito”.  
**Resultado obtenido:** Pendiente  
**Estado:** Pendiente
