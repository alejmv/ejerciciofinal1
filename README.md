# Repositorio ejerciciofinal1

Adjunto en este repositorio se encuentran 3 documentos que son `proyectofinal.Rmd`, que es donde se encuentra el archivo de `Rmarkdown` con los comandos utilizados, `proyectofinal.html` que es el resultado final en formato `HTML`, y `FIFA 2018 Statistics.xlsx` que es la base de datos utilizada en una de las secciones (aunque en el documento de `RMarkdown` los datos estan cargados vía Google Drive).

**IMPORTANTE:** 
- Para poder cargar los datos de Google Drive se debe pegar en la consola de R el código que se muestra a continuación:

`url <- 'https://drive.google.com/open?id=1G7xOGjsY3j2aveXKZDCbP8jFDZ0TY4Mr'
drive_download(url, overwrite = TRUE)`
- Luego de esto la consola de R te preguntará si le das permiso y escribimos `Yes` en la consola.
- Se abrirá una ventana en tu navegador predeterminado y concederás acceso a la API para que pueda descargar los archivos.
- Ya será posible ejecutar el código del archivo `proyectofinal.Rmd`.

Además de esto, el documento en formato Rmd para poder ser leído se requiere instalar los paquetes `readxl`, `ggplot2`, `dplyr`, `shiny`, `rvest`, `plyr`, `ggrepel`, `plotly`, `DT`, `lubridate`, `googledrive` mediante los comandos: 

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
install.packages('googledrive')
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
library(googledrive)
```
