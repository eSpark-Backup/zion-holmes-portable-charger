# ZionHolmes-PortableCharger

To develop an electrical product for a power bank as per client provided specifications and also a AC to DC charger that can charge 10 x Individual Power Banks

The product will comprise of 2 x PCBs that will be referred throughout the course of development as:
1. Portable Charger PCB
2. POS PCB

## Requirements
### Portable Charger PCB
* The PCB will support the following specifications:
  * Capacity: 10500mAh
  * Charge Input: 24W(max)
  * Output: 22.5W(max)
  * PCB Dimension: Not defined yet
  * Weight: Not defined yet
  * Output Types: Type-A x 1; Type-C x 1; Wireless Charge x 1; iPhone Slot (no clarity yet)
  * Input: Prongs for supplying power (preferably spring contacts TBD)
  * Battery type: Li-polymer 1S
  
* The circuit should provide support for charing the battery and delivering output specified in the list above.
* LED display or separate LEDs TBD.
* There will be a magnetic lock on the PCB. It is not yet decided how that lock will be controlled.
* The confirmation of above points will decide if an MCU is required or not.

### POS PCB
* The PCB should be capable of delivering up to 300W of power for charging the 10 x portable charger PCBs.
* Input to the PCB will come via direct AC supply 120VAC / 60Hz. If possible and feasible, use of off-the-shelf AC to DC supply is acceptable.
* PCB dimensions are not yet finalized. These can be decided by the Electronics team.
* Charge indication to be decided with client.
* Integration with POS system is to be decided.
