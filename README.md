# .gitignore
_informacion sobre gitignore_
```
gitignore: especifica que los archivos no rastreados se deben ignorar. Es decir, ignora los archivos que yo deseo no subirlos.
```
_¿Porque es conveniente incluirlo?_
```
Es conveniente incluirlo, porque asi evitamos subir archivos no deseados, como por ejemplo:
+ Subir archivos basura como lo son los archivos generados por el compilador o archivos temporales.
+ Archivos privados, podriamos por error subir archivos con datos personales.
```
_¿Cuando se debe hacer?_
```
Los mas conveniente es crearlo al comienzo de todo, justamente despues de hacer el git init, sino podriamos subir algun archivo no deseado.
```
_¿Como configurar el archivo gitignore?_
```
En la raiz de nuestro proyecto ejecutamos el comando touch .gitignore
Luego, podemos abrirlo desde visual usando el comando code .gitignore para poder poner alli lo que no queremos que se suba a nuestro repositorio.
Dentro del mismo podemos hacer :

    * ignorar el ejecutable de windows
    *.exe

    # ignorar objetos o archivos temporales
    *.o
    *.out
entre otros archivos que podemos evitar o ignorar.    
```