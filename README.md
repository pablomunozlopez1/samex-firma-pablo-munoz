# Firma de correo — Pablo Muñoz (SAMEX)

Firma HTML para Microsoft 365 / Outlook, con **modo claro y oscuro automático**.

- **Sitio:** https://pablomunozlopez1.github.io/samex-firma-pablo-munoz/
- **Copiar la firma:** https://pablomunozlopez1.github.io/samex-firma-pablo-munoz/copiar.html
- **HTML de la firma:** https://pablomunozlopez1.github.io/samex-firma-pablo-munoz/firma.html

## Contenido

| Ruta | Uso |
|---|---|
| `index.html` | Vista de los dos modos de color |
| `copiar.html` | Página fija en modo claro para copiar y pegar en Outlook |
| `firma.html` | HTML completo de la firma (con `prefers-color-scheme` y `[data-ogsc]`) |
| `assets/` | 9 PNG con transparencia: logotipos en versión clara y oscura |

## Notas

- Las imágenes se sirven por HTTPS desde `assets/` y se referencian con URL absoluta,
  que es lo que necesitan los clientes de correo.
- Las versiones oscuras de los logotipos se muestran sólo cuando el cliente de
  correo está en modo oscuro; el resto del tiempo quedan ocultas.
- Para cambiar textos o colores, edita `firma.html` y `copiar.html` y vuelve a subirlos.
