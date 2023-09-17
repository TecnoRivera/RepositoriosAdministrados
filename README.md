# Introduccion a Git como herramienta de trabajo en equipo

Aqui realice un README de como utilice Git

## Iniciando

Antes que nada primero instalamos Linux, en este caso utilice Ubuntu

### Prerequisitos

Primero instale Git

```
sudo apt update
sudo apt install git
```

### Configurando

Una vez instalado, y verifique que si esta instalado con un git --version, inicio sesion

```
$ git config --global user.name "Mi nombre"
$ git config --global user.email alumno@micorreo.com
```

y verifico que todo este bien

```
$ git config --global user.name
$ git config --global user.email
```

## Versionando con git

Aqui preparamos los archivos, pero antes tenemos que crear una carpeta 

Ahora si podemos inicializar el git y de una vez subir el documento al escenario

```
git init
git add mi_archivo.ejemplo
```

Para eliminar y subir los datos con un mensaje personalizado estan los siguientes comandos

```
git rm --cached mi_archivo.ejemplo
git commit -m "Cambios en mis archivos"
```

Ahora podemos checar el estatus, ignorar archivos en comun y manejar llaves publicas y privadas

* git status (checar el estatus)
* creamos un archivo .gitignore
* ssh-keygen -t rsa -C "email@correo.com"

## Utilizar repositorios remotos

```
git remote add origin git@gitlab.com:user/demo-git.git
```

## Para subir los cambios al repositorio en la red

```
git push origin master
```

## Autor

* **Emiliano Rivera** - *Trabajo inicial* - [TecnoRivera](https://github.com/TecnoRivera)
