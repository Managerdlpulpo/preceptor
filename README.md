# Preceptor

App web móvil para que cada profesor gestione su lista de preceptuados y registre las reuniones de tutoría.

## Cómo usar

1. Abre la app en el navegador (o añádela a la pantalla de inicio en el móvil).
2. Crea tu perfil (nombre, iniciales, curso).
3. Añade alumnos o importa un Excel/CSV.
4. Registra reuniones. Todo se guarda solo en la memoria del navegador de ese dispositivo.

## Publicación

Repositorio: https://github.com/Managerdlpulpo/preceptor

Dominio de la app: **https://preceptor.andelmanager.es**

(La web principal de entrenador en andelmanager.es no se toca.)

### DNS (PiensaSolutions)

En el panel DNS de andelmanager.es crea **solo** este registro:

| Tipo  | Host / Nombre | Valor / Destino              |
|-------|---------------|------------------------------|
| CNAME | preceptor     | managerdlpulpo.github.io     |

No modifiques los registros de `@` ni de `www`.

### GitHub Pages

1. Settings → Pages.
2. Source: Deploy from branch → `main` / `/ (root)`.
3. Custom domain: `preceptor.andelmanager.es` (el archivo CNAME ya está en el repo).
4. Marca **Enforce HTTPS** cuando esté disponible.