# T6_Poblaciones
- Romel Alvarado
- Grupo 1
- Sexto semestre
- Biotecnología
# Detalles de la tarea
## Creación del modulo
Se creó un módulo "poblacionmendeliana.py" con 3 funciones:
### Función 1. Creacción de la población
Se creó una función de simulación "build.population" importando datos del modulo scipy considerando como tamaño de entrada la población (N) y una variable de salida la probabilidad de tener un alelo "A" o "a"(p). Se crea un listado vación llamado "population" y para cada elemnto dentro del rango "N". Se crea dos alelos el "A" y "a", el calculo y la combinaciones se realiza si son > p.

### Función 2. Cuantificación de frecuencias de alelos
Se creó la función "compute_frecuencias" para calcular las frecuencias genotipicas utilizando el argumento de entrada los datos de población (population) que contiene combinaciones alelicas de "AA" "Aa", "aA" y "aa".

### Función 3. Creación de la población
Se creó la función "reproduce_populatión" que toma la población actual y genera la proxima generación de individuos. Se crea un listado vación llamado "new_generation" y dentro del rango N, se realiza una combinación aleatorio, creando asi los progentiores llamado "dad" "mom". Luego, secruza los cromosomas del padre y de la madre, creando asi una nueva generación.

## Ejecución del modulo
Se creó un for que ejecute el modulo para generar las 500 generaciones con la frecuencia alelica.
