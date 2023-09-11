# Hackathon Iberia 2023 Demo

## Description
The 2023 Hackathon organized by AWS Iberia was based on the use of technology to generate a social impact. Several companies and NGOs proposed challenges related to sustainability and environment, inclusion and accessibility, and disadvantaged and vulnerable groups.

The project developed as a response to one of the proposed challenges was based on the definition of “energy regions” in Spain from municipal data of electric power generated with renewable sources, obtained from the Ministry for Ecological Transition. Machine Learning algorithms and geospatial analysis, in conjunction with graph theory, were used to generate clusters of neighboring municipalities with similar values of electricity production from different renewable energy sources. In this way, it is possible to know in detail the distribution and exploitation of these renewable sources in Spanish territory, identifying regions with potential for improvement.

## Team
Team "Team 33" formed by:
* Antonio Castañares Rodríguez
* Ignacio Gómez Valverde
* Francisco Moraleda Moreno

## Content
* Data/
    * energia/ | población/ | poly_canarias/ | poly_peninbal/ - Input Data
    * Mapas/ - Output Data
* Demo.ipynb - Notebook with the demo webpage interface
* prueba-geoclustering-energ-a.ipynb - Notebook containing all the data analysis and clustering
* requirements.txt - Python packeges needed for the demo to work

## RUN
Its highly recommended to use a python virtual enviroment (venv o conda) for both insalling the packages and deploying the webapp.\
Deployment made using voila on localhost:8866\
```pip install -r requirements.txt```\
```jupyter trust demo.ipynb```\
```jupyter trust prueba-geoclustering-energ-a.ipynb```\
```voila --VoilaConfiguration.file_whitelist="['.*']" .\demo.ipynb```
