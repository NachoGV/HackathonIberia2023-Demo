# Demo para el Hackathon Iberia 2023

## Contenido
* Data/ - Carpeta con los datos utilizados en el notebook
    * energia/ | población/ | poly_canarias/ | poly_peninbal/ - Datos de entrada
    * Mapas/ - Datos de salida
* Demo.ipynb - Notebook con el código de la demo de la interfaz
* prueba-geoclustering-energ-a.ipynb - Notebook con el código que genera los mapas de la demo
* requirements.txt - Paquetes necesarios para ejecutar el notebook

## RUN
Se recomienda utilizar un entorno virtual (venv o conda) para instalar los paquetes y desplegar la interfaz.\
La interfaz se despliega con voila en localhost:8866\
```pip install -r requirements.txt```\
```jupyter trust demo.ipynb```\
```jupyter trust prueba-geoclustering-energ-a.ipynb```\
```voila --VoilaConfiguration.file_whitelist="['.*']" .\demo.ipynb```