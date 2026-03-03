# ANEXO A — Base de Datos y Preprocesamiento

## Propósito
Documentar la estructura del dataset (16 estaciones, 4 zonas, 2017–2022), el preprocesamiento y la generación de variables derivadas (ρ, WPD, Eh), garantizando coherencia física y trazabilidad.

## Entradas
- `data/Datos_demo.csv` (incluido)
- `data/Datos.txt` (dataset real, no incluido)

## Salidas esperadas
- `outputs/anexoA/`:
  - Resúmenes por estación y zona
  - Control de NA y outliers
  - Variables derivadas (ρ, WPD, Eh)
  - Log de imputación oscilatoria
- `logs/sessionInfo_anexoA.txt`

## Variables y definiciones
- Densidad del aire: ρ = ρ(P, T)
- Densidad de potencia eólica: WPD = 0.5 · ρ · v^3
- Energía integrada por horizonte: Eh (definición según tesis)

## Imputación oscilatoria
Aquí se documentará:
- definición operacional
- justificación física
- criterios de aplicación
- control de impacto en estadísticos y espectros

## Reproducibilidad
Script asociado:
- `scripts/01_anexoA_prepro.R`

Ejecución (demo):
- `Rscript scripts/01_anexoA_prepro.R`

Ejecución (full):
- colocar `data/Datos.txt` y ejecutar el mismo script.
