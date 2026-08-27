# Invitación de XV años

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube **todo el contenido de esta carpeta**, manteniendo `index.html` en la raíz.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda. GitHub Pages generará la URL del sitio.

## Personalizar fecha y nombre

Abre `index.html` y busca:

```js
const CONFIG={
  nombre:'Fiorella',
  fechaEvento:'2026-12-31T20:00:00',
  fechaTexto:'SÁBADO · 31 DE DICIEMBRE · 2026',
  fechaCorta:'31 · DICIEMBRE · 2026'
};
```

`fechaEvento` usa el formato `AAAA-MM-DDTHH:MM:SS` y controla el contador real.

## Personalizar enlaces

Cambia los enlaces de Google Maps y WhatsApp dentro de `index.html` por los datos reales del evento.
