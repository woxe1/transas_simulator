
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

Then starting the boilers preparing...............