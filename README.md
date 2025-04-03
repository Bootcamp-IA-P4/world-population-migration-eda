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
- Carga del dataset de migración neta y población total  
- Limpieza y transformación de datos  
- Análisis descriptivo inicial  

### 2. Impacto de la migración neta en la población total  
- Explicación de la variación de la población simulada eliminando migración neta negativa  
- Comparación entre población real y simulada  
- Visualización de las tendencias  

### 3. Análisis histórico de la emigración argentina  
- Principales destinos de emigración (América, Europa, Israel, Australia)  
- Factores históricos y políticos que impulsaron la emigración (dictadura militar, crisis económica, políticas migratorias)  
- Registros de salidas y documentación disponible  

### 4. Factores socioeconómicos de la emigración  
- Perfil del emigrante argentino (clase social, ocupación, lugar de origen)  
- Análisis de las provincias con mayor emigración (Buenos Aires, Mendoza, Córdoba)  
- Comparación con políticas migratorias en países de destino  

## Principales Hallazgos  

- La migración neta tiene un impacto relativamente pequeño en la población total de Argentina, dominada por el crecimiento natural (nacimientos menos muertes).  
- La población simulada, eliminando migración neta negativa, es ligeramente mayor que la población real, pero las diferencias no son significativas.  
- Las principales olas de emigración ocurrieron durante la dictadura militar (1976-1983), la crisis económica de 2001 y la eliminación de visas hacia Estados Unidos en los años 90.  
- Los destinos más comunes de emigración incluyen España, Italia, Estados Unidos, y países vecinos como Chile, Paraguay y Brasil.  

## Posibles Mejoras Futuras  

Este análisis puede enriquecerse con:  

1. **Mayor contextualización histórica**  
   - Relacionar eventos clave (dictaduras,