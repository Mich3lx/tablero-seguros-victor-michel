# Tablero Seguros Victor Michel

Aplicación Streamlit para explorar una cartera de seguros de auto, analizar siniestros, consultar indicadores por segmento y cotizar primas con modelos GLM.

Basada en el material del Diplomado Machine Learning en Seguros, FC UNAM, y el tablero original de MaritzaBFR-97/tablero-seguros.

## Ejecutar

```bash
python -m pip install -r requirements.txt
python -m streamlit run app_streamlit.py
```

Los datos están en `datos/datos.parquet`. La base SQLite se genera automáticamente y no se sube a GitHub.

## Publicar en Streamlit Community Cloud

1. Subir este proyecto al repositorio `tablero-seguros-victor-michel` de GitHub.
2. En https://share.streamlit.io seleccionar **Create app**.
3. Seleccionar el repositorio, la rama `main` y `app_streamlit.py`.
4. Usar Python 3.13 en las opciones avanzadas.
5. Solicitar el subdominio `tablero-seguros-victor-michel` y pulsar **Deploy**.

Enlace solicitado (pendiente de publicación y disponibilidad): https://tablero-seguros-victor-michel.streamlit.app
