# LABORATORIO-5
## 1.Objetivos:
### Objetivo general
- Desarrollar el circuito propuesto a través de la aplicación del Teorema de Thevenin para la simplificación de circuitos extensos usando los conocimientos que se proponen en el libro dado por el docente.
### Objetivos específicos
- Reconocer la equivalencia de un circuito con respecto a una carga y sus valores con respecto a los componentes que conforman Thevenin.
## 2.Marco teórico

![image](https://user-images.githubusercontent.com/105740772/178020237-78f5d504-bb19-44e8-93c1-17189dc09ae8.png)

![image](https://user-images.githubusercontent.com/105740772/178022827-64d57d37-5565-42bd-a583-6337e1853a28.png)

## 3.Explicación del procedimiento
### Material y equipo
		
![image](https://user-images.githubusercontent.com/105740772/178024127-990ec30e-3535-491a-a390-e3e11e1751d5.png)

### Procedimiento
Se procede a recrear el circuito mostrado en el esquema siguiente en un simulador

![image](https://user-images.githubusercontent.com/105740772/178019138-c4bddc32-c665-46e8-b7fa-e01ed2668497.png)

### Circuito armado en el simulador de tinkercad

![image](https://user-images.githubusercontent.com/105740772/178020554-81545b93-c6df-4e15-910d-14b53c389a0e.png)

### Esquema obtenido del simulador de tinkercad

![image](https://user-images.githubusercontent.com/105740772/178020399-e7d20307-db37-4de0-adbb-8f6ccfd0a7cb.png)

### Mediciones de voltaje y corriente
Medición del voltaje y la corriente en el resistor R5.

![image](https://user-images.githubusercontent.com/105740772/178020521-d52be2ad-0a42-4fee-82b3-4d2831ef4021.png)

Desconectar el resistor R5 y medir el voltaje en el circuito abierto.

![image](https://user-images.githubusercontent.com/105740772/178020780-0f9ebd16-a5ca-41fa-b8d8-82d0bb014072.png)

Anular el efecto de las fuentes de alimentación, desconectar R5 y desde el circuito abierto resultante medir la resistencia equivalente.

![image](https://user-images.githubusercontent.com/105740772/178021365-55c4518a-db84-4416-8801-3cc35c07d9e2.png)

Implementar el circuito equivalente de Thévenin, agregar el resistor R5 y medir la corriente y el voltaje en el mismo.

![image](https://user-images.githubusercontent.com/105740772/178021865-f516e272-d0d6-4942-9d7c-30e93d5b29ff.png)

## 4.Respuesta a interrogantes
### Resultados obtenidos
Tabla de los valores del circuito equivalente de Thévenin.

![image](https://user-images.githubusercontent.com/105740772/178048284-58fabc56-62b9-4644-8f6c-0c0badddc5c5.png)

Tabla de la comprobación del teorema de Thévenin.


### Resolución de cálculos

![image](https://user-images.githubusercontent.com/105740772/178038041-d6ede5d6-6a64-4863-80fd-85a72bf2b36f.png)

![image](https://user-images.githubusercontent.com/105740772/178047758-c5e182b4-538a-4e0e-a2c7-e69b98d32fe4.png)

![image](https://user-images.githubusercontent.com/105740772/178047775-de553b2a-5127-40c8-8be1-8b01f27c645e.png)

### Comparación de mediciones
- Al realizar los cálculos pertinentes y compararlos con los resultados obtenidos en el simulador, se puede notar que hay una pequeña diferencia, analizando esto, se puede decir que, esta diferencia aparece ya que al realizar los cálculos se utilizan todos las cifras, mientras que, el simuldaor tiende a redorndear las cifras, motivo por el cual hay pequeñas diferencias. 

## 5.Video


## 6.Conclusiones
- Thevenin es un método de simplificación que consiste en poder reemplazar toda lo que no forma parte de esta con respecto a una fuente de voltaje y resistencia en serie pero los valores de estas igualan las cantidades de amperaje o corriente sin afectar al circuito como tal.
## 7.Bibliografía

Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.

Xnomid. (7 de Noviembre de 2019). Teorema. Obtenido de https://www.teorema.top/teorema-de-thevenin/
