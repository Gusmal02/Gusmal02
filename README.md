# ¡Hola! Soy Gustavo Alfonso Maldonado Vallejo 👋

## Data Scientist & Cybersecurity Specialist | Machine Learning aplicado a la Ciberseguridad

Me apasiona la intersección entre la **Ciencia de Datos** y la **Seguridad Informática**. Mi enfoque principal está en el desarrollo de modelos predictivos, el análisis inteligente de datos para la detección de amenazas y la automatización de auditorías de seguridad. Me destaco por mi curiosidad extrema, capacidad de investigación independiente y resolución de problemas técnicos complejos.

---

## 🛠️ Stack Tecnológico

### 📊 Ciencia de Datos & Machine Learning
* **Modelos Predictivos:** Regresión Lineal, Regresión Logística, Árboles de Decisión, Random Forest, LightGBM, CatBoost.
* **Procesamiento de Datos:** Pandas, NumPy, Scikit-Learn.
* **Técnicas Avanzadas:** Balanceo de clases (Upsampling / Downsampling), evaluación avanzada de métricas (F1-Score, AUC-ROC, Matrices de Confusión).
* **Deep Learning (Bases Teóricas):** Fundamentos de aprendizaje no supervisado con PyTorch, Redes Convolucionales (CNN), Visión Artificial y lógica del algoritmo YOLO.

### 🛡️ Ciberseguridad & Automatización
* **Seguridad Defensiva:** Análisis de comportamiento de entidades (UEBA), respuesta a incidentes (IR), técnicas de enmascaramiento y ofuscación de datos sensibles (PII).
* **Auditoría de Redes:** Escaneo y descubrimiento de servicios mediante Nmap.
* **Infraestructura & Contenedores:** Gestión y despliegue local con Docker y Kubernetes.
* **Automatización:** Comprensión lógica y diseño de flujos con n8n.

---

## 🚀 Portafolio de Proyectos Destacados

### 1. 🛡️ Network Sentinel: Detección Temprana de Ataques DDoS
* **Descripción:** Sistema ligero basado en Machine Learning local (Edge Computing) diseñado para diferenciar picos de tráfico legítimos de ataques volumétricos.
* **Solución:** Implementa ventanas deslizantes (lags de 24h) y Regresión Lineal para establecer una línea base de tráfico estacional diario, disparando alertas críticas automatizadas cuando el tráfico real supera 3 veces la predicción.
* **Tecnologías:** Python 3.12, Pandas, NumPy, Scikit-Learn, Matplotlib.

### 2. ⚡ Sistema Dinámico de Respuesta ante Incidentes
* **Descripción:** Motor de decisión en tiempo real que optimiza la latencia y la profundidad del análisis en la detección de intrusiones en red según el estado actual del servidor.
* **Solución:** Evalúa la carga de CPU y la criticidad del activo para seleccionar dinámicamente entre **LightGBM** (respuesta rápida con baja latencia) y **CatBoost** (inspección profunda). Procesó más de 400,000 registros del dataset CIC-IDS2017 con una precisión del 99.2%.
* **Tecnologías:** Python 3.12, LightGBM, CatBoost, Scikit-Learn, Pandas.

### 3. 📦 Network Security Scanner Container
* **Descripción:** Contenedor portable diseñado para agilizar y automatizar las auditorías de seguridad perimetral sin configuraciones complejas en el host.
* **Solución:** Empaqueta un script de Python que automatiza el descubrimiento de servicios y escaneo de puertos mediante el motor profesional **Nmap**, entregando reportes legibles de riesgos potenciales.
* **Tecnologías:** Docker, Python 3.11, Nmap, Debian Slim.

### 4. 🧮 Ofuscación de Datos mediante Enmascaramiento Matricial
* **Descripción:** Algoritmo de protección de datos en reposo enfocado en la privacidad de información confidencial (PII) al compartir bases de datos para análisis estadísticos.
* **Solución:** Implementa un método basado en álgebra lineal que utiliza la multiplicación de una matriz invertible como "llave". Los datos se vuelven irreconocibles para atacantes pero son 100% recuperables mediante el uso de la matriz inversa.
* **Tecnologías:** Python, NumPy, Pandas.

### 5. 📉 Monitor de Anomalías y Análisis de Riesgo Financiero
* **Descripción:** Clasificador optimizado para detectar comportamientos anómalos (Churn) e integridad de cuentas financieras en escenarios con alto desbalance de clases.
* **Solución:** Utiliza un modelo **Random Forest** combinado con técnicas de sobremuestreo (Upsampling) para identificar eventos raros, evaluando el desempeño mediante F1-Score y AUC-ROC para minimizar falsos positivos.
* **Tecnologías:** Python, Scikit-Learn, Pandas.

---

## 📬 Conéctate conmigo

Si quieres platicar sobre Machine Learning aplicado a la seguridad, automatización o proyectos open-source, no dudes en contactarme:

* 📧 **Correo Electrónico:** [gustavo.a.maldonado.v@gmail.com](mailto:gustavo.a.maldonado.v@gmail.com)
* 💼 **LinkedIn:** [linkedin.com/in/gustavo-maldonado-519638376](https://www.linkedin.com/in/gustavo-maldonado-519638376/)
* 💻 **GitHub:** [github.com/Gusmal02](https://github.com/Gusmal02)
