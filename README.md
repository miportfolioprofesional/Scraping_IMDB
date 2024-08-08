# 🎬 IMDB Top 250 Movies Web Scraper 🕷️

## 📝 Descripción
Este proyecto es un web scraper automatizado diseñado para extraer información sobre las 250 mejores películas según IMDB. Utiliza técnicas avanzadas de web scraping para recopilar datos como títulos, años de lanzamiento, duración y valoraciones, proporcionando una solución eficiente para el análisis de datos cinematográficos.

## ✨ Características
- 🤖 Extracción automatizada de datos de la página Top 250 de IMDB.
- 🌐 Manejo de elementos dinámicos de la página web.
- 🧠 Clasificación inteligente de metadatos (año, duración, valoración).
- 📊 Generación de un archivo Excel con datos estructurados y limpios.

## 🛠️ Tecnologías Utilizadas
- 🐍 Python
- 🌐 Selenium con undetected_chromedriver
- 🐼 Pandas para manipulación de datos
- 🔍 Expresiones regulares para procesamiento de texto

## 🚀 Funcionamiento
1. **🔧 Inicialización del WebDriver**: Configura un navegador Chrome no detectable para evitar bloqueos.
2. **📚 Extracción de Títulos**: Navega a la página de IMDB y extrae los títulos de las películas.
3. **🕵️ Recopilación de Metadatos**: Realiza una segunda pasada para extraer información adicional (año, duración, valoración).
4. **🧮 Procesamiento de Datos**: Clasifica y estructura la información extraída.
5. **🔗 Fusión de Datos**: Combina los títulos con sus respectivos metadatos.
6. **💾 Exportación**: Genera un archivo Excel con toda la información recopilada y procesada.

## 💡 Beneficios
- **⏱️ Automatización**: Reduce significativamente el tiempo necesario para recopilar datos manualmente.
- **🎯 Precisión**: Minimiza errores humanos en la recopilación de datos.
- **🔄 Actualización**: Facilita la obtención de datos actualizados regularmente.
- **📈 Análisis**: Proporciona una base de datos estructurada lista para análisis posteriores.

## 🔧 Uso
1. Asegúrate de tener todas las dependencias instaladas.
2. Ejecuta el script principal.
3. El script navegará automáticamente por IMDB, extraerá los datos y generará un archivo Excel llamado 'df_merged.xlsx'.

## ⚠️ Nota
Este proyecto está diseñado con fines educativos y de demostración. Asegúrate de cumplir con los términos de servicio de IMDB y las leyes de propiedad intelectual al utilizar este scraper.
