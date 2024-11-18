# ###############################
alias zipealo='for dir in ~/zipear/*/; do \
  dir_name=$(basename "$dir"); \
  cd "$dir" && \
  zip -r ~/zipear/"$dir_name".zip . && \
  cd - && \
  rm -rf "$dir"; \
done'


# ###############################

Este codigo era largo y lo hemos partido con \ para poder leerlo mejor.
por cada directorio en el directorio zipear, los vuelve .zip con el nombre 
del  directorio que ha zipeado y elimina el directorio

# ##############################
Problemas  como hace un rm y es peligroso ya que podria destruir archivos
queremos por eso solo funciona dentro de la carpeta ~zipear porque no 
quiero romper nada fuera por error.  se mueve dentro de las carpetas
pero no sale de zipear

Puede dar problemas si existen varios directorios ya que puede que 
mezcle carpetas, por eso aunque pueda hacer varios mejor hacer solo 1

# #####################

Valoracion de 1 a 5

Dificultad = 3 + =
Utilidad ahorro de tiempo = 3 + =
Posibles problemas = 3 + =
 