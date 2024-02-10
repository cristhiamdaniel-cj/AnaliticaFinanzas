# Introducción a Python para Análisis de Datos

## Conceptos básicos de Python: 

### Variables y Tipos de Datos

**Variables**: Son contenedores para almacenar datos. Python es dinámicamente tipado, lo que significa que no necesitas declarar el tipo de variable al crearla.

**Tipos de Datos**: Los tipos de datos básicos en Python incluyen int (enteros), float (números de punto flotante), str (cadenas de texto), bool (Booleanos: True o False).

### Estructuras de Datos

**Listas** : Colecciones ordenadas y modificables. Pueden contener elementos de diferentes tipos. Ejemplo: ```[1, 2.5, 'cadena']```


**Tuplas**: Colecciones ordenadas e inmutables. Ejemplo: ```(1, 2.5, 'cadena')```


**Diccionarios**: Colecciones no ordenadas de pares clave-valor. Ejemplo: ```{'nombre': 'Juan', 'edad': 30}```

**Sets**: Colecciones no ordenadas, no indexadas y sin elementos duplicados. Ejemplo: ```{1, 2, 3, 4}```

### Bucles y Condicionales

**Bucles**: Permiten ejecutar un bloque de código varias veces. Python tiene principalmente dos tipos de bucles: ```for``` y ```while```.

**Condicionales**: Permiten ejecutar bloques de código dependiendo de una o más condiciones. Usan palabras clave como ```if```, ```elif```, y ```else```.

## Funciones en Python

* Definición de Funciones: Se utiliza ```def``` para definir una función. Las funciones pueden tener argumentos y pueden retornar valores.
* Argumentos: Son los valores pasados a una función. Pueden ser argumentos posicionales o argumentos con palabras clave.
* Retorno de Valores: Se utiliza ```return``` para devolver valores desde la función al llamador.

## Ejercicio 1: Calculadora de Interés Compuesto

Supongamos que queremos calcular el interés compuesto para las inversiones de nuestros clientes en el banco. El interés compuesto se calcula con la fórmula $A = P(1 + \frac{r}{n})^{nt}$, donde:
- \(P\) es el principal (monto de inversión inicial),
- \(r\) es la tasa de interés anual,
- \(n\) es el número de veces que el interés se compone por año,
- \(t\) es el número de años,
- \(A\) es el monto al final del período de inversión.

https://replit.com/@camposjulca/AnaliticaFinanciera#interesCompuesto.py

## Ejercicio 2: Categorización de Clientes por Saldo

Vamos a categorizar a los clientes del banco en función de su saldo en cuenta, para ofrecerles productos financieros adecuados.

https://replit.com/@camposjulca/AnaliticaFinanciera#categorizacionCliente.py

# Librerías Esenciales

## NumPy: Operaciones con Arrays y Matrices

NumPy es una librería fundamental para la computación científica en Python. Proporciona un objeto de matriz multidimensional de alto rendimiento y herramientas para trabajar con estas matrices.

**Ejemplo: Calcular el retorno logarítmico de una serie de precios de acciones.**

https://replit.com/@camposjulca/AnaliticaFinanciera#retornoLog.py

## Pandas: Manipulación de DataFrames

Pandas es una librería que proporciona estructuras de datos y herramientas de manipulación de datos diseñadas para hacer el análisis de datos rápido y fácil en Python.

**Ejemplo: Cargar datos financieros y calcular la media móvil de 3 días de un precio de acciones.**

https://replit.com/@camposjulca/AnaliticaFinanciera#mediaMovil.py

## Matplotlib y Seaborn: Visualización de Datos

Matplotlib es una librería de trazado para la creación de gráficos estáticos, animados e interactivos en Python. Seaborn es una librería de visualización de datos basada en matplotlib que proporciona una interfaz de alto nivel para dibujar gráficos estadísticos atractivos.

**Ejemplo: Visualizar los precios de acciones y su media móvil de 3 días.**

https://replit.com/@camposjulca/AnaliticaFinanciera#visualizacionData.py

# Manipulación y Tratamiento de Datos Financieros

# Ejercicios Prácticos y Casos de Uso