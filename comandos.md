# Comandos de WintPy

La lógica de los comandos en WintPy es bastante simple. Pues en vez de ser como en una shell normal que escribes por ejemplo "mkdir ejemplo" WintPy no funciona así.
En WintPy se escribe el comando y al enviarlo te dice como quieres usarlo, aquí hay un ejemplo:
```
cd
Ir a directorio:
```
En WintPy, existen bastantes comandos, esta es la explicación de todos ellos:

| Comando | Descripción |
| :--- | :--- |
| `--help` | Este comando en WintPy muestra una ventana que indica para que sirven todos los otros comandos incluido este. |
| `mkdir` | Tiene las siglas de "Make Directory", y como el nombre lo dice, te deja crear un directorio/carpeta. |
| `rmdir` | Tiene las siglas de "Remove Directory", que indican "Eliminar directorio", como lo ves, te deja eliminar un directorio/carpeta. |
| `mkfle` | Este comando es interesante, ya que introduce algo que nunca se vio antes, mkfle tiene las siglas de "Make File". Lo que hace es que te deja crear un archivo, el comando te va a preguntar como se va a llamar y su extensión, esto permite hacer archivos de texto (.txt) archivos Python (.py) o cualquier otro tipo de archivo. |
| `mkuser` | Tiene las siglas de "Make User". Te deja crear usuarios, es útil si omitiste la creación de un usuario en futuras sesiones de WintPy, este comando despues de escribir el nombre va a preguntarte si quieres integrar carpetas de paquetes para el usuario, con esto se refiere a crear las carpetas necesarias para tener tus propias aplicaciones y no compartirlas con el sistema. (todos los usuarios) |
| `rm` | Tiene las siglas de "Remove", es simple, te deja eliminar un archivo, no funciona con directorios. |
| `cd` | Permite ir a un directorio y operar desde ese mismo directorio. Tiene una variante llamada `cd ..` que es para retrodecer un directorio atrás. |
| `cp` | Tiene las siglas de "Copy", cp es para copiar un archivo, si bien puedes copiar un directorio, pero cuando quieras pegarlo, te va a tirar un error diciendo que el directorio que copiaste es un directorio, por lo que solo funciona con archivos. |
| `pt` | Tiene las siglas de "Paste" Sirve para pegar un archivo que hayas copiado anteriormente con `cp`. |
| `ls` | Este comando te permite mostrar que directorios y archivos hay en la rutas actual en la que estás, útil si quieres usar `cd` pero no recuerdas bien el nombre del directorio. |
| `exit` | Creo que se explica bien con solo ver el nombre, lo que hace es salir de WintPy, te devuelve a tu shell de terminal. |
| `clear` | Limpia todo el texto que está en la pantalla. |
| `refetch` | Muestra la información del sistema, cómo el tiempo en el que lleva encendido WintPy, o tu sistema operativo real. |
| `chuser` | Tiene las siglas de "Change User", es para cambiar de usuario si es que tienes más de 1. |
| `logout` | Este comando te permite cerrar sesión, durante la sesión cerrada no se puede ejecutar ningún comando, solo se puede ejecutar `login`, que es para volver a iniciar sesión en un usuario o de invitado. |
| `disa` | WintPy posee un sistema de seguridad llamado Sandbox que hace que no pueda interactuar con el sistema ya que puede ser algo peligroso, lo que hace este comando es desactivarlo. No esta recomendando pero se puede hacer. |
| `ensa` | Si desactivaste el Sandbox previamente, este comando te deja volver a activarlo facilmente. |
| `pkg -list` | Este comando te deja ver y instalar las aplicaciones que estan en el repositorio de paquetes de WintPy, posee una interfaz cómoda así que es muy fácil usarlo. |
| `pkg -remove` | Este comando permite desinstalar una aplicación instalada en el sistema. |
| `exec` | Tiene las siglas de "Execute", permite ejecutar una aplicación que hayas instalado, también se puede usar `exec` de la misma manera escribiendo `run`- |
| `edit` | Permite editar un archivo que hayas creado o que ya este en el sistema, se puede hacer grande uso de esto si lo combinas con el comando `mkfle`. |
| `devmode` | Activa una serie de comandos especiales altamente recomendados para los desarrolladores o gente que quiera crear una aplicación. |

- [Página de inicio](README.md) 
