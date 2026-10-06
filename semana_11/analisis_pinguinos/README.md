# Análisis de Pingüinos

Proyecto de ciencia de datos para analizar un conjunto de datos sobre pingüinos.
Este repositorio contiene la configuración del entorno de desarrollo para que
cualquier integrante del equipo pueda replicarlo.

## Requisitos previos

- Python 3.13.14
- pip (incluido con Python)

## Estructura del proyecto

```
analisis_pinguinos/
├── .venv/              # Entorno virtual (no se sube a GitHub)
├── analisis.py         # Script de análisis
├── requirements.txt    # Dependencias con versiones fijadas
└── README.md           # Este archivo
```

## Configuración del entorno

### 1. Crear el entorno virtual

Desde la carpeta `analisis_pinguinos`:

**Windows**

```bash
python -m venv .venv
```

**macOS / Linux**

```bash
python3 -m venv .venv
```

### 2. Activar el entorno virtual

**Windows (PowerShell)**

```bash
.venv\Scripts\Activate.ps1
```

**Windows (CMD)**

```bash
.venv\Scripts\activate.bat
```

**macOS / Linux**

```bash
source .venv/bin/activate
```

Cuando el entorno está activo, aparece `(.venv)` al inicio de la línea de la terminal.

### 3. Instalar las dependencias

```bash
pip install -r requirements.txt
```

### 4. Verificar la instalación

```bash
pip list
```

Deben aparecer `pandas`, `matplotlib` y `seaborn` junto con sus dependencias.

## Librerías principales

| Librería   | Uso                                  |
|------------|--------------------------------------|
| pandas     | Manipulación de datos                |
| matplotlib | Visualización                        |
| seaborn    | Visualizaciones estadísticas         |

## Desactivar el entorno

```bash
deactivate
```
