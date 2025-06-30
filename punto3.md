# Punto 3 - Gestión de Permisos y Trabajo Colaborativo

## Parte individual

- Se creó la carpeta `/home/vagrant/rodriguez_espacio`
- Se creó el archivo `privado.txt` con permisos `600`
- Se creó el archivo `publico.txt` con permisos `644`
- Se crearon los usuarios `usuario1`, `usuario2`, `usuario3`

## Parte grupal

- Se creó el grupo `equipotrabajo`
- Se agregaron los usuarios `usuario1`, `usuario2`, `usuario3` y `vagrant` al grupo
- Se creó el directorio colaborativo `/tmp/colaborativo`
- Se asignó el grupo al directorio con `chgrp`
- Se dieron permisos `770` para que los usuarios del grupo puedan trabajar

## Pruebas

- Desde `usuario3` se creó un archivo en `/tmp/colaborativo`
- Luego, desde `usuario1` se accedió y leyó correctamente
- También se verificó que los permisos estaban correctamente asignados

## GitHub

Repositorio del trabajo práctico:
��� https://github.com/hernanDMielniczuk/practica-linux-Arguello-Rodriguez-Mielniczuk

