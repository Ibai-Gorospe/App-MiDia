# 📱 Mi Día — Guía de instalación

## Opción 1: Netlify (la más fácil, sin cuenta de GitHub)

1. Ve a [netlify.com](https://www.netlify.com) y crea una cuenta gratuita
2. En el dashboard, busca la zona que dice **"Drag and drop"**
3. Arrastra la carpeta **`mi-dia`** completa ahí
4. ¡Listo! Netlify te dará una URL tipo `https://algo-random.netlify.app`
5. Abre esa URL en el navegador de tu móvil

### Instalar en tu móvil:
- **iPhone (Safari)**: Pulsa el botón compartir (↑) → "Añadir a pantalla de inicio"
- **Android (Chrome)**: Debería aparecer un banner automático. Si no, pulsa ⋮ → "Instalar app" o "Añadir a pantalla de inicio"

---

## Opción 2: GitHub Pages (gratis, necesitas cuenta GitHub)

1. Crea una cuenta en [github.com](https://github.com) si no tienes
2. Crea un repositorio nuevo (ej: `mi-dia`)
3. Sube todos los archivos de la carpeta `mi-dia` al repositorio
4. Ve a **Settings → Pages → Source**: selecciona `main` branch y `/root`
5. En unos minutos tendrás tu app en `https://tu-usuario.github.io/mi-dia`

---

## Opción 3: Vercel (gratis, muy rápido)

1. Ve a [vercel.com](https://vercel.com) y crea cuenta
2. Haz clic en "Add New Project"
3. Sube la carpeta o conecta tu repo de GitHub
4. Deploy automático → URL tipo `https://mi-dia.vercel.app`

---

## Archivos del proyecto

```
mi-dia/
├── index.html      ← La app completa
├── manifest.json   ← Configuración PWA
├── sw.js           ← Service Worker (funciona offline)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── GUIA.md         ← Este archivo
```

## Personalizar URL en Netlify

Si quieres una URL más bonita:
1. En Netlify, ve a **Site settings → Domain management**
2. Haz clic en "Change site name"
3. Ponle algo como `mi-dia-ibai` → quedará `https://mi-dia-ibai.netlify.app`

---

## Funcionalidades

- ✅ Añadir tareas para hoy, mañana o cualquier día
- ✅ Marcar tareas como completadas
- ✅ Barra de progreso visual
- ✅ Navegación por días (flechas o deslizar)
- ✅ Funciona sin conexión a internet
- ✅ Se instala como app nativa en el móvil
- ✅ Los datos se guardan en tu dispositivo (localStorage)
