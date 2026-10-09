# Política de privacidad de Lubenware

Página publicada: **https://lubenware.github.io/privacy/**

Este repositorio publica, con GitHub Pages, la política de privacidad de las esferas
de reloj que **Lubenware** publica en Google Play para relojes Wear OS.

Es una **sola política para todas las esferas**: la misma URL se enlaza desde la
ficha de Google Play de cada una, y la tabla "Esferas cubiertas" indica a qué
aplicaciones se aplica (nombre y package name).

## Esferas cubiertas

| Esfera | Nombre del paquete |
|---|---|
| Runner Style | `com.lubenware.watchfaces.runnersportstyle` |
| Atmos | `com.lubenware.watchfaces.atmos` |

Todas funcionan igual: **no piden ningún permiso** y **no recogen ni transmiten
datos**. No hay analítica, ni publicidad, ni SDKs de terceros.

## Contenido del repositorio

| Fichero | Para qué |
|---|---|
| `index.html` | La política, en español e inglés, autocontenida (sin CDN, sin fuentes ni imágenes externas) |
| `.nojekyll` | Evita que GitHub Pages procese el contenido con Jekyll |
| `README.md` | Este resumen |

## Añadir una esfera nueva

1. Añadir una fila a la tabla "Esferas cubiertas" de `index.html` **en los dos
   idiomas** (español e inglés).
2. `git add -A && git commit -m "Cubre la esfera <nombre>" && git push`

Si la esfera nueva se comportara de otro modo (internet, analítica, anuncios,
permisos sensibles o datos de salud), hay que ampliar la política **antes** de
publicarla y actualizar su formulario de *Data safety* en Play Console: ese
formulario es **por package name**, cada esfera tiene el suyo.

Contacto: el indicado en la sección 7 de la política.

Última actualización: 9 de octubre de 2026.
