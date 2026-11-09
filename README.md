# TecnoElige: blog de tecnología

Blog estático con Jekyll que GitHub Pages construye y publica solo.

## Publicarlo por primera vez (unos 10 minutos, una sola vez)

1. Entra en github.com → **New repository**.
   - Nombre: `TU-USUARIO.github.io` (con tu usuario real). Así la web queda en
     `https://TU-USUARIO.github.io`.
   - Público. Sin README.
2. En el repositorio vacío: **uploading an existing file** → arrastra **todo el contenido**
   de esta carpeta (no la carpeta en sí) → **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. Espera 1-2 minutos y abre `https://TU-USUARIO.github.io`.
5. Edita `_config.yml` en GitHub (icono del lápiz) y pon `url: "https://TU-USUARIO.github.io"`.
6. Edita `aviso-legal.md` y rellena tus datos entre [corchetes].

## Ganar dinero

- **Amazon Afiliados** (afiliados.amazon.es): date de alta y pon tu ID en `amazon_tag`, dentro
  de `_config.yml`. Todos los enlaces del blog se actualizan solos.
  Amazon exige al menos 3 ventas en los primeros 180 días o cierra la cuenta, así que
  date de alta cuando el blog ya tenga unos 10-15 artículos.
- **Google Search Console**: da de alta la web para que Google la indexe antes.

## Rutina semanal (15 minutos)

Cada lunes, la tarea programada deja 3 artículos nuevos en el chat.

1. Léelos por encima y corrige lo que veas raro.
2. En GitHub → carpeta `_posts` → **Add file → Upload files** → arrastra los `.md` → Commit.
3. En 1-2 minutos están publicados.

Los nombres de archivo deben seguir el formato `AAAA-MM-DD-titulo.md`.
Un artículo con fecha futura no aparece hasta ese día.
