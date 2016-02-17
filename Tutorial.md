#Tutorial sobre la realización de la práctica

##Instalación de git

Para la instalación de git es necesario abrir una terminal y escribir el siguiente comando:

    $ sudo apt-get install git
Una vez instalado debemos configurarlo con nuestro nombre y correo electrónico.

    $ git config --global user.email "mi_email@ejemplo.com"
    $ git config --global user.name "Mi Nombre"

A continuación ya seremos capaces de iniciar git en cualquier directorio con el comando

    $ git init

##Abrir cuenta en GitHub

Para abrir una cuenta en github debemos dirigirnos a su página oficial [github.com][git], rellenar los datos que nos encontramos de usuario, email y contraseña y pinchar en **"Sign up for GitHub"**

##Instalación de Atom

Sólo será necesario ejecutar estas sentencias:

    $ sudo add-apt-repository ppa:webupd8team/atom
    $ sudo apt-get update
    $sudo apt-get install atom

Una vez tenemos instalado atom ya podemos abrirlo desde la aplicación o directamente por consola:

    $ atom [nombre_fichero]

##Instalación de Pandoc

Pandoc es un traductor de Markdown a HTML. Para instalarlo nos debemos dirigir a la [página oficial][pandoc] y seguir los pasos dependiendo del sistema operativo. Una vez descargado el paquete correspondiente desde terminal o bien desde el centro de software.

Una vez instalado, para darle uso sólo será necesario escribir en terminal, y dentro del directorio donde se encuentre el fichero markdown, lo siguiente:

    $pandoc fichero.md -o fichero.html



[git]: https://github.com
[pandoc]:http://pandoc.org/installing.html
