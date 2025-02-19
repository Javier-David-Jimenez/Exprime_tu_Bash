
# 🚀 Alias `code_html` y `code_node` – Abre proyectos en VS Code rápidamente  

Estos alias permiten abrir Visual Studio Code directamente en los directorios de tus proyectos sin necesidad de navegar manualmente a ellos.  

## 📌 Código  

```bash
alias code_html='code ~/projects/workspace/html'
alias code_node='code ~/projects/workspace/core-node'
```


---

## 📝 ¿Qué hacen estos alias?  

1. **Abren Visual Studio Code (`code`) en el directorio especificado.**  
2. **Evitan que tengas que moverte manualmente a cada carpeta antes de abrir el editor.**  
3. **Permiten cambiar de un proyecto a otro rápidamente.**  

✔️ `code_html` → Abre el proyecto HTML en `~/projects/workspace/html`  
✔️ `code_node` → Abre el proyecto Node.js en `~/projects/workspace/core-node`  

> Puedes definir más alias para otros proyectos siguiendo el mismo formato.  

---

## 🔧 Personalización  

Si trabajas en varios proyectos, puedes añadir más alias como estos:  

```bash
alias code_react='code ~/projects/workspace/react-app'
alias code_python='code ~/projects/python-scripts'
```

---

## ⚠️ Posibles Problemas  

✔️ **Este alias es muy sencillo y no debería dar problemas.**  
⚠️ **Asegúrate de que Visual Studio Code (`code`) está instalado y accesible desde la terminal.**  
⚠️ **Si la carpeta no existe, el comando no hará nada o creará una nueva vacía.**  

---
