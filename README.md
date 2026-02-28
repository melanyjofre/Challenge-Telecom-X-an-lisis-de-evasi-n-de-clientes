# Challenge-Telecom-X-análisis-de-evasión-de-clientes

## Resumen:

El objetivo principal de este análisis fue generar un informe completo para Telecom X que abordara la pérdida de clientes. Este informe busca identificar los factores clave que influyen, comprender los patrones y tendencias asociados y proporcionar información valiosa para estrategias de retención más efectivas y personalizadas.

### Hallazgos clave del análisis de datos

* **Tasa de pérdida general**: La compañía experimenta una tasa de pérdida significativa, con un 26,9 % de sus clientes que han abandonado el servicio.
* **El tipo de contrato es crucial**: Los clientes con contratos mensuales presentan la tasa de pérdida más alta, con aproximadamente un 42,7 %, mientras que aquellos con contratos de dos años presentan la tasa más baja, con tan solo un 2,8 %, lo que indica una fuerte correlación inversa entre la duración del contrato y la pérdida. * **Impacto del método de pago**: El método de pago "Cheque electrónico" se asocia con la tasa de abandono más alta (aproximadamente el 45,3%), mientras que los métodos de pago automáticos como "Tarjeta de crédito (automática)" y "Transferencia bancaria (automática)" muestran tasas de abandono significativamente más bajas (alrededor del 15-17%).
* **El tipo de servicio de internet es importante**: Los usuarios de internet de fibra óptica tienen la tasa de abandono más alta (aproximadamente el 41,9%), en comparación con los usuarios de "DSL" (19,0%) y los clientes sin servicio de internet (7,4%).
* **La antigüedad del cliente es clave**: Los clientes con menor antigüedad (especialmente en los primeros meses) son significativamente más propensos a abandonar el servicio, lo que destaca la importancia de la experiencia temprana del cliente.
* **Cargos y abandono**: Los clientes que abandonan el servicio tienden a tener cargos mensuales más altos, lo que sugiere sensibilidad al precio o una percepción de falta de valor. Por el contrario, los clientes que permanecen tienen cargos totales más altos, lo que se correlaciona con una mayor antigüedad. **El género y el servicio telefónico son irrelevantes**: No se observaron diferencias significativas en las tasas de abandono según `customer.gender` ni si un cliente tiene `phone.PhoneService`, lo que sugiere que estos no son los principales impulsores de la pérdida.

### Perspectivas o próximos pasos

* **Mejorar la experiencia inicial del cliente y los programas de fidelización**: Implementar programas proactivos de incorporación y retención para nuevos clientes, especialmente durante los primeros meses, centrándose en la interacción y en la resolución rápida de posibles problemas.
* **Promover contratos a largo plazo y pagos automáticos**: Incentivar activamente a los clientes para que cambien de planes mensuales a contratos a largo plazo y fomentar la adopción de métodos de pago automáticos para fomentar una mayor fidelidad y reducir el riesgo de pérdida.
* **Investigar y mejorar el valor del servicio de fibra óptica**: Realizar una revisión exhaustiva de la oferta de servicios de fibra óptica, incluyendo la calidad, el rendimiento, la competitividad de precios y la atención al cliente, para abordar la alta tasa de abandono en este segmento.
