
Iram Jimenez Machine Learning pandas, NC 0079
Iram Jimenez Machine Learning pandas, NC 0079
Iram Jimenez Machine Learning pandas, NC 0079

--- 1. DataFrame Convertido ---
      Exposicion  Obras  Meses
0   Arte Moderno    120      3
1     Fotografía     80      2
2      Escultura     60      2
3        Pintura    100      4
4        Digital     50      1
5  Contemporánea     90      3

--- 2.1 Primeras Filas (head) ---
     Exposicion  Obras  Meses
0  Arte Moderno    120      3
1    Fotografía     80      2

--- 2.2 Últimas Filas (tail) ---
      Exposicion  Obras  Meses
4        Digital     50      1
5  Contemporánea     90      3

--- 2.3 Dimensiones (Filas, Columnas) ---
(6, 3)

--- 2.4 Tipos de Datos por Columna ---
Exposicion      str
Obras         int64
Meses         int64
dtype: object

--- 2.5 Información General (info) ---
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column      Non-Null Count  Dtype
---  ------      --------------  -----
 0   Exposicion  6 non-null      str
 1   Obras       6 non-null      int64
 2   Meses       6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes


--- 3. Estadísticas Generales de la Columna 'Meses' ---
count    6.000000
mean     2.500000
std      1.048809
min      1.000000
25%      2.000000
50%      2.500000
75%      3.000000
max      4.000000
Name: Meses, dtype: float64

--- 4. Ordenar Ascendente por Meses ---
      Exposicion  Obras  Meses
4        Digital     50      1
1     Fotografía     80      2
2      Escultura     60      2
0   Arte Moderno    120      3
5  Contemporánea     90      3
3        Pintura    100      4

--- 5. Ordenar Descendente por Obras ---
      Exposicion  Obras  Meses
0   Arte Moderno    120      3
3        Pintura    100      4
5  Contemporánea     90      3
1     Fotografía     80      2
2      Escultura     60      2
4        Digital     50      1

[ÉXITO] Archivo generado correctamente en: c:\IA_Gpo3H\ML_0079\resultados-0079\resultados-ml-0079.md
Iram Jimenez Machine Learning pandas, NC 0079