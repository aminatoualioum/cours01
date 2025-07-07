# cours01
recensement sur les differentes maladies pour un effectif de 50 personnes

## Importation d'un fichier csv avec R


```{r}
db<- read.csv( file ="classeur.csv" ,header = TRUE,sep = ";")
db
```