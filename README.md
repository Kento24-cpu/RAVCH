# Ríos de Agua Viva Chinandega — RAVCH

Ministerio Evangelístico Ríos de Agua Viva Chinandega.
Sitio web oficial con información del ministerio, eventos, transmisiones y mapa de ubicación.

## Tech Stack

- [Astro](https://astro.build) — Framework web
- [Tailwind CSS v4](https://tailwindcss.com) — Estilos
- [React](https://react.dev) — Componentes interactivos
- [astro-icon](https://github.com/natemoo-re/astro-icon) — Iconos (Heroicons, MDI)

## Project Structure

```
src/
├── assets/          # Imágenes estáticas
├── components/      # Componentes reutilizables
│   ├── Footer.astro
│   ├── MobileSideBar.astro
│   └── VerseDay.astro
├── layouts/
│   └── BaseLayout.astro   # Layout principal con header, sidebar, footer
├── pages/
│   ├── index.astro        # Inicio
│   ├── about.astro        # Sobre nosotros
│   ├── eventos.astro      # Eventos
│   ├── mapa.astro         # Ubicación
│   └── social.astro       # Redes sociales
└── styles/
    └── global.css         # Tema Tailwind + dark mode
```

## Commands

| Comando | Acción |
|---------|--------|
| `npm run dev` | Inicia servidor local |
| `npm run build` | Build producción a `dist/` |
| `npm run preview` | Vista previa del build |
