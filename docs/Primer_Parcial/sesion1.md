# Sesión 1

## Objetivos de la sesión

- [x] Crear mi repositorio en GitHub
- [x] Armar mi sitio de documentación y publicarlo
- [x] Aprender los comandos básicos de la terminal y de Git

## Herramientas utilizadas

- **GitHub:** lo usé para alojar mi repositorio y consultar los cambios publicados.
- **Visual Studio Code:** lo usé para editar los archivos de mi sitio.
- **Git Bash:** lo usé para ejecutar comandos de Git y de la terminal.
- **MkDocs Material:** lo usé para crear y presentar mi sitio de documentación.

## Sobre mí

Me llamo [MI NOMBRE] y estudio [MI CARRERA] en [MI UNIVERSIDAD]. En esta sesión empecé a organizar mi trabajo en un repositorio y a documentar lo que voy aprendiendo.

Me gusta [MIS GUSTOS] y quiero seguir desarrollando mis habilidades. A futuro, mi meta profesional es [MI META PROFESIONAL].

## Comandos de Git que practiqué

```bash
git clone URL_DEL_REPOSITORIO
```
Usé este comando para descargar una copia del repositorio a mi equipo.

```bash
git status
```
Lo usé para revisar qué archivos cambiaron y cuál era el estado de Git.

```bash
git add docs/index.md
```
Agregué un archivo específico a la preparación del próximo commit.

```bash
git add .
```
Preparé los cambios de todos los archivos del directorio actual.

```bash
git commit -m "Describe mis cambios"
```
Guardé los cambios preparados en el historial con un mensaje que los describe.

```bash
git push origin main
```
Envié mis commits de la rama `main` al repositorio remoto `origin`.

Mi rutina para subir cambios:

```bash
git add .
git commit -m "Describe mis cambios"
git push origin main
```
Sigo estos tres pasos para preparar mis cambios, registrarlos y publicarlos en GitHub.

## Problema que tuve y cómo lo resolví

!!! warning

    - **Síntoma:** mis cambios en VS Code no aparecían en GitHub.
    - **Cómo lo descubrí:** revisé el estado con `git status` y el repositorio remoto con `git remote -v`.
    - **Solución:** hice `add`, `commit` y `push`, y comprobé en GitHub que los cambios ya estaban.

## Lo que aprendí

Antes creía que guardar el archivo bastaba para que el cambio apareciera en GitHub. Ahora entiendo que guardar, hacer un commit y hacer un push son tres pasos distintos. Cuando algo no se sube, lo primero que debo revisar es `git status`.

## Próximos pasos

!!! tip

    Para la siguiente sesión, voy a practicar cómo crear una rama y revisar el historial de commits con `git log`.