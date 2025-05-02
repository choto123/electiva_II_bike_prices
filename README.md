# PREDICCION PRECIOS DE BICICLETAS

Explicacion del proyecto y su funcionamiento.
/bike prices
|
|-- main.py
|-- data/
    |-- bike_prices.csv
|-- models/
|   |-- model.pkl
|-- templates/
|   |-- index.html
|-- static/
|   |-- style.css
|-- requirements.txt
|-- README.md
|-- .gitignore
|-- model_builder.py
|-- model_manager.py

## ejecucion del proyecto
1. clonar el repositorio
'git remote add origin https://github.com/choto123/electiva_II_bike_prices.git'

```bash
git clone 
```

2. crear un entorno virtual:
```bash
python -m venv .venv
```
3. activar entorno virtual
```bash
.venv\Script\activate
```
4. intalar las dependencias
```bash
pip install -r requirements.txt
```

5. lanzar la aplicacion:
```bash
uvicorn main:app --reload
```

6. abrir el navegador y acceder a 'http://localhost:8000'
