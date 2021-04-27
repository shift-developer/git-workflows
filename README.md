# Indice

1. Git


# Git

Git es un sistema distribuido de control de versiones (DVCS). Donde cada computadora tiene acceso a una copia de todo el historial de cambios de un proyecto.
Otros sistemas se basan en *deltas* que representan sólo las diferencias entre una versión y otra. En cambio, git trabaja con **snapshots**. En términos simples, git le saca una foto a los archivos en el momento de una versión y guarda sus referencias solo en el caso que haya cambios en el archivo especifico respecto de su foto anterior.

#### Snapshot-based
![snap-based-system](https://raw.githubusercontent.com/shift-developer/git-workflows/main/img/snapshot-based.png)

#### Delta-based
![delta-based-system](https://raw.githubusercontent.com/shift-developer/git-workflows/main/img/delta-based.png)

### Los 3 estados
- modified
- stagged
- commited

![basic-workflow](https://raw.githubusercontent.com/shift-developer/git-workflows/main/img/basic-workflow.png)


### Initial config

#### Identidad
```bash
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

#### Editor
Puede ser por ejemplo en macOS se usa por defecto "vim" como editor para git, pero tambien se puede elegir "nano"
```bash
$ git config --global core.editor nano
```

#### Default branch name
Puedes cambiar el nombre de la rama master por defecto a tu preferencia a por ejemplo "main" que es lo que se usa actualmente en github.
```bash
$ git config --global init.defaultBranch main
```

#### Help
```bash
$ git help <verb>
$ git <verb> --help
$ man git-<verb>
```


### Basics


