---
{"dg-publish":true,"permalink":"/git/git-merge/"}
---


El comando `git merge` se utiliza en Git para combinar los cambios de una rama específica con la rama actual en la que te encuentras. Este comando es comúnmente utilizado para fusionar los cambios realizados en la rama principal (`main`) con la rama en la que estás trabajando, por ejemplo, una rama de características o una rama de desarrollo.

Aquí está cómo funciona en términos sencillos:

### **Preparación**: 

Antes de ejecutar `git merge main` es recomendable estar en la rama donde deseas incorporar los cambios. 
Puedes cambiar de rama usando `git checkout nombre-de-la-rama`.

**Ejecución del merge**: Una vez estás en la rama que quieres actualizar, ejecutas `git merge main`. Esto le dice a Git que tome los cambios realizados en la rama `main` y los combine con la rama actual.

**Resolución de conflictos (si los hay)**: En algunos casos, si los cambios en ambas ramas entran en conflicto (es decir, modifican las mismas líneas de código), Git puede no ser capaz de fusionar automáticamente los cambios y pedirá al usuario que resuelva esos conflictos manualmente.

**Finalización del merge**: Después de resolver los conflictos, si los hubiera, y si no hay problemas, Git completará la fusión y los cambios de la rama `main` se incorporarán a la rama actual.

Es importante tener en cuenta que al realizar un merge, los cambios que se fusionan pueden afectar el código y la historia de tu proyecto, por lo que se recomienda tener cuidado al hacer estas operaciones, especialmente en ramas importantes como la rama `main` (o `master` en repositorios más antiguos).