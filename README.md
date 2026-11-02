# Recomendador de canciones de Spotify

Trabajo práctico final de **Fundamentos de Aprendizaje Automático** (MCD, Universidad Austral, 2026).

A partir de las canciones favoritas de un usuario y de un catálogo público de ~90.000 canciones, el notebook analiza en qué se diferencian las favoritas del resto y prototipa un recomendador por contenido basado en las *audio features* de Spotify.

## Archivos

| Archivo | Contenido |
|---|---|
| `TP_Recomendador_Spotify.ipynb` | El trabajo práctico, ejecutado |
| `TP_Analisis_de_Dataset_v3.ipynb` | Consigna original |
| `Liked_Songs.csv` | Favoritas del usuario, exportadas con [Exportify](https://exportify.net) (sin ID de cuenta) |
| `recomendaciones.csv` | Top 100 de canciones recomendadas por el modelo final |
| `requirements.txt` | Versiones de las librerías usadas |

El catálogo (*Spotify Tracks Dataset*) se descarga desde Hugging Face al ejecutar el notebook.

## Cómo ejecutarlo

En Google Colab: abrir el notebook y ejecutar todas las celdas (si no encuentra `Liked_Songs.csv`, abre un diálogo para subirlo).

En local:

```bash
python -m venv venv_recomendador_spotify
venv_recomendador_spotify\Scripts\activate
pip install -r requirements.txt
jupyter lab TP_Recomendador_Spotify.ipynb
```
