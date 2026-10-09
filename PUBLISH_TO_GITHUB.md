# Cómo publicar este portafolio en GitHub

## Opción A — README del perfil

GitHub muestra un README especial en tu perfil si creas un repositorio público cuyo nombre sea exactamente tu nombre de usuario.

1. Abre https://github.com/new e inicia sesión.
2. En **Repository name**, escribe exactamente `banalisisydesarrollo`.
3. Selecciona **Public**.
4. Marca **Add a README file** si GitHub lo ofrece.
5. Crea el repositorio.
6. Abre `README.md`, selecciona editar y reemplaza su contenido por el archivo `README.md` de esta carpeta.
7. Guarda los cambios con un mensaje como `Add professional profile README`.

Si ya existe un repositorio llamado `banalisisydesarrollo`, no crees otro: abre el repositorio existente y revisa su contenido antes de reemplazar archivos.

## Opción B — Subir el portafolio web y las fichas

1. Crea un repositorio público llamado `portafolio-profesional` (o un nombre similar).
2. Dentro del repositorio, selecciona **Add file → Upload files**.
3. Sube el contenido de las carpetas `portfolio/` y `projects/`, junto con un `README.md` apropiado.
4. Confirma que `portfolio/index.html`, `portfolio/styles.css` y `portfolio/script.js` conserven sus rutas.
5. Selecciona **Commit changes**.

También puedes usar Git desde tu computador:

```bash
git clone https://github.com/banalisisydesarrollo/portafolio-profesional.git
cd portafolio-profesional
# Copia aquí los archivos y carpetas del paquete
git add .
git commit -m "Add initial professional portfolio"
git push origin main
```

Si usas HTTPS y Git solicita autenticación, sigue el flujo oficial de GitHub. No pegues contraseñas, tokens ni claves privadas en el repositorio.

## Publicar la web con GitHub Pages

La carpeta `portfolio/` contiene una web estática que no necesita backend.

**Camino más sencillo:** crea un repositorio independiente llamado `banalisisydesarrollo.github.io`, coloca `index.html`, `styles.css` y `script.js` en la raíz y ve a **Settings → Pages**. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`. Guarda y espera a que termine la publicación.

Alternativamente, si mantienes la web dentro de `portfolio/` de un repositorio de proyecto, configura Pages con GitHub Actions o mueve los archivos web a la raíz de un repositorio dedicado. La URL habitual de un sitio de usuario es `https://banalisisydesarrollo.github.io/`.

## Antes de hacerlo público

- Revisa todas las rutas y prueba los enlaces.
- Confirma las tecnologías exactas de los proyectos históricos.
- No subas código institucional o comercial sin permiso.
- Usa datos sintéticos y capturas anonimizadas.
- Añade solo certificaciones obtenidas y enlaces de verificación válidos.
- No incluyas `.env`, claves API, tokens, contraseñas ni datos personales de terceros.

## Checklist final

- [ ] README del perfil actualizado.
- [ ] Repositorio de portafolio creado.
- [ ] Sitio web probado en móvil y escritorio.
- [ ] Proyectos etiquetados honestamente: existente, documentación inicial o planificado.
- [ ] Certificación AI CERTs confirmada con nombre y fecha del diploma.
- [ ] Enlaces de LinkedIn, email y web comprobados.
