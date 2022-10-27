# Arduminimum - implementacao minima de Arduino sobre PCB

Implementaçao minima de um microcontrolador baseado em Arduino Uno. 




**Especificaçoes técnicas**

|Componente|Valores|
|-----------------|-------------------------| 
|Microcontroladora: |Atmel ATMega328P 8 bit AVR family controller|
|Voltagem de operaçao:| 5V| 
|Vin recomendada: |7V-12V|
|Limites de voltagem de entrada:| 6V-20V|
|Pins analogos: |6 (A0 - A5)|
|Pins digitais: |14 |
|Corrente DC nos pins de IO:| 40mA|
|Corrente DC no pin 3.3V:| 50mA|
|Flash memory:| 32Kb|
|SRAM: |2Kb|
|EEPROM: |1Kb|
|Frequência (Clock speed):| 16MHz|  
|Vout:| +5V|

Tensões disponíveis:
- +9V em AREF
- +5V diretamente de Vout 
- +3.3V via un divisor de tensão aplicado à linha de +5V

Conector de entrada: barrel jack 2.5mm, polaridade positiva ao centro

Switch on/off 

Proteção contra sobrecarga e corrente reversa 

<!-- 
## Schematics 

<img src="./assets/images/Schematics.png" width="1000">


## Board

### Projeto 
Frente 

<img src="./assets/images/KicadFront.png" width="800">

Verso  

<img src="./assets/images/KicadBack.png" width="800">

### Versão do fabricante 

Frente 

<img src="./assets/images/Board top.png" width="800">

Verso 

<img src="./assets/images/Board Bottom.png" width="800">


### Visão 3D

Frente 

<img src="./assets/images/3DViewFront.png" width="800">

Verso

<img src="./assets/images/3DViewBack.png" width="800">


--> 

## Referências

### Datasheets

Atmel ATMega328p 

https://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-7810-Automotive-Microcontrollers-ATmega328P_Datasheet.pdf

LM7805 
 
https://www.ti.com/general/docs/suppproductinfo.tsp?distId=10&gotoUrl=https%3A%2F%2Fwww.ti.com%2Flit%2Fgpn%2Flm340

NE555 

https://www.ti.com/lit/ds/symlink/ne555.pdf

PN532 

https://www.nxp.com/docs/en/nxp/data-sheets/PN532_C1.pdf