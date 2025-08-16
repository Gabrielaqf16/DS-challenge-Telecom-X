# DS-challenge-Telecom-X
📊 Proyecto: Churn de Clientes – Telecom X
📌 Introducción

Este proyecto forma parte del análisis de la tasa de abandono (churn) en la empresa Telecom X, que atraviesa una crisis debido al elevado número de cancelaciones de sus servicios.

El objetivo principal fue identificar los factores que influyen en la deserción de clientes, con el fin de generar información estratégica que permita diseñar acciones para mejorar la retención.

El trabajo incluyó un proceso ETL (Extracción, Transformación y Carga) y se desarrolló en Python, utilizando librerías como pandas, matplotlib y seaborn.

🧹 Limpieza y Tratamiento de Datos

Se aplicaron diferentes pasos de depuración para garantizar la calidad y consistencia del dataset:

🔹 Eliminación de valores nulos: se descartaron registros incompletos (ej. cargo_total).

🔹 Conversión de tipos: variables binarias (Yes/No) fueron transformadas a 0/1 (int64).

🔹 Estandarización de nombres: todas las columnas se normalizaron al español en minúsculas y con guiones bajos.

🔹 Nuevas variables creadas:

cargo_diario → derivado del cargo mensual.

cantidad_servicios → suma de servicios contratados por cliente.

🔎 Análisis Exploratorio de Datos (EDA)

El análisis reveló patrones clave en el comportamiento de los clientes:

📉 Tasa de churn: cerca del 25% de los clientes abandonan el servicio.

🔄 Variables categóricas: tipo de contrato, forma de pago, servicios adicionales y presencia de dependientes muestran diferencias significativas en los niveles de churn.

📊 Variables numéricas:

Mayor permanencia ↔ clientes con más meses de contrato y más servicios contratados.

Mayor churn ↔ clientes con cargos mensuales más altos o con pocos servicios.

🧩 Correlaciones: meses_contrato tiene la correlación negativa más fuerte con el churn → la antigüedad es un factor clave de retención.

📈 Conclusiones e Insights

Antigüedad con la empresa: los clientes con más tiempo de permanencia tienen menor propensión a abandonar → fidelización temprana es clave.

Carga económica: cargos mensuales altos aumentan levemente el abandono → revisar precios y valor percibido.

Compromiso con el servicio: más servicios contratados se asocian con menor churn → impulsar paquetes integrados.

Factores personales: clientes con pareja o dependientes presentan menor churn → segmentar estrategias de acuerdo al perfil familiar.

✅ Recomendaciones

Modelo predictivo de churn: construir un modelo para identificar clientes con alto riesgo de abandono.

Campañas de retención focalizadas: dirigir acciones a clientes vulnerables (ej. contratos mensuales o con pocos servicios).

Mejorar el onboarding: fortalecer la experiencia de nuevos clientes para aumentar la probabilidad de permanencia.

🚀 Tecnologías utilizadas

Python 🐍

Pandas

Matplotlib

Seaborn

👉 Este análisis constituye una base sólida para analítica avanzada, orientada a decisiones estratégicas basadas en datos (data-driven decision making).
