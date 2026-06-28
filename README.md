# TP de Visualización de Datos

Análisis y visualización geoespacial de datos educativos de Argentina: distribución de establecimientos, matrícula escolar y conectividad a internet, integrando datos del Relevamiento Anual del Ministerio de Educación con capas geoespaciales.


## Cómo correrlo

Requiere **Python 3.11**

### 1. Crear y activar un entorno virtual

```bash
py -3.11 -m venv .venv
```

**Windows (PowerShell):**
```powershell
.venv\Scripts\activate
```

Vas a ver `(.venv)` al principio de la línea de comandos cuando esté activado correctamente.

### 2. Instalar las dependencias

Con el entorno activado:
```bash
pip install -r requirements.txt
```

Esto instala las versiones exactas de cada librería (pandas, geopandas, folium, etc.) que se usaron para armar el TP, evitando errores por incompatibilidad de versiones entre distintas máquinas.

### 3. Abrir y correr el notebook

## Fuentes de datos

- Portal Nacional de Datos Públicos: https://datos.gob.ar/
- API Georef / IGN: https://www.ign.gob.ar/ y https://apis.datos.gob.ar/georef/api/v2.0/
- Mapa Educativo Nacional: https://mapa.educacion.gob.ar/
