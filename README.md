## Telecom X – Parte 2: Predicción de Cancelación (Churn)

📣 Desafío

Luego de ser promovido por mi excelente desempeño en el análisis exploratorio de la cancelación de clientes en Telecom X. Tu dedicación, claridad al comunicar los datos y visión estratégica marcaron la diferencia.

Ahora, ¡Fuí invitado oficialmente a formar parte del equipo de Machine Learning de la empresa!

🎯 Mi Misión:

Es desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios.

La empresa quiere anticiparse al problema de la cancelación, y te corresponde a ti construir un pipeline robusto para esta etapa inicial de modelado.

🧠 Objetivos:

Preparar los datos para el modelado (tratamiento, codificación, normalización).

Realizar análisis de correlación y selección de variables.

Entrenar dos o más modelos de clasificación.

Evaluar el rendimiento de los modelos con métricas.

Interpretar los resultados, incluyendo la importancia de las variables.

Crear una conclusión estratégica señalando los principales factores que influyen en la cancelación.

🧰 Lo que debo practicar:

✅ Preprocesamiento de datos para Machine Learning
✅ Construcción y evaluación de modelos predictivos
✅ Interpretación de resultados y entrega de insights
✅ Comunicación técnica con enfoque estratégico

🚀 Ahora como Analista Junior de Machine Learning, Telecom X confía en tu entrega para dar los próximos pasos hacia una solución de inteligencia predictiva eficaz. ¡Buena suerte!

## ✅ CONCLUSIÓN

🔍 Principales causas de cancelación (churn)
Lead Time elevado Clientes que reservan con mucha anticipación tienden a cancelar más. Esto puede reflejar indecisión o falta de compromiso inicial.

Historial de cancelaciones previas Aquellos que ya han cancelado antes tienen mayor probabilidad de volver a hacerlo. Es un patrón de comportamiento que se repite.

Cambios en la reserva (booking_changes) Las modificaciones frecuentes en la reserva indican inestabilidad en la decisión del cliente, lo que se asocia con mayor riesgo de churn.

Bajo número de solicitudes especiales (total_of_special_requests) Clientes que no solicitan servicios adicionales suelen estar menos comprometidos o satisfechos.

Tarifa diaria promedio (adr) elevada en clientes nuevos Cuando el costo es alto y el cliente es nuevo (bajo tenure), la probabilidad de cancelación aumenta.

Método de pago electrónico (PaymentMethod_Electronic check) Este método mostró correlación con mayor tasa de cancelación, posiblemente por menor percepción de compromiso.

🎯 Recomendaciones clave para reducir el churn
Segmentar y monitorear clientes con alto lead time Implementar alertas para clientes que reservan con mucha anticipación y ofrecerles incentivos o recordatorios personalizados.

Detectar y actuar sobre historial de cancelaciones Crear un sistema de scoring que identifique clientes reincidentes y aplicar estrategias de retención específicas (como ofertas exclusivas o atención personalizada).

Reducir fricción en el proceso de cambios Mejorar la experiencia de modificación de reservas para que el cliente no se sienta frustrado y termine cancelando.

Fomentar solicitudes especiales Promover servicios adicionales como upgrades, beneficios o experiencias personalizadas para aumentar el compromiso emocional del cliente.

Revisar pricing para clientes nuevos Ofrecer tarifas promocionales o paquetes de bienvenida para clientes con bajo tenure y alto adr.

