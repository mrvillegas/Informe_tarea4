# Informe_tarea4
Resolucion del libro de pricipios de circuitos electricos de Floyd

**Capitulos**: Tarea capitulo 7 y 8

**NRC**: 7322

**Profesor**: Darwin Omar Alulema Flores

**Objetivos:** 

**Marco teorico:** 

Capitulo 7:

Circuitos en serie - paralelo :

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/Circuitos%20en%20serie%20-%20paralelo%20-%20P%C3%A1gina%201.png)

DIVISORES DE VOLTAJE CON CARGAS RESISTIVAS:

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/Circuitos%20en%20serie%20-%20paralelo%20-%20P%C3%A1gina%202%20(1).png)

REDES EN ESCALERA:

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/Circuitos%20en%20serie%20-%20paralelo%20-%20P%C3%A1gina%203%20(1).png)

EL PUENTE WHEATSTONE:

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/Circuitos%20en%20serie%20-%20paralelo%20-%20P%C3%A1gina%204%20(1).png)

Capitulo 8:

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/Circuitos%20en%20serie%20-%20paralelo%20-%20P%C3%A1gina%205.png)

 **Resolucion capitulo 7:**
 
     2. Visualice y trace los siguientes circuitos en serie-paralelo: 
     
(a) Una combinación serie de tres circuitos en paralelo, cada circuito con dos resistores
 
((R7+R8) IIR9) +((R4+R1) IIR6) +((R2+R5) IIR3)
 
![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/1.PNG)
 
(b) Una combinación en paralelo de tres ramas, cada rama con dos resistores en serie 
 
-   R5+R6, R7+R8, está en serie y R9+R10 + (R3IIR4) están en serie

-   R3 Y R4 están en paralelo

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/2.PNG)

    4. En cada uno de los circuitos de la figura 7-63, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente.
    
![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/3.PNG)

A) (R1IIR3) +R2+R4

B) (R2IIR3) +(R1IIR4)

C) R1+R2II(R3IIR4) +R5+(R6IIR7)

    *6. Desarrolle un diagrama esquemático de la tarjeta de circuito impreso de doble cara mostrada en la figura 7-65, y marque los valores de resistor

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/4.PNG)

R1=27M, R2=33M, R3=47M, R4= 22M, R5= 68M, R6= 56M, R7= 1M, R8= 1.2M, R9= 2.2M , R10= 3.9M , R11= 27M, R12= 9.1M, R13= 4.7M

    8. Un cierto circuito se compone de dos resistores en paralelo. La resistencia total es de 667 . Uno de los resistores es de 1.0 k. ¿Cuál es el otro resistor?

1/667= 1/1000+1/R2

1/R2= -1/1000+1/667

R2= 667000/333=2.003K

    10. Repita el problema 9 para cada uno de los circuitos mostrados en la figura 7-63

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/5.PNG)

A) (R1IIR3) +R2+R4

1kII(1k+2.2kII3.3k)= 699

B) (R2IIR3) +(R1IIR4)

RT=1/(1/1M+1/1M+1/3.3M+1/6.2M)=406K

C) R1+R2II(R3IIR4) +R5+(R6IIR7)

Ra=R1+R2+R3(R4)R3+R4=1K+1K+10K(4.7K)10K+4.7K=5.2K

Ra=R5+R8+R6R7R6+R7=3.3K+1.8K+6.8K2=8.5K

RT=11Ra+1Rb=115.2k+18.5k=3.23K

    12. Determine la corriente a través de cada resistor en cada circuito de la figura 7-63; luego calcule cada caída de voltaje.

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/6.PNG)

It=1V/699=1.43mA

I1=(2.32/K699)1.43mA=1mA

V1=(1mA)(1K)=1V

I2=(1k/3.32k)*1.43mA=4.31μA

V2=431μA*1K=431mV

I3=3.3K/5.5K*431=259A

V3=259μA*2.2K=570mV

V4=570mV

I4=570mV3.3K=173μA

V1 = V2 = V3 = V4 = 2V
I1=2V1M=2A

I2=2V3.3M=606nA

I3=2V6.2M=323nA

I4=2V1M=2A

It=5V3.23k=1.55mA

I5=5.2K13.7K1.55mA=588μA

V5=(588A)(3.3K)=1.94V

I6=I7=I52=5882=294μA

V6=V7=294μA*6.8K=2V

I8=I5=588μA

V8=588μA*1.8K=1.06V

I1=I2=8.5K13.7K*1.55mA=962μA

V1=V2=962μA(1K)=962mV

I3=4.7K14.7K962A=308μA

V3=V4=(308μA)(10K)=3.08V

I4=10K14.7K962A=654μA

    14. Determine la resistencia entre A y B en la figura 7-67 sin la fuente.
    
![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/7.PNG)

RAB= (10 K +5.6 K)II4.7 K = 15.6KII4.7 K= 3.61 K

En donde el 1.8 K y los 1 K se encuentran en cortocircuito.

    16. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-68.
    
![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/8.PNG)

Va=(56 K/716 k)50v=3.91v

Vb=(616 K/716 k)50v=43.0v

Vc=50v

Vd=(100K/1.1 M)50v=4.55v

    18. Determine la resistencia del circuito mostrado en la figura 7-67 como se ve desde la fuente de voltaje.
 
![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/9.PNG)

Rt=(10K//(4.7 K+5.6K))+(1.8K//(1K+1K))

Rt=10K//10.3K+1.8K//2K

Rt=5.07 K + 947 K= 6.02 K

    20. Determine el voltaje, VAB, en la figura 7-69.

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/10.PNG)

Resistencia de la lado derecha:

Rd=R2+R5//R6+R7+R8=330 +600+680+100=1710

Resistencia del lado izquierdo:

Rz=R3+R4=470+560=1030

Resistencia total:

Rtotal=R1+Rz//Rd=1 K +643=1.64 K

Itotal=(100V/1.64 K)=60.9 mA

Corriente del lado derecho:

Id=(Rz/Rz+Rd)Itotal=(1030/2740)60.9 mA=22.9 mA

Corriente del lado izquierdo:

Iz=(Rd/Rd+Rz)Itotal=(1710/2740)60.9 mA=38.0 mA

    * 22. En la figura 7-71, determine la resistencia entre el nodo A y cada uno de los demás nodos (RAB, RAC,RAD, RAE, RAF, y RAG).

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/11.PNG)

RAB=R1//(R2+R7+R8)= 1K//(2.2K+3.3K+4.7K)=1K//10.2K=911

RAG=R8//(R1+R2+R7)= 4.7K//(1K+2.2K+3.3K)=4.7K//6.5K=2.73K

RAC=(R1+R2)//(R7+R8)= (1K+2.2K)//(3.3K+4.7K)=3.2K//8K=2.29K

RAD=RAC+R3//(R4+R5+R6)= 2.29K+1K//10.2K=3.2 K

RAE=RAC+(R3+R4)//(R5+R6)=2.29K+3.2K//8K=4.58K

RAF=RAC+R6//(R3+R4+R5)= 2.29K+4.7K//6.5K=5.02 K

    * 24. Determine el valor de cada resistor mostrado en la figura 7-73.

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/12.PNG)

V2=V5-V6=5V-1V=4V

I2=I6=2/4V==0.5A

I5=I8-I6=1A-0.5A=0.5A

I1=I2+I5+I4=0.5A+0.5A+1A=2A

I3=IT-I1=40V-20V=20V

V1=20/2A=10V

V4=V3-V1=10V

V8=V4-V5=5V

R1=(10V/2A)=5

R2=(4V/0.5A)=8

R3=(20V/2A)=10

R4=(10V/1A)=10

R5=(5V/0.5A)=10

R6=(1V/0.5A)=2

R7=(20V/4A)=5

R8=(5V/1A)=5

    26. La salida de una batería de 12 V se divide para obtener dos voltajes de salida. Se utilizan tres resistores de 3.3 k para proporcionar dos tomas. Determine los voltajes de salida. Si se conecta una carga de 10k a la más alta de las salidas, ¿cuál será su valor con carga?

VA=(6.6K/9.9K)12V=8V

VB=(3.3K/9.9K)12V=4V

RAB=(6.6Kx10K)/(6.6K+10K)=3.98K

VA=(3.98K/7.28K)12V=6.56 V

    28. En la figura 7-74, determine el voltaje de salida sin carga entre las terminales de salida. Con una carga de 100 k conectada de A a B, ¿cuál es el voltaje de salida?

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/13.PNG)

RT=10K+5.6K+2.7K=18.3K

VAF=(R2+R3/R1+R2+R3)VS=(8.3K/18.3K)22V=9.98V

Con 100k:

Rt=R1+((R2+R3)RL/(R2+R3+RL))=10K+((8.3K)100K/108.3K)=17.7K

VOU=(7.7K/17.7K)22V=9.57 V

    30. En la figura 7-74, determine la corriente continua extraída de la fuente sin carga entre las terminales de salida. Con una carga de 33 k, ¿cuál es la corriente extraída?
    
![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/13.PNG)

RT=10K+5.6K+2.7K=18.3K

I=(22 V/18.3K)=1.2 mA

RT=10K+[(8.3K x 33K)/8.3K + 33K]=16.6K

I=(22 V/16.6 K)=1.33 mA

    32. El divisor de voltaje de la figura 7-75 tiene una carga controlada por interruptor. Determine el voltaje en cada toma (V1, V2 y V3) para cada posición del interruptor.

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/14.PNG)

Parte 1:

RT=10K+30K//68K =10K+20.82K=30.8K

V1=(20.8K/30.8K)120V=81 V

V2=(20K/30K)81 V=54 V

V3=(10K/30K)81 V=27 V

Parte 2:

RT=20K+20K//68K =20K+15.5K=35.5K

V1=(10K+15.5k/35.5K)120V=86.2 V

V2=(15.5K/35.5K)81 V=52.4 V

V3=(10K/20K)52.4 V=26.2 V

Parte 3:

RT=30K+10K//68K =30K+8.72K=38.7K

V1=(20K+8.72k/38.7K)120V=89 V

V2=(10K+8.72k/38.7K)120V=58 V

V3=(8.72K/38.7K)81 V=27 V

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/15.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/16.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/17.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/18.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/19.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/20.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/21.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/22.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/23.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/24.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/25.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/26.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/27.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/28.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/29.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/30.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/31.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/32.jpg)

![1](https://github.com/mrvillegas/Informe_tarea4/blob/main/33.jpg)

 **Video:**

https://www.youtube.com/watch?v=JFbY4-Rvbfc

 **Conclusiones:**
 
-  La resolucion de los ejercicios propuestos tanto del capitulo 3 como tambien del capitulo 7 como 8 ayudo en la nuevas formas de resolver un circuito, y poder encontrar sus resistencia,corrientes y voltajes dependiendo de su complejidad.

- Se logro la comprencion del comportamiento de la corriente como tambien del voltaje que existe en un circuito con diferentes fuentes de voltaje.

  **Bibliografia:**
  
  Thomas L. Floyd(2007). Principios de circuitos eléctricos. Octava edición
