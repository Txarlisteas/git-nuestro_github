#ENUNCIADO PRÁCTICA GIT

**Ejercicio 1

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

He utilizado el comando *git reset --hard HEAD~1*, para eliminar el commit y perder la información del working copy.

- ¿Qué comando o comando utilizaste en el paso 12? ¿Por qué?

Pues he buscado el commit con *reflog*, posteriormente he utilizado *checkout* al hush del commit.
Me he cambiado a la rama master con *checkout* y he eliminado la rama styled con *git branch -d styled*.
Me he posicionado otra vez en el commit y he creado nuevamente la rama styled con *git branch styled*.

- El merge del 13, ¿Causó algún conflicto? ¿Por qué?

No me ha creado ningún conflicto. Me he movido al commit inicial, para crear el readme.md y posteriormente he hecho el merge.
Styled ha absorvido todo el trabajo de la rama master, sin problema.

- El merge del paso 19, ¿ Cuasó algún conflicto? ¿Por qué?



