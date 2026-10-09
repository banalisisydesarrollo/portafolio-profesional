# Portafolio Creadigita — Brayan Smith Andrades Rentería

Sitio estático bilingüe ES/EN para publicar con GitHub Pages y dominio `creadigita.com`.

## Publicación
1. Crea un repositorio público, por ejemplo `creadigita-portfolio`, en https://github.com/banalisisydesarrollo.
2. Sube el contenido de esta carpeta a la raíz del repositorio.
3. Ve a Settings → Pages y elige **GitHub Actions**.
4. El workflow de `.github/workflows/pages.yml` publicará la web en cada push a `main`.
5. En Settings → Pages → Custom domain, introduce `creadigita.com`. El archivo `CNAME` ya está incluido.

## DNS en Cloudflare
En Cloudflare → `creadigita.com` → DNS → Records, revisa primero los registros existentes y no borres MX/TXT ni registros de otros servicios.

Registros A para el dominio raíz:
- `@` → `185.199.108.153`
- `@` → `185.199.109.153`
- `@` → `185.199.110.153`
- `@` → `185.199.111.153`

Para `www`, crea CNAME `www` → `banalisisydesarrollo.github.io` (ajusta si publicas desde otra cuenta de GitHub). Para validar la conexión inicial, deja los registros como **DNS only** (nube gris). Después de la validación en GitHub Pages, activa **Enforce HTTPS** cuando esté disponible. DNS puede tardar en propagarse.

Documentación oficial:
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain
- https://developers.cloudflare.com/dns/

## Pendiente de verificar
- Estado exacto de graduación de Ingeniería de Sistemas (fecha informada: julio de 2026).
- Detalles verificables de AI Foundation™.
- Stack y evidencias de los proyectos históricos.
- Tu contribución concreta al sitio Elite Producción y Montaje.
- Añadir PDF de CV si quieres ofrecer descarga.

No subir bases de datos reales, credenciales ni datos personales/institucionales sensibles.
