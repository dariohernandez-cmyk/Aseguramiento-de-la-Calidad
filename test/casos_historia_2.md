# Casos de Prueba - Historia 2: Inicio de sesión

## Caso de Prueba TC-003
**Título:** Inicio de sesión exitoso  
**Objetivo:** Validar que el sistema permite acceder con credenciales correctas.  
**Precondiciones:** El usuario debe estar registrado.  
**Datos de prueba:**  
- Correo: usuario@test.com  
- Contraseña: Abc12345  

**Pasos:**  
1. Ingresar al formulario de inicio de sesión.  
2. Introducir correo válido.  
3. Introducir contraseña válida.  
4. Presionar botón "Iniciar sesión".  

**Resultado esperado:** El sistema permite el acceso y muestra la página principal.  
**Resultado obtenido:** Pendiente  
**Estado:** Pendiente  

---

## Caso de Prueba TC-004
**Título:** Inicio de sesión fallido por credenciales incorrectas  
**Objetivo:** Validar que el sistema rechaza credenciales inválidas.  
**Precondiciones:** El usuario debe estar registrado.  
**Datos de prueba:**  
- Correo: usuario@test.com  
- Contraseña: 123456  

**Pasos:**  
1. Ingresar al formulario de inicio de sesión.  
2. Introducir correo válido.  
3. Introducir contraseña incorrecta.  
4. Presionar botón "Iniciar sesión".  

**Resultado esperado:** El sistema muestra mensaje de error y no permite el acceso.  
**Resultado obtenido:** Pendiente  
**Estado:** Pendiente
