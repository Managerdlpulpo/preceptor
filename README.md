# Preceptor

App web móvil para que cada profesor gestione su lista de preceptuados y registre las reuniones de tutoría.

## Cómo usar

1. Abre la app en el navegador (o añádela a la pantalla de inicio en el móvil).
2. Crea tu perfil (nombre, iniciales, curso).
3. Añade alumnos o importa un Excel/CSV.
4. Registra reuniones. Todo se guarda solo en la memoria del navegador de ese dispositivo.

## Publicación

Repositorio: https://github.com/Managerdlpulpo/preceptor

Dominio: **https://andelmanager.es**

### DNS (PiensaSolutions)

En el panel DNS de andelmanager.es crea:

| Tipo  | Host / Nombre | Valor / Destino              |
|-------|---------------|------------------------------|
| CNAME | @             | managerdlpulpo.github.io     |
| CNAME | www           | managerdlpulpo.github.io     |

Si el panel no deja CNAME en `@`, usa un registro A con las IPs de GitHub Pages:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Y un CNAME `www` → `managerdlpulpo.github.io`.

### GitHub Pages

1. Settings → Pages.
2. Source: Deploy from branch → `main` / `/ (root)`.
3. Custom domain: `andelmanager.es` (el archivo CNAME ya está en el repo).
4. Marca **Enforce HTTPS** cuando esté disponible.
