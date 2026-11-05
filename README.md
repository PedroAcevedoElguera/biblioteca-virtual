# Biblioteca Virtual IE 121 Virgen de Fatima

Frontend estático para GitHub Pages. El catálogo permanece en Google Sheets y se consulta mediante una aplicación web de Google Apps Script.

## Configuración

1. Copie el contenido de `Code.gs.backend` a su proyecto de Apps Script.
2. En Apps Script, seleccione **Implementar > Nueva implementación > Aplicación web**.
3. Configure **Ejecutar como: Yo** y el acceso apropiado para su público.
4. Copie la URL que termina en `/exec`.
5. En `js/config.js`, sustituya la URL de ejemplo por la URL `/exec` completa.
6. Suba `index.html`, `css`, `js`, `.gitignore` y este `README.md` a GitHub.
7. En GitHub, abra **Settings > Pages**, seleccione **Deploy from a branch**, rama `main`, carpeta `/root`.

## Importante

- No suba `Code.gs.backend` al repositorio público si después agrega secretos.
- La URL de Apps Script no es un secreto. La seguridad debe aplicarse en el backend.
- Los PDF y portadas de Drive deben tener permisos que permitan su visualización por el público objetivo.
- Después de cambiar `Code.gs`, cree una nueva versión de la implementación o edite la implementación existente.
