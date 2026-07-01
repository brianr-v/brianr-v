# ¡Hola! Soy Brian Rosales 👋

### Mathematical Engineer & Data Scientist
Egresado de la Ingeniería Matemática por el **Instituto Politécnico Nacional (IPN)**. Especializado en el diseño, desarrollo e implementación de modelos de Machine Learning, forecasting de alta precisión y analítica de datos orientada a resolver impactos reales de negocio.

Comprometido con la eficiencia de cómputo, la optimización algorítmica y la transformación de datos crudos en decisiones estratégicas de negocio.

---

##  Stack Tecnológico

* **Lenguajes:** Python (Avanzado), SQL.
* **Manipulación de Datos & Rendimiento:** Polars (Optimización en paralelo), Pandas, NumPy.
* **Machine Learning & Forecasting:** LightGBM, Facebook Prophet, Scikit-learn, XGBoost, Random Forest.
* **Bases de Datos & Infraestructura:** PostgreSQL, Docker, Docker-compose.
* **Entorno de Desarrollo:** Git, GitHub, Linux/VPS.

---

##  Proyectos Destacados de Machine Learning / Forecasting

### 1. Motor Predictivo End-to-End: El Dilema del Stock (M5 Forecasting - Walmart)
**Claves:** `LightGBM` | `Polars` | `Feature Engineering` | `Time Series` | `Big Data`

Desarrollo de un motor predictivo a escala industrial para anticipar la demanda diaria de más de 3,000 productos distribuidos en 10 tiendas de Walmart (CA, TX, WI) con un horizonte de 28 días, mitigando el problema de la demanda intermitente.

* **Optimización de Memoria (Big Data):** Migré el pipeline completo de preparación de datos de Pandas a **Polars**, procesando 5 años de ventas históricas de manera ultra eficiente en paralelo, evitando el colapso de RAM.
* **Ingeniería de Variables Avanzada:** Construcción de matrices de características basadas en tres pilares:
    1. *Inercia del Consumidor:* Lags de 7, 14 y 28 días.
    2. *Tendencias Suavizadas:* Ventanas móviles (medias y desviaciones estándar).
    3. *Contexto Externo:* Mapeo de días festivos y el impacto masivo del subsidio alimentario de EE.UU. (**Efecto SNAP**).
* **Modelado Jerárquico:** Implementación de `LGBMRegressor` basado en histogramas para capturar relaciones no lineales y entrenar modelos especializados por jerarquías (categorías específicas por estado).
* **Impacto de Negocio:** El modelo final alcanzó un **MAE de 2.10 unidades** y un **RMSE de 3.62**. Esto se traduce en una desviación promedio de apenas ~2 unidades por artículo, permitiendo:
    * **Optimización del Stock de Seguridad:** Reducción del sobrestock y liberación de flujo de caja inmovilizado.
    * **Garantía de Disponibilidad:** Prevención de quiebres de stock en góndolas mediante alertas automatizadas.

🔗 [https://github.com/brianr-v/M5-Forecasting](url-repositorio)

---

### 2. Predicción de Ventas Mensuales con Intervalos de Confianza
**Claves:** `Facebook Prophet` | `Time Series Forecasting` | `Business Analytics`

Desarrollo e implementación de un modelo de forecasting utilizando **Facebook Prophet** enfocado en predecir tendencias de ventas a nivel mensual.

* **Enfoque de Negocio:** Diseñado para la toma de decisiones macro (planeación financiera y de inventario a mediano plazo).
* **Incertidumbre Controlada:** Incorporación de intervalos de confianza robustos para mitigar el riesgo financiero en escenarios de alta volatilidad.
* **Análisis de Estacionalidad:** Modelado automático de componentes de tendencia y estacionalidades anuales/mensuales.


---

##  Otros Proyectos & Experiencia Técnica
* **Desarrollo de Sistemas de Análisis:** Diseño y backend de sistemas web con arquitectura robusta utilizando **PostgreSQL**, **Clerk** para autenticación y empaquetamiento con **Docker / Docker-compose**.
* **Modelación Matemática Aplicada:** Experiencia en optimización y análisis de datos en sectores estratégicos (energía/retail).

---

##  Hablemos de Datos y Negocio
* **LinkedIn:** [https://www.linkedin.com/in/brian-axel-rosales-valderrama-1b94772a2/](url-linkedin)
* **Ubicación:** Ciudad de México



