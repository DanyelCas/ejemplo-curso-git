# 🏗️ Proyecto Angular para Curso Git

_Ejemplo práctico para aprender control de versiones_

## Estructura del Proyecto

```
mi-proyecto-angular/
├── .gitignore
├── README.md
├── angular.json
├── package.json
└── src/
    ├── app/
    │   ├── app.component.ts
    │   └── app.module.ts
    └── index.html
```

## Cómo Usar Este Proyecto

### 1. Configuración inicial

```bash
git init
git add .
git commit -m "Primer commit"
```

### 2. Archivos ignorados

Los siguientes archivos/carpetas están excluidos en `.gitignore`:

- `/dist` - Carpeta de compilación  
- `/node_modules` - Dependencias  
- `/.angular` - Caché de Angular CLI

### 3. Comandos para practicar

```bash
# Crear una nueva rama
git checkout -b nueva-funcionalidad

# Hacer cambios y confirmarlos
git add .
git commit -m "Implemento nueva funcionalidad"

# Fusionar cambios
git checkout main
git merge nueva-funcionalidad
```

## Propósito Educativo

Este proyecto permite practicar:

- Flujo básico de Git (`add`, `commit`, `push`)
- Manejo de ramas
- Uso de `.gitignore`
