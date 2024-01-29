
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