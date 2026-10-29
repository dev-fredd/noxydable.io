# Noxydable Pages

Sitio estatico para los enlaces de marca requeridos por la pantalla de consentimiento OAuth de Google.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo llamado `dev-fredd.github.io` en la cuenta `dev-fredd`.
2. Configura ese repositorio como `origin` de esta carpeta y publica la rama `main`.
3. En GitHub, abre **Settings > Pages** y selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`.
4. Espera a que GitHub publique `https://dev-fredd.github.io/`.

## Verificar el dominio para Google OAuth

1. En [Google Search Console](https://search.google.com/search-console), crea una propiedad de prefijo de URL para `https://dev-fredd.github.io/`.
2. Selecciona la verificacion por etiqueta HTML.
3. Copia la etiqueta que entrega Google dentro de `<head>` en `index.html`, publica el cambio y confirma la verificacion en Search Console.
4. En Google Auth Platform, registra `dev-fredd.github.io` como dominio autorizado.

Usa despues estas URLs en Branding:

- Pagina principal: `https://dev-fredd.github.io/`
- Politica de privacidad: `https://dev-fredd.github.io/privacy.html`
- Terminos de servicio: `https://dev-fredd.github.io/terms.html`
