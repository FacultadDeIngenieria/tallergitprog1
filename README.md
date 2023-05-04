# Taller Git Programación 1 2013

## Instalación

1. Generar una clave ssh: [Guía para generar clave SSH](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
2. Agregar la clave ssh a su cuenta de GitHub: [Guía para agregar clave SSH a GitHub](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
3. Hacer un Fork de este repositorio: [Guía para hacer un Fork](https://docs.github.com/es/get-started/quickstart/fork-a-repo)
4. Clonar el repositorio bifurcado: [Guía para clonar un repositorio](https://docs.github.com/es/get-started/quickstart/fork-a-repo#step-2-create-a-local-clone-of-your-fork)
5. Configurar usuario y mail de git:
    ```bash
    git config --global user.name "Nombre Apellido"
    git config --global user.email "su mail austral"
    # Opcional, configura nano como editor de texto en git (por defecto usa vim)
    git config --global core.editor "nano"
    ```
6. Ir a la branch practica2023: `git checkout practica2023`
7. Crear una branch con su nombre y apellido: `git checkout -b nombre_apellido`

## Práctica

Antes de comenzar la práctica, asegúrese de:
- Tener instalado git (si no lo tiene, puede descargarlo desde [aquí](https://git-scm.com/downloads))
- Tener una cuenta en GitHub (si no la tiene, puede crearla desde [aquí](https://github.com))
- Tener una clave ssh configurada en su cuenta de GitHub (si no la tiene, puede crearla desde [aquí](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent))
- Tener este repositorio "forkeado" o bifurcado en su cuenta de GitHub (si no lo tiene, puede hacerlo desde [aquí](https://docs.github.com/es/get-started/quickstart/fork-a-repo))
- Tener clonado este repositorio en su computadora (si no lo tiene, puede clonarlo desde [aquí](https://docs.github.com/es/get-started/quickstart/fork-a-repo#step-2-create-a-local-clone-of-your-fork))
- Tener configurado su nombre y mail en git (si no lo tiene, puede hacerlo desde [aquí](https://docs.github.com/es/get-started/getting-started-with-git/setting-your-username-in-git))

### Ejercicios

Cada ejercicio, se encuentra dentro de una carpeta con el nombre del ejercicio. Dentro de cada carpeta, se encuentra un archivo README.md con las instrucciones del ejercicio.

La resolución de cada ejercicio debe hacerse dentro de la carpeta del ejercicio, en un archivo con el nombre `nombre_apellido.md`. Por ejemplo, si su nombre es Juan Pérez y su apellido es López, el archivo debe llamarse `juan_perez_lopez.md`.

Una vez que haya resuelto el ejercicio, debe agregarlo al repositorio local, hacer un commit y luego hacer un push al repositorio remoto. Para hacer esto, debe ejecutar los siguientes comandos:

```bash
# Agrega el archivo al repositorio local
git add nombre_apellido.md
# Hace un commit con el mensaje "Resuelto ejercicio 1"
git commit -m "Resuelto ejercicio 1"
# Hace un push al repositorio remoto
git push
```

Luego de resolver **todos** los ejercicios y hacer un push de cada uno, debe hacer un pull request desde su repositorio remoto a este repositorio (FacultadDeIngenieria/tallergitprog1). Tiene una guía para hacerlo [aquí](https://docs.github.com/es/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).

### Terminé los ejercicios, ¿ahora qué?

Una vez que haya terminado los ejercicios, debe hacer un pull request desde su repositorio remoto a este repositorio (FacultadDeIngenieria/tallergitprog1). Tiene una guía para hacerlo [aquí](https://docs.github.com/es/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).

Espere a que un ayudante/profesor revise su pull request y lo apruebe. Una vez que su pull request haya sido aprobado.

