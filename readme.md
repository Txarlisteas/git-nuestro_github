#ENUNCIADO PRÁCTICA GIT

**Ejercicio 1

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

He utilizado el comando *git reset --hard HEAD~1*, para eliminar el commit y perder la información del working copy.

- ¿Qué comando o comando utilizaste en el paso 12? ¿Por qué?

Pues he buscado el commit con *reflog*, posteriormente he utilizado *checkout* a la referencia corta del commit.
Me he cambiado a la rama master con *checkout* y he eliminado la rama styled con *git branch -d styled*.
Me he posicionado otra vez en el commit y he creado nuevamente la rama styled con *git branch styled*.

- El merge del 13, ¿Causó algún conflicto? ¿Por qué?

No me ha creado ningún conflicto. Me he movido al commit inicial, para crear el readme.md y posteriormente he hecho el merge.
Styled ha absorvido todo el trabajo de la rama master, sin problema.

- El merge del paso 19, ¿ Cuasó algún conflicto? ¿Por qué?

Si ha habido un conflicto. Al hacer el merge, el archivo git-nuestro.md creaba el conflicto, puesto que git no ha sabido unirlo. 
He tenido que abrir el archivo y modificarlo. He leido tarde el punto 20 y me he quedado con los cambios del HTML
que la rama htmlify nos daba :-).Voy a tener que modificar el archivo y volver a ponerle asteriscos ;-).

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

Este merge, no ha causado ningún conflicto.
Porque al estar en la rama master que se habia quedado atras, ha podido absorber todas las modifaciones de la rama styled.
Si, lo sé tengo que modificar el archivo git-nuestro en styled y volver a los asteriscos.

-¿Qué comando o comandos utilizaste en el paso 25?

Para dibujar el gráfico, he hecho un "nano ~/.config" y he modificado el archivo metiendo en la última linea, lo siguiente:

graph = log --all --graph --decorate --oneline

Y posteriormente en la consola y en la rama master he metido el comando "git graph".

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si que sería posible hacer un merge con fast forward, lo que sucede que con fast forward cuando master absorbe a title,
quedarían en una misma rama. Haciendolo con no fast forward, se mantiene la rama title, y master continua.
El commit que se genera, tiene dos padres. Haciendolo con Fast Forward, movemos el puntero y master absorbe el trabajo de title.

- ¿Qué comando o comandos utilizaste en el paso 27?

Para deshacer el merge, he buscado el commit con reflog y he utilizado git reset con la referencia corta del commit.
Asi se quedan los archivos git-nuestro.md y readme.md en el working copy.

- ¿Qué comando o comandos utilizaste en el paso 28?
Para descartar los cambios de git-nuestro, he utilizado "git checkout git-nuestro.md" para descartar los cambios.
Asi lo recomendaba GIT.

- ¿Qué comando o comandos utilizaste en el paso 29?

Para eliminar la rama, he utilizado git branch reset -D title.

- ¿Qué comando o comandos utilizaste en el paso 30?
- ¿Qué comando o comandos utilizaste en el paso 32?
Utilizando el comando "checkout" y la referencia del commit que he buscado con reflog.

- ¿Qué comando o comandos utilizaste en el paso 33?

Utilizando el comando "checkout" y la referencia del commit que he buscado con reflog.
