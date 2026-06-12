# Entorno de Desarrollo en Windows

Este documento te guiará para montar un entorno de desarrollo moderno en Windows desde cero. Ideal para desarrollo en Python, contenedores con Docker, proyectos con IA (Ollama), y más.

> 💡 **Atajo:** Windows incluye el gestor de paquetes [winget](https://learn.microsoft.com/windows/package-manager/winget/). Casi todo lo de esta guía se puede instalar desde PowerShell con un solo comando; en cada sección encontrarás la alternativa `winget` junto al instalador gráfico.

---

## 1. Instalar Git

Git es el sistema de control de versiones más usado.

🔗 [Descargar Git para Windows](https://git-scm.com/download/win) — o con winget:

```powershell
winget install Git.Git
```

- Ejecuta el instalador.
- En las opciones, selecciona:
  - **Git from the command line and also from 3rd-party software**
  - **Use bundled OpenSSH**
  - **Checkout as-is, commit Unix-style line endings**

Después de instalar, abre `Git Bash` o tu terminal y ejecuta:

```bash
git --version
```

---

## 2. Instalar una terminal moderna (tipo Linux)

### Opción 1: Windows Terminal

🔗 [Instalar desde Microsoft Store](https://aka.ms/terminal)

Una terminal moderna que permite usar PowerShell, CMD, Git Bash o WSL (Linux en Windows).

### Opción 2: Activar WSL2 (Subsistema de Windows para Linux)

1. Abre PowerShell como administrador y ejecuta:

```powershell
wsl --install
```

2. Reinicia el equipo si lo solicita.
3. Elige una distro como Ubuntu desde la Microsoft Store.

Una vez instalado, puedes usar Linux directamente desde Windows.

---

## 3. Instalar Docker Desktop

Docker te permite crear contenedores para tus aplicaciones.

🔗 [Descargar Docker Desktop](https://www.docker.com/products/docker-desktop/) — o con winget:

```powershell
winget install Docker.DockerDesktop
```

- Asegúrate de que WSL2 esté instalado (Docker lo usará por defecto).
- Tras la instalación, abre Docker Desktop y verifica que está funcionando.

Verifica con:

```bash
docker --version
```

---

## 4. Instalar Ollama (para modelos de IA locales)

🔗 [Descargar Ollama](https://ollama.com/download) — o con winget:

```powershell
winget install Ollama.Ollama
```

- Ejecuta el instalador y sigue las instrucciones.
- Luego, abre la terminal y prueba:

```bash
ollama run gemma4
```

> Esto descargará y ejecutará el modelo `gemma4` localmente. Catálogo completo en [ollama.com/library](https://ollama.com/library) (por ejemplo `gemma4`, `qwen3` o `llama3.3`).

---

## 5. Instalar Visual Studio Code (VSCode)

🔗 [Descargar VSCode](https://code.visualstudio.com/Download) — o con winget:

```powershell
winget install Microsoft.VisualStudioCode
```

- Recomendado instalar también las siguientes extensiones:
  - **Python**
  - **Docker**
  - **WSL** (antes "Remote - WSL")
  - **GitLens**

Desde la terminal, puedes abrir VSCode con:

```bash
code .
```

> Asegúrate de marcar la opción **"Agregar a PATH"** durante la instalación.

---

## 6. Instalar Python

🔗 [Descargar Python (desde la web oficial)](https://www.python.org/downloads/windows/) — o con winget:

```powershell
winget install Python.Python.3.13
```

- Marca **"Add Python to PATH"** durante la instalación.
- Selecciona la opción de instalar para todos los usuarios.
- Después de instalar, verifica con:

```bash
python --version
pip --version
```

---

## 7. Recomendaciones extra

- 💡 Instala [Node.js](https://nodejs.org/) si planeas trabajar con herramientas front-end (`winget install OpenJS.NodeJS.LTS`).
- 💡 Usa [uv](https://github.com/astral-sh/uv) para gestionar Python, entornos virtuales y dependencias de forma ultrarrápida (`winget install astral-sh.uv`).
- 💡 Para tareas comunes, usa scripts `.ps1` en PowerShell o `make` dentro de WSL.

---

## 🎉 ¡Listo!

Ahora tienes un entorno completo para desarrollar en Python, Docker, IA y mucho más, todo desde tu máquina con Windows.

➡️ Siguiente paso: [crear un entorno virtual en Python](virtual_environment.md).
