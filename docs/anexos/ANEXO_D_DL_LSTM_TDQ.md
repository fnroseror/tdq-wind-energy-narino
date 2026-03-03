# ANEXO D — Deep Learning (LSTM–TDQ)

## Propósito
Documentar el pipeline reproducible de DL (LSTM–TDQ), incluyendo arquitectura, regularización, estabilidad numérica, curvas de entrenamiento y evaluación.

## Entradas
- Dataset desde `data/` o features derivados del pipeline (según implementación)

## Salidas esperadas
- `outputs/anexoD/`: curvas entrenamiento, métricas, predicciones, (PI si aplica)
- `logs/sessionInfo_anexoD.txt`

## Elementos mínimos
- Arquitectura (capas, ventanas, horizonte)
- Función de pérdida
- Regularización / callbacks
- Control de semillas y reproducibilidad

## Reproducibilidad
Script asociado:
- `scripts/04_anexoD_dl_lstm.R`

Ejecución:
- `Rscript scripts/04_anexoD_dl_lstm.R`
