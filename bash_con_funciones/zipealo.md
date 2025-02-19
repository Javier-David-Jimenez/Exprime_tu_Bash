# 🚀 Alias `zipealo` – Comprime y limpia automáticamente  

Este alias permite comprimir en `.zip` cada directorio dentro de `~/zipear/`, nombrando el archivo comprimido según el nombre del directorio original y eliminando el directorio tras la compresión.  

## 📌 Código  

```bash
alias zipealo='for dir in ~/zipear/*/; do \
  dir_name=$(basename "$dir"); \
  cd "$dir" && \
  zip -r ~/zipear/"$dir_name".zip . && \
  cd - && \
  rm -rf "$dir"; \
done'
```

---

## 📝 ¿Qué hace este alias?  

1. **Recorre cada directorio dentro de `~/zipear/`**.  
2. **Obtiene el nombre del directorio** y lo usa como nombre para el `.zip`.  
3. **Accede al directorio, lo comprime en `~/zipear/` y vuelve al directorio anterior**.  
4. **Elimina el directorio original después de comprimirlo**.  

---

## ⚠️ Posibles Problemas y Precauciones  

🔴 **Eliminación de archivos**  
- Usa `rm -rf` para borrar los directorios después de zipearlos. Si se ejecuta en otra ubicación por error, podría eliminar archivos importantes. **Por eso, solo actúa dentro de `~/zipear/`**.  

⚠️ **Riesgo de mezclar archivos**  
- Si hay varios directorios dentro de `~/zipear/`, los procesa todos seguidos. Puede ser más seguro ejecutar `zipealo` cuando haya solo **un directorio a la vez**.  

🔄 **No sale de `~/zipear/`**  
- El código se asegura de no modificar nada fuera de `~/zipear/`, reduciendo el riesgo de borrar archivos importantes en otros lugares.  



> **Conclusión:** Es un alias muy útil para organizar archivos rápidamente, pero hay que usarlo con cuidado debido al uso de `rm -rf`.  
