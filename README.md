
# Guía Rápida 🚀

En este repo se utilizará el flujo de trabajo basado en ramas individuales para cada miembro de nuestro grupo. Paso a paso a continuación:




### 🛠️ 1. Creando rama individual
#### Clona primeramente el repositorio remoto
```bash
  git clone <URL_DEL_REPO>
```

#### Cambia a la rama principal y haz pull para actualizarla
```bash
  git checkout main
  git pull origin main
```


#### Crea y sube tu rama personal
```bash
  git checkout -b develop/<nombre-propio>
  git push -u origin develop/<nombre-propio>
```

#### Cambia a la rama principal y haz pull para actualizarla
```bash
  git checkout main
  git pull origin main
```
### 📤 2. Subir cambios
#### Clona primeramente el repositorio remoto
```bash
  git add .
  git commit -m "Descripción de los cambios"
  git push
```

### 🔄 3. Mantener actualizada la rama
Es importante que siempre trabajes con la ultima versión del pryecto. Haz esto antes de trabajar o cuando se comunique que subieron cambios
#### Cambia a la rama principal y haz pull para actualizarla
```bash
  git checkout main
  git pull origin main
```
#### Cambia a tu rama personal y haz merge 
```bash
  git checkout develop/<nombre-propio>
  git merge main
```

### ⚠️ Nota:
Informa al equipo cuando subas cambios importantes
