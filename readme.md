# 1. Deteccion de Fugas
## Como Clonar el repositorio
Para clonar el repositorio utilizando HTTPS, ejecutar el siguiente código
```bash
git clone https://github.com/kjyanez98/Deteccion-de-Fugas.git
```
## Para crear un commit
Seguir los siguientes pasos:
1. Para verificar que cambios existen en el repositorio:
```bash
git status
```
    En rojo salen los archivos nuevos o modificados.

2. Para agregar los archivos que queremos que estén en el commit:
```bash
git add RUTA_AL_ARCHIVO RUTA_AL_SEGUNDO_ARCHIVO RUTA_AL_DIRECTORIO
```

3. Para verificar que cambios se agregan al commit:
```bash
git status
```
    En verde salen los archivos que se agregaron al commit.
4. Crear el commit junto con su mensaje:
```bash
git commit -m "El mensaje del commit, describiendo los cambios"
```
5. Para subir el commit o los commits:
```bash
git push origin NOMBRE_DE_LA_RAMA
```

## Para actualizar nuestro repositorio local
```bash
git pull
```

## Como crear una rama
Para crear la rama:
```bash
git branch NOMBRE_DE_LA_RAMA
```
Para movernos, posteriormente debemos ejecutar:
```bash
git checkout NOMBRE_DE_LA_RAMA
```
Para crear la rama y movernos a esa rama:
```bash
git checkout -b NOMBRE_DE_LA_RAMA 
```

Para borrar una rama:
```bash
git branch -D NOMBRE_DE_LA_RAMA
```

## Git Flow
Consiste en:
1. Crear una nueva rama
2. Movernos a la rama nueva
3. Hacer cambios y crear los commits en la nueva rama.
4. Subir nuestros cambios a la nube en la nueva rama.
5. Crear un Merge Request(o Pull Request)
    
    Significa que pasa por un proceso de revisión de código (Code review), y una vez se aprueban los cambios, se hace merge (se funciona), los cambios de la rama, con la rama objetivo (normalmente es la rama Main)

