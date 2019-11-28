# Repositorio ejerciciofinal1

Adjunto en este repositorio se encuentran 3 documentos que son `proyectofinal1.Rmd`, que es donde se encuentra el archivo de `Rmarkdown` con los comandos utilizados, `proyectofinal1.html` que es el resultado final en formato `HTML`, y `FIFA 2018 Statistics.xlsx` que es la base de datos utilizada en una de las secciones.

**IMPORTANTE:** 
- Para poder ejecutar el documento correctamente en `Rmarkdown` primero se debe descargar la carpeta completa del repositorio en formato `.zip` y luego de esto se debe extraer (o `unzip`) la carpeta `.zip`.

- Después de extraer la carpeta, abrir el archivo `proyectofinal1.Rmd` y correr de manera normal.

- De no extraer (unzip) la carpeta descargada, no cargará la base de datos utilizada (también adjunta en la carpeta) en `R`.

Además de esto, el documento en formato Rmd para poder ser leído se requiere instalar los paquetes `readxl`, `ggplot2`, `dplyr`, `shiny`, `rvest`, `plyr`, `ggrepel`, `plotly`, `DT`, y `lubridate` mediante los comandos:

```
install.packages('readxl')
install.packages('ggplot2')
install.packages('dplyr')
install.packages('shiny')
install.packages('rvest')
install.packages('plyr')
install.packages('ggrepel')
install.packages('plotly')
install.packages('DT')
install.packages('lubridate')
```

Luego de instalados para cargarlos:

```
library(readxl)
library(ggplot2)
library(dplyr)
library(shiny)
library(rvest)
library(plyr)
library(ggrepel)
library(plotly)
library(DT)
library(lubridate)
```
