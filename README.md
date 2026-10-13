# Preceptor

App web móvil para que cada profesor gestione su lista de preceptuados y registre las reuniones de tutoría.

## Cómo usar

1. Abre la app en el navegador (o añádela a la pantalla de inicio en el móvil).
2. Crea tu perfil (nombre, iniciales, curso).
3. Añade alumnos o importa un Excel/CSV.
4. Registra reuniones. Todo se guarda solo en la memoria del navegador de ese dispositivo.

## GitHub Pages

Repositorio: https://github.com/Managerdlpulpo/preceptor

Para publicar:

1. Ve a **Settings → Pages**.
2. Source: Deploy from branch → `main` / `/ (root)`.
3. Save.

La URL será: `https://managerdlpulpo.github.io/preceptor/`

### Dominio propio

1. En el mismo Settings → Pages, Custom domain: escribe tu dominio (ej. `preceptor.tudominio.es`).
2. En el DNS de tu dominio crea un registro **CNAME** que apunte a `managerdlpulpo.github.io`.
3. Espera unos minutos y marca "Enforce HTTPS".

Los datos siguen guardándose solo en el navegador de cada usuario (no hay servidor de base de datos).
