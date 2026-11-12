# Acta de Impacto — RFC-003

- **Corrida:** corrida2

## Sistemas afectados directamente

| Sistema | Criticidad | Fila del inventario que lo respalda |
|---|---|---|
| AUTH-CORE | Media | `\| AUTH-CORE \| Autenticación interna \| Media \| Ninguna \|` |

## Sistemas afectados indirectamente

| Sistema | Criticidad | Por qué se afecta | Fila del inventario que lo respalda |
|---|---|---|---|
| PAGOS-RT | Alta | Depende de AUTH-CORE | `\| PAGOS-RT \| Pagos en tiempo real \| Alta \| AUTH-CORE \|` |
| INTRANET | Baja | Depende de AUTH-CORE | `\| INTRANET \| Portal interno \| Baja \| AUTH-CORE \|` |
