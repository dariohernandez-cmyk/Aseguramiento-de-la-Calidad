# Casos de Prueba - Historia 1: Registro de usuario

## Caso de Prueba TC-001
**Título:** Registro exitoso de usuario  
**Objetivo:** Validar que el sistema permite crear una cuenta con correo y contraseña válidos.  
**Precondiciones:** El usuario no debe estar registrado previamente.  
**Datos de prueba:**  
- Correo: usuario@test.com  
- Contraseña: Abc12345  

**Pasos:**  
1. Ingresar al formulario de registro.  
2. Introducir correo válido.  
3. Introducir contraseña válida.  
4. Presionar botón "Registrar".  

**Resultado esperado:** El sistema muestra mensaje de confirmación y crea la cuenta.  
**Resultado obtenido:** Pendiente  
**Estado:** Pendiente  
**Notas/Evidencias:** Se completará tras ejecución.

---

## Caso de Prueba TC-002
**Título:** Registro fallido por contraseña inválida  
**Objetivo:** Validar que el sistema rechaza contraseñas que no cumplen requisitos.  
**Precondiciones:** El usuario no debe estar registrado previamente.  
**Datos de prueba:**  
- Correo: usuario@test.com  
- Contraseña: abc  

**Pasos:**  
1. Ingresar al formulario de registro.  
2. Introducir correo válido.  
3. Introducir contraseña inválida.  
4. Presionar botón "Registrar".  

**Resultado esperado:** El sistema muestra mensaje de error indicando que la contraseña no cumple requisitos.  
**Resultado obtenido:** Pendiente  
**Estado:** Pendiente  
**Notas/Evidencias:** Se completará tras ejecución.
