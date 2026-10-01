# Especificación de Requisitos

## Requisitos Funcionales (RF)
- **RF-01**: El usuario debe poder iniciar sesión con credenciales válidas y soporte de tokens JWT.
- **RF-02**: Permitir el registro, edición y baja lógica de productos del catálogo.
- **RF-03**: Generar reportes de ventas mensuales exportables en formato PDF.

## Requisitos No Funcionales (RNF)
- **RNF-01 (Rendimiento)**: El tiempo de respuesta de las consultas a la API no debe superar los 300 ms.
- **RNF-02 (Seguridad)**: Las contraseñas se almacenarán cifradas mediante el algoritmo BCrypt.
