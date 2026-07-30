# Casos de Prueba - Historia 4: Agregar productos al carrito

## Caso de Prueba TC-007
**Título:** Producto agregado correctamente al carrito  
**Objetivo:** Validar que el sistema permite agregar productos con cantidad válida.  
**Precondiciones:** El usuario debe estar autenticado.  
**Datos de prueba:**  
- Producto: Café Latte  
- Cantidad: 2  

**Pasos:**  
1. Seleccionar producto.  
2. Introducir cantidad válida.  
3. Presionar botón "Agregar al carrito".  

**Resultado esperado:** El producto aparece en el carrito con cantidad y subtotal correctos.  
**Resultado obtenido:** Pendiente  
**Estado:** Pendiente  

---

## Caso de Prueba TC-008
**Título:** Error al agregar cantidad inválida  
**Objetivo:** Validar que el sistema rechaza cantidades no permitidas.  
**Precondiciones:** El usuario debe estar autenticado.  
**Datos de prueba:**  
- Producto: Café Latte  
- Cantidad: -1  

**Pasos:**  
1. Seleccionar producto.  
2. Introducir cantidad inválida.  
3. Presionar botón "Agregar al carrito".  

**Resultado esperado:** El sistema muestra mensaje de error y no agrega el producto.  
**Resultado obtenido:** Pendiente  
**Estado:** Pendiente
