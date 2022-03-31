# 28ioniq42
Synopsis: Upgrade the 28kWh 2017 ioniq EV so that it gets 42kWh

The 2017 ioniq EV has a 28kWh 96S2P LG LQ 1729-A2 with a weight of around 260 kg. The plan is to buy another complete battery, put it into the trunk, and link it to the main battery power cord so that the car will experience a larger capacity. Because the battery is 2P (meaning 2-parallel) it is only possible to either add 14kWh or 28kWH. In order to achieve a good tradeoff between weight and range, I will go for 14 kWh. The original car has a summer/winter range of about 200/170 km, and I hope I can achieve somewhere about 300/260.

In this log I will reverse engineer and explain how I hopefully succeed to fit this extra battery capacity.


## Phase 1: Validate concept

The main idea is to link the aux (short for auxiliary) battery with a parallel connection directly onto the main battery cord that connects to the junction box. I need the aux battery to be linked in parallel with the main battery in 3 use states: 1) driving, 2) OBC charging and 3) DC charging
Make sure that accessing the main power rail is possible by parallel coupling the main battery cord.
The main 

In short:
  - [x] Buy an used EV HV cord
  - [ ] Connect a thin wire from which I can check that the battery is connected in all three use states.
  - [ ]

## Phase 2: Dummy battery

Buy and build a very small battery, possibly a 96S1P battery without a BMS which I can connect to

  - [ ] Connect a heavy gauge wire that is able to handle full current. The main battery is able to deliver 248A at peak power (88kW), and since the aux battery will have a capacity half of the main battery, the heavy gauge wire should be able to withstand 124A worst case.

## Phase 3:

## Phase ?: Cooling the battery at long trips

## Phase ?: Heating the battery at low degrees


