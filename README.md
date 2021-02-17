# Laboratorio-5
* Objetivos

  1.- Objetivo General
    - Estudiar el teorema de Thévenin en circuitos mixtos apoyandose de los simuladores para comprobar que se cumple el teorema con los resultados analíticos.

  1.1.- Objetivos Específicos
    - Identificar la resistencia de Thévenin con la ayuda del amperímetro y voltímetro en los simuladores.
    - Analizar el circuito y su comportamiento al momento de hacer hacer cero las fuentes de voltaje y calcular la resistencia equivalente.
    - Comparar los datos en el simulador con resultados calculados y realizar el cálculo del error.
   
  2.- Marco Teórico
  
  3.- Diagramas
  
    - Circuito General
    
    ![image](https://user-images.githubusercontent.com/76132461/108272461-3d95b880-7140-11eb-821f-1f64a39c6265.png)
    
    - Voltaje y corriente en R5
    
    ![image](https://user-images.githubusercontent.com/76132461/108272845-c4e32c00-7140-11eb-8401-173306480925.png)
    
    - Voltaje cuando la R5 se desconecta
    
    ![image](https://user-images.githubusercontent.com/76132461/108272869-cf052a80-7140-11eb-8c60-f3b38919e988.png)
    
    - R5 desconectada y dos fuentes de voltaje en 0, para medir la resistencia
    
    ![image](https://user-images.githubusercontent.com/76132461/108272898-daf0ec80-7140-11eb-8cfa-014eacfdcbed.png)
    
    - Implementación del circuito Thevenin

    ![image](https://user-images.githubusercontent.com/76132461/108272931-e512eb00-7140-11eb-907e-bdb11437ad38.png)


     4.- Lista de componentes

    ![image](https://user-images.githubusercontent.com/76132461/108274276-a7af5d00-7142-11eb-915c-c5b806a57f94.png)
    
    5.- Explicación
    
    5.1.- Procedimiento
    
    1. Se ingresa a la plataforma Tinkercad, se crea una cuenta, a continuación en el apartado de circuitos seleccionar nuevo circuito.
    
    2. Se seleccionan los materiales que vamos a utilizar, una placa de pruebas, 5 resistencias, multimetros digitales y dos fuente de voltaje.
     
    3. En la primera fuente de voltaje, se la configura con 12 V, mientras que la segunda fuente de voltaje tendrá un valor de 2 V.
     
    4. Se procede a configurar cada resistencia con el valor ya establecido en el circuito.
    
    5. De la fuente positiva de 12 V se conecta hacia hacia un extremo de la resistencia de 560 ohms.
    
    6. Del extremo de la resistencia 1, se conecta hacia la resistencia de 4.7 kohms, del otro extremo de esta resistencia se la conecta hacia el negativo de la fuente
     
    7. Se conecta la fuente de voltaje de 2 V, el lado negativo se conecta hacia el nodo de R1 y R2, el lado positivo irá conectado hacia un extremo de la resistencia de 330 ohms.
    
    8. Del otro extremo de la resistencia de 330 ohms, se conectará hacia R2.
    
    9. La resistencia de 100 ohms, va conectada en el nodo formado por la fuente de voltaje de 2 voltios y por la R3.

   10. Finalmente la resistencia de 1 kohm, se conecta hacia la resistencia 4 y el otro extremo hacia la R3.
   
   11. Se mide el voltaje y la corriente en R5

   12. Se desconecta el resistor 5 y con el voltímetro en paralelo se mide el voltaje, que es 5.06 V.

   13. Las 2 fuentes de voltaje se hacen 0 y con el multímetro en paralelo se mide resistencia que nos da un valor de 299 ohms.

   14. Con esos valores, se procede a hacer el circuito equivalente de Thevenin, con la resistencia de 299 ohms, el voltaje de 5 V y la resistencia de 1 kohm.














