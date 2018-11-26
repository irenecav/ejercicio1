# ejercicio1

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1.
Es necesario poner --hard para modificar el working copy

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog
git checkout f3e37df
Utilice reflog para ver el historial de acciones y seleccioné el commit anterior al paso 11.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No. No había líneas de código en el archivo git-nuestro.md que causasen conflicto a la hora de la absorción de la rama.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si. Había conflicto en todas las líneas del archivo git-nuestro.md, fue resuelto añadiendo el contenido de las líneas de la rama styled.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No. No había líneas de código en el archivo git-nuestro.md que causasen conflicto a la hora de la absorción de la rama.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --pretty=oneline
--graph-->Para ver el gráfo del log. --pretty:oneline-->Para ver la información de cada commit en una sola línea.

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1.
Ya que no queríamos modificar el working copy.

- ¿Qué comando o comandos utilizaste en el paso 28?
git add git nuestro
git commit -m "Descartando los cambios del merge que hemos deshecho"

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git checkout 57b3266

- ¿Qué comando o comandos usaste en el paso 32?
git checkout 0d9030b

- ¿Qué comando o comandos usaste en el punto 33?
git checkout 2b95e81
