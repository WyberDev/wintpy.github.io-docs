# Crear aplicaciones
Una función interesante que tiene WintPy es que es capaz de desarrollar aplicaciones y ejecutarlas todo dentro de el mismo WintPy.
Ahora vamos a aprender a crear aplicaciones
# Comienzo
Para que WintPy automáticamente instale una aplicación, debe ser una carpeta, y ubicada desde la carpeta packages, para hacer una aplicación se requieren
dos archivos: Un archivo Python (La aplicación en sí) y un info.json, con esto WintPy reconocera que es una aplicación.
# Crear la aplicación
Crear la aplicación es tan sencillo como hacer un programa más de Python, no se necesita ninguna herramienta, lo que facilita mucho el proceso.
# Crear el info.json
Hay 2 maneras para crear el 'info.json', la primera es desde WintPy, debes escribir 'devmode' para activar el modo desarrollador, lo que te va a dar
el acceso al comando 'autojson', que se ve de esta forma:
![autojson](/Assets/autojson.png)

El archivo json se generará automáticamente en la carpeta donde lo ejecutaste.

Ahora la segunda manera, es escribiendo el .json, puedes usar tu editor de código favorito o crear el 'info.json' con `mkfle` y luego editandolo con `edit`
El archivo tiene que verse de esta manera:
```
{
  "name": "Ejemplo",
  "version": "Ejemplo",
  "main_file": "Ejemplo"
}
```
Despues de juntar los dos archivos en una carpeta, reinicia WintPy (Si es que ya lo estabas ejecutando), ahora solo ejecutas exec o run con el nombre de la aplicación
y funciona!


[Página anterior - Comandos](comandos.md)

[Página de inicio](README.md)
