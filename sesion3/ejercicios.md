# Sesión 3 – Modelado predictivo con IA

## Ejercicio 3.1 – Construir un modelo

En Google Colab, usando el dataset `churn_clientes.csv`:

1. Pide a la IA (ChatGPT o GitHub Copilot) que genere el código para un modelo de clasificación básico que prediga si un cliente va a cancelar (`churn = 1`).
2. Ejecuta el código y captura las métricas obtenidas.
3. Guarda el notebook como `modelo_churn.ipynb`.

**Prompt sugerido para la IA:**
> "Tengo un dataset CSV con clientes de telecomunicaciones. La columna objetivo es 'churn' (1 = canceló, 0 = sigue activo). Genera el código Python para entrenar un modelo de clasificación básico y mostrar sus métricas principales."

**Resultado de la actividad:** `modelo_churn.ipynb`

---

## Ejercicio 3.2 – Evaluar la métrica elegida

La IA probablemente eligió `accuracy` como métrica principal. Responde en `evaluacion_metrica.md`:

1. ¿Qué métricas obtuvo tu modelo? (accuracy, precision, recall, F1)
2. ¿Es `accuracy` la métrica más adecuada para predecir churn? ¿Por qué sí o por qué no?
3. ¿Qué métrica usarías tú para este caso de negocio? Justifica tu respuesta.
4. ¿Qué le dirías al área de negocio basándote en estas métricas?

**Pista:** Piensa en el costo de un falso negativo (predecir que el cliente NO se va, cuando sí se va) vs. un falso positivo.

**Resultado de la actividad:** `evaluacion_metrica.md`
