# Crear aplicaciones
Una función interesante que tiene WintPy es que es capaz de desarrollar aplicaciones y ejecutarlas todo dentro de el mismo WintPy.
Ahora vamos a aprender a crear aplicaciones
# Comienzo
Para que WintPy automáticamente instale una aplicación, debe ser una carpeta, y ubicada desde la carpeta packages, para hacer una aplicación se requieren
dos archivos: Un archivo Python (La aplicación en sí) y un info.json, con esto WintPy reconocera que es una aplicación.
# Crear la aplicación
Crear la aplicación es tan sencillo como hacer un programa más de Python, no se necesita ninguna herramienta, lo que facilita mucho el proceso.
# Crear el info.json
Tienes dos métodos para crear el archivo de configuración

## Método 1:
Activa el modo desarrollador ejecutando el comando: `devmode`.
Esto te otorgará acceso a la herramienta `autojson`.
Así se ve el comando de autojson:

![autojson](/Assets/autojson.png)

> **Nota**: El archivo .json se generará automáticamente en el directorio exacto donde hayas ejecutado el comando.

## Método 2:
Puedes utilizar tu editor de código preferido, o bien crear el archivo directamente desde la consola usando mkfle y posteriormente modificarlo con edit.
El archivo debe respetar la siguiente estructura:

```
{
  "name": "Ejemplo",
  "version": "Ejemplo",
  "main_file": "Ejemplo"
}
```
# Lanzar la aplicación

Una vez que tengas ambos archivos reunidos dentro de su respectiva carpeta en packages:
Reinicia WintPy (en caso de que lo estuvieras ejecutando).
Lanza tu creación utilizando los comandos exec o run seguido del nombre de tu aplicación.

¡Y listo! Tu aplicación estará corriendo.

[Página posterior - Entornos](entornos.md)

[Página anterior - Comandos](comandos.md)

[Página de inicio](README.md)
