# Solución

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
```bash
git reset --hard HEAD~1
```
Con *reset* deshacemos el commit, con el modificador *--hard* además descartamos los cambios en el *working copy* y utilizamos el puntero *HEAD* para referirnos de manera indirecta al *commit* anterior. 

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
```bash
git reflog  
```
```bash
git reset --hard f393469 
```
  Desde la posición actual del *HEAD* no es posible acceder al *commit*(porque es hijo del actual) y tampoco desde *log*, por lo que debemos buscar en el histórico de acciones para encontrar el *commit* y realizar un *git reset*. 

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

 No, porque fue *fast-forward*

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

 
Sí, en éste caso no fue *fast forward* y el archivo contenía cambios en las mismas líneas. 

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque es *fast-forward*. 

- ¿Qué comando o comandos utilizaste en el paso 25?
```bash
git graph
```
que es un alias de 
```bash
git log --graph --decorate --pretty=oneline
```

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

 Sí, porque la rama *master* y la rama *title* forman una lista.

- ¿Qué comando o comandos utilizaste en el paso 27?
```bash
git reset HEAD~1
```

- ¿Qué comando o comandos utilizaste en el paso 28?
```bash
git checkout -- git-nuestro.md
```

- ¿Qué comando o comandos utilizaste en el paso 29?
```bash
git branch -D title
```

- ¿Qué comando o comandos utilizaste en el paso 30?
```bash
git reflog
git reset --hard 893b50d
```

- ¿Qué comando o comandos usaste en el paso 32?
```bash
git log
git checkout 1761e1c4cb85495255a11772f352e03c9318eff0
```

- ¿Qué comando o comandos usaste en el punto 33?
```bash
git checkout master
```
