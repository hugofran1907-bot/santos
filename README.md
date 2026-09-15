# Autoescola Santos - Web (Cambrils)

Web completa y funcional a partir del diseño de Stitch, con 6 páginas HTML en catalán.

## 📄 Páginas incluidas
- `index.html` — Inicio
- `permisos.html` — Permisos de conducir (AM, A1, A2, A, B) + calculadora de edad interactiva
- `sobre-nosaltres.html` — Sobre nosotros
- `resultats-dgt.html` — Resultados DGT
- `contacte.html` — Contacto (formulario validado)
- `privacitat.html` — Política de privacidad (creada para completar el flujo del checkbox de consentimiento del formulario)

## ✅ Qué se ha hecho sobre el diseño de Stitch
- Todos los `href="#"` de navegación (menú desktop, drawer móvil, bottom nav, footer) se han sustituido por enlaces reales entre las 5 páginas.
- El logo del header ahora enlaza a `index.html` en todas las páginas.
- El formulario de contacto ya incluía validación, estados de carga y mensaje de éxito — se ha dejado tal cual (funciona a nivel frontend; no hay backend conectado).
- Se ha creado `privacitat.html` porque el checkbox de consentimiento del formulario enlazaba a una página inexistente. Contiene texto legal estándar (RGPD) usando solo los datos reales de contacto de la escuela.
- El botón de WhatsApp de la página de Permisos usa el número 977 36 17 67, confirmado por Hugo como el WhatsApp real de la autoescuela.
- El logo ya no depende de una URL externa de Google: ahora se usa el archivo local `logo-santos-small.png` (el logo real que nos diste, en granate sobre transparente) en el header, menú móvil y footer de las 6 páginas. También se incluye `logo-santos.png` en alta resolución por si se necesita en algún otro sitio. Los dos están en la **raíz** del proyecto (no en una subcarpeta), porque la subida de carpetas vía el "Upload files" de GitHub no siempre conserva subcarpetas.
- Se ha eliminado la regla CSS que ocultaba la barra de scroll (pensada originalmente para una app móvil). Ahora el scroll se ve y funciona con normalidad en escritorio.

## ⚠️ Nota
No queda ningún pendiente por confirmar por tu parte — todos los puntos anteriores están resueltos.

## 🚀 Cómo subirlo a GitHub + Vercel
1. Descomprime el ZIP.
2. Ve a tu repositorio de GitHub → "Add file" → "Upload files".
3. Arrastra **todos** los archivos sueltos (los .html, el README y las dos imágenes .png) directamente — todos van en la raíz del repo, no hay subcarpetas.
4. Haz commit.
5. Ve a Vercel → "New Project" → selecciona el repo → Deploy.

**Importante:** todos los archivos (HTML + las 2 imágenes .png) deben quedar sueltos en la raíz del repo, o Vercel dará error 404 y el logo no se verá.
