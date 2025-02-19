# 📌 **Día 3: Herramientas y automatización** ⚙️

## 🔹 **Uso de Git en VS Code y GitHub Desktop**

1. Abrir un proyecto en VS Code
2. Ver cambios en la pestaña de control de versiones
3. Realizar commits y push desde la interfaz

📖 [Git en VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview)  
📖 [GitHub Desktop](https://desktop.github.com/)

---

## 🔹 **Comandos avanzados de Git**

```sh
git stash         # Guarda cambios sin hacer commit 
git reset --hard  # Revierte cambios permanentemente 
git revert        # Crea un nuevo commit que revierte cambios anteriores 
git tag v1.0.0    # Marca una versión específica`
```
📖 Más sobre `git reset`, `revert` y `checkout`

---

## 🔹 **GitHub Actions y CI/CD**

💡 **¿Qué es CI/CD?**

- CI (Integración Continua): Automatiza pruebas
- CD (Despliegue Continuo): Automatiza despliegues

Ejemplo de **GitHub Actions** (`.github/workflows/ci.yml`):
```yaml
name: CI 
on: [push, pull_request] 
jobs:   
	build:     
		runs-on: ubuntu-latest     
		steps:       
			- uses: actions/checkout@v2       
			- name: Ejecutar pruebas         
			  run: npm test`
```

📖 [Documentación de GitHub Actions](https://docs.github.com/en/actions)

---

## 🔹 **Seguridad y mantenimiento en GitHub**

- **`.gitignore`**: Evita subir archivos innecesarios (ej. `node_modules/`, `secrets.env`).
- **Protección de ramas**: Evita commits directos a `main`.
- **GitHub Secrets**: Para almacenar credenciales seguras.

📖 [Guía sobre `.gitignore`](https://git-scm.com/docs/gitignore)