# Power Suppy for microcontrollers v.1.0

Fonte de alimentação para projetos de microcontroladores. A entrada de corrente se dá via adaptador de 9 a 12 V

**Caracteristicas**

Vin: 9V-12V  
Vout: +9V, +5V, +3.3V


Tensões disponíveis:
- +9V em AREF
- +5V diretamente de Vout 
- +3.3V regulado em Vout

Conector de entrada: barrel jack 2.5mm, polaridade positiva ao centro

Switch on/off 

Proteção contra sobrecarga e corrente reversa 

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


## Plano de soldagem 

* Etapas a serem seguidas
    - Resistores
        - Orientar a banda de tolerância para a direita ou para o alto, conforme a posição do resistor
    - Diodo 
        - Observar a polaridade 
    - Switch 
    - Jumpers 
    - Capacitores 
        - Observar as polaridades 
    - CI 7805
        - Observar orientação dos pinos 
    - Jack 
        - Quantidade de solda suficiente para os pinos 


## Referências

### Datasheets

LM7805 - Voltage regulator 5V
 
https://www.ti.com/general/docs/suppproductinfo.tsp?distId=10&gotoUrl=https%3A%2F%2Fwww.ti.com%2Flit%2Fgpn%2Flm340

LM1086 - Voltage regulator 3.3V 

https://www.ti.com/lit/ds/symlink/lm1086.pdf?HQS=dis-mous-null-mousermode-dsf-pf-null-wwe&ts=1667479620648&ref_url=https%253A%252F%252Fwww.mouser.fr%252F