# UGO Arena H

Repositorio independiente para consolidar las versiones `ugo hecho arena` y `ugoarenapro`.

## Estado

Repositorio inicializado. **El código de los ZIP todavía no se ha importado a GitHub.**

## Estructura prevista

- `ugo-hecho-arena/` — variante con administración ampliada.
- `ugoarenapro/` — variante alternativa.

## Seguridad antes del despliegue

Ambas variantes requieren revisar el control de acceso a `/api/auth/current`, `/api/seed` y endpoints administrativos. No conectar a Supabase Arena PROD, ni publicar sin corregir autenticación, autorización y modo demostración.

## Configuración

Guardar credenciales solo en variables de entorno del proveedor; nunca incluir archivos `.env` reales en Git.
