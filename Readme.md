
# Proceso de *Git Pull Request*

## Paso 1: Inicializar el Repositorio

El líder del proyecto comienza repositorio de git

```bash
git init
git add [archivos]
git commit -m "primer comentario"
git branch -M main
git remote add origin [URL del repositorio]
git push -u origin main
```
## Paso 1.2: Clonar el Repositorio

Los demás miembros del proyecto realizar un fork al repositorio y lo clonan

```bash
git clone [URL del repositorio]
cd [nombre del repositorio]
```

## Paso 2: Crear una Rama Local

Cada miembro crea una rama propia

```bash
git checkout -b [nombre de lu rama propia]
```

## Paso 3: Realizar Cambios

Cada miembro inicia una nueva clase y le va realizando commits

## Paso 4: Subir la Rama al Repositorio Remoto

Cada miembro sube su rama al repositorio remoto

```bash
git push origin [nombre de la rama]
```

## Paso 5: Crear el Pull Request

En repositorio de GitHub  se utiliza la opción para crear un Pull Request.
Se selecciona la rama a fusionar y la rama main. Luego, se crea el Pull Request.

## Paso 6: Fusión del Pull Request

Una vez que los revisores estén satisfechos con los cambios, el Pull Request sera fusionado en la rama principal.

## Paso 7: Actualizar el Repositorio Local

Cada miembro actualiza su repositorio local para reflejar los cambios en la rama principal

```bash
git checkout [nombre de la rama principal]
git pull origin [nombre de la rama principal]
```