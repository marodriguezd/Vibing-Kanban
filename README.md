# 📋 Mi Kanban

Un tablero Kanban simple, funcional y elegante para organizar tus tareas. Sin dependencias, sin complicaciones.

## ✨ Características

- 🎯 **5 columnas**: To Do, In Progress, In Review, Done, Cancelled
- 📋 **Múltiples tableros**: Crea tantos tableros como necesites
- 📝 **Crear, editar y eliminar tareas**
- 🖱️ **Arrastrar y soltar** para mover tareas entre columnas
- 💾 **Persistencia automática**: tus datos se guardan en el navegador
- 📤 **Exportar/Importar**: respalda y transfiere tus datos en formato JSON
- 🔍 **Búsqueda** de tareas
- 📱 **Responsive**: funciona en móvil y escritorio
- ⚡ **Rápido**: un solo archivo HTML, sin dependencias

## 🚀 Cómo usar

### Opción 1: GitHub Pages (Recomendado)

1. Crea un nuevo repositorio en GitHub
2. Sube el archivo `index.html`
3. Ve a **Settings** → **Pages**
4. Selecciona "Deploy from a branch" → **main**
5. Accede a tu Kanban en `https://TU_USUARIO.github.io/NOMBRE-REPO/`

### Opción 2: Uso local

Simplemente abre el archivo `index.html` en tu navegador. ¡No necesitas servidor!

## 📖 Guía de uso

### Crear un tablero
1. Haz clic en el menú ☰
2. Selecciona "Nuevo tablero"
3. Introduce el nombre

### Cambiar de tablero
- Haz clic en el nombre del tablero actual en el header
- O usa el menú lateral para ver todos tus tableros

### Crear tareas
- Haz clic en el botón **+** del header
- O en "Añadir tarea" en cualquier columna

### Mover tareas
- **Arrastra y suelta** la tarjeta a otra columna

### Editar/Eliminar tareas
- Haz clic en los **tres puntos** (⋯) de la tarjeta

### Exportar datos (backup)
1. Abre el menú ☰
2. Selecciona "Exportar datos (JSON)"
3. Se descargará un archivo `.json` con todos tus tableros y tareas

### Importar datos
1. Abre el menú ☰
2. Selecciona "Importar datos (JSON)"
3. Elige el archivo de backup
4. ¡Listo! Todos tus datos se restaurarán

## 💾 Persistencia de datos

Tus tableros y tareas se guardan **automáticamente** en tu navegador usando `localStorage`. Esto significa:

- ✅ Los datos persisten entre sesiones
- ✅ Funciona sin conexión a internet
- ⚠️ Los datos están vinculados al navegador específico

**Para transferir datos entre dispositivos/navegadores**, usa la función de **Exportar/Importar**.

## ⌨️ Atajos de teclado

| Tecla | Acción |
|-------|--------|
| `Escape` | Cerrar modales/menús |
| `+` (botón) | Nueva tarea |

## 🎨 Personalización

Puedes modificar los colores editando las variables CSS:

```css
:root {
    --todo-dot: #666666;
    --progress-dot: #3b82f6;
    --review-dot: #f59e0b;
    --done-dot: #22c55e;
    --cancelled-dot: #ef4444;
}
```

## 📁 Estructura

```
kanban/
├── index.html    # Todo en uno: HTML, CSS y JavaScript
└── README.md     # Este archivo
```

## 🔒 Privacidad

Tus datos se almacenan **localmente** en tu navegador. No se envían a ningún servidor.

## 📝 Licencia

MIT - Úsalo libremente.

---

Hecho con ❤️ para ser útil.
