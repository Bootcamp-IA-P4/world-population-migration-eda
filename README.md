# Análisis Exploratorio de Datos: Migración Global y Regional

## 📋 Descripción

Este repositorio contiene un análisis exploratorio de datos (EDA) sobre los patrones de migración global y regional, con un enfoque especial en América Latina. El estudio analiza las causas y efectos demográficos de la migración en diferentes países y regiones, utilizando datos del Banco Mundial.

Este proyecto profundiza en los fenómenos migratorios que impactan directamente en las tendencias demográficas globales, analizando cómo los procesos migratorios transforman las estructuras poblacionales.

## 🔍 Hipótesis

Las personas tienden a emigrar en masa debido a acontecimientos muy marcados en la historia de cada lugar. Estos desplazamientos masivos, comúnmente llamados éxodos, generan cambios demográficos significativos tanto en los países emisores como en los receptores.

## 🌎 Casos de Estudio

El análisis se enfoca en varios casos emblemáticos:

1. **Venezuela**: Éxodo masivo (2014-2022) y su impacto en la reconfiguración demográfica regional.
2. **México**: Tendencias migratorias históricas (1980-2023) y análisis de factores determinantes.
3. **Argentina**: Flujos migratorios (1960-2023) y su relación con crisis políticas y económicas.
4. **Perú**: Transición de país emisor a receptor de migrantes y comparativa regional.
5. **Patrones Globales**: Perspectiva geoespacial de las principales crisis migratorias contemporáneas.

## 📊 Datos y Metodología

Los datos utilizados en este análisis provienen de:

- Población mundial: Banco Mundial (transformación a `world_population_long.csv`)
- Migración neta por países: Datos oficiales del Banco Mundial
- Análisis específico por país: Fusión de datasets generando `world_population_net_migration.csv`
- Factores adicionales (México): Incorporación de datos sobre criminalidad del Banco Mundial

## 📈 Principales Hallazgos

### Venezuela
- Pérdida poblacional de 4.57 millones de personas entre 2014-2022
- Transformación de patrones migratorios regionales, convirtiendo a países tradicionalmente emisores en receptores

### México
- Migración constante hacia EE.UU. con valores negativos persistentes
- Influencia de múltiples factores: sismos (1985, 2017), crisis económicas (1994, 2008, 2015), violencia y cambios políticos

### Argentina
- Flujos migratorios marcados por crisis políticas y económicas
- Migración neta positiva en la mayoría de los años, con éxodos significativos durante la dictadura militar (1977), Crisis del Corralito (2001) y crisis reciente (2020)

### Perú
- Transición de emigración neta constante a inmigración neta desde 2015
- Mayor emigración en 2007 (-236,745 personas) y máxima inmigración en 2018 (+339,067 personas)

### Global
- Crisis migratorias contemporáneas: Siria (2011-2022), Venezuela (2016-2022), Ucrania (2022)
- Regionalización de flujos migratorios y emergencia de nuevos polos de atracción económica

## 🛠️ Estructura del Repositorio

```
├── data/                     # Datos utilizados en el análisis
├── EDAS/                     # Notebooks de análisis exploratorio
│   ├── global_migration_patterns.ipynb
│   ├── mexico_migrate.ipynb
│   ├── Migraciones_Argentinas.ipynb
│   ├── peruvian_eda.ipynb
│   ├── population_eda.ipynb
│   └── venezuela_migrate.ipynb
├── .gitignore                # Archivos y carpetas ignorados por git
├── README.md                 # Este archivo
└── requirements.txt          # Dependencias del proyecto
```

## 🚀 Comenzando

### Prerrequisitos

```bash
# Clonar el repositorio
git clone https://github.com/Bootcamp-IA-P4/world-population-migration-eda.git
cd world-population-eda

# Crear entorno virtual
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt
```

### Uso

Los principales análisis se encuentran en notebooks Jupyter individuales dentro de la carpeta EDAS. Puedes ejecutarlos con Jupyter Notebook, Jupyter Lab, VSCode o cualquier otro entorno compatible con archivos .ipynb:

```bash
# Ejemplo para ejecutar un notebook específico
jupyter notebook EDAS/global_migration_patterns.ipynb
```

## 🔄 Relación con el EDA de Población Mundial

Este proyecto expande el análisis demográfico global inicial que se encuentra en el archivo `EDAS/population_eda.ipynb`, que exploró:

- La evolución de la población mundial desde 1960 hasta 2022
- Crisis demográficas como la post-soviética en Rusia (1985-2005)
- Impacto de políticas como la del hijo único en China (1979-2020)
- Comparaciones entre regiones como África Subsahariana y la Unión Europea (1960-2022)

Al identificar los importantes cambios demográficos causados por la migración, surgió la necesidad de un análisis más profundo enfocado específicamente en los patrones migratorios y sus causas, dando origen a este proyecto.

## 📑 Informe Ejecutivo

Para una visión completa y resumida de este análisis, puedes consultar nuestro [Informe Ejecutivo](https://github.com/jruizndev/world-population-eda/blob/main/InformeEjecutivo.pdf) que presenta los principales hallazgos y conclusiones del estudio.

## 📚 Referencias

1. World Population - [Banco Mundial](https://data.worldbank.org/indicator/SP.POP.TOTL)
2. Base de Datos Limpia - [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/ayushparwal2026/country-population-from-1960-to-2022/data))
3. Migración Neta - [Banco Mundial](https://data.worldbank.org/indicator/SM.POP.NETM)
4. Tasa de Homicidios - [Banco Mundial](https://data.worldbank.org/indicator/VC.IHR.PSRC.P5)

## 👥 Contribuidores

| Contribuidor | GitHub |
|--------------|--------|
| Jose Alfonso Ruiz | [![GitHub](https://img.shields.io/badge/GitHub-jruizndev-2ea44f?style=flat&logo=github)](https://github.com/jruizndev) |
| Veida Velázquez | [![GitHub](https://img.shields.io/badge/GitHub-DarthVada36-2ea44f?style=flat&logo=github)](https://github.com/DarthVada36) |
| Máximiliano Scarlato | [![GitHub](https://img.shields.io/badge/GitHub-MaximilianoScarlato-2ea44f?style=flat&logo=github)](https://github.com/MaximilianoScarlato) |
| Omar Lengua | [![GitHub](https://img.shields.io/badge/GitHub-Omarlsant-2ea44f?style=flat&logo=github)](https://github.com/Omarlsant) |

## 📄 Licencia

Este proyecto está bajo la Licencia MIT 
