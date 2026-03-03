# ANEXO B — Pipeline Clásico (ARIMA / ARIMAX)

## Propósito
Presentar el pipeline reproducible de modelos clásicos, incluyendo selección de orden, validación temporal walk-forward y métricas comparativas, con justificación física-estadística.

## Entradas
- Dataset desde `data/` (demo o real)
- Variables derivadas desde Anexo A (si aplica)

## Salidas esperadas
- `outputs/anexoB/`: métricas, pronósticos, diagnósticos de residuos
- `logs/sessionInfo_anexoB.txt`

## Modelo matemático
Documentar forma ARIMA/ARIMAX y supuestos.

## Validación
- Esquema walk-forward
- Métricas: RMSE, MAE, R², Skill vs persistencia

## Reproducibilidad
Script asociado:
- `scripts/02_anexoB_arima_arimax.R`

Ejecución:
- `Rscript scripts/02_anexoB_arima_arimax.R`
