# Sesión 2 – Limpieza de datos con IA

## Ejercicio 2.1 – Detección de problemas

Carga `clientes_sucios.csv` en ChatGPT y solicita:
- Detección de valores nulos o faltantes
- Detección de outliers (valores fuera de rango lógico)
- Inconsistencias de formato (emails inválidos, ciudades con nombres distintos para el mismo lugar, etc.)

Genera un archivo `reporte_problemas.md` listando cada problema encontrado, indicando:
- Columna afectada
- Tipo de problema
- Filas involucradas

**Resultado de la actividad:** `reporte_problemas.md`

---

## Ejercicio 2.2 – Decisiones de limpieza

Por cada problema identificado en el ejercicio anterior, decide y documenta en `decisiones_limpieza.md`:

| Problema | Corrección sugerida por IA | ¿La aceptas? | Justificación |
|----------|---------------------------|--------------|---------------|
| ...      | ...                        | Sí / No      | ...           |

Preguntas guía:
- ¿Qué impacto tendría en el análisis si no se corrige este problema?
- ¿Hay alguna corrección que la IA sugiere que podría distorsionar los datos?

Luego genera `clientes_limpios.csv` con las correcciones que decidiste aplicar.

**Resultado de la actividad:** `decisiones_limpieza.md` + `clientes_limpios.csv`
