# Twisi - Twitch Dashboard

Dashboard interactivo para streams de Twitch con diseño bento grid.

## 🎨 Características

- **Diseño Bento Grid** con 6 contenedores personalizados
- **Esquema de colores**: Rosa, blanco y celeste
- **Contenedores incluidos**:
  - Stream en vivo (horizontal)
  - Chat de Twitch
  - Estado Live/Offline
  - Descripción del canal
  - Horario de streams
  - Enlaces sociales

## 🚀 Desarrollo

```bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# Compilar para producción
npm run build

# Vista previa de producción
npm run preview
```

## ⚙️ Configuración

Para conectar tu canal de Twitch, edita el archivo `src/pages/index.astro` y reemplaza `YOUR_CHANNEL` con tu nombre de usuario de Twitch:

```html
<iframe
  src="https://player.twitch.tv/?channel=TU_CANAL&parent=localhost"
  ...
</iframe>
```

Y también en el chat:

```html
<iframe
  src="https://www.twitch.tv/embed/TU_CANAL/chat?parent=localhost"
  ...
</iframe>
```

## 📱 Responsive

El diseño es completamente responsive y se adapta a:
- Desktop (4 columnas)
- Tablet (2 columnas)
- Mobile (1 columna)

## 🛠️ Tecnologías

- Astro
- TypeScript
- CSS Grid
- Twitch Embed API
