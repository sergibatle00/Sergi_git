# Practica 1

Clonamos el repositorio de github a nuetro pc con el comando:

```
git clone [URL del directorio]
```

![git clone](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/1.1.PNG)

## git add y commit
Usamos git add  y git commit -r "comentario" para subi el directorio al repositorio local
![git commit](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/1.add.PNG)
![git add](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/1.2.PNG)

## git pull y git push

Usamos git pull origin main y git push origin main para subirlo al repositorio remoto

![git push](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/1.3.PNG)

![git pull](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/1.4.PNG)

Para devolver un archivo a un hash concreto usamos git checkout hash-de-la-revisión -- nombre-de-archivo

![git pull](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/1.6.PNG)

# Practica 2

## Comprobamos commits realizados con el comando git log --oneline --all

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.PNG)

## Miramos el contenido del Readme en el último commit con el comando cat README.md

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.1.PNG)

## Nos movemos al primer commit usando el comando: git checkout [hash del commit] en este caso git checkout 711f4fb y comprobamos que ahora el main se encuentra en el primer commit con git log --oneline --all

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.3.PNG)

## Volvemos al último commit usando el comando git checkout main

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.4.PNG)

# Practica 3

Etiquetar commits

Para etiquetar utilizamos el comando

```
git  tag  -a  nombre_etiqueta  -m  "Mensaje"   commit_a_etiquetar
```


![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/3.1.PNG)

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.3.PNG)

Si por cualquier motivo nos equivocamos al crear la etiqueta podemos eliminarla con

```
git tag -d nombre_etiqueta
```

## 2. Usando etiquetas para movernos

Las etiquetas nos permiten referenciar commits de una forma más cómoda que usando el identificador de hash.

Por ejemplo:


![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/3.2.PNG)

## 3. Examinado cambios de un commit respecto al anterior.

Para ver los cambios introducidos respecto al commit anterior hacemos:

```
git show
```


![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/3.4.PNG)

## 4. Diferencias entre varios commits

Usando el comando git diff podemos ver las diferencias entre una serie de commits:

```
git diff main..v1
```


![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/3.5.PNG)

Así podemos ver los cambios del primer commit respecto al ultimo

## Directorio de trabajo
 
Son los datos que clonas desde el directorio git hasta tu pc 
 
## Área de preparación (Staging area)

Es el lugar en el que se encuentran datos de un proyecto y sus cambios.

## Repositorio local

Es tu directorio de trabajo que contiene los archivos, el segundo es el Index que actua como una zona intermedia, y el último es el HEAD que apunta al último commit realizado.








