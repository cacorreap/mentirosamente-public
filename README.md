# Mentirosamente — descarga pública

Página de descarga y distribución del APK de **Mentirosamente** (juego social para Android).
El código fuente de la app vive en un repositorio privado aparte; aquí solo está la web de descarga.

- **Página:** https://cacorreap.github.io/mentirosamente-public/
- **Descarga directa (último APK):** https://github.com/cacorreap/mentirosamente-public/releases/latest/download/mentirosamente.apk
- **Privacidad:** https://cacorreap.github.io/mentirosamente-public/privacy.html

## Cómo publicar una versión nueva

El APK **no** se sube a git (está en `.gitignore`). Se publica como asset de un **Release**:

1. Genera el APK y renómbralo a `mentirosamente.apk`.
2. En GitHub → pestaña **Releases** → **Draft a new release**.
3. Crea un tag (ej. `v1.0.0`), arrastra el `mentirosamente.apk` como asset y publica.

El link de descarga de la página siempre apunta al **último** release (`releases/latest`), así que no hay que tocar el HTML al actualizar.

## Estructura

- `index.html` — página de descarga.
- `privacy.html` — política de privacidad.
- `assets/` — icono y logo.
