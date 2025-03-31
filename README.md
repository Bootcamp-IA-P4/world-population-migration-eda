# Análisis Exploratorio de Datos Demográficos Mundiales  

## Descripción del Proyecto  

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre la evolución demográfica mundial desde 1960 hasta 2022. Utilizando un dataset limpio, se analizan tendencias globales y casos específicos que ilustran fenómenos demográficos relevantes.  

## Tecnologías Utilizadas  

- **Python**: Lenguaje principal de programación  
- **Pandas**: Manipulación y análisis de datos  
- **Matplotlib/Seaborn**: Visualización de datos  
- **NumPy**: Operaciones numéricas  

## Configuración del Entorno  

Para replicar este análisis en tu propio entorno, sigue estos pasos:  

### 1. Clonar el repositorio  
```bash
git clone https://github.com/jruizndev/population_eda.git  
cd population_eda
```

### 2. Crear y activar un entorno virtual  
#### En Windows  
```bash
python -m venv venv  
venv\Scripts\activate
```
#### En macOS/Linux  
```bash
python3 -m venv venv  
source venv/bin/activate
```

### 3. Instalar dependencias  
```bash
pip install -r requirements.txt
```

### 4. Ejecutar el notebook  
Abre Jupyter Notebook y ejecuta el archivo principal:  
```bash
jupyter notebook population_eda.ipynb
```

## Estructura del Análisis  

El análisis está dividido en las siguientes secciones:  

### 1. Exploración inicial y preparación de datos  
- Carga del dataset  
- Transformación de formato ancho a largo  
- Limpieza y análisis descriptivo básico  

### 2. Evolución de la población mundial  
- Análisis de la tendencia global de crecimiento poblacional  
- Visualización de la evolución desde 1960 hasta 2022  

### 3. Casos de estudio demográficos específicos  
- **Crisis demográfica post-soviética en Rusia (1985-2005)**: Impacto de la disolución de la URSS  
- **Crisis de refugiados en Venezuela (2014-2022)**: Éxodo masivo de población  
- **Impacto de la política del hijo único en China**: Análisis de tasas de crecimiento tras su implementación  

### 4. Comparación entre regiones  
- Contraste entre África Subsahariana y la Unión Europea  
- Diferencias en tasas de crecimiento y sus implicaciones socioeconómicas  

## Principales Hallazgos  

- La población mundial ha crecido exponencialmente pasando de 3 mil millones en 1960 a casi 8 mil millones en 2022.
- Eventos históricos y políticos pueden impactar fuertemente en las tendencias demográficas.  
- Regiones como África siguen creciendo, mientras que Europa enfrenta un estancamiento por envejecimiento poblacional.  
- Políticas gubernamentales, como la del hijo único en China, pueden modificar significativamente la evolución demográfica.  

## Posibles Mejoras Futuras  

Este análisis puede enriquecerse con:  

1. **Mayor contextualización histórica**  
   - Relacionar eventos clave (guerras, crisis económicas, pandemias) con cambios demográficos específicos.  
   
2. **Incorporación de nuevas variables**  
   - Tasas de natalidad y mortalidad  
   - Distribución de población por género y edad  
   - Movimientos migratorios más detallados  

3. **Análisis más avanzados**  
   - Predicción de tendencias demográficas usando modelos de Machine Learning  
   - Análisis de correlación entre factores económicos y crecimiento poblacional  

## Conclusiones  

El análisis demuestra cómo los datos demográficos reflejan cambios sociales, económicos y políticos a nivel global. Comprender estos patrones es clave para anticipar desafíos y oportunidades en el desarrollo mundial.  

