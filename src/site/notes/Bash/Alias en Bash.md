---
{"dg-publish":true,"permalink":"/bash/alias-en-bash/"}
---

## generar alias para directorios

editar archivo bashrc

```bash
sudo nano ~/.bashrc
```

agregar las lineas necesarias al final del archivo, justo antes de export PS1=’> ’

por ejemplo para acceder al directorio `/home/devhome/diazignacio` agrego un alias llamado `diaz` con el valor del directorio

`alias diaz='cd /home/devhome/diazignacio'`

correr `source ~/.bashrc` para reiniciar bash y poder usar los comandos

de ahora en mas cada vez que quieras acceder al directorio `/home/devhome/diazignacio` puedes escribir en la terminal diaz.

Agilizando el trabajo cotidiano. Good code!


