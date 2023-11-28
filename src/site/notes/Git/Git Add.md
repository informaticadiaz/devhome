---
{"dg-publish":true,"permalink":"/git/git-add/"}
---

`git add` es un comando en Git que se utiliza para agregar cambios específicos en archivos o directorios al área de preparación (también conocida como "staging area") para prepararlos para ser incluidos en el próximo commit.

Cuando realizas modificaciones en tu código, Git no rastrea automáticamente esos cambios. Debes agregar explícitamente los archivos o cambios que deseas incluir en el próximo commit utilizando el comando `git add`. Esto coloca esos archivos en el área de preparación, lo que significa que están listos para ser confirmados en el repositorio.

### Uso básico de `git add`:

1. **Agregar archivos específicos:**

   ```bash
   git add nombre-del-archivo
   ```
   Este comando agrega un archivo específico al área de preparación para incluirlo en el próximo commit.

2. **Agregar todos los archivos modificados:**

   ```bash
   git add .
   ```
   El punto (`.`) agrega todos los archivos modificados en el directorio actual al área de preparación.

3. **Agregar todos los archivos nuevos y modificados recursivamente:**

   ```bash
   git add -A
   ```
   Este comando agrega todos los archivos nuevos y modificados en el repositorio, de manera recursiva, al área de preparación.

### Ejemplo de uso:

Imagina que realizas cambios en varios archivos en tu proyecto y deseas incluir esos cambios en un commit:

1. Realizas modificaciones en diferentes archivos

3. Usas `git add` para agregar los archivos modificados al área de preparación:

   ```bash
   git add archivo1.js carpeta/archivo2.js
   ```

   o
   
   ```bash
   git add .
   ```

3. Realizas un commit para guardar los cambios en el repositorio:

   ```bash
   git commit -m "Mensaje descriptivo del commit"
   ```

`git add` es un paso fundamental en el flujo de trabajo de Git, ya que te permite seleccionar qué cambios incluirás en tu próxima confirmación (commit), lo que te brinda control sobre el contenido de cada commit en tu historial de versiones.

[[Git/Git\|Git]]