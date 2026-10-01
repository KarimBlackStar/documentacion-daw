# Análisis de Caja Blanca

Pruebas enfocadas en la cobertura de rutas de ejecución del módulo de autenticación.

## Método Evaluado: `validarAcceso(Usuario u)`

### Caminos Identificados
1. **Camino 1**: Usuario no existe en la base de datos $\rightarrow$ Retorna error 404.
2. **Camino 2**: Contraseña incorrecta $\rightarrow$ Incrementa contador de intentos y retorna error 401.
3. **Camino 3**: Credenciales correctas y cuenta activa $\rightarrow$ Genera token de sesión.

## Métricas de Cobertura
- **Cobertura de ramas**: 100%
- **Complejidad ciclomática**: $V(G) = 3$
