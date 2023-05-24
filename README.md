# Workflow 3 de Git con Pull Request

## Proceso
1. Hacer `Fork ` al repositorio de la otra persona
2. Crear el repositorio en nuestra propia cuenta de GitHub.
3. Clonar el repositorio de nuestro repositorio
```bash
git clone https://github.com/VanessaRubiera/gitworkflow3.git
```
4. Realizar cambios, agregarlos a git y hacer commit
```bash
git add .
git commit -am "Nuevos cambios"
```


## Buenas practicas
1. Revisar los ultimos cambios del repositorio original, hacer upstream constantemente, sobre todo antes de hacer nuestros cambios
```bash
git pull upstream main
```
2. Para hacer pull a nuetro repositorio remoto (el del Fork):
```bash
git pull origin main
```
3. Para revisar las conexiones que tenemos:
```bash
git remote -v
```