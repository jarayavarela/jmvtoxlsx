# Instalación de jsontoxlsx

Sigue estos pasos para instalar y configurar correctamente el software **jsontoxlsx** en tu computadora.
La instalación se divide en dos partes principales: la instalación de Python y la instalación del software.

## 1. Instalación de Python

Antes de instalar **jsontoxlsx**, es necesario tener Python instalado en tu computadora. Si ya tienes Python instalado, puedes saltar este paso.

### Paso 1: Descargar Python

- Ve a la página oficial de [Python](https://www.python.org/downloads/).
- Descarga la última versión estable de Python compatible con tu sistema operativo. Para este proyecto, necesitas al menos la versión 3.11. Puedes descargarla directamente desde los siguientes enlaces:
  - [Python 3.11 para Windows](https://www.python.org/ftp/python/3.11.0/python-3.11.0-amd64.exe)
  - [Python 3.11 para macOS](https://www.python.org/ftp/python/3.11.0/python-3.11.0-macos11.pkg)
  - [Python 3.11 para Linux](https://www.python.org/ftp/python/3.11.0/Python-3.11.0.tgz)

### Paso 2: Instalar Python

- Abre el instalador de Python que acabas de descargar.
- Marca la opción **"Add Python to PATH"** para asegurarte de que el intérprete de Python esté disponible desde la línea de comandos.
- Haz clic en **"Install Now"** y sigue las instrucciones en pantalla.

### Paso 3: Verificar la instalación

- Abre una terminal (Cmd, PowerShell en Windows; Terminal en macOS/Linux).
- Escribe `python --version` o `python3 --version` para verificar que Python se haya instalado correctamente. Deberías ver un número de versión como salida, por ejemplo, `Python 3.11.0`.

## 2. Instalación de jsontoxlsx

Una vez que Python esté instalado, puedes proceder con la instalación de **jsontoxlsx** utilizando el archivo `.whl` proporcionado.

### Paso 1: Descargar el archivo `.whl`

- Obtén el archivo `.whl` del software **jsontoxlsx** desde el repositorio oficial o el enlace proporcionado por el equipo de desarrollo.

### Paso 2: Instalar jsontoxlsx usando pip

- Abre una terminal en la ubicación donde descargaste el archivo `.whl`.
- Ejecuta el siguiente comando para instalar el software:

````
pip install nombre_del_archivo.whl
````

Asegúrate de reemplazar `nombre_del_archivo.whl` con el nombre real del archivo que descargaste. Por ejemplo, si el archivo que descargaste se llama `jsontoxlsx-1.0.0-py3-none-any.whl`, entonces el comando sería:

````
pip install jsontoxlsx-1.0.1.post0-py3-none-any.whl
````

### Paso 3: Verificar la instalación

Una vez que el proceso de instalación se complete, verifica que **jsontoxlsx** esté instalado correctamente ejecutando:

````
jsontoxlsx --version
````

Deberías ver la versión del software como salida si la instalación fue exitosa.

