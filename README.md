# LABORATORIO 2

1. Objetivos

1.1. Objetivo General

Estudiar de manera experimental las características de la onda sinusoidal y a su vez su aplicación en los circuitos de los simuladores.

1.2. Objetivo Especifico

- Utilizar DCAC lab y Multisim cómo entornos de desarrollo de circuitos y a su vez el estudio y comprobación de onda sinusoidales en circuitos electrónicos.

- Definir la lectura de una onda sinusoidal y también la frecuencia y el periodo con el que estas se pueden llegar a repetir a través del osciloscopio.

2. Información general

Se denomina corriente alterna (ca) a la corriente eléctrica en la que la magnitud y dirección varían periódicamente. La forma de onda de la corriente alterna más comúnmente utilizada es la de una onda senoidal, puesto que se consigue una transmisión más eficiente de la energía.

Generalmente, la corriente alterna se refiere a la forma en la cual la electricidad llega a los hogares y a las empresas. Sin embargo, las señales de audio y de radio transmitidas por los cables eléctricos, son también ejemplos de corriente alterna.

3. Materiales y Equipo

![image](https://user-images.githubusercontent.com/94079321/155056238-235beb54-2a4e-499b-a590-420870a45451.png)

4. Procedimiento

Implemente el circuito que se presenta en la figura 7.1

![image](https://user-images.githubusercontent.com/94079321/155056203-49ef0db3-50e3-41ab-bdc6-b78f3073ac75.png)

1. Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.

![image](https://user-images.githubusercontent.com/94079321/155056265-22b2c8f2-3009-4ec3-800a-b7c13b4b7012.png)

La señal obtenida en DCAClab es de forma aproximada con una equivalencia de 9.98 como vp y vpp = 19.96.

2. Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.

![image](https://user-images.githubusercontent.com/94079321/155056453-39fc88d2-4b45-4d19-a317-1d50c890a93c.png)

![image](https://user-images.githubusercontent.com/94079321/155056480-421fbfb8-b087-45e9-b9ab-d514e365d749.png)

La señal que aparece en el osciloscopio en la carga del resistor Rl es inferior con un valor vp = 6.88 y vpp = 13.76

3. Responda las siguientes preguntas:

¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

Debido a la configuración indicada en el osciloscopio proporcionado por DCAClab, nos indica que cada cuadro abarca 3V, teniendo como amplitud pico 6.88 V, es decir que ocupa dos cuadros y una pequeña fracion extra de un tercer cuadro.

![image](https://user-images.githubusercontent.com/94079321/155182082-63a242a1-4852-441f-a25a-a3993f786ace.png)

¿En qué valor está posicionada la perilla VOLTS/DIV?

Para ambos casos medidos con el osciloscopio la perrilla VOLTS/DIV se encuentra ubicada en 3V como se ve en la imagen

![image](https://user-images.githubusercontent.com/94079321/155057682-f56f5dd7-00bc-4a13-bf94-5b4d94cd5912.png)

¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

![image](https://user-images.githubusercontent.com/94079321/155146337-66314dc1-619a-410e-ac9d-5542c13ce54a.png)

Cuenta con 4 divisiones. 

¿En qué valor está posicionada la perilla TIME/DIV?

![image](https://user-images.githubusercontent.com/94079321/155146662-9b0c3153-6dca-4137-9478-d35a43bd167e.png)

TIME/DIV= 0.1 ms 

4. ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla
del osciloscopio?

Amplitud de voltaje:  6.88V

Periodo: 0.4ms = 0.0004 s

5. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.

![image](https://user-images.githubusercontent.com/94079321/155174587-8538f19b-dfed-4402-af8d-fd8e600bb449.png)

6. Con el multímetro digital mida el voltaje de salida en RL:

![image](https://user-images.githubusercontent.com/94079321/155147726-c3b4168e-ab87-4c09-a904-8f2437bfb3ed.png)

V= 4.644V

Compare el voltaje medido en el punto 4 y el obtenido en el punto 6. ¿Coinciden?, ¿Por qué?.

![image](https://user-images.githubusercontent.com/94079321/155176014-7b6fff38-64aa-44f7-8230-4d5001c3df86.png)

El voltaje no coincide debido a que el voltaje 4 es un voltaje pico y el voltaje en 6 es un voltaje rms

5. Conclusiones

- Mediante la presente experimentación podemos determinar valores como frecuencia periodo voltajes pico pico y también voltajes rms

- Gracias a nuestra herramienta osciloscopio podemos determinar los valores a encontrar ya que es una herramienta fácil de manipular además de que muestra datos exactos si es que es bien manipulado mediante las perillas del simulador

6. Biblíografia

- Floyd, T. (2007). Principios de circuitos eléctricos. Ciudad de México: Pearson Eduación.
