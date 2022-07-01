# Sandal_Andres_NRC7318_Informe-Tarea4
                                                 Universidad de las Fuerzas Armadas - Espe
                                                   Fundamentos de circuitos electrónicos 
- Nombre: Andrés Sandal
- NRC: 7318
- Fecha de entrega:30/06/2022
- Ing. Alulema Darwin

                                                             Informe Tarea N°4
1.- Tema: Circuitos en serie-paralelo / Teoremas de circuitos y conversiones

2.- Objetivos:

  2.1.- Objetivo general:
  
Determinar y analizar las características que componen a un circuito en serie-paralelo (mixto) para poder hallar variantes o incognitas que se presenten en este tipo de circuitos por medio del uso de formulas, planteamiento de ecuaciones basadas en leyes fundamentales, tales como la de ohm y kitchhoff.    
        
  2.2.- Objetivo específicos:
  
        * Analizar el comportamiento de la corriente, resistencia y voltaje en los circuitos en serie-paralelo (mixto).
        * Explicar el funcionamiento de como un voltímetro puede llegar a cargar un circuito.
        * Determinar las características que existen en un circuito al presentarse un puente de Wheatstone.
        
3.- Marco teórico

![image](https://user-images.githubusercontent.com/105684550/176059501-9105324f-1342-45eb-bc76-bfea2d08cc14.png)

Link del mapa mental: https://gitmind.com/app/doc/85511727393 

4.- Resolución

-Circuito en serie-paralelo

2. Visualice y trace los siguientes circuitos en serie-paralelo:

(a) Una combinación en paralelo de tres ramas, cada rama con dos resistores en serie

![image](https://user-images.githubusercontent.com/105684550/176824476-2e381241-0ec3-4013-975b-2f9e1b7ab5bf.png)
 
(b) Una combinación serie de tres circuitos en paralelo, cada circuito con dos resistores
 
![image](https://user-images.githubusercontent.com/105684550/176824500-4bf419dd-4a0f-4820-80b2-4c4bf73a6d17.png)

4. En cada uno de los circuitos de la figura 7-63, identifique las relaciones en serie-paralelo de los resistores
vistas desde la fuente.
a.
 
![image](https://user-images.githubusercontent.com/105684550/176824521-0180504c-226c-4fe0-af3e-a625087658a3.png)

b.

![image](https://user-images.githubusercontent.com/105684550/176824535-97685f97-5eb6-4083-b521-a0e9cfb1e322.png)

c.

![image](https://user-images.githubusercontent.com/105684550/176824554-ba85e9a5-69d9-496f-a6bc-84ee14d96ada.png)
 
6. Desarrolle un diagrama esquemático de la tarjeta de circuito impreso de doble cara mostrada en la figura
7-65, y marque los valores de resistor.

![image](https://user-images.githubusercontent.com/105684550/176824630-9eeaa00c-eb3e-4509-92fa-9d11c1c267c8.png)

![image](https://user-images.githubusercontent.com/105684550/176824643-5d555ed8-d9df-43a4-bc0a-fcbf0566c711.png)

8. Un cierto circuito se compone de dos resistores en paralelo. La resistencia total es de 667 Ω. Uno de
los resistores son de 1.0 k Ω. ¿Cuál es el otro resistor?

RT =667 Ω

R1= 1 k Ω= 1000 Ω

RT=1/(1/R1+1/R2)

667Ω=1/(1/1000Ω+1/R2)

R2(99.9 9Ω )=0.15 Ω

R2=1.50 〖x10〗^(-3)

10. Repita el problema 9 para cada uno de los circuitos mostrados en la figura 7-63.
 
![image](https://user-images.githubusercontent.com/105684550/176824778-841e1664-bad8-4ed0-b503-be2073c9a7ef.png)

a) Re1=R1+R2=1kΩ+1kΩ=2kΩ 

Re2=R3||R4=(2.2kΩ×3.3kΩ)/(2.2kΩ+3.3kΩ)=1.32kΩ

RT=2kΩ+1.32kΩ=3.32kΩ

b) Re1=R3||R2=(6.2MΩ×3.3MΩ)/(6.2MΩ+3.3MΩ)=2.15MΩ

Re2=R1||R4=(1MΩ×1MΩ)/(1MΩ+1MΩ)=0.5MΩ

RT=Re1||Re2=(2.15MΩ×0.5MΩ)/(2.15MΩ+0.5MΩ)=0.41MΩ

c) Re1=R1+R2=1kΩ+1kΩ=2kΩ

Re2=R6||R7=(6.8kΩ×6.8kΩ)/(6.8kΩ+6.8kΩ)=3.4kΩ

Re3=R5+R8+Re2=3.3kΩ+1.8kΩ+3.4kΩ=8.5kΩ

Re4=R3||R4=(10kΩ×4.7kΩ)/(10kΩ+4.7kΩ)=3.2kΩ

RT=Re1+Re3+Re4=2kΩ+8.5kΩ+3.2kΩ=13.7kΩ

12. Determine la corriente a través de cada resistor en cada circuito de la figura 7-63; luego calcule cada caída de voltaje.

![image](https://user-images.githubusercontent.com/105684550/176824793-d790cbca-c899-4f52-9831-62276704b4b2.png)
 
a) VR3=VRE=VR

VR3=0.57mV

VR4=0.57mV

IR3=V/R=0.57/2.2

IR3=0.25mA

IR4=V/R=0.57/3.3=0.17mA

IR2=0.43mA

VR2=IR2-R2=0.43mV

VRE=IRE×RE=0.57wV

IR1=V/R=1mA

IT=Vs/RE=1.42mA

b) IR5=IRE2=IR3=0.24mA

VR5=0.24×3.3=0.79V

VR8=0.24×1.8=0.43V

VRE2=0.24×3.4=0.81V

IRE1=V/R=2.03/0.76=2.67mA

IRE3=V/R=2.03/8.5=0.24mA

14. Determine la resistencia entre A y B en la figura 7-67 sin la fuente
 
![image](https://user-images.githubusercontent.com/105684550/176824861-57a98447-732b-44cd-b781-36560cd878ee.png)

La resistencia entre A y B seria la sumatoria de las resistencias comprendidas en paralelo, la respuesta es: RT: 4.7KΩ+5.6KΩ= 10.3KΩ.

16. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-68.

![image](https://user-images.githubusercontent.com/105684550/176824895-9c83860a-2e03-47f1-aecf-bc00797f4c40.png)

![image](https://user-images.githubusercontent.com/105684550/176824902-6329c6a6-772e-4824-bb96-0a0aa98b2f99.png)

Tensiones en los nodos: nodo principal C

I_1+I_2+I_3=0

(V_C-50)/1000kΩ+V_C/2.2kΩ+V_C/1100=0

V_C (1/1000+1/2.2+1/1100)-50/1000=0

V_C (5021/11000)=V_A=(50/1000)/(5021/11000)=0.00662=33mV

18. Determine la resistencia del circuito mostrado en la figura 7-67 como se ve desde la fuente de voltaje.
 
 ![image](https://user-images.githubusercontent.com/105684550/176824945-41c3d171-fb95-41f0-8178-7b519cb583e2.png)

Las resistencias comprendidas entre A y B,  tienen una suma total de 10.3 kΩ. Mientras que la suma de resistencias comprendidas desde la fuente hasta el punto C es de 2kΩ. Las resistencias equivalentes mostradas se encuentran en paralelo con la suma de las resistencias 10 y 1.8 kΩ, dando como resultado una resistencia equivalente de 11.8kΩ. La suma en paralelo de esas tres resistencias equivalentes R= 1.46KΩ.
20. Determine el voltaje, VAB, en la figura 7-69.
 
![image](https://user-images.githubusercontent.com/105684550/176824956-461820ed-94a4-4c72-adef-d6303639c392.png)

R_E=(1/(1/1+1/1.5))=0.6kΩ

V_AB=7V+47.6V+67.2V

V_AB=167.2V
	
V_R1+V_R3+V_R4=V_S  

〖1000I〗_1+470(I_1-I_2)+560(I_1-I_2)=100

〖1000I〗_1+470I_1-470I_2+560I_1-〖560I〗_2=100

〖910I〗_1-1030I_2=100
	
V_R3+V_R4+V_R2+V_R7+V_RE+V_R8=0

〖470(I〗_2-I_1)+560(I_2-I_1)+330(I_2)+600I_2+680I_2+100I_2=0

〖-1030I〗_1+2740I_2=0

Sistemas de ecuaciones:

〖910I〗_1-1030I_2=100

〖-1030I〗_1+2740I_2=0

Se obtiene:

I_1=0.19A

I_2=0.07A

22. En la figura 7-71, determine la resistencia entre el nodo A y cada uno de los demás nodos (RAB, RAC,RAD, RAE, RAF, y RAG).

 ![image](https://user-images.githubusercontent.com/105684550/176825024-7e760f69-6449-4a9d-8c35-ac902c49e523.png)

Resistencias nodo A y C

R1+R2=3.2 kΩ

R8+R7=8 kΩ

(R1+R2)||(R8+R7)=2.29 kΩ

Resistencia en A y D

RT=3.28 kΩ

Resistencia en A y F

RT=6.98kΩ

26. La salida de una batería de 12 V se divide para obtener dos voltajes de salida. Se utilizan tres resistores de 3.3 kΩ para proporcionar dos tomas. Determine los voltajes de salida. Si se conecta una carga de 10 kΩ a la más alta de las salidas, ¿cuál será su valor con carga?


V=((R2||R3)/(R1+R3))Vs

R2||R3=(3.3 kΩ×3.3 kΩ)/(3.3 kΩ+3.3 kΩ)=1.65kΩ

V=(1.65kΩ/(3.3 kΩ+3.3 kΩ))12V

V=(0.25kΩ)12V

V=3V

28. En la figura 7-74, determine el voltaje de salida sin carga entre las terminales de salida. Con una carga de 100 kΩ conectada de A a B, ¿cuál es el voltaje de salida?
 
 ![image](https://user-images.githubusercontent.com/105684550/176825107-14b55363-2244-4eae-8941-1126416a77fb.png)

V=(R3/(R2+R3))Vs

V=((2.7 kΩ)/(5.6 kΩ+2.7 kΩ))22V

V=((2.7 kΩ)/(8.3 kΩ))22V

V=(0.325)22V

V=7.15 V

30. En la figura 7-74, determine la corriente continua extraída de la fuente sin carga entre las terminales de salida. Con una carga de 33 kΩ, ¿cuál es la corriente extraída?

![image](https://user-images.githubusercontent.com/105684550/176825158-9cd244f8-918b-4e4d-b6a6-df329aa36bf5.png)
 
RT=R1+R2+R3=10kΩ+5.6kΩ+2.7Ω=18.3 kΩ

RA=R2+R3=5.6kΩ+2.7Ω=8.3 kΩ

VA=(RA/RT)Vs=(8.3kΩ/18.3kΩ)22V=9.978 V

IA=VA/3.3kΩ=(9.978 V)/(3.3 kΩ)=3.02 µA

32. El divisor de voltaje de la figura 7-75 tiene una carga controlada por interruptor. Determine el voltaje en cada toma (V1, V2 y V3) para cada posición del interruptor.

![image](https://user-images.githubusercontent.com/105684550/176825190-fa56b77d-dd41-464b-88d2-0673d430ca6c.png)
 
V1=(R2/(R1+R2))Vs=(10kΩ/(10kΩ+10kΩ))120V=60V

V2=(R3/(R2+R3))Vs=(10kΩ/(10kΩ+10kΩ))120V=60V

V3=(R4/(R3+R4))Vs=(10kΩ/(10kΩ+10kΩ))120V=60V

34. Diseñe un divisor de voltaje que produzca una salida de 6 V sin carga y un mínimo de 5.5 V entre los extremos de una carga de 1.0 kΩ. El voltaje de fuente es de 24 V y la corriente extraída sin carga no debe exceder de 100 mA.

 ![image](https://user-images.githubusercontent.com/105684550/176825202-5a22d52a-08ff-4af6-a768-a70700b6f745.png)

36. Determine la resistencia interna de un voltímetro de 20,000 Ω/V en cada uno de los siguientes ajustes de intervalo.


(a) 0.5 V 

20000(Ω/V)=0

Ω=V/20000=0.5V/20000=25µΩ

(b) 1 V 

20000(Ω/V)=0

Ω=V/20000=1V/20000=50µΩ

(c) 5 V 

20000(Ω/V)=0

Ω=V/20000=5V/20000=250µΩ

(d) 50 V 

20000(Ω/V)=0

Ω=V/20000=50V/20000=2.5mΩ

(e) 100 V 

20000(Ω/V)=0

Ω=V/20000=100V/20000=5mΩ

(f) 1000 V

20000(Ω/V)=0

Ω=V/20000=1000V/20000=0.05Ω=50mΩ

38. Repita el problema 37 si se utiliza el voltímetro para medir voltaje entre los extremos de R4 en el circuito de la figura 7-62(b).
 
 ![image](https://user-images.githubusercontent.com/105684550/176825301-d527e7cc-e4d5-4243-930d-af11095c2ad2.png)

El multímetro se debe colocar de la siguiente manera:
 
![image](https://user-images.githubusercontent.com/105684550/176825320-bd7abc78-31b3-4285-b6ce-5eb029b0e6e8.png)

Redes en escalera

40. Determine la resistencia total y el voltaje en los nodos A, B y C de la red en escalera mostrada en la figura 7-78.
 
 ![image](https://user-images.githubusercontent.com/105684550/176825351-4dbe827f-799a-4063-937c-2315ed5d4c7a.png)

a) RB=(R4(R5+56))/(R4+(R5+R6))=(2.2kΩ(1kΩ+1kΩ))/(2.2kΩ+(1kΩ+1kΩ))=1.05kΩ

RA=(R2(R3+RB)=)/(R2+(R3+RB))=(2.2kΩ(1kΩ+1.5kΩ))/(+(1kΩ+1.5kΩ))=1.17kΩ

RT=R1+RA=5.6kΩ+1.17kΩ=6.77kΩ

b) IT=VT/RT=18V/6.66KΩ=2.7mA

I2=1.35mA

I3=1.35mA

I4=((R5+R6)/(R4+(R5+R6) ))I3=(0.625kΩ)(1.35mA)=0.84mA

I5=I6=I3-I4=1.35mA-0.84mA=0.51mA

VA=I2×R2=(2.2kΩ)(1.35mA)=2.97V

VB=I4×R4=(2.2kΩ)(0.84mA)=1.85V

VC=I6×R6=(1kΩ)(0.51mA)=0.51V

42. En la figura 7-79, ¿cuál es el voltaje entre los extremos de cada resistor con 10 V entre A y B?

![image](https://user-images.githubusercontent.com/105684550/176825567-51a41dbf-b4ff-4583-b01e-ff3843a44a6e.png)
 
Re1=(R4(R5+56+R7))/(R4+(R5+R6+R7))=(820Ω(100Ω+680Ω+100Ω))/(820Ω+(100Ω+680Ω+100Ω))=424.47Ω

Re2=(R2(R3+R8+Re1)=)/(R2+(R3+R8+Re1))=(820Ω(220Ω+220Ω+242.47Ω))/(820Ω+(220Ω+220Ω+242.47Ω))=372.47Ω

RT=R1+Re2+R9=100Ω+372.47Ω+100Ω=572.47Ω

IT=V1/R1=10V/100Ω=0.1A

VAB=IT×RT=(0.1A)(572.47Ω)=57.25V

44. Determine VSALIDA para la red R/2R en escalera mostrada en la figura 7-81 para las siguientes condiciones:

![image](https://user-images.githubusercontent.com/105684550/176825614-d480db8b-dacf-4637-b55c-77a255303e49.png)
 
RA=2R1/2+R3=24kΩ/2+12kΩ=24kΩ

RB=2RA/2+R5=24kΩ/2+12kΩ=24kΩ

RC=2RB/2+R7=24kΩ/2+12kΩ=24kΩ

R=RA=RB=RC=24kΩ

Vsalida=(2R/4R)V=V/24

Interruptor SW2 conectado a 12 V y los demás conectados a tierra

Vsalida=V/36

Interruptor SW1 conectado a 12 V y los demás conectados a tierra
  
Vsalida=V/48

46. Se conecta un resistor de valor desconocido a un circuito puente Wheatstone. Los parámetros del puente en equilibrio se establecen como sigue: RV =18 kΩ y R2/R4= 0.02. ¿Cuál es RX?

Rx=Rv(R2/R4)=(18kΩ)

48. Determine el voltaje de salida para el puente desequilibrado mostrado en la figura 7-83 a una temperatura
de 60℃

![image](https://user-images.githubusercontent.com/105684550/176825693-ad6ad241-0916-41ae-ac73-c51ac28b4eb7.png)

∆Rtermistor=27 kΩ=27.000Ω

∆Vsalida=∆Rtermistor(Vs/4R)

∆Vsalida=27.000Ω(9V/4(27.000Ω)

∆Vsalida=0.25 V   

50. ¿Son correctas las lecturas del medidor mostrado en la figura 7-85?
 
![image](https://user-images.githubusercontent.com/105684550/176825788-c8e37127-e6e6-4733-85f9-3055abf5c4d1.png)

R2+R4= 47kΩ+10kΩ=57kΩ

(R2+R4)||R5= (57*100)/(57+100)=36.30kΩ

RAG=33+36.30 =69.3 kΩ

R1+R2+ R2+R4)||R5=27+33+36.30

RT=96.3 kΩ

VAG=(RAG/RT)(Vs)=(69.3/96.3)(18)=12.95

VCG=(R2/R2+R4)(6.79)=5.60 V

VAG-VCG=12.95-5.60=7.35V

Con los cálculos obtenidos se verifica que los valores si son correctos

54. Si en la figura 7-89 R2 se abre, ¿qué voltajes se leerán en los puntos A, B y C?

 ![image](https://user-images.githubusercontent.com/105684550/176825859-9e974590-f456-458d-b0b4-b504f8e83412.png)

Si se abre la resistencia R2 el circuito quedaría de la siguiente manera
 
 ![image](https://user-images.githubusercontent.com/105684550/176825874-84812401-ca9e-40b0-9f40-cb5032e42a89.png)

Entonces el voltaje que pasa por A es de 15v y el voltaje en B y C es de 0 voltios.


- Teoremas de circuitos y conversiones 

2. Convierta las fuentes de voltaje prácticas de la figura 8-67 en fuentes de corriente equivalentes

![image](https://user-images.githubusercontent.com/105684550/176825960-237f3537-47fe-45b4-b529-eb4e33cdde88.png)

Is=Vs/Rs=(5000 V)/100Ω

![image](https://user-images.githubusercontent.com/105684550/176826006-1d6f917e-c723-4b26-8539-59aef5a49603.png)

Is=Vs/Rs=(12 V)/(2.2Ω  )  = 5.45 A

6. Convierta las fuentes de corriente prácticas de la figura 8-68 en fuentes de voltaje equivalentes

a)
![image](https://user-images.githubusercontent.com/105684550/176826044-c07d3d6d-717d-49a7-a175-b9e9e5dab18b.png)  

Vs=Is*RT= (10mA)(4.7k Ω)=47 V

b)
![image](https://user-images.githubusercontent.com/105684550/176826069-35964a59-32ef-424a-946a-10c2fd1c1338.png)  

Vs=Is*RT= (10mA)(2.7k Ω)=27 V


8. Use el teorema de superposición para determinar la corriente a través, y el voltaje entre, los extremos
de la rama R2 de la figura 8-69.

![image](https://user-images.githubusercontent.com/105684550/176826102-55ce3edd-b9a1-42f3-bca7-077752c9e821.png) 
![image](https://user-images.githubusercontent.com/105684550/176826127-137abeda-2a35-4a9a-9646-caef38221c0a.png)

R1||R2=(1)(2.2)/(1+2.2)=0.69k Ω            R3+ R1eq=0.69+1 =1.69 k Ω

R5eq=(1.69)(2.2)/(1.69+2.2)=0.96k Ω              RT= R5eq+R4     RT=0.96+1= 1.96 k Ω

IT=3/1.96=1.53 mA

I2(V1)= R1/(R1+R2) (IT)=1/(1+2.2) (1.53)=0.48mA

![image](https://user-images.githubusercontent.com/105684550/176826195-5b268618-f910-4066-87ac-7f87786caf0d.png)

IT=2/1.96=1.02 mA

I2(V2)= R3/(R2+R3) (IT)=1/(2.2+1) (1.02)=0.32 mA

I2= I2(V1)+I2(V2)

I2=0.48mA+0.32mA

I2=0.8mA

10. Con el teorema de superposición, determine la corriente de carga en cada uno de los circuitos mostrados
en la figura 8-71.

![image](https://user-images.githubusercontent.com/105684550/176826259-deec61d7-4967-4e61-b7f0-d6447634fa9c.png)
![image](https://user-images.githubusercontent.com/105684550/176826284-12825c51-0cb4-48d3-9570-17c26c1cb98c.png)

Req(2.2)=(RL.R(2.2))/(RL+R(2.2) )=(3.9)(2.2)/((3.9+2.2) )=1.41 kΩ

RT=10 k Ω+1.41k Ω

RT=11.41 k Ω

Vs=IT*RT

Vs=1A*(11,41k Ω)

Vs=11410 V

I1(RL)= 11410V/(3.9k Ω)=0.003 A
 
![image](https://user-images.githubusercontent.com/105684550/176826318-a14b987b-35af-45e3-8b36-a7a84f2d1d25.png)

I1(RL)=2A

IT(RL)=2A+0.003A

IT(RL)= 2.003A

14. Los interruptores mostrados en la figura 8-74 se cierran en secuencia, SW1 primero. Determine la corriente
a través de R4 después del cierre de cada interruptor

![image](https://user-images.githubusercontent.com/105684550/176826339-42a3aed3-6196-4fa0-9497-b04744eb1326.png)

Corriente 1: 
 
RT=R1+R4

RT=5.6+18

RT=23.6 kΩ

IRT= (12 V)/(23.6k Ω)=0.50 mA=500A 

IR4= 500A

Corriente 2:
 
![image](https://user-images.githubusercontent.com/105684550/176826386-8da56834-bad2-4392-9fbc-f891460479ed.png)

RT=R2+R4
RT=8.2+18
RT=26.2 kΩ
IRT= (6 V)/(26.2k Ω)=0.23 mA=230A 
IR4= 230ª

Corriente 3:

 ![image](https://user-images.githubusercontent.com/105684550/176826408-0b0a06b1-bbf8-458e-8bea-0ca58c4123b3.png)

RT=R3+R4
RT=12+18
RT=30 kΩ
IRT= (9 V)/(30k Ω)=0.3 mA=300A 
IR4= 300 A


16. Para cada uno de los circuitos de la figura 8-76, determine el equivalente de Thevenin como se ve desde
las terminales A y B.
a)
 
![image](https://user-images.githubusercontent.com/105684550/176826477-086ddc4f-fe47-41e8-ab34-e07141ed2d50.png)

b)
  
![image](https://user-images.githubusercontent.com/105684550/176826490-66acb306-aa02-4f32-8bbb-31c8c548431c.png)

C)
 
![image](https://user-images.githubusercontent.com/105684550/176826500-f9dab228-fd1b-49c5-880f-495c31fc8b0b.png)

20. Determine la corriente que se dirige al punto A cuando R8 es de 1.0 kΩ, 5 kΩ, y 10 kΩ en la figura 8-80.

![image](https://user-images.githubusercontent.com/105684550/176826535-975a8580-1912-43bd-9641-4158cf8eb07e.png)
![image](https://user-images.githubusercontent.com/105684550/176826548-d3c40f11-b96d-4884-8164-829e2f2a208b.png)

Calcular la resistencia total:

R_7=R_7+R_8=8.2kΩ+1.0kΩ=9.2kΩ

R_6equ=(R_7*R_6)/(R_7+R_6 )=(9.2kΩ*12kΩ)/(9.2kΩ+12kΩ)=5.2kΩ

R_5=R_6equ+R_5=5.2kΩ+1.0kΩ=6.2kΩ

(6.8kΩ*9.1kΩ)/(6.8kΩ+9.1kΩ)=3.9kΩ+10kΩ=13.9kΩ

R_1equ=(13.9kΩ*4.7kΩ)/(13.9kΩ+4.7kΩ)=3.5kΩ

R_T=(3.5kΩ*6.2kΩ)/(3.5kΩ+6.2kΩ)=2.2kΩ=2200Ω

I_T=V/R_T =48V/2200Ω=0.02A

I_X=R_T/R_X *I_T=2200Ω/1000Ω*(0.02A)=0.04A

22. Determine el equivalente de Thevenin del circuito mostrado en la figura 8-82 visto desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105684550/176826600-184c40da-5b67-413c-beb8-78a067f2c8c8.png)
![image](https://user-images.githubusercontent.com/105684550/176826606-eb6e65bf-ddf0-44e4-9318-2b0bf20f4761.png)

Eliminar Rl: 

Determinar V_TH

![image](https://user-images.githubusercontent.com/105684550/176826725-712409d6-7269-4a98-a234-cf778775162b.png)

V_TH=V_A-V_B=(R_2/(R_1+R_2 ))*V_S-(R_4/(R_3+R_4 ))*V_S

V_TH=(12000Ω/(10000Ω+12000Ω))*(10V)-(50000Ω/(15000Ω+50000Ω))*(10V)

V_TH=(0.55)*(10V)-(0.77)*(10V)=-2.2V

Determinar la R_TH
  
R_TH=R_1 |(|R_2+R_3 |)| R_4=((R_2*R_1)/(R_1+R_2 ))+(〖R_3*R〗_4/(R_3+R_4 ))=(((10KΩ*12KΩ)/(10KΩ+12KΩ))+((15KΩ*50KΩ)/(15KΩ+50KΩ))

R_TH=16.99KΩ ~16993Ω

 ![image](https://user-images.githubusercontent.com/105684550/176826781-6ff50a0f-adf3-441c-874a-4a2f622102a2.png)

24. Con el teorema de Norton, determine la corriente que circula a través del resistor de carga RL en la figura 8-77.

![image](https://user-images.githubusercontent.com/105684550/176826804-23d875c9-5be7-40b6-98d9-f9d4b25782c1.png)
![image](https://user-images.githubusercontent.com/105684550/176826814-88603604-1d9a-4d59-8a50-75e1c15b3c4e.png)

a) Determinar la resistencia total:

R_T= R_1+(R_2*R_3)/(R_2+R_3 )+(R_4*R_5)/(R_4+R_5 )

R_T= 10KΩ+(5.6KΩ*10KΩ)/(5.6KΩ+10KΩ)+(5.6KΩ*10KΩ)/(5.6KΩ+10KΩ)=10kΩ+3.59kΩ+3.59kΩ

R_T=17.18kΩ 

I_T=V_S/R_T =32V/(17.18kΩ )=1.86mA

b) Aplicar divisor de corriente para hallar I_N: 

I_N=((R_4  )/(R_4+R_5 ))*I_T=(5.6KΩ/(5.6KΩ+10KΩ))*(1.86mA)=(0.35)(1.86mA)

I_N=0.67mA
 
 ![image](https://user-images.githubusercontent.com/105684550/176826878-7984a699-4263-4786-a2f4-3cc90f30d0b7.png)
![image](https://user-images.githubusercontent.com/105684550/176826895-328c4304-7583-44ff-b7c8-2dae90878cf0.png)
![image](https://user-images.githubusercontent.com/105684550/176826901-d1bc9b22-6909-407f-a83c-e7248254da63.png)

26. Con el teorema de Norton, determine la corriente que circula a través de R1 en la figura 8-80 cuando R8 = 8 kΩ.

a) Determinar la resistencia total:

R=R_2+R_4=11.5kΩ 

R_b=R_7+R_8=16.2kΩ

R_5=R_5+R_6eq=7.89kΩ

R_6 ||R_b=(R_6*R_b)/(R_6+R_b )=R_6eq=6.89kΩ

R_3 ||R=(R*R_3)/(R+R_3 )=R_3eq=5.35kΩ

R_T=((R_5*R_3)/(R_5+R_3 ))=((7.89kΩ*5.35kΩ)/(7.89kΩ+5.35kΩ))=3.19kΩ

I_T=(V_5/R_T )=(48V/3.19kΩ)=15.05 mA

![image](https://user-images.githubusercontent.com/105684550/176827022-caaad833-103c-4055-be3a-480e66da0674.png)

b) Aplicar el divisor de corriente para hallar I_N: 

I_N=(R_5/(R_5+R_6 ))*I_T=(7.89kΩ/(7.89kΩ+5.35kΩ))*(15.05mA)=8.97mA

![image](https://user-images.githubusercontent.com/105684550/176827042-da777ca1-91a7-4512-9270-e67576b0c70f.png)

28. En la figura 8-83, reduzca el circuito entre las terminales A y B a su equivalente Norton. 
 
 ![image](https://user-images.githubusercontent.com/105684550/176827073-7b6f7934-f4a8-48f3-b279-45731df9a78d.png)

30. En cada circuito mostrado en la figura 8-85, se tiene que transferir potencia máxima a la carga RL. Determine el valor apropiado de RL en cada caso.
 
 ![image](https://user-images.githubusercontent.com/105684550/176827096-858e9f03-cb6b-4641-b76c-78a10e699cca.png)

Solución:

La Resistencia de carga para máxima transferencia de potencia es igual a:

R_L= R_S  ó R_L= R_TH   

R_L= 12Ω
 
 ![image](https://user-images.githubusercontent.com/105684550/176827132-67282839-428b-4bca-bb32-50c24284bb25.png)

R_L= R_S  ó R_L= R_TH   

R_L= 8.2Ω

 ![image](https://user-images.githubusercontent.com/105684550/176827146-af94bc68-e869-49cb-bf4f-dc3289c47eb5.png)

a) Determinar V_TH

V_TH=V_A-V_B=(R_2/(R_2+R_3 ))*V_S-(R_1/(R_1+R_3 ))*V_S

V_TH=(1Ω/(1Ω+4.7Ω))*(1V)-(2Ω/(2Ω+4.7Ω))*(1V)

V_TH=(0.18)*(1V)-(0.29)*(1V)=-1.1V

b) Determinar la R_TH
  
R_2=((R_2*R_1)/(R_1+R_2 ))=0.67Ω

R_TH=((R_2*R_3)/(R_1+R_3 ))=(((0.67Ω*4.7Ω)/(0.67Ω+4.7Ω))=0.59Ω

R_TH=0.59Ω

 ![image](https://user-images.githubusercontent.com/105684550/176827339-adbaa779-81bf-412e-afa7-0084ff028f3f.png)

34. En la figura 8-88, convierta cada red delta en una red Y.
  
  ![image](https://user-images.githubusercontent.com/105684550/176827440-f3e313b4-b4ca-490e-8120-86e2fbe26320.png)
![image](https://user-images.githubusercontent.com/105684550/176827447-6aab8ee1-6d0b-400e-8fdf-88994421d7db.png)

Solución:

R_1=(R_A*R_C)/(R_A+R_B+R_C )=(0.56MΩ*1.0MΩ)/(0.56MΩ+1.0MΩ+1.5MΩ)=0.18MΩ

R_2=(R_B*R_C)/(R_A+R_B+R_C )=(1.5MΩ*1.0MΩ)/(0.56MΩ+1.0MΩ+1.5MΩ)=0.49MΩ

R_3=(R_A*R_B)/(R_A+R_B+R_C )=(0.56MΩ*1.5MΩ)/(0.56MΩ+1.0MΩ+1.5MΩ)=0.27MΩ

![image](https://user-images.githubusercontent.com/105684550/176827483-33bd0401-72cf-4eef-960e-275f58e5c2ba.png)
![image](https://user-images.githubusercontent.com/105684550/176827500-e2b2e371-ee41-4d9c-8b1e-cdce30e52740.png)

Solución:

R_1=(R_A*R_C)/(R_A+R_B+R_C )=(1.0Ω*2.2Ω)/(1.0Ω+2.7Ω+2.2Ω)=0.37Ω

R_2=(R_B*R_C)/(R_A+R_B+R_C )=(2.7Ω*2.2Ω)/(1.0Ω+2.7Ω+2.2Ω)=1.0Ω

R_3=(R_A*R_B)/(R_A+R_B+R_C )=(1.0Ω*2.7Ω)/(1.0Ω+2.7Ω+2.2Ω)=0.46Ω
 
 ![image](https://user-images.githubusercontent.com/105684550/176827570-921e22a8-665e-4fd2-9f5e-3f0f831b857d.png)

36. Determine todas las corrientes que circulan en el circuito de la figura 8-90
Solución:

![image](https://user-images.githubusercontent.com/105684550/176827584-e2db9030-f79d-4481-9e5b-9a80e4fe8227.png)

a) Hallar la resistencia total

R_4=((R_1*R_4)/(R_1+R_4 ))=((10kΩ*12kΩ)/(10kΩ+12kΩ))=5.45kΩ

![image](https://user-images.githubusercontent.com/105684550/176827608-48dc60b6-56cc-4f61-8989-0607d3a7f3d7.png)

R_5=((R_2*R_5)/(R_2+R_5 ))=((39kΩ*9.1kΩ)/(39kΩ+9.1kΩ))=7.38kΩ

R_3=(R_3+R_5 )=22kΩ+7.38kΩ=29.38kΩ

R_T=((R_4*R_3)/(R_4+R_3 ))=((5.45kΩ*29.38kΩ)/(5.45kΩ+29.38kΩ))=4.60kΩ

I_T=(V_S/R_T )=(136V/40.60kΩ)=29.57mA

![image](https://user-images.githubusercontent.com/105684550/176827633-b19802ca-4c65-4948-9d5f-2a2d58efe03a.png)

b) Utilizar divisor de corriente:

I_A=(V_S/R_1 )=(136V/10)=13.6mA

I_B=(R_4/(R_4+R_5 ))*I_T=(12kΩ/(12kΩ+22kΩ))*(29.57mA)=10.43mA

I_C=((R_2-R_5)/(R_2+R_3+R_5 ))*I_T=((39kΩ-9.1kΩ)/(39kΩ+22kΩ+9.1kΩ))*(29.57mA)=12.61mA
 
![image](https://user-images.githubusercontent.com/105684550/176827670-df11ed48-d4dd-4117-87ed-d276d952bc4c.png)

5.- Video

https://youtu.be/8g9G9uxm0mY

6.- Conclusiones

- Se ha podido determinar que el comportamiento de corriente, voltaje y resitencia se podría decir que se combinan al estar en un circuito mixto (serie-paralelo) y se tendría que ir agrupanto por medio de un análisis para poder hallar las variables que se presenten de la manera correcta.

- Se logró observar que un múltimetro también puede llegar a cargar un circuito dependiendo el lugar y la posición en la que se la coloque, y a su vez tiene sus debidas aplicaciones para poder observarlas.

- Se pudo definir que el puente Wheatstonoe es un circuito eléctrico que se requiere para medir resistencias que se desconocen, mediante el equilibrio de los brazos del puente, este esta conformado por 4 resitencias y a su vez forman un circuito cerrado.

7.- Bibliografía

* Roberth, L. (2013, mayo 29). Circuitos en serie y en paralelo. La guía de Física. Recuperado junio 2, 2022, de https://fisica.laguia2000.com/general/circuitos-en-serie-y-en-paralelo
* Torres Ortega, H. H. (2021, agosto 19). Puente de Wheatstone - Puente Wilton Resistencias HETPRO TUTORIAL. HeTPro. Recuperado junio 27, 2022, de https://hetpro-store.com/TUTORIALES/puente-de-wheatstone/ 
