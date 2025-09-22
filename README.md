# OpenPowerModuleBrainDead_V0SL

Kicad Design 
You can view on https://kicanvas.org (for non kicad users)


## Power Module Board
![](Doc\PowerModuleTopView.png)
![](Doc\PowerModuleBottomView.png)

Minimal BLDC drive hardware
Minimal Fabrication requirements , Single Layer PCB

### The hardware 
* 3phase H-bridge and all its related circuitry (MGD , Snubber , decoupling , etc)

Requires External 12V supply in addition to DC bus voltage

## Power Module Interface Board
![](Doc\PowerModuleInterfaceTopView.png)
![](Doc\PowerModuleInterfaceBottomView.png)

* IDC-2x15 Connector to be interfaced with a controller/MCU
* 12V-->5V buck converter , 3.3V LDO
* Hall Sensor Conditioning Circuits
* Back Emf Zero cross detection circuitry
* Phase Voltage Conditioning Circuitry
* 3x NTC interface
* IDC-2x15 Connector to be interfaced with a controller/MCU
* LED as logic indicators


Requires External 12V supply

### Repo Structure
* PowerModule : Power Module Design Files
* PowerModuleInterface : Power Module Interface Design Files
* LIB : Project Components library
* Doc : Design Reference , guide , step file , etc...