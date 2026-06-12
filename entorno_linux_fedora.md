# Entorno de Desarrollo en Fedora (Linux)

Guía para configurar un entorno de desarrollo moderno en Fedora Linux. Incluye Git, terminal mejorada, Docker, Ollama, VSCode y Python.

---

## 1. Actualizar el sistema

```bash
sudo dnf update -y
```

---

## 2. Instalar Git

```bash
sudo dnf install git -y
git --version
```

---

## 3. Instalar una terminal moderna

Fedora ya viene con una terminal funcional. Puedes mejorarla con:

### Opcional: Instalar Zsh + Oh My Zsh

```bash
sudo dnf install zsh -y
chsh -s $(which zsh)
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

> Cierra sesión y vuelve a entrar para que el cambio de shell tenga efecto.

---

## 4. Instalar Docker

1. Agrega el repositorio oficial de Docker:

```bash
sudo dnf -y install dnf-plugins-core
sudo dnf config-manager addrepo --from-repofile=https://download.docker.com/linux/fedora/docker-ce.repo
```

> En versiones antiguas de Fedora (dnf4, anteriores a Fedora 41) la sintaxis era `sudo dnf config-manager --add-repo <url>`.

2. Instala Docker:

```bash
sudo dnf install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```

3. Inicia y habilita el servicio:

```bash
sudo systemctl start docker
sudo systemctl enable docker
```

4. Permitir ejecutar docker sin sudo:

```bash
sudo usermod -aG docker $USER
newgrp docker
```

5. Verifica instalación:

```bash
docker --version
```

---

## 5. Instalar Ollama

```bash
curl -fsSL https://ollama.com/install.sh | sh
ollama run gemma4
```

> `ollama run <modelo>` descarga y ejecuta el modelo en local. Puedes ver el catálogo completo en [ollama.com/library](https://ollama.com/library) (por ejemplo `gemma4`, `qwen3` o `llama3.3`).

---

## 6. Instalar Visual Studio Code (VSCode)

```bash
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'

sudo dnf check-update
sudo dnf install code -y
```

---

## 7. Instalar Python

```bash
sudo dnf install python3 python3-pip -y
python3 --version
pip3 --version
```

### Opcional (recomendado): instalar uv

[uv](https://github.com/astral-sh/uv) es un gestor de Python ultrarrápido que reemplaza a pip, venv y pyenv:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
uv --version
```

---

## 🎉 ¡Entorno listo!

Tu entorno de desarrollo en Fedora está preparado para Python, Docker, VSCode y modelos de IA con Ollama.

➡️ Siguiente paso: [crear un entorno virtual en Python](virtual_environment.md).
