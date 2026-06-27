# TP de Visualización de Datos

Análisis y visualización geoespacial de datos educativos de Argentina: distribución de establecimientos, matrícula escolar y conectividad a internet, integrando datos del Relevamiento Anual (RA) del Ministerio de Educación con capas geoespaciales (Georef/IGN).

## Cómo correrlo

Requiere **Python 3.11**.

```bash
python -m venv .venv
source .venv/bin/activate      # En Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Después, abrí el notebook `TP_Visualizacion_datos.ipynb` con Jupyter o VSCode y ejecutá todas las celdas en orden. La primera celda instala automáticamente cualquier dependencia faltante.

## Estructura del repo


## Fuentes de datos

- Portal Nacional de Datos Públicos: https://datos.gob.ar/
- API Georef / IGN: https://www.ign.gob.ar/ y https://apis.datos.gob.ar/georef/api/v2.0/
- Mapa Educativo Nacional: https://mapa.educacion.gob.ar/
