git reset --soft deshace el commit mas reciente pero mantiene todos los cambios en staging

si cometiste un error y necesitas rehacer el commit sin perder tus cambios

git reset deshace el commit y quita los cambios del staging pero mantiene los archivos

cuando quieres deshacer un commit pero aun necesitas trabajar en los cambios antes de prepararlos nuevamente

git reset --hard elimina el commit y los cambios en el directorio de trabajo

cuando quieras borrar todo y volver a un estado limpio de la rama con cuidado ya que no hay vuelta atras

git revert es mas seguro que el git reset porque crea un nuevo commit que deshace los cambios de un commit anterior sin modificar la historia
