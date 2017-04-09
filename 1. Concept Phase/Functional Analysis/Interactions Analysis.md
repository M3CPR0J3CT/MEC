# Scope
The present Functional Analysis is aimed at defining the Functions the System needs to provide to the User.
First, it proposes a Critical Review of the Interactions taking place between MEC and its Operational Environment, then Functions are defined, and finally they are organised as a comprehensive Functional System.
This Analysis will lead to a Preliminary Functional Architecture and a Set of Function from which deriving the MEC Technical Requirements.

# Terms
The following terms and conventions are used in the Analysis:
- The System: MEC,
- The User: the Pilot,
- Terminal: Ground Station,
- MEC.Fi: The Function i of MEC,
- Functions description:  Infinitive form, without prejudice of Technical Solution or Possibility,
- Climatic Conditions: UK and FR Typical.

# Analysis
## Interactions Diagram
The Interactions between MEC and its Operational Environment are provided on Fig. 1 below.

![](/"MEC Interaction Diagram 2016 05 30.png")
MEC Interactions Diagram

## Operational Environment Items
The Table 2 below lists the Items called by the above Figure. This is for future reference only.

| ITEM |
| --- |
Air
Ground
Launch Pad
Regulation
Pilot
Remote Control
Terminal
Temperature
Dust
Sun
Wind
Container
Humidity
Water
Rain
EMC Agressors
GPS Signal
Flying Objects
Terrain Features
Generic Operational Equipment
Mission-Specific Operational Equipment
Core Operational Equipment
Power Source


## Functions
The Functions resulting from the Interactions between MEC and its environment are defined in Table 1 hereunder.

FUNCTION | DESCRIPTION
--- | --- |
MEC.F1 | To operate under Pilot supervision.
MEC.F2 | To be safe at all times.
MEC.F3 | To fly in the Air manually.
MEC.F4 | To fly in the Air autonomously.
MEC.F5 | To capture images of the Flight.
MEC.F6 | To capture images of the Ground in flight.
MEC.F7 | To start and terminate mission on a Launch Pad.
MEC.F8 | To comply with the applicable Regulation.
MEC.F9 | To operate at all Season’s.
MEC.F10 | To survive direct Solar Flow for the duration of the Flight.
MEC.F11 | To operate in a typical windy day.
MEC.F12 | To survive moderate rain conditions happening during the Flight.
MEC.F13 | To survive a Crash.
MEC.F14 | To float on Water.
MEC.F15 | To be hermetically sealed.
MEC.F16 | To handle Dust and minor projections at Take-Off and Landing.
MEC.F17 | To resist EMC Agressors.
MEC.F18 | To detect Terrain Features.
MEC.F19 | To provide Obstacle Avoidance capabilities.
MEC.F20 | To detect Flying Objects.
MEC.F21 | To acquire GPS Signal
MEC.F22 | To carry Generic Operational Equipment in flight.
MEC.F23 | To allow for Level 1 Maintenance of Generic Operational Equipment.
MEC.F24 | To carry additional Mission-Specific Operational Equipment in flight as required.
MEC.F25 | To allow for Level 1 Maintenance of Mission-Specific Operational Equipment.
MEC.F26 | To carry Core Operational Equipment in flight.
MEC.F27 | To allow for Level 2 and 3 Maintenance of the Core Operational Equipment.
MEC.F28 | To operate on a reusable Power-Source.
MEC.F29 | To be transportable by road in a Transportation Container.
MEC.F30 | To provide a Built-In Test Capability.
MEC.F31 | To provide a Built-In Plus Test Capability.
MEC.F32 | To allow for Mission Data Files Transfers from/to the Terminal.
MEC.F33 | To transmit Flight Parameters to the Terminal.
MEC.F34 | To transmit Position to the Terminal.
MEC.F35 | To transmit System Status to the Terminal.
MEC.F36 | To transmit First Person Views to the Terminal.
MEC.F37 | To emit Analog Signals in case of Crash.
MEC.F38 | To provide an Abort function for the Pilot to recover Manual Remote Control during an Automatic Flight at any time.
MEC.F39 | To provide a Fail Safe Mode.


## Functional Considerations
### Fail Safe Mode
MEC.F38 refers to situations where MEC still communicates with the Terminal but where an anomaly is detected by the Pilot (not by MEC). Contradictory to MEC.F39, a Manual Remote Control is required.
MEC.F39 refers to situations where Communication with MEC is lost or an anomaly is detected by MEC (not by the Pilot). MEC would switch to a Recovery Mode where it would head up to the Launch Pad.
MEC Fail Conditons need to be defined to close this component. TBU.

## Parameters Identified

- Flight Duration: Open
- Temperature Range: Open
- Wind Range: Open
- Maximum Altitude: Open
- Crash Location Range: Open
- Maintenance Levels: Definition Added to Project Management/Acronyms and Definitions
- Functional Test GO Sanction as a prerequisite in the Operational Sequence for a Mission GO: Open
- Launch Pad Coordinates to be recorded at Take-Off: Open

# Review and Comments
2016 05 30
I have completed Fig. 1, Table 1 and Table 2. Feel free to leave your comments/questions below.

2016 07 06
This is very impressive! We need to print this and put it on the wall of the mannex for reference and to keep us on track.
