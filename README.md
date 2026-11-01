# Mi Quiniela en directo

App web casera para seguir La Quiniela: aciertos en directo, probabilidades de premio, marcadores en vivo e historial de jornadas.

## Estructura

```
index.html   ← toda la app (HTML + CSS + JavaScript en un solo archivo)
README.md
```

## Cómo abrirla

- Doble clic en `index.html` → se abre en el navegador.
- En VS Code: extensión **Live Server** → clic derecho en `index.html` → *Open with Live Server* (recarga sola al guardar).

## Datos

Se guardan en el `localStorage` del navegador (clave `quiniela-casera-v3`).
Para pasar datos entre dispositivos: botones *Copiar datos* / *Importar* al final de la página.

## Próximos pasos

- [ ] Publicar en GitHub Pages / Netlify (instalable como app, sin barra de claude.ai)
- [ ] Resultados en directo automáticos con API-Football vía Cloudflare Worker
- [ ] Balance gastado/ganado, estadísticas de fallos y detector de signos sobreapostados
