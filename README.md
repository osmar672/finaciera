# Constructora ÁUREA — Suite V3

## Ejecutar

```bash
npm install
npm run dev
```

- Sitio React: http://localhost:5173
- Panel Admin completo: http://localhost:9173/production/index.html

## Usuarios

**Administrador**
- admin@aurea.cr
- admin123

**Persona**
- persona@aurea.cr
- persona123

El botón **Panel Admin** solo aparece para el administrador. Las páginas del panel incluyen una protección de acceso del lado del cliente para impedir el acceso directo sin la sesión administrativa de la demo.

> Para seguridad real en producción se necesita backend con autenticación y autorización del servidor.

## Qué se corrigió

- Se conserva el proyecto admin original como aplicación Vite independiente, evitando copiar HTML sin procesar dentro de `public`.
- Se conservan sus SCSS, JS, assets y dependencias originales.
- Se eliminó el cursor/bolita negra del sitio React.
- Se añadió login con roles Admin y Persona.
- Se agregó acceso visible al panel únicamente para Admin.
- Se añadieron guardas a todas las páginas administrativas.
