# astro-starter

Starter moderno con **Astro 5 + Tailwind CSS 4** para crear landing pages o sitios rápidos con una base limpia, componentes reutilizables y estilos globales listos para producción.

## 🖼️ Mockup

<img src="https://i.imgur.com/p7Zs6Bv.png" alt="Mockup de la página" />

## 🚀 Stack

- [Astro](https://astro.build/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)

## 📦 Requisitos

- Node.js 18+
- npm o bun

## ⚙️ Instalación y desarrollo

```bash
# instalar dependencias
npm install

# iniciar en modo desarrollo
npm run dev
```

El servidor se levanta con host `0.0.0.0` para poder acceder desde red local si lo necesitas.

## 🧪 Scripts disponibles

```bash
npm run dev      # entorno de desarrollo
npm run build    # build de producción
npm run preview  # vista previa del build
npm run astro    # CLI de Astro
```

## 🗂️ Estructura

```text
src/
  components/
    Button.astro
    Card.astro
    Footer.astro
    Header.astro
  layouts/
    Layout.astro
  pages/
    index.astro
  styles/
    global.css
public/
astro.config.mjs
tsconfig.json
```

## ✍️ Personalización rápida

1. Edita `src/pages/index.astro` para cambiar el contenido de la portada.
2. Reutiliza o ajusta componentes en `src/components/`.
3. Ajusta estilos base en `src/styles/global.css`.

## 🚢 Deploy

Genera el build con:

```bash
npm run build
```

Luego despliega la carpeta `dist/` en tu proveedor preferido (Vercel, Netlify, VPS, etc.).

---

Si quieres, en el siguiente paso te dejo también una propuesta de **descripción corta para GitHub** y **topics** recomendados para el repo.
