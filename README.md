# Laboratorio-1
1. OBJETIVOS
- Objetivo General:

    - Experimentar y analizar las leyes de Kirchhoff mediante su aplicación en simuladores, con el fin de ampliar los conocimientos tanto prácticos como teóricos.

- Objetivos Específicos:

    - Demostrar en la práctica que las leyes de Kirchhoff de Voltajes son cumplidas.
    - Demostrar en la práctica que las leyes de Kirchhoff de Corrientes son cumplidas.
    - Mediante la medición y el cálculo de los voltajes y las corrientes del circuito, observar y analizar las diferencias y los errores.

2. MARCO TEÓRICO

![image](https://github.com/Matthew-Benitez/Laboratorio-1/blob/main/2020-12-18%20(6).png?raw=true)
![image](https://github.com/Matthew-Benitez/Laboratorio-1/blob/main/2020-12-18%20(8).png?raw=true)

3. DIAGRAMAS

- Modelo del circuito

![image](https://github.com/Matthew-Benitez/Laboratorio-1/blob/main/Diagramas/20201221_213206.jpg)

*Figura 1.1*

- Circuito

![image](https://user-images.githubusercontent.com/75439689/102837560-074eed80-43ca-11eb-89eb-7a74e9d81bd6.png)

*Figura 1.2*

- Circuito y Voltímetros

![image](https://user-images.githubusercontent.com/75439689/102837593-19c92700-43ca-11eb-93ac-4d4344f0b5b0.png)

*Figura 1.3*

- Circuito y Amperímetros

![image](https://user-images.githubusercontent.com/75439689/102837613-277eac80-43ca-11eb-908e-8be461993555.png)

*Figura 1.4*

4. LISTA DE COMPONENTES

![image](https://user-images.githubusercontent.com/75439689/102837452-d1116e00-43c9-11eb-9b84-074ea2931773.png)

*Tabla 1.1*

5. EXPLICACIÓN

   5.1. Procedimiento

     - Ingresar a la plataforma *Tinkercad* y crear un nuevo circuito, en el cual se escogen los componentes listados anteriormente.
     - Se conecta el suministro de energía de 10 voltios a la placa de pruebas (*protoboard*) uniendo respectivamente los polos positivos y negativos del suministro y la placa.
     - A continuación se conecta un extremo de la resistencia *R1* al polo positivo de la placa que se encuentra a su vez conectada al polo positivo de la fuente de voltaje.
     - Posteriormente se une el otro extremo de la resistencia *R1* a un extremo de la resistencia *R2* y a otro extremo de *R3*, generándose así un nodo.
     - El otro extremo de *R3* se conecta a un extremo de la resistencia *R4*.
     - Posteriormente se conectan los otros extremos de *R2* y *R4* a un extremo de *R5*, obteniéndose así otro nodo.
     - Por último, se une el otro extremo de *R5* al polo negativo del suministro de energía, cerrándose el circuito por completo y obteniéndose así un circuito con dos mallas y dos nodos.
     
    5.2. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.
    
      Una vez realizado el circuito, se procede a realizar las respectivas mediciones, tanto de voltaje como de intensidad de corriente para cada uno de los cinco resistores, obteniéndose así los valores medidos para la elaboración de la tabla; y a la vez, se procede a realizar los cálculos, aplicando la Ley de Ohm y las Leyes de Kirchhoff, para obtener dichos valores de cada resistencia mediante operaciones matemáticas.
      
    ![image](https://github.com/Matthew-Benitez/Laboratorio-1/blob/main/Tablas/2020-12-21%20(2).png)
    
    *Tabla 2.1*  
      
   5.3. Verificación de la Ley de Kirchhoff de Voltaje
   
      A continuación se tabulan los voltajes de cada resistencia y se analizan por mallas, es decir, por trayectorias de cada circuito cerrado y se procede a sumar dichos valores por cada malla, verificando si se cumple la Ley de Kirchhoff de Voltajes.
      
      ![image](https://github.com/Matthew-Benitez/Laboratorio-1/blob/main/Tablas/2020-12-21%20(1).png)
      
      *Tabla 2.2*
      
   5.4. Verificación de la Ley de Kirchhoff de Corrientes
   
      Una vez realizado la tabulación de corrientes de cada resistencia, se procede a analizar los nodos, puntos de uniones entre componentes, donde se verifica que la intensidad de entrada antes del nodo, es equivalente a la intensidad de salida de dicho nodo. Y con los cálculos se verifica que estas se anulan, cumpliendo así la Ley de Corrientes de Kirchhoff.
      
    ![image](https://user-images.githubusercontent.com/75439689/102837059-07022280-43c9-11eb-8c49-d843c51a51fa.png)
    
    *Tabla 2.3*
    
    5.5. Comparación de Resultados Medidos y Calculados
    
      Mediante el cálculo de voltaje, corriente y resistencias se pudo deducir que el simulador de Tinkercad puede sacar estos datos de una forma mas rápida pero con menos precisión, ya que falla como se puede observar en las tablas que hay una diferencia de entre 0.007 entre los cálculos y las mediciones. Por otra parte, en los cálculos de los errores se puede observar que los datos calculados son más precisos que los medidos ya que cuentan con un error porcentual de menos 0.1%, mientras que los medidos son mayores a estos. Se concluye que en efecto los valores que son extraídos mediante fórmulas son precisos pero ideales, lo que en la realidad solo pueden ser usados como modelos.
      
      - Porcentajes de error de la *tabla 2.2*
      
      ![image](https://github.com/Matthew-Benitez/Laboratorio-1/blob/main/2020-12-21%20(3).png)
      
      - Porcentajes de error de la *tabla 2.3*
      
      ![image](https://user-images.githubusercontent.com/75439689/102842026-0f138f80-43d4-11eb-8a83-17c3b79970e4.png)
      
6. CONCLUSIONES

La práctica de laboratorio nos ofreció conocimiento acerca de las Leyes de Kirchhoff, de las cuales fueron expuestas las Leyes de Voltaje de Kirchhoff donde: en la simulación fueron comprobados que la sumatoria de voltajes de un circuito cerrado es igual al voltaje de fuente; demostrado en la tabla 2 donde además de distinguir 3 trayectorias, en todas estas se comprobaban las LVK. Además las Leyes de Corriente de Kirchhoff fueron corroboradas en la tabla 3, indicando como en cada nodo las corrientes de salidas eran iguales a las corrientes de entrada; fue indicado así en 3 nodos. También se analizaron los datos medidos y calculados, cada uno de ellos, en el cálculo de corrientes, resaltan con un error menor al 1%, sin embargo, los datos calculados demuestran un error menor al 0.1%, esto implica que a pesar de tener un simulador que muestra información, no emite datos tan precisos.
Para concluir, el laboratorio fue un claro ejercicio y práctica, tanto analítica como simulada, para practicar y comprobar las leyes de Kirchhoff que son esenciales para los circuitos básicos y que serán muy utilizados en el futuro para circuitos más avanzados.

7. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).
