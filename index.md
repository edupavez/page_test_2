# "Brecha Educativa en Chile: Un Análisis de las Diferencias Geográficas y Socioeconómicas en la Calidad de la Educación"

Hemos hecho un análisis sobre algunos factores que pueden afectar el proceso de admisión a la educación superior en Chile,
específicamente en el periodo de admisión 2023, mirando la relación entre ingresos familiares per capita de los estudiantes,
el índice de desarrollo comunal de las comunas donde viven y estudian, y los resultados individuales  y de los mejores 100 colegios
en la PAES.

Para mayores detalles visite nuestro repositorio en Github: [repositorio](https://github.com/crist0balsoto/Proyecto_Ciencia_de_datos)

## Objetivos

Nuestro objetivos es responder a las siguientes preguntas:
1. ¿Cómo la brecha socioeconómica afecta a la educación en Chile?
2. ¿Hay una fuerte correlación entre índice de desarrollo comunal y puntaje PAES?
3. En base a lo anterior, ¿qué outliers podemos encontrar? ¿Cambia según la región?
4. ¿Influye la proximidad a la Región metropolitana?
5. ¿Qué otros factores pueden afectar el proceso de admisión?

## Resultados

Hemos hecho uso principalmente de resultados que disponibiliza el DEMRE sobre el proceso 2023, del índice de desarrollo comunal de la Universidad autónoma, y del ranking de los 100 mejores colegios por rendimiento en la PAES.

Podemos ver los siguientes gráficos que obtuvimos de la data, que muestran la relación entre los mejores colegios y su IDC:

![output.png](output.png)

Y luego tenemos la relación entre decil económico y los distintos aspectos que afectan el ingreso a la educación superior: NEM, Promedio PAES de matemática y lenguaje, y promedio de todas las pruebas rendidas.

![output2.png](output2.png)

De esto observamos que los ingresos familiares per capita son un importante predictor del rendimiento de los alumnos en la PAES, e incluso observamos que entre los alumnos en hogares del decil con mayores ingreso (y en menor menor medida del segundo decil de mayores ingresos) también se genera una ventaja relevante en cuanto a las notas que determinan el NEM.

Luego podemos observar este mapa de calor que grafica la correlación entre el rendimiento de los alumnos en la PAES y los distintos componentes del IDC:

![output3](output3.png)

Haciendo uso del coeficiente de determinación ($corr^2$)

