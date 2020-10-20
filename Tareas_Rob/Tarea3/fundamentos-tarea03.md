# Fundamentos Estadísticos - Tarea 3

### Jose Roberto Pérez Chávez (000173013)

### Agosto 31 2020



---

## Tipos de estudio y PGD

Para cada uno de los siguientes estudios, ubícalos en el recuadro y contesta lo que se pide. Envíen las respuestas por correo electrónico (con título fundamentos-tarea03).

![Screen Shot 2020-08-29 at 6.12.57](/Users/rp_mbp/Library/Application Support/typora-user-images/Screen Shot 2020-08-29 at 6.12.57.png)

*Inferencia estadística de acuerdo al tipo del diseño (Ramsey and Schafer [2012](https://tereom.github.io/fundamentos/tareas.html#ref-ramsey)).*

1. En 1930 se realizó un experimento en 20,000 niños de edad escolar de Inglaterra. Los maestros fueron los responsables de asignar a los niños de manera aleatoria al grupo de tratamiento -que consistía en recibir 350 ml de leche diaria - o al grupo de control, que no recibía suplementos alimenticios. Se registraron peso y talla antes y después del experimento. El estudio descubrió que los niños que recibieron la leche ganaron más en peso en el lapso del estudio. Una investigación posterior descubrió que los niños del grupo control eran de mayor peso y talla que los del grupo control, antes de iniciar el tratamiento. ¿Qué pudo haber ocurrido? ¿Podemos utilizar los resultados del estudio para inferir causalidad?

   - **Selección de unidades ->** A pesar que el planteamiento del experimento no especifica si la selección de los 20k niños para el estudio fue aleatoria, supongo que sí lo fue debido a que el experimento no requería nada particularmente especial de los niños.

   - **Asignación de unidades a grupos ->** El planteamiento detalla que los maestros fueron los responsables de asignar a los niños al grupo de control de manera aleatorio, sin embargo, después del experimento se notó que los alumnos del grupo control eran de mayor peso y talla. Este último hallazgo sirve como evidencia para concluir que la asignación de unidades a grupos no fue realizada correctamente, por lo que no podríamos decir que fue aleatoria. Probablemente los maestros, sabiendo que los alumnos del grupo de tratamiento iban a recibir suplementos alimenticios, optaron por elegir los alumnos de menor peso y talla.

   - **Asignación de cuadrante ->** Con base en el análisis descrito arriba, posicionaría el caso particular de este estudio en el cuadrante superior-derecho.

   - **Inferencia de causalidad ->** Dado que se supone la presencia de errores en la asignación de unidades a grupos, no podríamos utilizar estos resultados para inferir causalidad. Es posible que los niños de menor talla naturalmente sean propensos a subir más de peso que los niños de menor talla. El proceso generador de los datos no es del todo claro.

     

2. Supongamos que de los registros de un conjunto de doctores se slecciona una muestra aleatoria de individuos americanos caucásicos y de americanos de ascendencia china, con el objetivo de comparar la presión arterial de las dos poblaciones. Supongamos que a los seleccionados se les pregunta si quieren participar y algunos rechazan. Se compara la distribución de presión arterial entre los que accedieron a participar. ¿En que cuadro cae este estudio? ¿Qué supuesto es necesario para permitir inferencias a las poblaciones muestreadas?

   - **Selección de unidades ->** Dado que los individuos seleccionados para el estudio provienen de una base médica, es muy probable que estos ya tengan una condición de salud anormal. Adicionalmente, hubo individuos que rechazaron participar en el estudio. Ambos eventos le añaden incertidumbre al proceso generador de los datos y nos aleja de la posibilidad de afirmar que la selección de unidades fue realizada de manera aleatoria.

   - **Asignación de unidades a grupos ->** El "tratamiento" en este caso sería la raza de la persona.

   - **Asignación de cuadrante ->** En este caso se posicionaría el estudio en el cuadrante inferior derecho.

   - **Suposición para permitir inferencias ->** Los supuestos que deberían tomarse para permitir inferencias acerca de las poblaciones son los siguientes:

     - Los individuos registrados en la base de datos de los doctores no presentaban condiciones de salud anómalas como para que el conjunto de datos tuviera un sesgo.
     - Las razones por las que ciertos individuos rechazaron participar en el estudio no tienen nada que ver con el padecimiento de presión arterial.

     

3. Un grupo de investigadores reportó que el consumo moderado de alcohol estaba asociado con un menor riesgo de demencia (Mukamal et al. (2003)). Su muestra consistía en 373 personas con demencia y 373 sin demencia. A los participantes se les preguntó cuánta cerveza, vino, o licor consumían. Se observó que aquellos que consumían de 1-6 bebidas por semana tenían una incidencia menor de demencia comparado a aquellos que se abstenían del alcohol. ¿se puede inferir causalidad?

- **Selección de unidades ->** No es claro el proceso a través del cual se generaron los datos. No se puede concluir que fue un proceso aleatorio.

- **Asignación de unidades a grupos ->** Esta asignación depende de una condición preexistente.

- **Asignación de cuadrante ->** En este caso se posicionaría el estudio en el cuadrante inferior derecho.

- **Inferencia de causalidad ->** No se podría inferir causalidad en este caso porque no están claros los protocolos que se siguieron para seleccionar a los participantes del estudio. Por ejemplo, es posible que se hayas escogido a personas con demencia que estén siguiendo un tratamiento que les prohiba el consumo de alcohol, lo cual haría parecer que las personas que no toman alcohol tienen un índice de demencia más elevado. Correlación no necesariamente significa causalidad.

  

4. Un estudio descubrió que los niños que ven más de dos horas diarias de televisión tienden a tener mayores niveles de colesterol que los que ven menos de dos horas diarias. ¿Cómo se pueden utilizar estos resultados?

- **Selección de unidades ->** No se provee información al respecto.

- **Asignación de unidades a grupos ->** Dado que el proceso solamente consistió en estudiar la situación de dos grupos distintos de niños, no hubo un ejercicio de asignación de unidades a grupos.

- **Asignación de cuadrante ->** En este caso se posicionaría el estudio en el cuadrante inferior derecho.

- **Utilización de los resultados ->** Considero que hay mucho análisis que debe hacerse para entender el proceso generador de datos (e.g. edad de los niños elegidos, distribución por sexo, criterios para seleccionar a los niños). Realmente no se puede hacer hacer mucho con los resultados del estudio sin antes conocer a detalle el proceso generador de datos.

  

5. Más gente se enferma de gripa en temporada de invierno, ¿esto prueba que las temperaturas bajas ocasionan las gripas? ¿Qué otras variables podrían estar involucradas?

- **Selección de unidades ->** No se provee información al respecto.

- **Asignación de unidades a grupos ->** Dado que el proceso solamente consistió en estudiar la situación de dos grupos distintos de niños, no hubo un ejercicio de asignación de unidades a grupos.

- **Asignación de cuadrante ->** En este caso se posicionaría el estudio en el cuadrante inferior derecho.

- **Prueba de hipótesis ->** No podríamos concluir que las temperaturas bajas ocasionan las gripas, hay muchos más factores que podrían estar influyendo en el fenómeno observado (gripas). Por ejemplo, durante temporada de invierno el horario que se adopta suele hacer que la gente se exponga menos a la luz solar, lo que limita la cantidad de vitamina B que producen. Esto podría afectar al sistema inmunológico y hacer que sean más propensos a contagiarse de gripa.

- **Otras variables que podrían estar involucradas ->** Algunas variables involucradas que podrían ser relevantes para el caso de estudio son:

  1. Patrones migratorios de las personas.
  2. Disponibilidad de fuentes de vitamina C (frutas).
  3. Cambios en los hábitos alimenticios de las personas.
  4. Cambios en las rutinas de descanso y actividades de las personas.
  5. Cambios del estado de ánimo de las personas.

  

6. ¿Cuál es la diferencia entre un experimento aleatorizado y una muestra aleatoria?

- El experimento aleatorizado no permite que se tomen muestras aleatorias, solamente que se realicen reproducciones controladas de un fenómeno, con las cuales no es posible eliminar la incertidumbre sobre el resultado que se obtendrá.

- Una muestra aleatoria es una selección al azar de un conjunto de muestras individuales con el fin de obtener una muestra representativa de las características de la población total.

  

---

### Referencias

- Ramsey, Fred, and Daniel Schafer. 2012. *The Statistical Sleuth: A Course in Methods of Data Analysis*. Cengage Learning.
- Angulo Bustíos, César (2011). «1». *Estadística*. Universidad de Piura.