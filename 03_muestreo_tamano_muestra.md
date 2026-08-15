# Clase 3 --- Muestreo y tamaño de muestra

## 1. Propósito

Que el alumno comprenda por qué se utilizan muestras, identifique
técnicas de muestreo aleatorio y no aleatorio y pueda calcular un tamaño
de muestra mediante un procedimiento sencillo apoyado en Excel.

El programa contempla cálculo de tamaño de muestra, técnicas de muestreo
aleatorio y no aleatorio y su aplicación mediante software.
fileciteturn1file0L27-L31

------------------------------------------------------------------------

# 2. Distribución

  Tiempo         Actividad
  -------------- ----------------------
  0--20 min      Repaso
  20--45 min     Población y muestra
  45--75 min     Técnicas de muestreo
  75--85 min     Descanso
  85--120 min    Tamaño de muestra
  120--150 min   Excel
  150--170 min   Caso contable
  170--180 min   Cierre y tarea

------------------------------------------------------------------------

# 3. ¿Por qué utilizar una muestra?

Preguntar:

> Una empresa tiene 100,000 clientes. ¿Podemos entrevistar a todos?

A veces sí sería posible, pero puede resultar costoso o lento.

La muestra permite estudiar una parte de la población.

------------------------------------------------------------------------

# 4. Muestreo aleatorio

La selección utiliza algún mecanismo aleatorio.

## Aleatorio simple

Cada elemento tiene una posibilidad conocida de ser seleccionado.

Ejemplo:

Seleccionar 100 facturas al azar de una base de 10,000.

## Sistemático

Seleccionar elementos siguiendo un intervalo.

Ejemplo:

Cada décima factura después de establecer un punto de inicio.

## Estratificado

Dividir la población en grupos o estratos y seleccionar elementos de
cada grupo.

Ejemplo:

Clientes:

-   pequeños;
-   medianos;
-   grandes.

## Por conglomerados

Se seleccionan grupos o conglomerados.

Para este curso basta con comprender la idea general.

------------------------------------------------------------------------

# 5. Muestreo no aleatorio

La selección no se basa en un mecanismo aleatorio de la misma manera.

## Conveniencia

Se seleccionan los elementos más accesibles.

## Intencional

El investigador selecciona casos con determinadas características.

## Cuotas

Se buscan cantidades determinadas de ciertos grupos.

------------------------------------------------------------------------

# 6. Advertencia importante

Una muestra grande no necesariamente es una buena muestra.

También importa **cómo fue seleccionada**.

Ejemplo:

Preguntar solamente a clientes que entran a una sucursal puede no
representar a todos los clientes.

------------------------------------------------------------------------

# 7. Tamaño de muestra

El tamaño depende de factores como:

-   tamaño de población;
-   nivel de confianza;
-   margen de error;
-   variabilidad esperada.

Para mantener el curso sencillo utilizaremos una fórmula introductoria.

------------------------------------------------------------------------

# 8. Fórmula para población grande

`n = Z²pq / E²`

Donde:

-   `n` = tamaño de muestra;
-   `Z` = valor asociado al nivel de confianza;
-   `p` = proporción esperada;
-   `q = 1-p`;
-   `E` = margen de error.

Para 95% de confianza:

`Z ≈ 1.96`

Cuando no conocemos p:

`p = 0.5`

`q = 0.5`

------------------------------------------------------------------------

# 9. Ejemplo

Nivel de confianza: 95%

Margen de error: 5%

`p = 0.5`

`q = 0.5`

`n = (1.96² × 0.5 × 0.5)/(0.05²)`

`n ≈ 384.16`

Redondeamos hacia arriba:

**385 personas**

------------------------------------------------------------------------

# 10. Población finita

Cuando la población es conocida y relativamente pequeña, puede
utilizarse una corrección para población finita.

Una forma sencilla:

`n = N Z²pq / [E²(N-1) + Z²pq]`

Donde:

`N = tamaño de población`

No entrar en demostración.

------------------------------------------------------------------------

# 11. Ejemplo

Empresa con 2,000 clientes.

95% de confianza.

5% de margen de error.

`p = 0.5`

`q = 0.5`

Aplicar la fórmula de población finita.

Resultado aproximado:

**323 clientes**.

------------------------------------------------------------------------

# 12. Excel

Crear una hoja:

`Muestra`

Columnas:

-   Población
-   Confianza
-   Z
-   Error
-   p
-   q
-   Tamaño

Introducir los valores y construir la fórmula.

La intención es que el alumno pueda modificar:

-   población;
-   error;
-   confianza;

y observar cómo cambia el tamaño requerido.

------------------------------------------------------------------------

# 13. Interpretación

Preguntar:

> ¿Qué pasa si queremos reducir el margen de error?

Respuesta:

Se necesita una muestra mayor, manteniendo las demás condiciones.

> ¿Qué pasa si aumentamos el nivel de confianza?

Generalmente necesitamos una muestra mayor, manteniendo las demás
condiciones.

------------------------------------------------------------------------

# 14. Caso de contaduría

Una firma desea revisar el cumplimiento de ciertos procedimientos en
5,000 operaciones.

No puede revisar todas inmediatamente.

Los alumnos deben:

1.  identificar población;
2.  proponer muestra;
3.  elegir método de muestreo;
4.  justificarlo;
5.  calcular tamaño de muestra;
6.  explicar qué información recopilarían.

------------------------------------------------------------------------

# 15. Actividad colaborativa

Cada pareja recibe un escenario:

### Caso A

Auditar 10,000 facturas.

### Caso B

Analizar satisfacción de 3,000 clientes.

### Caso C

Revisar 1,500 empleados.

### Caso D

Analizar 20,000 transacciones.

Cada pareja debe presentar:

-   población;
-   unidad de análisis;
-   muestra;
-   técnica;
-   tamaño de muestra;
-   justificación.

------------------------------------------------------------------------

# 16. Tarea

Resolver tres escenarios de tamaño de muestra.

Además, seleccionar una técnica de muestreo para cada escenario y
justificarla.

### Lectura

Lectura introductoria sobre:

-   muestreo;
-   muestra;
-   población;
-   muestreo aleatorio;
-   muestreo no aleatorio.

### Evidencia

Entregar:

-   archivo Excel;
-   ejercicios;
-   justificación del método.

Se incorpora al **portafolio de ejercicios prácticos** y a la **lista de
cotejo de prácticas**.

------------------------------------------------------------------------

# 17. Registro docente

Verificar que los alumnos no confundan:

-   población con muestra;
-   tamaño de muestra con número de variables;
-   muestreo aleatorio con muestreo por conveniencia.
