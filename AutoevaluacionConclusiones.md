[Regrese al index](index.md)
# **Autoevaluación**
---
## Bitácora de Autoevaluación

### Aprendizajes de la Unidad 2

A lo largo de esta unidad comprendí que la inferencia estadística es el puente entre los datos disponibles y las conclusiones sobre la realidad que no podemos observar completamente. Aplicar la Prueba Z unimuestral me permitió entender que el valor-p no confirma ni niega una hipótesis: cuantifica cuán incompatibles son los datos con $H_0$. El A/B Testing me demostró que comparar dos grupos requiere evaluar primero si sus varianzas son iguales antes de elegir la prueba adecuada. Y el ANOVA me enseñó que con más de dos grupos la prueba Post-Hoc de Tukey es indispensable para identificar qué grupos específicos difieren.

### Dificultades superadas

- **Interpretación del valor-p:** La tentación de decir 'hay X% de probabilidad de que H0 sea falsa' es incorrecta. El valor-p es la probabilidad de obtener un resultado tan extremo *asumiendo que H0 es verdadera*.
- **Z vs T:** Con $n$ grande ambas convergen, pero T siempre es más conservadora (colas más pesadas), por lo que justificar la elección del test con el tamaño de muestra es clave.
- **ANOVA vs múltiples T:** Tres pruebas T individuales inflan el error Tipo I hasta ~14%; Tukey HSD controla ese error manteniendo el nivel de significancia global en 5%.
