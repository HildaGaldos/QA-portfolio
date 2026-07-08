## Primer bug simulado

| Campo                 | Descripción                                                                           |
| --------------------- | ------------------------------------------------------------------------------------- |
| ID                    | BUG-001                                                                               |
| Título                | El sistema permite iniciar sesión con contraseña incorrecta                           |
| Ambiente              | Chrome, Windows 11                                                                    |
| Precondición          | Usuario registrado                                                                    |
| Pasos para reproducir | 1. Ingresar correo válido 2. Ingresar contraseña incorrecta 3. Clic en iniciar sesión |
| Resultado esperado    | El sistema debe mostrar un mensaje de error                                           |
| Resultado actual      | El sistema permite ingresar al sistema                                                |
| Severidad             | Alta                                                                                  |
| Prioridad             | Alta                                                                                  |
| Evidencia             | Pendiente                                                                             |

## Segundo bug simulado

| Campo                 | Descripción                                                                         |
| --------------------- | ----------------------------------------------------------------------------------- |
| ID                    | BUG-002                                                                             |
| Título                | No aparece mensaje de error cuando el campo correo está vacío                       |
| Ambiente              | Chrome, Windows 11                                                                  |
| Precondición          | Estar en la pantalla de login                                                       |
| Pasos para reproducir | 1. Dejar vacío el campo correo 2. Ingresar una contraseña 3. Clic en iniciar sesión |
| Resultado esperado    | El sistema debe mostrar un mensaje indicando que el correo es obligatorio           |
| Resultado actual      | No aparece ningún mensaje de validación                                             |
| Severidad             | Media                                                                               |
| Prioridad             | Media                                                                               |
| Evidencia             | Pendiente                                                                           |
