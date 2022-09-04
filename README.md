# Primer dia con Git/Github

Lista de comando de git

* Para poder ver la version de Git

```bash
git --version
```

* Para configurar el correo
```bash
git config --global user.email "email"
```

* Para configurar el username
```bash
git config --global user.username "username"
```

* Sirve para poder empezar a usar el control de version(git) en nuestra carpeta (esto solo se usa una vez por carpeta)
```bash
git init
```

* Para ver el estado de nuestros cambios
```bash
git status
```

* Agrega los archivos a la memoria de la pc
```bash
git add
```

* Crea el registro de los cambios realizados
[ ] Se usa cada que se hace un cambio
```bash
git commit -m "comentarios"
```

* Poder ver historial de commits

[ ] Git log retorna un ID con este id vamos a poder ver el detalle de los cambios que se hicieron en ese commit
```bash
git log
```

* Para poder ver el detalle del commit
```bash
git show id-de-commit
```