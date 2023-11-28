---
{"dg-publish":true,"permalink":"/git/comandos-basicos/"}
---

## Ramas

### Cambiar de rama

```bash
git checkout [nombre de la rama]
```

### Crear nueva rama

```Bash
git checkout -b [nombre de la rama]
```

### Publicar una rama

```Bash
git push origin <nombre-de-la-rama>
```

### Publicar todas las ramas locales

```Bash
git push origin --all
```

### Eliminar ramas

```Bash
git branch -d <nombre de la rama>
```

### Ver si las ramas están actualizadas

```bash
git fetch --verbose
```

```Bash
git fetch
```

### Ver el estado de la rama

```Bash
git status
```

###  Agregar cambios 

**Agregar todos los archivos modificados:**

   ```bash
   git add .
   ```

### Guardar cambios 

```bash
git cammit -m "Mensaje Descriptivo"
```

### conflictos en el codigo

hacer merge

git config merge.strategy

Resolver estrateguia
git pull origin main --strategy=resolve

git pull origin main --strategy={tipo-de-strateguia}


git remote -v

git merge main


git pull


[[Git/Git\|Git]]