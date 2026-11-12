# Acta de Impacto — RFC-003

- **Corrida:** corrida3

## Sistemas afectados directamente

| Sistema | Criticidad | Fila del inventario que lo respalda |
|---|---|---|
| AUTH-CORE | Media | `\| AUTH-CORE \| Autenticación interna \| Media \| Ninguna \|` |

## Sistemas afectados indirectamente

| Sistema | Criticidad | Por qué se afecta | Fila del inventario que lo respalda |
|---|---|---|---|
| INTRANET | Baja | Depende de AUTH-CORE, el sistema afectado directamente. Ningún otro sistema del inventario depende de INTRANET. | `\| INTRANET \| Portal interno \| Baja \| AUTH-CORE \|` |
