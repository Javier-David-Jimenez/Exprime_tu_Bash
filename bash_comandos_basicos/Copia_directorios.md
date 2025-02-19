
# 🚀 Alias: `cp_html_basico`  

Este alias permite copiar rápidamente una plantilla HTML básica desde un directorio predefinido al directorio actual.  

```bash
alias cp_html_basico='cp -r ~/plantillas/html/basico/* .'
```

## 📝 ¿Qué hace este alias?  
Este comando copia todos los archivos y carpetas dentro de `~/plantillas/html/basico/` al directorio en el que te encuentras.  

Es ideal para tener plantillas listas para usar, por ejemplo, de HTML y CSS. En este caso, la plantilla contiene:  
- **Estructura de archivos básica** de un proyecto web.  
- Un `head` con enlaces preconfigurados a archivos `.css`, `.js` y favicon.
- algo sencillito, pero podria ser una base de express o react o un proyecto de otro tipo que suelas usar

## 📌 Personalización  
Puedes modificar este alias según tus necesidades:  
1. **Cambia el nombre del alias** por algo más intuitivo para ti.  
2. **Edita la ruta de origen** para que apunte a la plantilla que prefieras.  

## ⚠️ Precauciones  
- **Revisa en qué directorio lo ejecutas** antes de usarlo. Podrías copiar archivos en un lugar no deseado.  
- **Evita llenar tu sistema de archivos innecesarios.** Si lo usas muchas veces sin limpieza, puedes acabar con muchas carpetas inútiles.  
- **Si los archivos ya existen, serán sobrescritos sin advertencia.**  
