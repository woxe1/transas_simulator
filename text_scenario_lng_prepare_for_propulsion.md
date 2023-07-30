
<div align="center">

# LNG Short algo start generator and take in parallel operation #

</div>

### Precautions

- IAS → MAING GE FUEL OIL SERVICE SYSTEM
  - start MAIN G.E. MDO SUPPLY P/P #1
  - start MAIN G.E. H.F.O. supply pump
  - start F.O. BOOSTER PUMP
  - start PILOT F.O. SUPPLY PUMP
#
- MSB → LV MSB1 → GSP 1/3
  - switch to local G/E  G.V.U. ROOM (STBD) No2 EXH.FAN (ESB)
  - press start 
  - back to remote position
#
- EMG → ESB GROUP STARTER PANEL
    - switch to local No2 E/R SUPPLY FAN (2 SPEED) REV
    - press START HIGH SUPPLY
    - back to remote
#
- IAS → MAIN MENU → No1 MAIN GENERATOR ENGINE
  - start JACK UP P/P N-END
  - start JACK UP P/P D-END
  - start L.O. P/P N-END
  - start L.O. P/P D-END
#

### Starting DG

- ER2 → MG1 LOP
  - switch to local
  - press main menu → engine start/stop → start → confirmation
  - wait for 514 rpm (about)
  - switch to remote
#
- MSB → MCD
  - check that the generator working (red) and buses are green(without power)
#
- MSB → HV MSB1 → Synchro & bus tie panel
    - switch synchronoscope to gen 1 (not necessary due to absence of power on buses)
    - switch GEN 1 MODE → AUTO LOC
    - switch GEN 1 CB → CLOSE
#



### Connection additional switchboard

- MSB → MCD
  - HM1LM1 →  MAIN TRANS HV CSBD No1 (4500 kVA) → HM1LM1 CB CONTROL → CLOSE
  - LM1HM1 → INCOMING Bus Tie Panel → LV MSB No1 INCOMING PANEL → ACB CONTROL → CLOSE
  - LM1LM2 → LV MSB No 1 BUS TIE PANEL → BUS TIE ACB CONTROL → CLOSE
  - HM2HC2 → MAIN TRANS HV CSBD No2 PANEL (4500 kVA) → HM2LM2 CB CONTROL→ CLOSE
  - LM2HM2 →INCOMING Bus Tie Panel → LV MSB No2 INCOMING PANEL → ACB CONTROL → CLOSE
  - LM2LM1  → LV MSB No 2 BUS TIE PANEL → BUS TIE ACB CONTROL → CLOSE


### Starting cooling pumps and fans

- IAS → COOLING S.W & SERVICE SYS.
  - start MAIN C.S.W. PUMP #1
  - N2 to stand-by
  - start AUX C.S.W. PUMP #1
  - N2 to stand-by
#
- IAS → AUXUILIARY LT COOLING F.W. SYSTEM
  - startAUX EQUIP C.F.W. PUMP #1
  - N2 to standby
#
- MCB → LV MSB N1 → GSP 1/3
  - switch to local No 1 E/R SUPPLY EXH FAN
  - start
  - switch to remote
  - switch to local No 3 E/R SUPPLY FAN
  - start
  - switch to remote

### Boilers preparing

- ER4 → Dual Fuel Boiler No1 Control Panel
  - press RESET button
  - press CONTROL MODES → BOILER No1 to MASTER MODE
  - HOME → DIESEL OIL PUMPS → PUMP No1 (green)
  - Boiler overview → FD FAN → START
  - Atom Steam → SELECT
  - DO → SELECT
  - Oil Burner → START
  #
- ER4 → EGE Feed Water Circ. Pump CP
  - No 1 EGE FEED WATER CIRC PUMP → START
  - waiting for heating and starting of boiler (you can watch in BOILER OVERVIEW ER4)

### Preparing DG N4
- IAS → MAIN G/E F.O. SERVICE SYSTEM (2/2)
  - start MAIN G.E M.D.O. SUPPLY P/P N1
  - start MAIN G.E. H.F.O. SUPPLY P/P
  - start pilot F.O. SUPPLY P/P
  - start F.O. BOOSTER PUMP No4
#
- IAS → NO. 4 MAIN GENERATOR ENGINE
  - start JACK Up P/P N-END
  - start JACK UP P/P D-END
  - start L.O. P/P N-END
  - start L.O. P/P D-END
#
- ER2 → MG4 LOP
  - switch control mode to local
  - RESET BLOCKS → RESET - AUTOMATIC SHUTDOWN
  - MAIN OVERVIEW → MAIN MENU → ENGINE START/STOP → RESET → START → CONFIRMAION
  - switch control mode back to remote
  - go to MSB  → MCD and check that the GEN4 RUNNING
#
- MSB  → HV MSB2  → SYNCHRO & TG Panel
  - switch SYNCHRONOSCOPE TO  → GEN 4
  - GEN 4 MODE → AUTO LOC    (then recomend check all generators for remote control mode)
  - GEN 4 CB  → CLOSE (**pull it until closing!!!**)


### Check cooling of propulsion motors

- ER1 → LGSP 1
  - **START ALL PUMPS ON THAT PAGE DON'T FORGET PLACE TO REMOTE AFTER STARTING!!!**
#
- IAS  → NO1 PROPULSION MOTOR
  - ALARMS ACKN
  - wait for all alarms releasing
#
- ER2 → PM STBD LOP
  - press SUPPLY → ON

- ER2 → PM PORT LOP
  - press SUPPLY → ON

- IAS → NO1 PROPULSION MOTOR
  - just check that all pumps working

### START TURNING GEAR

- ER 1 → PM RG Turning Gear **STBD** LOP
    - switch to ENGAGE
    - press START

- ER 1 → PM RG Turning Gear **PORT** LOP
    - switch to ENGAGE
    - press START

- IAS → STERN TUBE LO SERV. SYSTEM (**STBD**)
  - start S/T L.O. CIRC P/P
  
- IAS → STERN TUBE LO SERV. SYSTEM (**PORT**)
  - start S/T L.O. CIRC P/P


### STOP TURNING GEAR

- ER 1 → PM RG Turning Gear **STBD** LOP
    - press STOP
    - switch to DISENGAGE
#
- ER 1 → PM RG Turning Gear **PORT** LOP
    - press STOP
    - switch to DISENGAGE
#
- IAS → ALARMS ACKN (just for check)
#

### Prepare for propulsion

- ER2 → PM PORT LOP
  - switch to LOCAL
  - press button LOC.REM
  - press button START DRIVE
  - back to remote
#
- ER2 → PM STBD LOP
  - switch to LOCAL
  - press button LOC.REM
  - press button START DRIVE
  - back to remote
#
- ECR → ECR PM CONTROL PANEL
  - press ACCEPT COMMAND
  - pull handles to DEAD SLOW ( start ahead ... YEAHHH)

    