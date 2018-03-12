# Léeme RefriBot BackEnd (RoR)

## Proyecto RefriBot

Descripción

El proyecto RefriBot es:


[ ] Un gestor de productos.
[ ] Indice de fechas de vencimiento por producto (código de barras).
[ ] Sistema que proveerá estadísticas de consumo al usuario.
[ ] Sistema que dará aviso al usuario ante la futura descomposición de un producto determinado.
[ ] Existe la posibilidad de hacer un robot web para encontrar los mejores precios (onda SoloTodo) - Solo si es que existe una API o página de donde poder extraer estos datos.

El proyecto Refribot NO es:


[ ] Un sistema de compras.
[ ] Un sistema de ventas (Depende del enfoque que se le dé - Primeramente para uso de hogar).


Base del Proyecto (IDEA)

Sistema que permita a un usuario ingresar los productos de la compra mensual, junto con su fecha de vencimiento, de manera de poder avisarle en un determinado lapsus de tiempo ante la futura descomposición de un producto definido.


Necesito
[ ] BackEnd RoR para ingreso de datos.
[ ] Sidekiq para procesos de alerta (Jobs programados).
[ ] App movil o sistema de alerta “x” para móviles.

Idea del proyecto por pasos


[ ] Construcción del BackEnd RoR, para el ingreso de datos y estadísticas.
[ ] Construcción (Evaluación e Investigación) de sistema o método de alertas para móviles.
[ ] Investigar procesos de escaneo de códigos de barra con el fin de poder obtener más información del producto. (No se si se pueda, pero igual).