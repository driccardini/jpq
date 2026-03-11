# JPQ Resultados (Streamlit)

App responsive para visualizar partidos y resultados por **categoría** y **zona** desde Google Sheets.

## Requisitos

- Python 3.9+

## Instalación

```bash
pip install -e .
```

## Ejecutar

```bash
streamlit run main.py
```

La app trae por defecto tu sheet de torneo y detecta automáticamente las pestañas visibles que contienen `Zonas`.

## Qué muestra

- Selector de **Categoría** (pestaña visible)
- Selector de **Zona**
- Tarjetas de partidos (día, hora, complejo, parejas y resultado)
- Tabla expandible con detalle
- Actualización automática cada **4 minutos**

## Notas

- El Google Sheet debe ser público de lectura para funcionar sin login.
- Si una planilla aún no tiene sets cargados, se muestra estado `No Jugado`.
- Fondo opcional: guardá tu imagen en `assets/logo.png` y la app la usa automáticamente como fondo.
