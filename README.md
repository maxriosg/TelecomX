Telecom X – Análisis de Evasión de Clientes
Descripción del Proyecto
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre los clientes de la empresa Telecom X con el objetivo de comprender los factores que influyen en la evasión de clientes (churn) y detectar patrones útiles para reducirla.
Estructura del Proyecto
- Telecomx.ipynb – Notebook principal con limpieza, análisis y visualización.
- README.docx – Documentación del proyecto.
- telecomx_dataset_limpio.csv – Dataset limpio y procesado (opcional).
- requirements.txt – Librerías necesarias para reproducir el análisis (opcional).
Objetivos
- Importar y transformar datos desde una fuente JSON.
- Aplicar procesos de limpieza y estandarización de datos.
- Analizar la distribución de la evasión según variables categóricas y numéricas.
- Extraer insights clave y ofrecer recomendaciones estratégicas para reducir el churn.
- Preparar los datos para futuras aplicaciones de modelos predictivos.
Requisitos y dependencias
Este proyecto fue desarrollado en Google Colab. Puedes ejecutarlo sin instalar nada localmente, pero si deseas reproducirlo en tu entorno local, asegúrate de tener instalado:

- Python 3.x
- pandas
- matplotlib
- seaborn
- requests

Instalación rápida:
pip install -r requirements.txt
Cómo usar el proyecto
1. Abre el archivo Telecomx.ipynb en Google Colab.
2. Ejecuta las celdas paso a paso:
   - Carga de datos desde GitHub (JSON)
   - Limpieza y estandarización
   - Análisis exploratorio
   - Visualizaciones
   - Conclusiones y recomendaciones
3. (Opcional) Exporta los datos o genera informes automáticos desde el notebook.
Resultados y hallazgos
- Los clientes con contrato mensual tienen tasas de evasión mucho más altas.
- El churn es mayor en usuarios con poca antigüedad y pago manual.
- Clientes que pagan más por día tienden a cancelar más frecuentemente.
- Hay oportunidades de retención a través de cambios de contrato y facturación electrónica.
Recomendaciones
- Incentivar la migración de clientes mensuales a contratos anuales.
- Implementar modelos de predicción de churn con las variables detectadas como clave.
- Ofrecer descuentos o beneficios a clientes con alto pago mensual o baja antigüedad.

Autor
Desarrollado por: Maximiliano Ríos
Contacto: maxrios@gmail.com
Institución/Curso: Alura Latam - Proyecto de Data Science – Telecom X LATAM
