<div align="center">

# Tanker algo gen control
</div>

### Start first generator
 - SYS → FO ME GE Service System
   - open pneumatic valve
#
- MSB → Synchro Panel
  - set STANDBY to 1 generator
  - select load sharing - OPTIONAL
#
- EmG → ESB Generator & Shore Panels
  - open the cb of SHORE POWER
  - go to mcd and check that generator connected
#
### Start second generator
- MSB → Synchro Panel
    - press Alarm Reset
    - switch Standby Selectrion → manual
    - switch Synchronoscope → G2
    - switch FREQ&Voltmeter → G2
    - switch SYNCRO/POWER → AUTO (if you are going to synchronize automatically)
#
- ER3 → GE 1-2 LOP
  - set two-positional selector switch of starting generator in local mode;
  - press the button START;
  - return two-positional selector switch in the remote state;
  - wait for 900 rpm on tachometer.
#
- MSB → Synchro Panel
  - switch SYNCRO/POWER → MANUAL;
  - with help of handles GOVERNOR CONTROL decrease phase shift between generators
  - when phase shift will be at 12 hours close the ACB of generator with help of ACB CONTROL switch
#
 - SYS → FO ME GE Service System
   - click on the upper motor and start it from menu
   - close the bottom valve


### Disconnect generator

- MSB → Synchro Panel
  - switch SYNCRO/POWER → MANUAL;
  - decrease the load of disconnecting generator less then 10% of nominal power (use both handles)
  - open the Circuit Breaker with help of handle CONTROL CB of disconnecting generator



