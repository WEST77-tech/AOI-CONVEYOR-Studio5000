
CONVEYOR AOI V1.0
Studio 5000 Logix Designer
Developed by 2WRTECH

DESCRIPTION
-----------
CONVEYOR is an Add-On Instruction (AOI) developed for
Allen-Bradley ControlLogix / CompactLogix controllers.

The AOI provides a reusable conveyor control object with:

- Local / Remote operation
- Start / Stop control
- Jog mode
- Emergency Stop monitoring
- Motor feedback monitoring
- Overload monitoring
- Thermal protection monitoring
- Breaker Trip monitoring
- Rope Switch monitoring
- Drift Switch monitoring
- Speed Switch monitoring
- Runtime counter
- Fault management

VERSION
-------
Version: 1.0

SOFTWARE
--------
Rockwell Studio 5000 Logix Designer
Controller: Logix Emulate 5570 v36

INPUT PARAMETERS
----------------
LOC         Local Mode
REM         Remote Mode
STRT        Start Pushbutton
STOP        Stop Pushbutton
ESD         Emergency Stop
JOG         Jog Mode
OL          Overload Signal
TOL         Thermal Trip
CBK_TRIP    Breaker Trip
RP_SW       Rope Switch
DF_SW       Drift Switch
SPD_SW      Speed Switch
RST         Reset Fault
RUN_DLY     Start Delay (ms)
SPD_DLY     Speed Switch Delay (ms)

OUTPUT PARAMETERS
-----------------
RDY         Ready Status
RUN         Run Command
FB          Feedback Status
FLT         General Fault
RUN_SEC     Runtime Counter (seconds)

ALARM OUTPUTS
-------------
ALM_ROPE    Rope Switch Alarm
ALM_DRIFT   Drift Switch Alarm
ALM_ESD     Emergency Stop Alarm
ALM_LOAD    Overload Alarm
FB_LOSS     Feedback Loss Alarm
BK_TRIP     Breaker Trip Alarm
ALM_THERM   Thermal Alarm
ALM_SPEED   Speed Switch Alarm

FEATURES
--------
- Conveyor ready status
- Conveyor start sequence
- Motor feedback supervision
- Speed switch verification timer
- Runtime accumulation
- Individual alarm reporting
- General fault indication
- Fault reset function

PROJECT FILES
-------------
AOI_CONVEYOR.ACD               Studio 5000 Project
CONVEYOR_AOI_V1.0.pdf         Project Documentation
CONVEYOR_AOI_V1.0.L5X         AOI Export File (if provided)

LICENSE
-------
This project is provided for educational,
training and industrial development purposes.

Contributions, improvements and bug fixes
are welcome.

AUTHOR
------
2WRTECH

GitHub:
https://github.com/
