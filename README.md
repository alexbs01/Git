# Como instalar git desde Ubuntu

## #1 Creación de una carpeta

Comenzaremos creando una carpeta en la que se alojarán los futuros repositorios de git, para ello abriremos la consola de comandos con Ctrl + Alt + T, y primero veremos donde estamos situados.  

```sh
~$ pwd
/home/alejandro
```
Y desde este directorio crearemos una carpeta llamada projects.  

```sh
~$ mkdir projects
```

A continuación entraremos en este directorio.  

```sh
~$ cd projects
```

## Instalación de git

Ahora instalaremos git con estos tres comandos.  

```sh
~$ sudo add-apt-repository ppa:git-core/ppa
~$ sudo apt update
~$ apt install git
```

A continuación, para comprobar que se instaló correctamente usaremos un comando de git para ver en que version está.  

```sh
~$ git --version
git version 2.24.1
```









































