# Repositorio ejerciciofinal1

Adjunto en este repositorio se encuentran 3 documentos que son `proyecto final.Rmd`, que es donde se encuentra el archivo de `Rmarkdown` con los comandos utilizados, `proyecto-final.html` que es el resultado final en formato `HTML`, y `FIFA 2018 Statistics.xlsx` que es la base de datos utilizada en una de las secciones (aunque en el documento de `RMarkdown` los datos estan cargados vía Google Drive).

Pegar el código que se muestra a continuación en la consola de R 
`url <- 'https://drive.google.com/open?id=1G7xOGjsY3j2aveXKZDCbP8jFDZ0TY4Mr'
drive_download(url, overwrite = TRUE)`
La consola de R te preguntara si le das permiso y escribimos `Yes` en la consola.
Se abrirá una ventana en tu navegador predeterminado y concederás acceso a la API para que pueda descargar los archivos
Ya puedes ejecutar el código de R-MarkDown!

El documento en formato Rmd para poder ser leído se requiere instalar los paquetes `readxl`, `ggplot2`, `dplyr`, `shiny`, `rvest`, `plyr`, `ggrepel`, `plotly`, `DT`, `lubridate`, `googledrive` mediante los comandos: 

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
