# Solución

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
```bash
git reset --hard HEAD~1
```
Con reset deshacemos el commit, con el modificador --hard además descartamos los cambios en el working copy y utilizamos el puntero HEAD para referirnos de manera indirecta al commit anterior. 

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
```bash
git reflog  
```
```bash
git reset --hard f393469 
```
  Desde la posición actual del HEAD no es posible acceder al commit(porque es hijo del actual) y tampoco desde git log, por lo que debemos buscar en el histórico de acciones para encontrar el commit y realizar un git reset. 

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, porque fue fast-forward

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, en éste caso no fue fast forward y el archivo contenía cambios en las mismas líneas. 

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?


- ¿Qué comando o comandos utilizaste en el paso 25?
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?


- ¿Qué comando o comandos utilizaste en el paso 27?


- ¿Qué comando o comandos utilizaste en el paso 28?


- ¿Qué comando o comandos utilizaste en el paso 29?


- ¿Qué comando o comandos utilizaste en el paso 30?


- ¿Qué comando o comandos usaste en el paso 32?


- ¿Qué comando o comandos usaste en el punto 33?

