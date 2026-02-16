# 📙 Ramas y Merges en Git

## 🌿 ¿Qué es una rama?
Es una línea de desarrollo paralela donde se pueden hacer cambios sin afectar el proyecto principal.

## 🔑 Comandos de ramas
- `git branch` → crear o listar ramas  
- `git checkout / switch` → cambiar de rama  
- `git merge` → unir ramas

## 🧠 Puntero HEAD
Indica en qué rama estás trabajando actualmente.

## 🔀 Merge (fusión)
Proceso de unir cambios de una rama a otra.

### Fast-forward
Ocurre cuando la rama principal no tiene cambios y solo avanza.

## ⚠️ Conflictos
Ocurren cuando dos personas modifican la misma línea.

Git marca con:
```
<<<<<<<
=======
>>>>>>>
```

El programador debe elegir la versión correcta y hacer commit.
