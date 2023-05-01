# 3. Conflicts

Para este ejercicio, se debe crear un archivo `nombre_apellido.txt`, dentro de la carpeta `1.commit`.

En este archivo, se va a guardar las respuestas teóricas y algunos resultados de los mismos.

## Ejercicio 3

### 3.1. Preguntas

1. ¿Qué es un conflicto? Cuando ocurre? ¿Es bueno o malo?
2. ¿Se puede evitar un conflicto? ¿Cómo?

### 3.2. Ejercicio Práctico

1. Crear un archivo `nombre_apellido.txt` dentro de la carpeta `3.conflicts`.
2. Crear una nueva branch `suprema` a partir de la branch `master`. (Puede usar el comando `git checkout -b suprema`).
3. Moverse a la branch `suprema`. (Puede usar el comando `git checkout`).
4. Cambiar el contenido del archivo `3.conflicts/milanesa.txt` donde dice lomo por `pollo`.
5. "Commitear" los cambios. (Puede usar el comando `git commit -am "Cambio de lomo a pollo"`).
6. Moverse a la branch `master`. (Puede usar el comando `git checkout`).
7. Crear una nueva branch `bife` a partir de la branch `master`. (Puede usar el comando `git checkout -b bife`).
8. Moverse a la branch `bife`. (Puede usar el comando `git checkout`).
9. Cambiar el contenido del archivo `3.conflicts/milanesa.txt` donde dice lomo por `bife`. 
10. Haga un `git diff master suprema` y un `git diff master bife`. ¿Qué observa? 
11. Moverse a la branch `master`. Corra un `git status`, ¿qué observa?
12. Ejecute `git merge bife`. Funcionó?
13. Ejecute `git merge suprema`. Funcionó?
14. Ejecute `git status`. Que observa?
15. Vea el contenido del archivo `3.conflicts/milanesa.txt`. ¿Qué observa?
16. Aborte el merge. (Puede usar el comando `git merge --abort`).
17. Vuelva a ejecutar `git merge suprema`.
18. Resuelva el conflicto manualmente.

## Finalizado

Una vez finalizado el ejercicio, recuerde guardar sus cambios en `nombre_apellido.txt` y subirlos a **su** repositorio remoto. Este archivo (`README.md`) y `milanesa.txt` tienen que mantenerse sin ningún cambio.

Para volver a `milanesa.txt` a su estado original, debe buscar el commit que lo contiene y correr el comando:
```bash
git checkout [commit ID] -- 3.conflicts/milanesa.txt

# ó

git checkout [commit ID] -- milanesa.txt

# dependiendo de donde esté ubicado
```
