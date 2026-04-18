# Curso: IA Aplicada al Análisis de Datos

## Estructura del repositorio

```
curso-ia-datos/
├── sesion1/
│   ├── ventas_retail.csv       # Dataset de ventas por producto, región y canal
│   ├── ejercicios.md           # Instrucciones de los ejercicios
│   ├── exploracion.md          # (tu entregable) Análisis + observaciones
│   └── preguntas_negocio.md    # (tu entregable) Preguntas y respuestas con IA
├── sesion2/
│   ├── clientes_sucios.csv     # Dataset con problemas de calidad intencionales
│   ├── ejercicios.md
│   ├── reporte_problemas.md    # (tu entregable)
│   ├── decisiones_limpieza.md  # (tu entregable)
│   └── clientes_limpios.csv    # (tu entregable)
├── sesion3/
│   ├── churn_clientes.csv      # Dataset de clientes con variable objetivo churn
│   ├── ejercicios.md
│   ├── modelo_churn.ipynb      # (tu entregable)
│   └── evaluacion_metrica.md   # (tu entregable)
└── sesion4/
    ├── ejercicios.md
    ├── narrativa_ia.md         # (tu entregable)
    └── dashboard/              # (tu entregable) imagen o PDF del dashboard
```

## Datasets incluidos

| Dataset | Sesión | Descripción |
|---------|--------|-------------|
| `ventas_retail.csv` | 1 | 58 registros de ventas de productos tecnológicos, con picos en noviembre/diciembre |
| `clientes_sucios.csv` | 2 | 35 clientes con problemas intencionales: nulos, edades imposibles, emails inválidos, formatos inconsistentes |
| `churn_clientes.csv` | 3 | 50 clientes de telecomunicaciones con variable `churn` (0/1) para clasificación |

## Cómo subir tus entregables

```bash
git add sesion1/exploracion.md sesion1/preguntas_negocio.md
git commit -m "Sesión 1: análisis exploratorio con IA"
git push
```
