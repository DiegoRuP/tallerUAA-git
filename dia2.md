# 📌 **Día 2: Trabajo colaborativo y buenas prácticas** 🤝

## 🔹 **Colaboración en GitHub**

### **1. Trabajo en equipo con Git**

```sh
git fetch         # Trae cambios remotos sin fusionarlos 
git pull origin main # Descarga y fusiona cambios remotos 
git push origin main  # Sube cambios al repositorio remoto
```

📖 [Guía oficial de trabajo colaborativo](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

---

## 🔹 **Manejo de ramas y flujos de trabajo**

**Git Flow vs GitHub Flow:**

- **Git Flow**: Usado en grandes proyectos. Separa desarrollo y producción.
- **GitHub Flow**: Flujo más simple con `main` y `feature branches`.

📖[Git Flow explicado]()

### 🛠 **Comandos útiles**

```sh
git branch nombre-rama  # Crear una nueva rama 
git checkout nombre-rama  # Cambiar de rama 
git merge nombre-rama  # Fusionar una rama en otra
```

---

## 🔹 **Resolviendo conflictos en Git**

1. Ejecutar `git pull origin main`
2. Editar los archivos en conflicto ($<<<<<<<$, $=======$, $>>>>>>>$)
3. Agregar y hacer commit de los cambios
4. Subir la versión corregida

```sh
git add . 
git commit -m "Resolviendo conflicto" 
git push
```

📖 [Más sobre resolución de conflictos]()

---

## 🔹 **Buenas prácticas en commits**

**Convención de mensajes de commits:**  
🔹 **Formato recomendado:**

```makefile
tipo: descripción corta del cambio
```

📌 **Ejemplos:**

- `feat: agregar autenticación de usuario`
- `fix: corregir error en formulario de login`
- `docs: actualizar README`

📖 [Guía sobre convenciones de commits](https://www.conventionalcommits.org/)