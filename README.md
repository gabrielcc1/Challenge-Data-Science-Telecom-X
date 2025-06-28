# 📊 Análisis de Evasión de Clientes (Churn) - TelecomX LATAM

Este proyecto tiene como objetivo analizar los datos de una empresa de telecomunicaciones ficticia para identificar **factores que influyen en la cancelación de servicios por parte de los clientes (churn)**. 
A través de análisis exploratorios y visualizaciones, se busca extraer insights accionables para mejorar la retención de usuarios.

---

## 🧠 Objetivos del Proyecto

- Detectar patrones en el comportamiento de los clientes que cancelan el servicio.
- Entender variables como duración del contrato, forma de pago y servicios contratados influyen en la evasión.
- Generar recomendaciones estratégicas basadas en datos.

---
## 📁 Estructura del Proyecto

- README.md               # Este archivo
- TelecomX_LATAM.ipynb    # Notebook principal con el análisis completo
- Datos                   # Datos utilizados (JSON desde URL)


---

## 🧹 Limpieza y Procesamiento de Datos

- Se importó un archivo `.json` estructurado en forma de diccionarios anidados.
- Se utilizaron herramientas como `pd.json_normalize()` para desanidar las columnas.
- Se tradujeron nombres de variables al español para mejor interpretación.
- Se convirtieron valores de texto ("Sí"/"No") a binarios (1/0).
- Se creó la variable `Cuentas_Diarias` basada en la facturación mensual.
- Se trataron valores faltantes y se ajustaron tipos de datos para análisis numérico.

---

## 🔍 Análisis Exploratorio

- **Distribución general del churn** (cancelación).
- Análisis por variables **categóricas**: contrato, método de pago, pareja, dependientes, etc.
- Análisis por variables **numéricas**: meses de contrato, cargos mensuales y totales.
- Uso de gráficos para representar insights clave.

---

## 📌 Principales Hallazgos

- El churn es **más alto en contratos mensuales** que en anuales.
- Clientes que pagan por **cheque electrónico o tienen cargos altos** son más propensos a cancelar.
- Aquellos con **menor antigüedad** en el servicio (menos meses contratados) presentan mayor evasión.
- Usuarios sin pareja o sin dependientes muestran mayor tasa de cancelación.

---

## ✅ Recomendaciones

- Fomentar contratos anuales con promociones.
- Automatizar y facilitar métodos de pago.
- Incentivar a nuevos usuarios en los primeros 3 meses.
- Segmentar campañas de fidelización según el perfil de riesgo.

---

## 📌 Herramientas Usadas

- Lenguaje: `Python 3`
- Librerías: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
- Formatos: `JSON`, `Jupyter Notebook`

---

## 📈 Visualizaciones

Las visualizaciones generadas ayudan a comunicar de forma efectiva los patrones detectados y acompañan las recomendaciones propuestas.

---

## 🧾 Licencia

Este proyecto es de uso libre para fines educativos y de análisis de datos.  

---

## ✍️ Autor

**Cesar Caballero**  
📍 Argentina  
🚀 En formación en Ciencia de Datos.

---
