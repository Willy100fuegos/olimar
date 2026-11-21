# Olimar - Limpieza Profesional Industrial y Corporativa

Sitio web estático oficial de **Olimar** ([https://olimar.com.mx](https://olimar.com.mx)).

Empresa especializada en servicios de limpieza industrial, corporativa, trabajos en altura y desazolve con más de 12 años de experiencia en el Sureste de México.

## Estructura del Proyecto

```text
olimar/
├── .gitignore   # Reglas de exclusión para Git y control de versiones
├── README.md    # Documentación del proyecto
└── index.html   # Sitio web principal estático (HTML5, Tailwind CDN, Remix Icon)
```

## Visualización y Desarrollo Local

Al ser un sitio web estático independiente en HTML, no requiere pasos de compilación ni dependencias de Node.js:

### Opción 1: Abrir directamente en el navegador
Puedes hacer doble clic en el archivo `index.html` o abrirlo desde tu navegador web preferido.

### Opción 2: Servidor local ligero

Con **Python**:
```bash
python -m http.server 8000
```
Luego abre `http://localhost:8000` en tu navegador.

Con **Node.js (npx)**:
```bash
npx serve .
```

Con **VS Code**:
Utiliza la extensión **Live Server** haciendo clic derecho en `index.html` -> *Open with Live Server*.
