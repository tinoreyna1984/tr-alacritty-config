# Alacritty - Configuración

## Windows

* Instalar Alacritty para Windows.
* En C:\Users\<usuario>\AppData\Roaming, copiar la carpeta "alacritty" con el archivo "alacritty.yml".
* En Panel de Control -> Sistema -> Configuración avanzada del sistema -> Variables de entorno, agregar a PATH la ruta "C:\Program Files\Alacritty\".
* Ir a la siguiente sección:

```bash
# Startup directory
#
# Directory the shell is started in. If this is unset, or `None`, the working
# directory of the parent process will be used.
#working_directory: None
working_directory: e:/ #windows
```

Modificar, si se requiere, la variable "working_directory" al directorio con el que se iniciará a trabajar.

## Linux

Pendiente.
