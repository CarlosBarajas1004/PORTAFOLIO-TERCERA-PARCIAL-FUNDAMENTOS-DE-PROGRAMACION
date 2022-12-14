# Barajas Cortes Carlos Alejandro, Facultad de Ingeniería Mecánica y Eléctrica, ICI 1°B
## Problemas resueltos en clase con diagramas de flujo de datos
### Ejercicio 1. USANDO 2 VECTORES CAPTURE EDAD Y SEMESTRE DE N ESTUDIANTES
#### Analisis: Se necesita un proceso en el que almacenemos un array de 100 para despues preguntar el numero de estudiantes e introducir el numero, para despues introducir un numero, y asi tener una condicion, para posteriormente empezar con un ciclo For y poder calcular la edad y que este dentro de el rango, y asi hacer lo mismo con el semestre para despues tener la impresiones de ambas cosas y dar fin.
[![DIAGRAMA-1.jpg](https://i.postimg.cc/YCVW6fTL/DIAGRAMA-1.jpg)](https://postimg.cc/0zYjxmk9)
#### Prueba de escritorio
corrida|valor i|VE|VS|i=n?|
|-|-|-|-|-|
|1|0|VE[0]=16|VS[0]=3|no|
|2|1|VE[1]=17|VS[1]=5|no|
|3|2|VE[2]=18|VS[2]=7|no|
|4|3|VE[3]=17|VS[3]=5|Si, impr VE y VS|

|Edad|Semestre|
|-|-|
|16|3|
|17|5|
|18|7|
|17|5|
### Ejercicio 2. USANDO MATRICES CAPTURE EDAD Y SEMESTRE DE N ESTUDUANTES
#### Analisis: rellenar una matriz y pedir el numero de el estudiante para que te lo introduzca que debe de estar dentro de el rango para despues tener un ciclo For y preguntar por la edad, y si la edad esta dentro de el rango se continua y si no se da un error despues tener un proceso M[i,0]= edad, para despues preguntar por el semestre y si esta dentro de el rango avanza para despues imprimir la matriz y dar fin.
#### Diagrama de flujo
[![DIAGRAMA-2.jpg](https://i.postimg.cc/d0SX48bf/DIAGRAMA-2.jpg)](https://postimg.cc/t1W2gVCd)
|corrida|valor i|valor j|matriz|i=n?|
|-|-|-|-|-|
|1|0|0|M[0,0]=16|no|
|2|1|0|M[1,0]=17|no|
|3|2|0|M[2,0]=17|no|
|4|3|0|M[3,0]=16|Si, entonces sig contador|

|corrida|valor i|valor j|matriz|i=n?|
|-|-|-|-|-|
|1|0|0|M[0,1]=3|no|
|2|1|0|M[1,1]=5|no|
|3|2|0|M[2,1]=5|no|
|4|3|0|M[3,1]=3|Si, entonces impr [M]|

|Edad|Semestre|
|-|-|
|16|3|
|17|5|
|17|5|
|16|3|

### Ejercicio 3. RELLENAR UNA MATRIZ CUADRADA (NxN) CON UN NUMERO LEIDO DEL TECLADO
#### Analisis: se necesita una matriz de 50,50 para despues que ingresen el tamaño de la matriz y si es mayor a 2 y menor que 50 pasa y si no marcara fuera de rango despues decir que nos den el numero leido de el teclado y que nos den el numero y si es mayor que 0 y menor que 50 pasa y si no fuera de rango para despues tener 2 ciclos For uno que sea i=0;i<n;i++ y el otro j=0;j<n;j++ para despues tener un proceso que la matriz este dentro de i y j y asi el final.
#### Diagrama de flujo
[![DIAGRAMA-3.jpg](https://i.postimg.cc/LXLTLL2L/DIAGRAMA-3.jpg)](https://postimg.cc/xJjMSkk1)
#### Prueba de escritorio
|i|j|Matriz|núm|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|5|no|
|0|1|M[0,1]|7|no|
|0|2|M[0,2]|8|si, entonces J+1 y vuelve a empezar|

|5|7|8|
|-|-|-|
|5|7|8|
|5|7|8|

### Ejercicio 4. RELLENAR UNA MATRIZ NxN CON NUMEROS CONSECUTIVOS
#### Analisis: se necesita una matriz de 50,50 para despues preguntar el tamaño de la matriz y si es mayor a 1 y menor o igual a 50 pasa si no fuera de rango para despues tener dos ciclos For i=0;i<n;i++ y el otro j=0;j<n;j++ y asi tener en la matriz que M[i,j] = C y despues tener que C = C+1 y que entre en un ciclo y haga lo mismo en el otro y asi dar la matriz con numeros.
#### Diagrama de flujo
[![DIAGRAMA-4.jpg](https://i.postimg.cc/d0MZdX1N/DIAGRAMA-4.jpg)](https://postimg.cc/0zfN1V77)
#### Prueba de escritorio
|i|j|Matriz|C|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|0|no|
|0|1|M[0,1]|0|no|
|0|2|M[0,2]|0|si, entonces vuelve a empezar|

|1|2|3|
|-|-|-|
|4|5|6|
|7|8|9|

### Ejercicio 5. RELLENAR UNA MATRIZ DE NxN PERo QUE REPITA TODO EL RENGLON EL MISMO NUMERO
#### Analisis: se necesita una matriz de [100,100] para despues pedir el numero de la matriz si es mayor que 1 y menor que 99 pasa si no da fuera de rango para despues tener dos ciclos For i=0;i<n;i++ y el otro j=0;j<n;j++ y despues un proceso que sea M[i,j]=j+1 y despues que pase por los dos ciclos y dar fin.
#### Diagrama de flujo
[![DIAGRAMA-5.jpg](https://i.postimg.cc/nLkVzwQD/DIAGRAMA-5.jpg)](https://postimg.cc/R3WxpddS)
#### Prueba de escritorio
|i|j|Matriz|C|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|1|no|
|0|1|M[0,1]|1|no|
|0|2|M[0,2]|1|si, entonces C+1 y vuelve a empezar|

|1|1|1|
|-|-|-|
|2|2|2|
|3|3|3|

### Ejercicio 6. GENERAR UNA MATRIZ QUE MUESTRE LO SIGUIENTE...
|1|0|0|0|
|-|-|-|-|
|0|2|0|0|
|0|0|3|0|
|0|0|0|4|
#### Analisis: se necesita una matriz de 100, 100 para despues pedir el tamaño de la matriz si la matriz es mayor que 1 y menor o igual que 100 entonces pasa y si no entonces se regresa, para despues tener dos ciclos For i=0;i<n;i++ y el otro j=0;j<n;j++ y despues decir que si j = i si es si entonces un proceso que diga que M[i,j] = i+1 y si es no M[i,j] =0 y pasan por los ciclos dando fin al diagrama
#### Diagrama de flujo
[![DIAGRAMA-6.jpg](https://i.postimg.cc/vBTym8sJ/DIAGRAMA-6.jpg)](https://postimg.cc/DW9HjTm6)
#### Prueba de escritorio
|corridas|i|j|M|j=m?|
|-|-|-|-|-|
|1|0|1|M[0,0]=0|no|
|2|0|2|M[0,0]=0|no|
|3|0|3|M[0,0]=0|no|
|4|0|4|0|0|M[0,0]=0|si, entonces i+1 yj=0|

|0|0|0|0|
|-|-|-|-|
|0|0|0|0|
|0|0|0|0|
|0|0|0|0|

|Corridas|i|M|
|-|-|-|
|1|0|M[i,i=i+1|
|2|1|M[i,i=i+1|
|3|2|M[i,i=i+1|
|4|3|M[i,i=i+1|

|1|0|0|0|
|-|-|-|-|
|0|2|0|0|
|0|0|3|0|
|0|0|0|4|

### Ejercicio 7. CONVERTIR LA SIGUIENTE MATRIZ EN UN VECTOR
|1|4|9|                      
|-|-|-|                     
|16|25|36|               
|49|64|81| 
#### Diagrama de flujo
[![diagrama7.jpg](https://i.postimg.cc/prD5sJ6Y/diagrama7.jpg)](https://postimg.cc/q6v7Ry0z)
#### Prueba de escritorio
|corridas|Matriz|Vector|j+1|
|-|-|-|-|
|1|M 0,0|M 0,0=V 0|j+1|
|2|M 0,1|M 0,1=V 1|j+1|
|3|M 0,2|M 0,2=V 2|j+1|

|1|2|3|
|-|-|-|
|4|5|6|
|7|8|9|

|1|
|-|
|2|
|3|
|4|
|5|
|6|
|7|
|8|
|9|

### Ejercicio 8. EL 1B QUIERE CONOCER EL PROMEDIO POR PERSONA Y POR MATERIA, ADEMAS DE LA MATERIA CON MEJOR PROMEDIO GRUPAL Y AL ALUMNO CON MEJOR PROMEDIO, SON 7 MATERIAS
Y 32 ALUMNOS, MENCIONE LOS ALUMNOS EN RIESGO (CON ALMENOS 1 MATERIA REPROBADA)
#### Analisis: 
             alumnos
             
             
            |1|2|3|4|5|6|7|
            |-|-|-|-|-|-|-|
            | | | | | | | |
          
#### Diagrama de flujo
[![DIAGRAMA-10.jpg](https://i.postimg.cc/DynS2sNH/DIAGRAMA-10.jpg)](https://postimg.cc/w34q2tgQ)
#### Prueba de escritorio
 
|corridas|i|j|M|j+1|
|-|-|-|-|-|
|1|0|0|M 0,0=Materia|j+1|
|2|0|1|M 0,1=Materia|j+1|
|3|0|2|M 0,2=Materia|j+1|
|4|0|3|M 0,3=Materia|j+1|

|Quimica|Matemáticas|Etica|Lengua materna|
|-|-|-|-|
|5|4|3|9|
|8|6|4|7|
|9|7|7|6|
|7|9|8|7|

### Ejercicio 9. PREGUNTE LAS DIMENSIONES DE UNA MATRIZ EL RANGO ES [5,5], VALIDA QUE SEA CUADRADA Y OBTENGA LA SUMA DE LA DIAGONAL PREINCIPAL Y LA INVERSA. DETERMINE CUAL ES MAYOR, PREGUNTE LOS VALORES PARA LLENAR LA MATRIZ
#### Diagrama de flujo
[![DIAGRAMA-9.jpg](https://i.postimg.cc/zXsPbzns/DIAGRAMA-9.jpg)](https://postimg.cc/crccPNkh)
#### Prueba de escritorio
 |corridas|j|M|j+1|
|-|-|-|-|
|1|0|M j,j+sig|j+1|
|2|1|M j,j+sig|j+1|
|3|2|Mj,j+sig|j+1|

|corridas|j|M|j-1|
|-|-|-|-|
|1|0|Mj,j+sig|j-1|
|2|1|M j,j+sig|j-1|
|3|2|M j,j+sig|j-1|

### Ejercicio 10. ALMACENAR EN UN ARRAY LA SUMATORIA DE LOS NUMEROS DEL 1 HASTA N EN CADA POSICION DEL ARRAY, EJEMPLO SI N:3 (2,1) EL ARRAY DEBERA SER 1,3,6
#### Analisis: 
|1|
|-|
|3|
|6|
#### Diagrama de flujo
[![DIAGRAMA-8.jpg](https://i.postimg.cc/vmQhfcDN/DIAGRAMA-8.jpg)](https://postimg.cc/xX4LSjvv)
#### Prueba de escritorio
|i|vector|i=V?|
|-|-|-|
|1|0|V[i]=V[i-1]+i+1|
|2|1|V[i]=V[i-1]+i+1|
|3|2|V[i]=V[i-1]+i+1|

|1|
|-|
|3|
|6|

### Ejercicio 11. DADA UNA MATRIZ DE NxM ALMACENAR EN UN VECTOR LAS MAYORES
#### Diagrama de flujo
[![DIAGRAMA-11.jpg](https://i.postimg.cc/SxQVznnt/DIAGRAMA-11.jpg)](https://postimg.cc/vcj5JHLW)
#### Prueba de escritorio
|i|j|M|Suma|
|-|-|-|-|
|0|0|M [i,j]>mayor?-->si, M[i,j]=V [c] y C=c+1|j+1|
|0|1|M [i,j]>mayor?-->si, M[i,j]=V [c] y C=c+1|j+1|
|0|2|M [i,j]>mayor?-->si, M[i,j]=V [c] y C=c+1|j+1|
|0|3|M [i,j]>mayor?-->si, M[i,j]=V [c] y C=c+1|j+1|











































































































