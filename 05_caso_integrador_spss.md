# Clase 5 --- Caso integrador de estadística aplicada a Contaduría

## 1. Propósito

Integrar las competencias desarrolladas durante las cuatro clases
anteriores:

-   organización de datos;
-   estadística descriptiva;
-   tablas;
-   gráficas;
-   muestreo;
-   tamaño de muestra;
-   pruebas de hipótesis;
-   interpretación.

El programa establece como producto final el **análisis y resolución de
casos implementando software estadístico, presentado mediante reporte de
caso**. fileciteturn1file0L56-L64

------------------------------------------------------------------------

# 2. Distribución

  Tiempo         Actividad
  -------------- -----------------------------
  0--15 min      Explicación del caso
  15--35 min     Identificación del problema
  35--65 min     Organización de datos
  65--75 min     Descanso
  75--105 min    Estadística descriptiva
  105--130 min   Gráficas e interpretación
  130--155 min   Prueba estadística
  155--170 min   Elaboración del reporte
  170--180 min   Presentación breve y cierre

------------------------------------------------------------------------

# 3. Caso propuesto

## Análisis de ventas de una empresa

Una empresa desea conocer el comportamiento de las ventas de sus
clientes y determinar si existe relación entre determinadas variables.

La base puede contener:

-   IDCliente;
-   Edad;
-   Sucursal;
-   FormaPago;
-   ImporteCompra;
-   NumeroProductos;
-   DiasCredito;
-   Satisfaccion.

Preparar entre 30 y 50 registros ficticios para la práctica.

------------------------------------------------------------------------

# 4. Pregunta principal

> ¿Qué características presentan las ventas de la muestra y qué
> información puede utilizar la empresa para tomar decisiones?

Preguntas secundarias:

1.  ¿Cuál es la venta promedio?
2.  ¿Cuál es la mediana?
3.  ¿Cuál es la dispersión?
4.  ¿Qué forma de pago es más frecuente?
5.  ¿Qué sucursal presenta mayor venta promedio?
6.  ¿Existe relación entre número de productos e importe?
7.  ¿Qué conclusión puede obtenerse?

------------------------------------------------------------------------

# 5. Paso 1 --- Identificar elementos

Los alumnos deben escribir:

**Población:** clientes de la empresa.

**Muestra:** clientes incluidos en la base.

**Unidad de análisis:** cliente o transacción, dependiendo de cómo se
haya construido la base.

**Variables:** edad, sucursal, forma de pago, importe, productos,
crédito, satisfacción.

------------------------------------------------------------------------

# 6. Paso 2 --- Preparar datos

En Excel:

1.  revisar encabezados;
2.  eliminar filas vacías;
3.  revisar valores faltantes;
4.  revisar formatos;
5.  detectar valores evidentemente incorrectos;
6.  guardar versión limpia.

Nombre:

`caso_estadistico_limpio.xlsx`

------------------------------------------------------------------------

# 7. Paso 3 --- Estadística descriptiva

Calcular:

-   número de observaciones;
-   media;
-   mediana;
-   moda cuando tenga sentido;
-   mínimo;
-   máximo;
-   rango;
-   desviación estándar.

------------------------------------------------------------------------

# 8. Paso 4 --- Tablas

Crear:

### Tabla 1

Forma de pago.

### Tabla 2

Sucursal.

### Tabla 3

Intervalos de importe.

Cada tabla debe incluir frecuencias y porcentajes cuando sea pertinente.

------------------------------------------------------------------------

# 9. Paso 5 --- Gráficas

Crear:

1.  gráfica de barras de forma de pago;
2.  gráfica de ventas por sucursal;
3.  histograma de importe;
4.  gráfico de dispersión para dos variables cuantitativas.

No utilizar gráficas solamente para decorar.

Cada gráfica debe responder una pregunta.

------------------------------------------------------------------------

# 10. Paso 6 --- Correlación

Analizar, por ejemplo:

`NumeroProductos` y `ImporteCompra`.

Preguntar:

> ¿Existe una relación entre cantidad de productos e importe?

Calcular correlación y explicar:

-   dirección;
-   fuerza;
-   significancia si se dispone de ella.

Recordar:

**correlación no implica causalidad.**

------------------------------------------------------------------------

# 11. Paso 7 --- Prueba de hipótesis

Proponer una hipótesis sencilla.

Ejemplo:

> El importe promedio de compra es de \$2,000.

`H0: μ = 2,000`

`H1: μ ≠ 2,000`

Nivel:

`α = 0.05`

Realizar la prueba que corresponda al conjunto de datos disponible.

------------------------------------------------------------------------

# 12. Excel como herramienta principal

El alumno debe poder completar el caso sin SPSS.

Esto es importante porque SPSS es software comercial. IBM ofrece una
prueba de 14 días y licencias académicas, pero no debemos suponer que
todos los estudiantes tendrán acceso permanente.
citeturn0search0turn0search6

Por ello:

**Excel = herramienta principal del curso.**

**SPSS = herramienta complementaria.**

------------------------------------------------------------------------

# 13. SPSS opcional

Si el profesor consigue acceso:

1.  importar el archivo de Excel;
2.  revisar Variable View;
3.  revisar Data View;
4.  ejecutar descriptivos;
5.  crear gráficas;
6.  ejecutar correlación;
7.  realizar la prueba de hipótesis;
8.  comparar los resultados con Excel.

### Objetivo

Que el alumno observe que diferentes herramientas pueden producir el
mismo resultado estadístico si se utilizan correctamente.

------------------------------------------------------------------------

# 14. Estructura del reporte de caso

El reporte final debe contener:

## 1. Portada

-   nombre de institución;
-   asignatura;
-   alumno/equipo;
-   profesor;
-   fecha.

## 2. Introducción

Explicar brevemente el problema.

## 3. Objetivo

Indicar qué se desea conocer.

## 4. Datos

Describir la población, muestra y variables.

## 5. Metodología

Explicar cómo se analizaron los datos.

## 6. Estadística descriptiva

Presentar tablas y medidas.

## 7. Gráficas

Incluir solamente las relevantes.

## 8. Prueba de hipótesis

Presentar:

-   H0;
-   H1;
-   α;
-   prueba;
-   resultado;
-   p-valor;
-   decisión.

## 9. Interpretación

Explicar qué significa para el negocio.

## 10. Conclusiones

Presentar las principales conclusiones.

------------------------------------------------------------------------

# 15. Rúbrica sugerida para la práctica final

  Criterio                                  Puntos
  -------------------------------------- ---------
  Identificación correcta del problema          10
  Organización de datos                         15
  Estadística descriptiva                       20
  Tablas y gráficas                             15
  Selección y aplicación de prueba              15
  Interpretación                                15
  Presentación del reporte                      10
  **Total**                                **100**

Esta rúbrica puede utilizarse como apoyo a la **bitácora de caso** y a
la lista de cotejo, respetando los porcentajes oficiales de evaluación.

------------------------------------------------------------------------

# 16. Bitácora de caso

Cada alumno deberá registrar:

### Antes

¿Qué queremos conocer?

### Durante

¿Qué datos utilizamos?

¿Qué dificultades encontramos?

¿Qué análisis realizamos?

### Después

¿Qué encontramos?

¿Qué significa?

¿Qué decisión podría tomar la empresa?

------------------------------------------------------------------------

# 17. Evaluación oficial

El programa establece:

  Evidencia                                  Peso
  ------------------------------------ ----------
  Examen                                      20%
  Lista de cotejo de prácticas                20%
  Portafolio de ejercicios prácticos          30%
  Bitácora de caso                            30%
  **Total**                              **100%**

fileciteturn1file0L65-L70

### Propuesta de uso

**Examen 20%**

Conceptos y ejercicios básicos.

**Lista de cotejo 20%**

Verificar que las prácticas se realizaron correctamente.

**Portafolio 30%**

Reunir ejercicios y prácticas de las clases.

**Bitácora de caso 30%**

Evaluar el proyecto final.

------------------------------------------------------------------------

# 18. Tarea final

Terminar el reporte de caso.

Entregar:

-   Excel;
-   reporte;
-   gráficas;
-   análisis;
-   conclusiones;
-   bitácora.

------------------------------------------------------------------------

# 19. Clase 6 --- Sesión de reserva

No asignar contenido nuevo obligatorio.

Utilizarla según las necesidades del grupo para:

-   examen;
-   presentación de casos;
-   revisión de proyectos;
-   recuperación;
-   reforzamiento de pruebas de hipótesis;
-   práctica adicional de Excel;
-   práctica de SPSS si existe acceso;
-   aclaración de dudas.

------------------------------------------------------------------------

# 20. Recomendación docente final

La asignatura debe mantenerse alrededor de esta pregunta:

> **"¿Qué puedo aprender de estos datos para tomar una mejor
> decisión?"**

La fórmula y el software son herramientas.

El objetivo es que el alumno pueda:

**Pregunta → Datos → Organización → Análisis → Resultado →
Interpretación → Decisión.**

No permitir que la clase se convierta en un curso de botones de Excel o
SPSS.

El alumno debe comprender qué está haciendo antes de ejecutar una
función.
