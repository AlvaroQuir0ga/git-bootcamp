# Clase 05 - Git 

## Para crear un repositorio de GIT 

```sh 
```

## Areas del repositorio GIT 

3 Areas 

* Working Directory (WD) : Directorio de trabajo donde se van agregando o quitando los archivos durante el desarrollo 
* Staging Area (SA) : Area de control de cambios. Area temporal/intermedia 
* Local Repo (LR) : Una caja donde voy a ir teniendo todas las fotos que vaya sacando 

## Estados de los archivos

* untracked: Archivos que estan en el WD pero GIT no les esta dando seguimiento
* unmodified: Archivos que GIT ya esta siguiendo y con respecto al WD, no fueron modificados
* modified: Archivos que se encuentran en el repositorio ( Estan siendo seguidos por GIT) pero difieren con lo que se encuentra actualmente en el WD 
* staged: Archivos que estan en el area temporal/intermedia  


# Persistimos los cambios agregados al area de confirmacion en un commit

```sh
git commit -m "mensaje descriptivo de lo que tiene el commit" 
``` 

# Corregir el mensaje del commit

```sh
git commit --amend -m "el mensaje corregido" 
```
# Como ver el timeline de commits 

```sh 
git log #version corta
git log --oneline #version larga 



