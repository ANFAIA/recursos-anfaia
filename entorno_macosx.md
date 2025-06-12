# Entorno de Desarrollo en macOS

Guía paso a paso para preparar un entorno de desarrollo en macOS con Git, terminal moderna, Docker, Ollama, VSCode y Python.

---

## 1. Instalar Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Agrega Homebrew al PATH si es necesario (el instalador te indicará cómo hacerlo).

---

## 2. Instalar Git

```bash
brew install git
git --version
```

---

## 3. Instalar iTerm2 (Terminal mejorada)

```bash
brew install --cask iterm2
```

Opcional: instalar Zsh y Oh My Zsh para una terminal más potente.

---

## 4. Instalar Docker Desktop

```bash
brew install --cask docker
```

Abre Docker desde Launchpad y acepta los permisos necesarios.

Verifica instalación:

```bash
docker --version
```

---

## 5. Instalar Ollama

```bash
brew install ollama
ollama run llama3
```

---

## 6. Instalar VSCode

```bash
brew install --cask visual-studio-code
```

Puedes abrir proyectos con:

```bash
code .
```

---

## 7. Instalar Python

```bash
brew install python
python3 --version
pip3 --version
```

---

## 🎉 ¡Listo!

Ahora puedes desarrollar en Python, usar contenedores Docker, ejecutar modelos IA con Ollama, y trabajar con VSCode en macOS.
