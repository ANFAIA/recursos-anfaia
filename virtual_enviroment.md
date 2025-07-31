# Crear un entorno virtual en Python e instalar `numpy` y `pandas`

Este documento explica cómo crear un entorno virtual en Python e instalar las bibliotecas `numpy` y `pandas`.

## Requisitos previos

Asegúrate de tener instalado **Python 3.6 o superior** en tu sistema. Puedes verificarlo con:

```bash
python3 --version
```

También necesitas tener `pip` y `venv` instalados (ambos vienen por defecto con la mayoría de las instalaciones de Python 3).

---

## Paso 1: Crear un entorno virtual

Abre una terminal y ejecuta el siguiente comando:

```bash
python3 -m venv env
```

Este comando creará una carpeta llamada `env` en tu directorio actual con un entorno virtual de Python.

---

## Paso 2: Activar el entorno virtual

- En **Linux/macOS**:

  ```bash
  source env/bin/activate
  ```

- En **Windows (CMD)**:

  ```cmd
  env\Scripts\activate.bat
  ```

- En **Windows (PowerShell)**:

  ```powershell
  .\env\Scripts\Activate.ps1
  ```

Una vez activado, deberías ver el nombre del entorno (por ejemplo, `(env)`) al principio de la línea de comandos.

---

## Paso 3: Instalar `numpy` y `pandas`

Con el entorno activado, instala las bibliotecas ejecutando:

```bash
pip install numpy pandas
```

---

## Paso 4: Verificar la instalación

Puedes probar si las librerías se instalaron correctamente ejecutando Python:

```bash
python
```

Y luego dentro del intérprete:

```python
import numpy
import pandas
print(numpy.__version__)
print(pandas.__version__)
```

Para salir del intérprete de Python, pulsa `Ctrl+D` (Linux/macOS) o `Ctrl+Z` y luego `Enter` (Windows).

---

## Paso 5 (opcional): Guardar dependencias

Puedes guardar las dependencias instaladas en un archivo `requirements.txt` con:

```bash
pip freeze > requirements.txt
```

Y más adelante puedes recrear el entorno con:

```bash
pip install -r requirements.txt
```

---

## Desactivar el entorno virtual

Cuando termines, puedes salir del entorno virtual con:

```bash
deactivate
```

---

## ¡Listo!

Ahora tienes un entorno aislado con `numpy` y `pandas` instalados para tus proyectos de Python.