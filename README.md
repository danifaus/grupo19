# grupo19
git status *este comando muestra un estado de los archivos, si fueron modificados, eliminados, etc.*

git diff nombre_archivo *dice cuáles son los cambios que sufrió el archivo, si se agregaron o eliminaron líneas, etc.*

git add nombre_archivo *este comando sirve para agregar un archivo a la lista de archivos que deseo subir, no necesariamente se agrega al repositorio. Luego se decide si se sube o no, queda en la lista.
ej. si quiero subir readme.md, esto se logra con la instruccion git add README.md*

git commit -m "aca va el comentario de lo que quiero aclarar" *con esto se hace un comentario. Para esto debo tener previamente archivos añadidos a la lista con git add. por ejem. git commit -m "se agregan comandos git a readme.md"