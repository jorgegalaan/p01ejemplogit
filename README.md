# GIT Básico

## Instalación

Instalación desde el asistente de Git

## Comandos para credenciales en nuestro equipo

```
git config --global user.name "nombreusuario"
git config --global.user.email "correousuario"
```

## Crear un repositorio git

```
git init
```

## Comprobar el estado de git

Ver la situación en la que están todos los cambios desde el ultimo comit

```
git status
```

## Añadir archivos al staging area

Añade todos los cambis pendientes
```
git add -A
```


## Crear un commit

Para guardar un conjunto de cambios y crear un ounto de control usamos los commit

```
git commit -m "mensaje de commit"
```

## Deshacer cambios a partir de los commit

2 opciones

```
git reset --soft <código commit>
```

Con --soft podemos volver a un commit anterior sin deshacer cambios.