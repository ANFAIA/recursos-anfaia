# Entorno de Desarrollo en Ubuntu (Linux)

Guía para configurar un entorno de desarrollo moderno en Ubuntu. Incluye instalación de Git, terminal mejorada, Docker, Ollama, VSCode y Python.

---

## 1. Actualizar el sistema

```bash
sudo apt update && sudo apt upgrade -y
```

---

## 2. Instalar Git

```bash
sudo apt install git -y
git --version
```

---

## 3. Instalar una terminal moderna

Ubuntu ya incluye una terminal funcional, pero puedes mejorarla con:

### Opcional: Instalar Zsh + Oh My Zsh

```bash
sudo apt install zsh -y
chsh -s $(which zsh)
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

> Cierra sesión y vuelve a entrar para que el cambio de shell tenga efecto.

---

## 4. Instalar Docker

```bash
sudo apt install ca-certificates curl gnupg -y
sudo install -m 0755 -d /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu   $(lsb_release -cs) stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y

# Permitir ejecutar docker sin sudo
sudo usermod -aG docker $USER
newgrp docker

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

## 6. Instalar VSCode

```bash
sudo apt install wget gpg -y
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
sudo install -o root -g root -m 644 packages.microsoft.gpg /etc/apt/trusted.gpg.d/
sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" > /etc/apt/sources.list.d/vscode.list'
sudo apt update
sudo apt install code -y
```

---

## 7. Instalar Python

```bash
sudo apt install python3 python3-pip python3-venv -y
python3 --version
pip3 --version
```

> En Ubuntu el módulo `venv` no viene incluido con `python3`: el paquete `python3-venv` es necesario para crear entornos virtuales.

### Opcional (recomendado): instalar uv

[uv](https://github.com/astral-sh/uv) es un gestor de Python ultrarrápido que reemplaza a pip, venv y pyenv:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
uv --version
```

---

## 🎉 ¡Entorno listo!

Tu entorno de desarrollo ya está listo para Python, Docker, VSCode y modelos de IA con Ollama en Ubuntu.

➡️ Siguiente paso: [crear un entorno virtual en Python](virtual_environment.md).
