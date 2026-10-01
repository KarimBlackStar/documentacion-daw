# Diagrama de Clases

Representación de las entidades principales del dominio del sistema.

```text
+-------------------+       1..* +-------------------+
|      Usuario      |<>--------->|      Pedido       |
+-------------------+            +-------------------+
| - id: Long        |            | - id: Long        |
| - email: String   |            | - fecha: LocalDate|
| - pass: String    |            | - total: Double   |
+-------------------+            +-------------------+
| + login(): Bool   |            | + calcularTotal() |
+-------------------+            +-------------------+
