## Configuración Básica

Configurar Nombre que salen en los commits
```ssh
	git config --global user.name "dasdo"
```
Configurar Email
```ssh	
	git config --global user.email dasdo1@gmail.com
```
Marco de colores para los comando
```ssh
	git config --global color.ui true
```

## Iniciando repositorio

Iniciamos GIT en la carpeta donde esta el proyecto
```ssh
	git init
```
Clonamos el repositorio de github o bitbucket
```ssh
	git clone <url>
```
Añadimos todos los archivos para el commit
```ssh
	git add .
```
Hacemos el primer commit
```ssh
	git commit -m "Texto que identifique por que se hizo el commit"
```
subimos al repositorio
```ssh
	git push origin master
```
## tres arboles git
```ssh 
directorio de trabajo
index @ intermediario
commit status actual
```
## Viajes en el tiempo 
ir al pasado
```ssh 
git checkuot IDENTIFICADORCOMIT
```
## resetear commits

```ssh
git reset HEAD
git reset --soft
git reset --hard

``` 
## ramas 
ir al pasado
```ssh 
git branch #ver ramas
git branch examplerama #crear ramas 
git checkuout examplerama
git merge pruebas master # agregar cambios de pruebas a master 
```
## git commit -a -m "Texto que identifique por que se hizo el commit"
## PUSH 
main
```ssh 
Crear main
git remote add origin https://github.com/JuanDigital/alfalfa.git
git push -u origin main
```