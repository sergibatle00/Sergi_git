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

#Practica 2

Comprobamos commits realizados con el comando git log --oneline --all

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.PNG)

Miramos el contenido del Readme en el último commit con el comando cat README.md

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.1.PNG)

Nos movemos al primer commit usando el comando: git checkout [hash del commit] en este caso git checkout 711f4fb y comprobamos que ahora el main se encuentra en el primer commit con git log --oneline --all

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.3.PNG)

Volvemos al último commit usando el comando git checkout main

![git log](https://github.com/sergibatle00/Sergi_git/blob/main/capturas/2.4.PNG)







