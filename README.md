# Desempeño-Academico-para-la-Prediccion-y-Mitigacion-de-la-Desercion-en-Estudiantes-Nuevos (En Proceso)

La deserción estudiantil en la educación superior es un fenómeno complejo que puede estar influenciado por factores cognitivos, individuales y socioeconómicos. En Colombia, aunque se han logrado avances en la tasa de matrícula universitaria, las altas tasas de deserción, especialmente en los primeros semestres, siguen siendo un desafío significativo.

En este proyecto, se desarrolla un modelo predictivo basado en estadística bayesiana para identificar a los estudiantes en riesgo de abandonar sus estudios durante los primeros semestres en la Universidad Externado de Colombia. Para ello, se utiliza una base de datos que incluye información académica, socioeconómica y demográfica de los estudiantes, con el fin de analizar las variables que más influyen en la deserción.

El objetivo es no solo clasificar a los estudiantes según su nivel de riesgo, sino también identificar las causas subyacentes que afectan su permanencia en el sistema educativo. Esto permitirá implementar estrategias preventivas más efectivas y contribuir al desarrollo académico y social del país.

Diccionario de Datos
1. ID Anónimo: ID anonimizado del estudiante. (Meta-dato)
2. Semestre Ubi: Semestre que cursa el estudiante. (Numérica, Rango: [1 - 5])
3. Sexo: Sexo del estudiante. (Categórica: M/F/N)
4. Edad: Edad del estudiante. (Numérica, Rango: [16 - 28])
5. Naturaleza Colegio: Tipo de colegio de procedencia. (Categórica: Privado/Público)
6. Discapacidad: Indica si el estudiante tiene una discapacidad. (Categórica: Sí/No)
7. Servicio Salud: Indica si el estudiante cuenta con servicio de salud. (Categórica: Sí/No)
8. Tipo Vivienda: Tipo de vivienda del estudiante. (Categórica: Propia/Arrendada/Prefiere no responder)
9. Estrato Vivienda: Estrato socioeconómico de la vivienda. (Numérica, Rango: [1 - 6])
10. Adultos Responsables: Adultos responsables en el hogar del estudiante. (Categórica)
11. Num Personas Hogar: Número de personas en el hogar. (Numérica, Rango: [1 - 7])
12. Aporte Monetario Madre: Indica si la madre aporta monetariamente. (Categórica: Sí/No)
13. Aporte Monetario Padre: Indica si el padre aporta monetariamente. (Categórica: Sí/No)
14. Educación Madre: Nivel educativo de la madre. (Categórica)
15. Educación Padre: Nivel educativo del padre. (Categórica)
16. Libros Leídos: Número de libros leídos en el año anterior. (Numérica, Rango: [0, 50])
17. Mudar Bogotá: Indica si el estudiante debe mudarse a Bogotá. (Categórica: Sí/No)
18. Tiempo Transporte U: Tiempo de transporte a la universidad en minutos. (Numérica, Rango: [30 - 150])
19. Num Transportes U: Número de transportes usados para llegar a la universidad. (Numérica, Rango: [0 - 3])
20. Pago Carrera: Método de pago de la matrícula. (Categórica)
21. Inconveniente Pago: Probabilidad de inconvenientes para pagar la matrícula. (Categórica)
22. Cantidad Refuerzo Áreas: Número de áreas donde el estudiante necesita refuerzo. (Numérica, Rango: [2 - 6])
23. Cantidad Deporte Interés: Número de deportes de interés. (Numérica, Rango: [1 - 4])
24. Cantidad Cultura Interés: Número de actividades culturales de interés. (Numérica, Rango: [1 - 4])
25. Tiempo Sin Estudios: Semestres sin estudiar antes de ingresar a la universidad. (Numérica, Rango: [0 - 36])
26. Puntaje ICFES: Puntaje en la prueba ICFES saber 11. (Numérica, Rango: [69 - 415])
27. Promedio: Promedio acumulado del estudiante. (Numérica, Rango: [0 - 4.89])

Este proyecto es una iniciativa del Grupo Los Caballos del Departamento de Matemáticas, Semestre 4, Año 2024.
