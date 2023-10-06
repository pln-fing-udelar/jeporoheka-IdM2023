# Jeporoheka (Ingeniería de Muestra 2023)

En este repositorio se encuentran los datos de entrenamiento (``train.csv``) y desarrollo (``dev.csv``) para la competencia **Jeporoheka**. 
Cada ``.csv`` contiene pares (palabra,lenguaje), donde el identificador del español es "es" y el del guaraní es "gn".


Para la carga de datos se puede seguir el enfoque que resulte más práctico, pero una recomendación es usar:

```
import urllib.request

urllib.request.urlretrieve("https://raw.githubusercontent.com/pln-fing-udelar/jeporoheka-IdM2023/main/train.csv", "train.csv")
urllib.request.urlretrieve("https://raw.githubusercontent.com/pln-fing-udelar/jeporoheka-IdM2023/main/dev.csv", "dev.csv")

```

## Más detalles

Por más detalles dirigirse a la web de los desafíos: https://www.fing.edu.uy/inco/grupos/pln/desafiosPLN/

Correo de contacto: pln@fing.edu.uy
