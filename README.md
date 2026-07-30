# LePetitDep

## Descripción
Aplicación web de prueba que permite a los usuarios pedir café y productos de panadería para recoger en su local.

## Funcionalidades principales
- Registro de usuario
- Inicio de sesión
- Exploración del menú
- Agregar productos al carrito
- Realizar pedido
- Historial de pedidos

---

## Historias de Usuario

1. **Historia 1:** Registro de usuario  
   - Crear cuenta con correo y contraseña.  
   - Validación de correo único y contraseña segura.  

2. **Historia 2:** Inicio de sesión  
   - Acceso seguro con credenciales válidas.  

3. **Historia 3:** Exploración del menú  
   - Visualización de cafés y productos de panadería con precios y descripciones.  

4. **Historia 4:** Agregar productos al carrito  
   - Selección de productos y cantidades.  

5. **Historia 5:** Realizar pedido  
   - Confirmación del pedido, método de pago simulado y número de orden.  

6. **Historia 6:** Historial de pedidos  
   - Consulta de órdenes anteriores y opción de repetir pedido.  

---

## Casos de Prueba

Cada historia tiene **dos casos de prueba**:  
- **Caso positivo (flujo normal)** → valida funcionalidad con datos válidos.  
- **Caso negativo (flujo alterno)** → valida respuesta ante errores o datos inválidos.  

### Índice de casos de prueba:

- [Historia 1: Registro de usuario](test/casos_historia_1.md)  
  - TC-001: Registro exitoso de usuario  
  - TC-002: Registro fallido por contraseña inválida  

- [Historia 2: Inicio de sesión](test/casos_historia_2.md)  
  - TC-003: Inicio de sesión exitoso  
  - TC-004: Inicio de sesión fallido por credenciales incorrectas  

- [Historia 3: Exploración del menú](test/casos_historia_3.md)  
  - TC-005: Visualización correcta del menú  
  - TC-006: Error al cargar menú vacío  

- [Historia 4: Agregar productos al carrito](test/casos_historia_4.md)  
  - TC-007: Producto agregado correctamente al carrito  
  - TC-008: Error al agregar cantidad inválida  

- [Historia 5: Realizar pedido](test/casos_historia_5.md)  
  - TC-009: Pedido confirmado exitosamente  
  - TC-010: Error al confirmar pedido sin productos  

- [Historia 6: Historial de pedidos](test/casos_historia_6.md)  
  - TC-011: Visualización correcta del historial  
  - TC-012: Historial vacío sin pedidos previos  

---

## Estado
- Todos los casos de prueba se encuentran **Pendientes de ejecución**.  
- Los campos **Resultado obtenido**, **Estado (Pass/Fail)** y **Notas/Evidencias** se completarán tras la ejecución práctica.  

---

## Notas
- Cada archivo en `test/` corresponde a una historia de usuario.  
- IDs de casos de prueba son consecutivos (TC-001 a TC-012).  
- Formato uniforme para facilitar lectura y ejecución.  
