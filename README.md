# GIT
> Sistema de control de versiones 
> Nacio juntamente con Linux

# Pasos 

- Inicializamos un repositorio
``` bash
    git init
```

### Si es la primera vez que usamos GIT en el dispositivo
- Configuramos el usuario
``` bash
    git config user.name "Jonathan"
    git config user.email "jonathan.cruz@davinci.edu.ar"
```

o configuro globalmente
``` bash
    git config --global user.name "Jonathan"
    git config --global user.email "jonathan.cruz@davinci.edu.ar"
```

# Estados
![areas](areas.png)

- Agrego los archivos
``` bash
 git add README.md
```

- Creamos un commit 
``` bash
git commit -m "Proyecto Base"
```

- Para saber el estado del repositorio
``` bash
git status
```
