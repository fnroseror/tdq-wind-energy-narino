# ANEXO C — Machine Learning

## Propósito
Documentar el pipeline reproducible de ML (Random Forest, XGBoost), optimización (Bayes), comparación por zonas y análisis de importancia de variables con interpretación física.

## Entradas
- Dataset desde `data/` o features derivados del pipeline

## Salidas esperadas
- `outputs/anexoC/`: tabla comparativa, mejores hiperparámetros, importancias, gráficos
- `logs/sessionInfo_anexoC.txt`

## Reproducibilidad
Script asociado:
- `scripts/03_anexoC_ml.R`

Ejecución:
- `Rscript scripts/03_anexoC_ml.R`
