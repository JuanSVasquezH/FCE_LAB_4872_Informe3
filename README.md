# FCE_LAB_4872_Informe3
"Teorema de Superposición" 

                                                      UNIVERSIDAD DE LAS FUERZAS ARMADAS-ESPE

                                                   DEPARTAMENTO DE ELÉCTRICA Y ELECTRÓNICA

                                             CARRERA DE INGENIERÍA ELECTRÓNICA Y AUTOMATIZACIÓN

                                    PERIODO        	                :       Noviembre 2020 – Abril 2021

                                    ASIGNATURA     	                :       Fundamentos de Circuitos Eléctricos 

                                    TEMA	                        : 	Informe de laboratorios
 
                                    NOMBRES       	          	:        Juan Sebastián Vásquez Hurtado 
				                                                 Freddy Stalin Cárdenas Carrera 

                                    NIVEL-PARALELO                  :       Segundo

                                    DOCENTE       	 	        :       Ing. Darwin Alulema MSc.

                                    FECHA DE ENTREGA                :       19/01/2021

                                    NRC 				:	4872
 
                                                             SANGOLQUI - ECUADOR

                                                                       2020
								       
								       
1.	Tema: Teorema de Superposición 

2.	Objetivos

	1.1 Objetivo General

	●	Mostrar el funcionamiento del teorema de superposición mediante la representación de un circuito y poder comprobar así que se cumple en cada caso específico.

	
	1.2 Objetivos Específicos

	●	Examinar detalladamente mediante el uso de simuladores que se cumpla el teorema de superposición, y poder compararlas con los valores obtenidos mediante la elaboración de los cálculos una vez ya establecidos.

	
	●	Justificar cada dato obtenido con la simulación y cálculos en el presente circuito y calcular el error y obtener una conclusión del porque existen esas variaciones y entenderlas de mejor manera.
	
	
	●	Considerar que elementos están presentes en cada circuito ya que no todos se comportan de la misma manera ya sea con fuentes de voltaje o fuentes de corriente.
	
	
3.	Marco Teórico 

      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/Mt1.png)


4.	Diagramas 
 
      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/D1.png) 
      

●	El circuito a implementar está establecido para poner en práctica el teorema de superposición, es decir el efecto de dos fuentes o más en un circuito tienen impedancia del mismo valor, a la suma de cada efecto de las fuentes por separado, y sustituirá las fuentes tensión (Voltaje), por corto circuito y las fuentes de corriente en un circuito abierto. 


5.	Lista De Componentes 

      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/LC.png)

  5.1 	Explicación
	 
     	●	Para le elaboración del análisis de mallas debemos tomar en cuenta el número de mallas presentes en el circuito, luego veremos el sentido de las corrientes el cual se va a tomar, esto es importante ya que este nos dará el signo en el valor final de cada corriente en las diferentes mallas que analizamos.

     	●	EL número de corrientes que se hallara es igual al número de mallas que se tenga en el circuito, en este caso analizamos 3 mallas por ende existe 3 corrientes una circulando en cada malla.

     	●	 Cabe mencionar que para el análisis es importante identificar que elemento en el circuito está compartiendo dos o más corrientes, ya que estas se restaran para poder realizar una correcta formulación de las ecuaciones.

     	●	 Ya identificado los resistores R4 y R5 que son los que comparten corrientes tanto de I2 e I1 para el resistor R4 y I2 e I3 para R5, procedemos a armar las ecuaciones. Si se tiene una fuente de voltaje solo se copia el valor que se encuentre, siempre respetando el orden de los signos ya que si no lo hacemos nos dará un valor erróneo y a su vez inservible para el análisis futuro que se realizara con la simulación del Simulador a implementar “MULTISIM”.	 

6.       Procedimiento.
      
      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/1.png)


Paso 1.	Abrimos el simular Liveware y creamos un nuevo proyecto 
      
![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/2.png)


Paso 2.	Colocamos las resistencias y las fuentes de voltaje que vamos a utilizar 


      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/3.png)      

Paso 3.	Armamos el circuito de acuerdo con el diagrama establecido y asignamos los valores correspondientes a cada resistencia y fuente de voltaje además colocamos lo voltímetro en la resistencia R3 y el amperímetro en Ix nodo 2. 
    
![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/4.png)


Paso 4.	Quitamos la fuente número 2 y observamos las mediciones y anotamos. 
      

![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/5.png)


Paso 5.	Quitamos la fuente número 1 y observamos las mediciones y anotamos. 
      
![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe3/blob/main/ImagenesInforme3/6.png)


      Paso 6. Asignamos el sentido de la corriente para sus respectivos cálculos y evitar fallas en 	las mediciones y comparaciones. 


7.       Descripción De Prerrequisitos Y Configuración.

En primer lugar, se advierte que cuando se considera una fuente independiente, las demás se fijan en cero. Entonces, una fuente independiente de voltaje aparece como un corto circuito con voltaje cero a través suyo. De igual forma, si una fuente independiente de corriente se fija en cero, no fluye corriente alguna y aparece como circuito abierto .Además, es importante destacar que, si existe una fuente dependiente, debe mantenerse activa (inalterada) durante el proceso de superposición.
Recordemos que este método solo es válido solo para circuitos lineales, aquél constituido por elementos lineales y fuentes independientes.

8.       Tabulación de Datos.

9.       Calculos.

10.      Aportaciones. 

•	Para la medición de corriente, se recomienda efectuar la medición del voltaje e impedancia en los bornes requeridos, luego por la segunda ley de Kirchhoff determinar el valor de la intensidad.


11.      Conclusiones. 

•	Tras finalizar la práctica de manera correcta podemos observar la gran utilidad del teorema de superposición ya que este nos facilita a gran escala los cálculos matemáticos de un circuito, los hace menos complejos permitiéndonos ahorrar gran cantidad de tiempo, este teorema es básico debido a que nos será una herramienta bastante útil a lo largo del semestre.

•	Como se puede apreciar la diferencia entre los cálculos matemáticos, los datos obtenidos de manera experimental y de manera simulada son muy pequeñas por lo cual se concluye que la práctica se desarrolló de manera correcta.

12.      Bibliografía. 

   ●	    SN (2020), Análisis de circuitos y sistemas lineales, recuperado de: 	https://repositorio.innovacionumh.es/Proyectos/P_19/Tema_1/UMH_05.htm 

   ●	    https://www.tina.com/. (2020). Teorema de Superposición, recuperado de:  https://es.wikipedia.org/wiki/An%C3%A1lisis_de_mallas 

   ●	    Wikipedia.com (2020). Teorema de Superposición, recuperado de: 	https://es.wikipedia.org/wiki/Teorema_de_superposici%C3%B3n


13.      Anexos
