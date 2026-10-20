Vamos a crear un nuevo repositorio llamado prueba2_tu_nombre. Ten en cuenta lo siguiente:  

Para ello entraremos a Github y crearemos un nuevo repositorio, con poner el nombre que te piden vale, no hace falta crear el readme.md para que funcione. 
![alt text](images/image-7.png)

En esta ocasión, crea primero el repositorio local en Windows (usando git init). El repositorio debe contener, al menos, dos archivos de texto: archivo1.txt y archivo2.txt. El contenido de ambos archivos es libre. 

Lo primero que haremos sera utilizar el git init para iniciar el repositorio y despues con un echo crearemos dos archivos .txt que estaran dentro del repositorio. Para subirlos al repositorio utilizaremos los comandos git add . y git commit -m para confirmarlo.
![alt text](images/image-8.png)

Agrega (conecta) el repositorio local con un repositorio remoto en GitHub (usando git remote add). 

Para ello utilizaremos el comando git remote add origin y pondremos la dirección del del repositorio remoto.

![alt text](images/image-9.png)

Sube el repositorio local a GitHub (usando git push). 

Con el comando git push -u origin main podremos subir los cambios hechos anteriormente al repositorio.

![alt text](images/image-10.png)

Clona el repositorio remoto en tu máquina virtual Linux Debian (usando git clone). 

Para ello entraremos en nuestra maquina virtual y utilizaremos el comando git clone y la dirección del directorio.

![alt text](images/image-11.png)

Modifica, en Windows, uno de los archivos y añade un 3º archivo de texto llamado archivo3.txt. Confirma los cambios(usando git add, git commit) y súbelos al repositorio (usando git push). 

Para ello utilizaremos los mismos comandos que utilizamos para subir los dos anteriores archivos que creamos anteriormente.

![alt text](images/image-12.png)

Actualiza la versión local del repositorio en Linux Debian (usando git pull). 

Para ello con escribir git pull sirve y te saldrá un mensaje como el siguiente:

![alt text](images/image-13.png)