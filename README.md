- Utilizar archivo choco.csv que se encuentra en la carpeta data

- renombrar columnas: company, name-origin, ref, review, cacao, location, rating, bean, bean-origin

- en una nueva columna con el nombre pur asignar los siguientes valores segun el % de cacao

    - si es menor que 60: BAJO

    - si es mayor o igual a 60 y menor a 80: INTERMEDIO

    - si es es mayor o igual a 80: ALTO

    - si es igual a 100: PURO

- crear una columna con el nombre res que este compuesta por:

    - company&pur&rating&location


hacer un decorador con el nombre indicado que devuelva un diccionario para cada una de las siguientes consultas

/puro

chocolate con 100% de cacao


/top10

top 10 en rating de chocolates

/full

lista completa con todos los chocolates


/ref

chocolates con el valor de ref menor al promedio 
