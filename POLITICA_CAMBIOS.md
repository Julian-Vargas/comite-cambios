# Política de Gestión de Cambios

> Documento ficticio para uso académico.

## 1. Campos obligatorios

Toda solicitud de cambio (RFC) debe incluir los siguientes campos:

| Campo | Descripción |
|---|---|
| Descripción | Qué se va a cambiar y por qué. |
| Sistema afectado | Sistema del inventario sobre el que se aplica el cambio. |
| Ventana propuesta | Día y horario en que se ejecutará el cambio. |
| Plan de reversión | Pasos para devolver el sistema a su estado anterior si el cambio falla. |
| Responsable | Equipo o persona a cargo de ejecutar el cambio. |

Una solicitud a la que le falte cualquiera de estos campos se considera incompleta.

## 2. Clasificación de riesgo

| Riesgo | Criterio |
|---|---|
| **ALTO** | El cambio afecta, directa o indirectamente, un sistema de criticidad alta. |
| **MEDIO** | El cambio afecta un sistema de criticidad media. |
| **BAJO** | Todo lo demás. |

La criticidad de cada sistema y sus dependencias se consultan en `INVENTARIO.md`.

## 3. Requisitos para cambios de riesgo ALTO

Todo cambio de riesgo ALTO requiere:

1. Una ventana **fuera de horario hábil**. Se considera horario hábil de lunes a viernes, de 8:00 a 17:00.
2. La **aprobación del comité completo**.
