# ##########################
alias gitvago='f(){ git add . &&  git status && git branch && \
  branch=$(git symbolic-ref --short HEAD) && echo "Introduce el mensaje del commit:" && \
  read mensaje && git commit -m "$mensaje" && git push origin "$branch"; }; f'



# #######################

Este código puede resultarte complejo o quizas no:   (Que alguien explique lo que hace)




 # ########################

 PROBLEMA: este código no funcionara correctamente en este directorio tendreis que hacer algún cambio y generar un script nuevo 
 poe ejemplo una variante debajo de la actual
 
Problemas, Este alias es complejo y debes de mirar en que rama y directorios estas (te lo dice el propio script) después ya haces el commit. si no estas donde debez cancela el scrip   control+C creo que era o dale aintro sin poner nada

Podrías subir cosas donde no crrespondiese ¡¡¡OJO!!!


# #####################
Valoracion de 1 a 5

Dificultad = 4 + =
Utilidad ahorro de tiempo = 4 + =
Posibles problemas = 3 + =
 
   