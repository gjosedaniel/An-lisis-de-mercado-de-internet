# Análisis del Mercado de Internet en Argentina.

## Introducción.
Este repositorio contiene un análisis integral sobre el mercado de conectividad a internet en Argentina, con un enfoque en:

- Identificar tendencias y oportunidades en el uso de tecnologías.
- Velocidades de conexión y cobertura. Incluye procesos de ETL (Extracción, Transformación y Carga de datos), un Análisis Exploratorio de Datos (EDA) para una comprensión inicial del dataset, y conclusiones presentadas mediante un dashboard interactivo en formato .PBIX, con KPIs medibles y filtros adaptados a diversas necesidades.

## Tabla de Contenido.

1. Introducción
2. Instalación y Requisitos
3. Estructura del Proyecto
4. Datos y Fuentes
5. Metodología
6. Reporte y KPIs
7. Autor y Licencia

## Instalación y Requisitos.

### Pasos para iniciar:
1. Clona este repositorio:

    git clone (URL)

2. Navega al directorio del proyecto:

    cd (directorio-proyecto)

3. Crea un entorno virtual:

    python -m venv venv

4. Activa el entorno virtual:

    - En Windows: venv\Scripts\activate
    - En macOS/Linux: source venv/bin/act

5. Instala las dependencias necesarias:

    pip install -r requirements.txt

## Estructura del Proyecto.
El proyecto está organizado de la siguiente manera:

├── data/
│   └── Archivos de datos en formato CSV generados a partir de Excel.
├── notebooks/
│   ├── ETL: Transformaciones y limpieza de datos.
│   ├── EDA: Análisis exploratorio y visualización inicial de los datos.
├── dashboard/
│   └── Archivo visual interactivo (.PBIX) creado en Power BI.
├── requirements.txt
│   └── Lista de bibliotecas y dependencias necesarias.
└── README.md
    └── Documentación detallada sobre la metodología y resultados.

## Datos y Fuentes.

**ENACOM Internet:**
El Ente Nacional de Comunicaciones (ENACOM) regula las telecomunicaciones en Argentina, abarcando servicios de internet, telefonía y radiodifusión.

## Metodología.

### Proceso ETL:
- Separación del archivo Excel por páginas.
- Conversión del tipo de dato y corrección de errores.
- Integración de datos como inflación e ingresos en una tabla consolidada.
- Exportación de los datos limpios en formato CSV a la carpeta data.

### EDA (Exploración de Datos):
- Análisis del crecimiento de conectividades por año.
- Evaluación del crecimiento de conexiones por provincia entre 2014-2024.
- Distribución tecnológica actual.
- Evolución de tecnologías y accesos dial-up.
- Impacto de la inflación en ingresos reales.

## Reporte y KPIs
El reporte cubre la evolución de tecnologías, velocidades de conexión y cobertura regional en Argentina desde 2014 hasta 2024. Utilizando un dashboard interactivo (.PBIX) desarrollado en Power BI, los usuarios pueden explorar:
- Métricas detalladas.
- Tendencias clave en internet y telecomunicaciones.

## KPIs principales.

1. **Reducción de accesos dial-up en Buenos Aires:**
    **Objetivo:** Migrar usuarios de tecnologías obsoletas a banda ancha.
    **Acciones sugeridas:**
    - Incentivos: Subvenciones y descuentos.
    - Publicidad segmentada enfocada en las ventajas de nuevas tecnologías.

2. **Aumento de velocidad promedio en el sur de Argentina:**
    **Objetivo:** Mejorar la infraestructura y capacidad de red en provincias rezagadas.
    **Acciones sugeridas:**
    - Evaluar infraestructura actual.
    - Desarrollar ofertas comerciales enfocadas en equipos modernos.

3. **Mejora de conectividad en el norte del país:**
    **Objetivo:** Reducir la brecha digital en provincias con menor penetración.
    **Acciones sugeridas:**
    - Expansión estratégica de infraestructura.
    - Programas promocionales para zonas rurales.