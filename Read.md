# Primer dia con Git/Githud

Lista de comandos de git

* Para poder ver la version de Git

```bash
git --version
```

*Para configurar el correo

```bash
git config --global user.email "email"
```

*Para configurar el name

```bash
git config --global user.name "name"
```

*Sirve para poder empezar a usar el control de version a nuestra carpeta

```bash
git init
```

*Para ver el estado de nuestros cambios

```bash
git status
```
*Agrega los archivos a la memoria de la pc

```bash
git add .   //  git add Read.md
```
*Registra los cambios realizados

```bash
git commit -m
```

* Poder ver historial de commits

[x] Git log retorna un `id` con este id vamos a poder ver el detalle de los cambios que se hicieron en ese commit

```bash
git log
```

*Para poder ver el detalle del commit usamos

```bash
git show `id`
```