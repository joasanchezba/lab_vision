# Warmup Questions

1.  What is the clone url of this repository?
    >   https://github.com/joasanchezba/lab_vision/blob/master/lab01_git/questions.md

2.  What is the output of the ``cal`` command?

            Febrero 2016      
do lu ma mi ju vi sá  
    1  2  3  4  5  6  
 7  8  9 10 11 12 13  
14 15 16 17 18 19 20  
21 22 23 24 25 26 27  
28 29                 
               

# Homework Questions

1.  What is the ``grep``command?
    >   es un comando que se usa para buscar un texto o un fichero que tenga coincidencia con una cadena de caracteres dada.
        > ref: http://www.cyberciti.biz/faq/howto-use-grep-command-in-linux-unix/

2.  What is a *makefile*?
    >   Es un archivo especial que contiene comandos de la shell, que a su vez es  un programa que toma los comandos del teclado y se los da al sistema operativo. El Makefile crea y define el nombre de un archivo MAKE (o Makefile dependiendo del sistema). Mientras que en el directorio que contiene el archivo MAKE, que va a escribir y hacer que se va a ejecutar los comandos en el archivo MAKE.

        >ref: http://www.sis.pitt.edu/mbsclass/tutorial/advanced/makefile/whatis.htm
        >ref: http://linuxcommand.org/lts0010.php

4.  What does the ``-prune`` option of ``find`` do? Give an example
    >  muestra todos los archivos que coinciden con los criterios especificados en el find.

5.  Where is the ``grub.cfg``  file
    >   ./usr/share/doc/grub-common/examples/grub.cfg
    >   ./boot/grub/grub.cfg

6.  How many files with ``gnu`` in its name are in ``/usr/src``
    >   0
        liee303@liee303:/usr/src$ ls
        linux-headers-3.13.0-44          linux-headers-3.13.0-45          linux-headers-3.13.0-52          linux-headers-3.13.0-53
        linux-headers-3.13.0-63          matlab linux-headers-3.13.0-44-generic  linux-headers-3.13.0-45-generic
        linux-headers-3.13.0-52-generic  linux-headers-3.13.0-53-generic  linux-headers-3.13.0-63-generic

7.  How many files contain the word ``gpl`` inside in ``/usr/src``
    >   0

8.  What does the ``cut`` command do?
    >    es usado para el procesamiento de texto. se puede usar para extraer una porción de textode un archivo seleccionado la columna.

9.  What does the ``wget`` command do?
    >   es una herramienta libre para descargas no interactivas  de archivos desde la web. Soporta HTTP, HTTPS y FTP protocolos.

9.  What does the ``rsync`` command do?
    >    es el comando mas utilizado para copiar y sincronizar archivos y directorios remotamenteen sistemas Linux/Unix.
    | ref: http://www.tecmint.com/rsync-local-remote-file-synchronization-commands/

10.  What does the ``diff`` command do?
    >   analiza dos archivos e imprime las líneas que son diferentes. especificqmente imprime instrucciones para hacer los dos archivos iguales.
    | ref: http://www.computerhope.com/unix/udiff.htm

10.  What does the ``tail`` command do?
    >   muestra algunas de las últimas 10 líneas de un archivo. este comando es usado para verlos 'ipdates' de archivos muy grandes.
    | ref: http://linoxide.com/linux-command/linux-tail-command/

10.  What does the ``tail -f`` command do?
    >   si el nombre es especificado, el archivo con ese nombre será seguido, esto es independiente del descriptor del archivo.
    
10.  What does the ``link`` command do?
    >   es un archivo especial que sirve como una referencia de otro archivo o directorio.

11.  How many users exist in the course server?
    >   answer

12. What command will produce a table of Users and Shells sorted by shell (tip: using ``cut`` and ``sort``)
    >   answer

13. What command will produce the number of users with shell ``/sbin/nologin`` (tip: using ``grep`` and ``wc``)
    >   answer

15. Create a script for finding duplicate images based on their content (tip: hash or checksum)
    You may look in the internet for ideas, but please indicate the source of any code you use
    Save this script as ``find_duplicates.sh`` in this directory and commit your changes to github

16. What is the meaning of ``#! /bin/bash`` at the start of scripts?
    >   answer

17. How many unique images are in the ``sipi_images`` database?
    >   answer
    
