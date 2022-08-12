# Ejercicios-faciles-SQL

Les comparto algunas consultas faciles para realizar si estas empezando a estudiar Análisis de datos. 

# Escenario 1-- Practiva de limpieza de datos
En este escenario, usted es un analista de datos que trabaja con una nueva empresa de concesionarios de automóviles usados. Los inversionistas quieren que averigüe qué automóviles son los más populares entre los clientes para que puedan asegurarse de almacenarlos en consecuencia.
Su nuevo conjunto de datos contiene datos históricos de ventas, incluidos detalles como las características y los precios de los automóviles. 
Puede usar estos datos para encontrar los 10 autos y modelos más populares. Pero antes de que pueda realizar su análisis, deberá asegurarse de que sus datos estén limpios. 
Si analiza datos sucios, podría terminar presentando la lista incorrecta de automóviles a los inversores. 
Eso puede hacer que pierdan dinero en su inversión en inventario de automóviles.

Descripcion de los datos 
Este conjunto de datos consta de tres tipos de entidades: 
(a) la especificación de un automóvil en términos de varias características
(b) su calificación de riesgo de seguro asignada
(c) sus pérdidas normalizadas en uso en comparación con otros automóviles.
La segunda calificación corresponde al grado en que el auto es más riesgoso de lo que indica su precio. A los automóviles se les asigna inicialmente un símbolo de factor de riesgo asociado con su precio. Luego, si es más arriesgado (o menos), se ajusta este símbolo moviéndolo hacia arriba (o hacia abajo) en la escala. Los actuarios llaman a este proceso "simbolización". Un valor de +3 indica que el auto es arriesgado, -3 que probablemente sea bastante seguro.
El tercer factor es el pago de pérdida promedio relativo por año de vehículo asegurado. Este valor está normalizado para todos los autos dentro de una clasificación de tamaño particular (pequeño de dos puertas, familiar, deportivo/especial, etc.), y representa la pérdida promedio por auto por año.

1. symboling: -3, -2, -1, 0, 1, 2, 3.
2. normalized-losses: continuous from 65 to 256.
3. make:alfa-romero, audi, bmw, chevrolet, dodge, honda,isuzu, jaguar, mazda, mercedes-benz, mercury,mitsubishi, nissan, peugot, plymouth, porsche,renault, saab, subaru, toyota, volkswagen, volvo
4. fuel-type: diesel, gas.
5. aspiration: std, turbo.
6. num-of-doors: four, two.
7. body-style: hardtop, wagon, sedan, hatchback, convertible.
8. drive-wheels: 4wd, fwd, rwd.
9. engine-location: front, rear.
10. wheel-base: continuous from 86.6 120.9.
11. length: continuous from 141.1 to 208.1.
12. width: continuous from 60.3 to 72.3.
13. height: continuous from 47.8 to 59.8.
14. curb-weight: continuous from 1488 to 4066.
15. engine-type: dohc, dohcv, l, ohc, ohcf, ohcv, rotor.
16. num-of-cylinders: eight, five, four, six, three, twelve, two.
17. engine-size: continuous from 61 to 326.
18. fuel-system: 1bbl, 2bbl, 4bbl, idi, mfi, mpfi, spdi, spfi.
19. bore: continuous from 2.54 to 3.94.
20. stroke: continuous from 2.07 to 4.17.
21. compression-ratio: continuous from 7 to 23.
22. horsepower: continuous from 48 to 288.
23. peak-rpm: continuous from 4150 to 6600.
24. city-mpg: continuous from 13 to 49.
25. highway-mpg: continuous from 16 to 54.
26. price: continuous from 5118 to 45400.


  
  
