# 📌 **Día 1: Fundamentos de Git** 🚀

## 🔹 **¿Qué es Git y por qué usarlo?**

Git es un sistema de control de versiones distribuido que permite rastrear cambios en archivos y coordinar el trabajo entre múltiples desarrolladores.

✅ **Diferencias entre Git y GitHub:**

- **Git:** Software de control de versiones que se usa en la terminal.
- **GitHub:** Plataforma en la nube donde se alojan repositorios remotos.

📚 **Recursos útiles:**

- [Pro Git (Libro oficial)](https://git-scm.com/book/en/v2)
- [Documentación de GitHub](https://docs.github.com/)

---

## 🔹 **Instalación y configuración de Git**

### 🔧 **1. Instalación de Git**

- **Windows:** Descargar e instalar desde [git-scm.com](https://git-scm.com/downloads)
- **Mac:** `brew install git`
- **Linux:** `sudo apt install git` (Debian/Ubuntu)

### ⚙ **2. Configuración inicial**

Configura tu usuario y correo electrónico:

```sh
git config --global user.name "Tu Nombre" 
git config --global user.email "tuemail@example.com"`
```
Verifica la configuración:
```sh
git config --list
```
### 🔑 **3. SSH vs HTTPS**

- **HTTPS:** Más fácil, requiere autenticación frecuente.
- **SSH:** Más seguro, usa una clave SSH para autenticarse sin escribir contraseñas.

🔗 **Cómo generar una clave SSH en GitHub:**  
[Guía oficial de GitHub](https://docs.github.com/es/authentication/connecting-to-github-with-ssh)

---

## 🔹 **Comandos básicos de Git**

```sh
git init           # Inicializa un repositorio 
git status        # Muestra el estado del repo 
git add .         # Agrega archivos al área de preparación 
git commit -m "Mensaje"  # Guarda cambios con un mensaje 
git branch        # Lista las ramas 
git checkout rama # Cambia de rama (Git < 2.23) 
git switch rama   # Cambia de rama (Git >= 2.23)
```

📖 **Más comandos en la [cheat sheet oficial](https://education.github.com/git-cheat-sheet-education.pdf)**

---

## 🔹 **Conectando Git con GitHub**

1. Crear un repositorio en GitHub
2. Conectarlo con Git:
```sh
git remote add origin https://github.com/usuario/repositorio.git 
git push -u origin main
```
3. Clonar un repositorio:
```sh
git clone https://github.com/usuario/repositorio.git
```



