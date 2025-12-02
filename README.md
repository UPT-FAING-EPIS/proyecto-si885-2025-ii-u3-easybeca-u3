[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/VMb-1xPS)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=20268708)
# 🎓 Proyecto de Inteligencia de Negocios  
**Análisis de Becas y Caracterización de Becarios en el Perú**  
📍 **Universidad Privada de Tacna**  
**Facultad de Ingeniería – Escuela Profesional de Ingeniería de Sistemas**  
---
## 👥 Integrantes del Equipo  
- Calizaya Ladera, Andy Michael
- Vargas Gutierrez, Angel Jose
- Colque Ponce, Sergio Alberto
- Castillo Mamani, Diego Fernadinho
---
## ❗ Problemática  
Las becas universitarias en el Perú representan una oportunidad crucial para jóvenes con talento académico y limitaciones económicas. Sin embargo, la información sobre **distribución de becas, caracterización de becarios y cobertura institucional** está dispersa en múltiples fuentes (PDFs, convocatorias web, APIs de PRONABEC), lo que dificulta evaluar:  
- ¿Cuáles son las carreras y programas con mayor demanda de becas?
- ¿Qué instituciones ofrecen más oportunidades de becas?
- ¿Cuál es el perfil socioeconómico y demográfico de los becarios?
- ¿Cómo se distribuyen geográficamente las becas en el territorio nacional e internacional?
---
## 🎯 Objetivo General  
Analizar y visualizar la **distribución, caracterización y cobertura** de becas de apoyo en el Perú durante el período 2020-2025, mediante un enfoque de Inteligencia de Negocios que permita identificar patrones, tendencias y oportunidades de acceso.
---
## ✅ Objetivos Específicos  
- Recolectar y consolidar información de becas de programas como **PRONABEC, Generación del Bicentenario, Becas Chevening, Fulbright** y otros.
- Analizar la distribución de becas por **carrera profesional, institución educativa y ubicación geográfica**.
- Caracterizar el perfil de los becarios según **género, estrato socioeconómico y procedencia**.
- Identificar las **instituciones con mayor número de becas otorgadas** (universidades nacionales, privadas e institutos técnicos).
- Diseñar dashboards interactivos que permitan visualizar tendencias temporales (2020-2025) y distribución geográfica nacional e internacional.
- Proveer información estratégica para la toma de decisiones de estudiantes, familias y entidades educativas.
---
## 🛠️ Tecnologías Utilizadas  
- **Python 🐍** → Procesamiento y análisis de datos (pandas, numpy, PyPDF, requests).  
- **MySQL 🗄️** → Almacenamiento estructurado de la información de becas y becarios.  
- **Power BI 📊** → Dashboards interactivos para visualización de métricas y análisis temporal.  
---
## 📡 Metodología  
### 1. Extracción de datos  
- Recolección de datos históricos 2020-2025 de **convocatorias PRONABEC**.  
- Obtención de información de **APIs oficiales y dashboards públicos** de becas.
- Web scraping de portales educativos y documentos oficiales.
### 2. Procesamiento y limpieza  
- Normalización de datos de becas por año.
- Clasificación por categorías:  
  - **Tipo de beca**: Pregrado, Posgrado Maestría, Posgrado Doctorado, Especiales
  - **Institución**: Universidades públicas/privadas, institutos técnicos, universidades internacionales
  - **Ubicación**: Departamentos del Perú y países para becas internacionales
  - **Perfil del becario**: Género, estrato socioeconómico (Pobre, Pobre Extremo, No Pobre)
  - **Carrera**: Áreas de estudio y programas académicos
### 3. Cálculo de KPIs  
- **Total de becas otorgadas por año**
- **Distribución por género**
- **Distribución por estrato socioeconómico**
- **Top instituciones con mayor número de becas**
- **Cobertura geográfica nacional e internacional**
### 4. Visualización en Power BI  
- **Becas de Apoyo**: Análisis por carrera, institución y tipo de beca
- **Mapa de Becas**: Distribución geográfica nacional e internacional
- **Caracterización de Becarios**: Perfiles demográficos y socioeconómicos
- **Top de Universidades**: Ranking de instituciones con mayor cobertura
- **Filtros interactivos**: Por año (2020-2025), categoría y carrera
---
## 📊 Visualizaciones Implementadas

### 1. **BECAS DE APOYO**
- 📊 **Becas por carrera**: Ranking de programas más demandados
- 🥧 **Becas por institución**: Distribución porcentual entre universidades
- 📈 **Becarios por beca**: Comparación entre programas
- 🎯 **Filtros**: Por año, categoría de becas y carrera específica

<img width="1236" height="745" alt="image" src="https://github.com/user-attachments/assets/11f3784e-27aa-45e2-8e9e-2b1a19f7e87d" />


### 2. **MAPA DE BECAS**
- 🗺️ **Visualización geográfica**: Distribución de becas en territorio nacional e internacional
- 📍 **Cobertura por lugar**: Distribución departamental
- 📋 **Lista de carreras**: Más de 200 programas académicos identificados

<img width="1320" height="709" alt="image" src="https://github.com/user-attachments/assets/bac072c9-f696-45cb-8210-821f5809098d" />


### 3. **CARACTERIZACIÓN DE BECARIOS**
- 👥 **Distribución por género**: Análisis de participación por sexo
- 💰 **Estrato socioeconómico**: Distribución entre Pobre, Pobre Extremo y No Pobre

<img width="1253" height="732" alt="image" src="https://github.com/user-attachments/assets/ac63a502-e249-41a7-af68-2300a4ec97c0" />


### 4. **TOP DE UNIVERSIDADES BECAS**
- 🏆 **Ranking de instituciones**: Top instituciones con mayor número de becas
- 🎓 **Total de estudiantes beneficiados**: Métricas generales

<img width="1122" height="722" alt="image" src="https://github.com/user-attachments/assets/9ff6da4a-959a-4866-b402-dc3b071f52b1" />

---
## 🚀 Resultados Esperados  
- Identificación de **tendencias en la asignación de becas** por carrera, institución y región
- Análisis del **perfil demográfico y socioeconómico** de los becarios peruanos
- **Mapeo completo** de cobertura geográfica nacional e internacional
- Identificación de **instituciones líderes** en captación de becarios
- Dashboards interactivos que permiten **explorar y filtrar** información por múltiples dimensiones
- Herramienta de **apoyo estratégico** para estudiantes, orientadores académicos y entidades educativas
---
## 📦 Inventario de Artefactos del Proyecto  
| Código | Nombre del Documento | Tipo | Enlace |  
|--------|----------------------|------|--------|  
| FD01   | Informe de Factibilidad | PDF / DOCX | Ver |  
| FD02   | Informe de Visión | PDF / DOCX | Ver |  
| FD03   | Especificación de Requerimientos | PDF / DOCX | Ver |  
| FD04   | Arquitectura de Software | PDF / DOCX | Ver |  
| FD05   | Proyecto Final | PDF / DOCX | Ver |  
---
## 📌 Roadmap Futuro  
- Integrar datos de convocatorias 2026-2027 en tiempo real
- Automatizar la actualización de dashboards con **pipelines ETL**
- Incluir análisis predictivo: **proyección de demanda de becas por carrera**
- Desarrollar módulo de **recomendación personalizada** según perfil del estudiante
- Ampliar análisis a **becas de movilidad estudiantil** y programas de intercambio
- Implementar **alertas automáticas** de nuevas convocatorias según perfil
---
📎 **Video Explicativo del Proyecto (YouTube)**  
🔗 *(Se añadirá una vez grabado)*  

📊 **Dashboard en Power BI**  
🔗 [Ver Dashboard Interactivo](https://app.powerbi.com/onedrive/open?pbi_source=ODSPViewer&driveId=b!jP5Slrdq-060CjwVVNLKYo-ZmT31FnVOpI28pZdpOk3GkrdIXeEJSLQoy_8NEVqt&itemId=01WBF24WHAZF7TQGB63FC3U56VMNJYRHCA)
