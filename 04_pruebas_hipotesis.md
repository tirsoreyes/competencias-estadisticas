# Clase 4 --- Estadística inferencial y pruebas de hipótesis

## 1. Propósito

Que el alumno comprenda qué es una hipótesis estadística, identifique
hipótesis nula y alternativa, conozca los pasos de una prueba de
hipótesis y pueda realizar una prueba introductoria con Excel y, si está
disponible, SPSS.

El programa contempla pruebas de hipótesis descriptivas, correlacionales
y explicativas, así como los pasos para realizarlas y ejemplos con IBM
SPSS. fileciteturn1file0L32-L46

> **Criterio docente:** esta es probablemente la clase más difícil. No
> intentar cubrir todas las pruebas estadísticas. El objetivo es enseñar
> el razonamiento que está detrás de una prueba y practicar una prueba
> sencilla.

------------------------------------------------------------------------

# 2. Distribución

  Tiempo         Actividad
  -------------- ------------------------------
  0--20 min      Repaso de muestreo
  20--45 min     ¿Qué es una hipótesis?
  45--70 min     Hipótesis nula y alternativa
  70--80 min     Descanso
  80--110 min    Pasos de una prueba
  110--140 min   Ejemplo sencillo
  140--165 min   Excel/SPSS
  165--180 min   Interpretación y tarea

------------------------------------------------------------------------

# 3. ¿Qué es una hipótesis?

Una hipótesis es una afirmación que podemos someter a análisis
estadístico.

Ejemplo:

> El promedio de ventas mensuales de una sucursal es \$50,000.

Podemos utilizar datos de una muestra para evaluar esta afirmación.

------------------------------------------------------------------------

# 4. Hipótesis nula

Se representa normalmente como:

`H0`

Es la hipótesis que se pone a prueba.

Ejemplo:

`H0: μ = 50,000`

------------------------------------------------------------------------

# 5. Hipótesis alternativa

Se representa:

`H1` o `Ha`

Representa una diferencia o relación que queremos investigar.

Ejemplo:

`H1: μ ≠ 50,000`

------------------------------------------------------------------------

# 6. Ejemplo empresarial

Una empresa afirma que sus clientes gastan en promedio \$1,000.

Queremos comprobar la afirmación.

`H0: μ = 1,000`

`H1: μ ≠ 1,000`

Recopilamos una muestra y realizamos la prueba.

------------------------------------------------------------------------

# 7. Nivel de significancia

Usaremos principalmente:

`α = 0.05`

Explicar que es un criterio establecido antes de realizar la prueba.

No entrar en teoría avanzada.

------------------------------------------------------------------------

# 8. Valor p

Explicar de forma práctica:

El valor p es un resultado que ayuda a decidir si existe suficiente
evidencia estadística contra la hipótesis nula bajo el criterio
establecido.

Regla introductoria:

-   si `p < 0.05` → rechazamos H0;
-   si `p ≥ 0.05` → no rechazamos H0.

**No decir "aceptamos H0" como regla general.**

------------------------------------------------------------------------

# 9. Pasos de una prueba de hipótesis

Utilizar siempre esta secuencia:

1.  Plantear el problema.
2.  Definir H0.
3.  Definir H1.
4.  Establecer α.
5.  Seleccionar la prueba adecuada.
6.  Obtener datos.
7.  Ejecutar la prueba.
8.  Revisar resultado/p-valor.
9.  Tomar decisión estadística.
10. Interpretar en el contexto del problema.

------------------------------------------------------------------------

# 10. Caso sencillo

Una empresa quiere comprobar si el gasto promedio de sus clientes es
diferente de \$1,000.

Se obtiene una muestra.

Supongamos que el software produce:

`p = 0.03`

Como:

`0.03 < 0.05`

Decisión:

**Rechazar H0.**

Interpretación:

> Existe evidencia estadística suficiente, bajo el nivel de
> significancia establecido, para considerar que el gasto promedio
> difiere de \$1,000.

------------------------------------------------------------------------

# 11. Caso contrario

Si:

`p = 0.18`

Como:

`0.18 > 0.05`

Decisión:

**No rechazar H0.**

Interpretación:

> No existe evidencia estadística suficiente para afirmar que el
> promedio sea diferente de \$1,000.

No decir que demostramos que H0 es verdadera.

------------------------------------------------------------------------

# 12. Tipos de pruebas del programa

El programa menciona pruebas para:

-   investigaciones descriptivas de una variable;
-   investigaciones correlacionales;
-   investigaciones explicativas con diseño experimental;
-   uno o más grupos. fileciteturn1file0L32-L46

En esta clase solo introducir la clasificación.

------------------------------------------------------------------------

# 13. Correlación

La correlación estudia la relación entre variables.

Ejemplo:

-   horas de capacitación;
-   productividad.

Pregunta:

> ¿Existe relación entre ambas variables?

No afirmar causalidad solamente porque exista correlación.

------------------------------------------------------------------------

# 14. Ejemplo conceptual

Si al aumentar horas de capacitación generalmente aumenta productividad,
podríamos observar una relación positiva.

Si una variable aumenta mientras otra disminuye, podría existir relación
negativa.

Si no hay patrón, la correlación puede ser cercana a cero.

------------------------------------------------------------------------

# 15. Práctica con Excel

Crear una pequeña base:

    HorasCapacitacion   Ventas
  ------------------- --------
                    2    10000
                    3    12000
                    4    12500
                    5    15000
                    6    16000

Crear gráfico de dispersión.

Calcular correlación.

En Excel puede utilizarse la función correspondiente para correlación,
según la versión disponible.

Preguntar:

-   ¿hay relación?
-   ¿es positiva o negativa?
-   ¿qué tan fuerte parece?

------------------------------------------------------------------------

# 16. SPSS

Si está disponible:

1.  Abrir SPSS.
2.  Crear/importar la base.
3.  Revisar **Variable View**.
4.  Revisar **Data View**.
5.  Seleccionar el análisis.
6.  Ejecutar.
7.  Identificar el valor de significancia.
8.  Interpretar.

IBM ofrece recursos oficiales para aprender a cargar datos, navegar Data
View y Variable View y ejecutar análisis descriptivos.
citeturn0search0

### Importante

No enseñar botones de memoria.

Enseñar:

**¿Qué pregunta estoy intentando responder?**

Después:

**¿Qué prueba corresponde?**

------------------------------------------------------------------------

# 17. Actividad de análisis

Entregar un conjunto de datos.

Cada pareja debe escribir:

1.  pregunta de investigación;
2.  H0;
3.  H1;
4.  α;
5.  prueba;
6.  resultado;
7.  decisión;
8.  interpretación empresarial.

------------------------------------------------------------------------

# 18. Errores comunes

### Error 1

"p = 0.03 significa que H0 tiene 3% de probabilidad de ser verdadera."

No.

### Error 2

"Si p \> 0.05, demostramos que H0 es verdadera."

No.

### Error 3

"Correlación significa causalidad."

No necesariamente.

### Error 4

Elegir una prueba solamente porque el software la ofrece.

La prueba depende de la pregunta y del tipo de datos.

------------------------------------------------------------------------

# 19. Tarea

Plantear un problema de contaduría.

Debe incluir:

-   pregunta;
-   H0;
-   H1;
-   nivel de significancia;
-   datos;
-   prueba propuesta;
-   resultado;
-   interpretación.

### Lectura

Lectura introductoria sobre:

-   hipótesis nula;
-   hipótesis alternativa;
-   significancia;
-   valor p;
-   correlación.

### Evidencia

Reporte de práctica para el **portafolio** y la **lista de cotejo de
prácticas**.

------------------------------------------------------------------------

# 20. Registro docente

El indicador principal de aprendizaje es que el alumno pueda explicar:

> "¿Qué pregunta estaba tratando de responder y qué significa el
> resultado?"

antes de hablar de la fórmula.
