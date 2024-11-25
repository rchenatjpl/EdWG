
 
This document largely includes sections of the following articles:
The Venus Express Spacecraft System Design, by P. Sivac and T.
Schirmann
[SIVAC&SCHIRMANN2007].
 
Instrument Host Overview
========================
 
Venus Express is the second of the so-called Flexi-missions of ESA
and with some differences imposed by the environment in orbit around
Venus is, from a spacecraft design point of view almost an exact
replica of the first Flexi-mission Mars Express. The satellite was
launched on 9 November 2005 on a Soyuz rocket from Baikonur and was
injected into its trajectory towards Venus using the Fregat upper
stage. After a journey of about five months, Venus Express was
inserted in orbit around the planet on 11 April 2006 and started its
nominal scientific mission on 4 June 2006.
The major objective of the Venus Express spacecraft design was to
cope with the specific mission requirements of a spacecraft orbiting
Venus (mainly associated with the much higher temperatures) whilst
maximising the reuse of the Mars Express design and so minimising the
development risks in order to guarantee the readiness of the
spacecraft for the launch window.
 
Mechanical design
=================
 
The mechanical design was driven by the following considerations:
    - reuse of the Mars Express mechanical bus as far as possible;
    - the specific constraints of the Venus Express mission;
    - the need to minimise the spacecraft dry mass and optimise the
      location of the centre-of-mass.
The reuse of the Mars Express mechanical bus (structure and
propulsion system) minimised the development risks and helped to
secure the programme very tight schedule. Drawing on the Mars Express
qualification, the core structure design remained basically
unchanged, which allowed qualification by similarity. The
modifications to the secondary structure were strictly limited to
accommodation of the new or modified units. Reusing the bus also
meant that most of the Venus Express units have the same mechanical
environment as on Mars Express. The main mechanical design
modifications relate to the payloads, the additional High Gain
Antenna and the constraints from the thermal design.
As on Mars Express, the overall spacecraft mass was close
scrutinised. The maximum mass of the spacecraft (including
propellants) allowed by the launcher was agreed at 1270 kg. Through
careful mass management, the propellant tanks   could be filled to
their maximum capacities.
Close attention was paid to the centre-of-mass and the alignment of
the main engine. During the main engine burn for Venus orbit
insertion, the disturbing torques imposed on the spacecraft were
directly linked to the offset between the direction of thrust and the
centre-of-mass, which migrated as propellant was depleted. To improve
the control torque margins, strict control of the centres-of-mass of
individual units was maintained and balance masses were added for
fine adjustment.
 
Thermal control
===============
 
The spacecraft thermal control subsystem is required to maintain the
temperatures of spacecraft elements within their allowed temperature
ranges during all mission phases.
The spacecraft equipment fall into two categories namely:
a) The units that are collectively controlled by the overall
spacecraft thermal control
b) The units that have their own thermal control such as individual
heaters or radiators.
The thermal control design of Venus Express is based on a robust and
passive concept having a maximum commonality with Mars Express but
having some specific design modifications in order to cope with the
hot environment at Venus.
 
The two main differences with Mars Express are:
a) A harsher thermal environment. The solar constant is almost four
times that of Mars. Furthermore, the Venus albedo makes a significant
contribution to the overall flux on the spacecraft during the
observation phase around the pericentre.
b) Since the orbit of Venus is closer to the Sun than the one of the
Earth, it is not possible to keep one wall of the spacecraft
permanently in the shadow during communications with the Earth having
a single antenna. For this reason, having analysed the allowable Sun
aspect angles on the various faces of the spacecraft, it has been
decided to include a second smaller high gain antenna on the top floor
of the spacecraft.
 
Most of the spacecraft units are collectively controlled inside
thermal enclosures that are naturally created by the spacecraft
mechanical configuration. The heat balance is controlled by radiators
and heaters, allowing the unit temperatures to be maintained within
their defined limits. The unit temperature control is achieved
through the use and the selection of flight-tested materials used on
numerous spacecraft.
 
The key features of the thermal control are summarised as follows:
a) Optical solar reflectors radiators which are electrically grounded
to the aluminum sandwich panel face sheet and dissipate internal
heat towards space
b) Dedicated radiators provided for both VIRTIS and PFS which require
low temperatures for operations
c) Platform high dissipative units mounted directly behind the
radiators in order to provide a good conductive path from unit to
radiator panel
d) Heat pipes implemented under the PCU and PDU units in order to
evenly spread the high PCU thermal dissipation
e) Thermal straps used to connect the Reaction Wheels and those
payload units requiring a dedicated radiator (i.e PFS,
SPICAV/SOIR,VIRTIS)
 
Heaters are managed either under software control or by thermostats.
 
Chemical propulsion subsystem
=============================
The Chemical Propulsion Subsystem (CPS) is a helium-pressurised
bipropellant system, using monomethyl hydrazine (MMH) as the fuel and
nitrogen tetroxide (NTO) with 3% nitric oxide as the oxidiser. The
main engine, essential for Venus orbit insertion, has a thrust of 414
N and a specific impulse of 317 s. Four pairs of 10 N thrusters (four
primary, four redundant) provide trajectory corrections and attitude
control and reaction wheel unloading. They are the same as those used
on Mars Express. The CPS operated in a constant-pressure mode during
main engine firings for the capture manoeuvre and the first part of
the apocentre reduction manoeuvre, using a regulated helium supply.
The CPS comprises two subsystems: the pressurant subsystem and the
propellant feed subsystem. The helium pressurant subsystem, commonly
referred to as the 'gas side', has two sections: high-pressure and
low-pressure. The highpressure gas side comprises a 35.5-litre
helium tank, normally-open and normally-closed pyrovalves, a
high-range pressure transducer, a fill & drain valve, and a test
port to support integration activities. This section has a maximum
expected operating pressure (MEOP) of 276 bar. During all ground
operations and launch, it was isolated from the pressure regulator by
a pair of normally-closed pyrovalves. These are arranged in parallel
for redundancy. The low-pressure gas side comprises a pressure
regulator, non-return valves, a pair of low-flow latch valves, a
low-range pressure transducer, normally-closed pyrovalves, and test
ports and fill & vent valves. This section has an MEOP of 20 bar,
controlled by the regulator that senses downstream pressure.
The propellant feed subsystem, commonly referred to as the 'liquid
side', supplies propellants to the main engine and thrusters. It
comprises a pair of 267-litre propellant tanks, normally-open and
normally-closed pyrovalves, propellant filters, low-range pressure
transducers, main engine, reaction control thrusters, and test ports
and fill & drain valves. This section is pressurised with helium from
the low-pressure gas side, and has an MEOP of 20 bar.
 
Power Subsystem
===============
 
Electrical power is provided by two solar wings equipped with
triple-junction GaAs cells. The array is oriented towards the Sun by
two Solar Array Drive Mechanisms (SADM). During eclipses, power is
provided by three lithium-ion batteries that recharge after the
eclipse. Power management and regulation is performed by the Power
Control Unit (PCU) that provides a regulated 28 V main bus. The PCU
uses a Maximum Power Point Tracker (MPPT) in order to operate at the
maximum power output of the solar array, which avoids the need to
oversize the solar array to cope with both near-Earth and Venus orbit
conditions. Battery management is performed using three Battery
Charge and Discharge Regulators (BCDRs) under the control of a Main
Error Amplifier (MEA) control loop. The resulting +28 V regulated bus
is distributed to all spacecraft users by a Power Distribution Unit
(PDU) featuring Latching Current Limiters (LCLs), which protect the
bus from overcurrents at unit level. The PDU is also responsible for
generating the commands for firing the pyrotechnics.
 
The solar array consists of two identical low-weight deployable
wings, each having two solar panels pointed towards the Sun by a one
degree-of-freedom SADM. When stowed, each wing was clamped to the
spacecraft side panel on four hold-down points and release
mechanisms. For deployment (which was performed autonomously after
launch as part of the separation sequence), redundant pyrotechnic
bolt cutters released each wing individually. In order to meet the
stringent requirements associated with the Venus radiation
environment, the chosen solar cell technology was GaAs with 100
micrometer cover glass. The maximum array current is 18 A per wing.
The total array power values are of the order of 820 W near Earth and
1400 W at Venus (end-of-life).
 
Three batteries supply the spacecraft power if either the solar array
is not illuminated by the Sun or if the power demand is higher than
can be generated by the array. The energy is stored in three
identical 24 Ah low-mass Li-ion batteries with a total capacity of
around 500 Wh. Each has 16 parallel strings of six serial 1.5 Ah
cells. The batteries are identical to those on Mars Express.
 
Radio-frequency communications subsystem
========================================
 
The radio-frequency (RF) communication subsystem consists of a
redundant set of dual-band transponders operating in both S-band and
X-band for either the uplink or the downlink.
The antennas on the spacecraft are:
   - two Low Gain Antennas (LGA), used primarily during the Launch
     and Early Operations Phase (LEOP), operating in S-band for
     omni-directional reception and hemispherical transmission;
   - the dual-band HGA1, operating in S-band and X-band for high-rate
     telemetry and telecommand;
   - the single-band offset HGA2, operating in X-band only, for
     high-rate telemetry and telecommand.
 
All nominal operations are performed at X-band. Selection of which
HGA to use depends on the mission phase and, particularly, the
relative positions of the Earth, spacecraft and Venus.
To maintain thermal control for instruments, solar illumination of
the -X side of the spacecraft (opposite to HGA1) is minimised. With
steady-state Earth communications, the spacecraft Z/X plane remains
in the Sun-spacecraft-Earth plane. This means that:
   - no Sun impinges on the lateral sides (+/-Y sides);
   - the solar array can be pointed towards the Sun;
   - HGA1 or 2 can be pointed towards Earth;
   - the cold side of the spacecraft (-X) remains facing cold space.
Before the Sun starts to impinge on the cold side, as the spacecraft
and Venus orbit the Sun, the spacecraft is flipped to point the
opposite antenna towards Earth.
 
Ground stations
===============
 
The ground station used throughout all mission phases are the ESA
Cebreros 35m station, complemented by the ESA New Norcia 35m station,
to support Venus Orbit Insertion and VeRa campaigns, and the Kourou
15m station during LEOP. Use of the NASA Deep Space Network (DSN) is
envisaged for emergency cases or for special campaigns.
 
Payload
=======
 
The Venus Express payload includes seven instruments. Five of them
are re-used from the Mars Express and Rosetta projects with small
modifications:
   - ASPERA analyzer of space plasma and energetic neutral atom
     imager;
   - PFS a high-resolution IR Fourier spectrometer;
   - SPICAV/SOIR a versatile UV-IR spectrometer for solar/ stellar
   occultation and nadir observations;
   - VeRa a radio science experiment;
   - VIRTIS a sensitive visible and near infrared spectro-imager and
     high resolution spectrometer.
These experiments are complemented by two small units specifically
developed for the Venus Express mission. They are:
   - Venus Monitoring Camera (VMC)
   - magnetometer (MAG).
Details about these instruments can be found in the INSTRUMENT.CAT
files that are included in the experiment data sets.
 
Payload operations
==================
 
Payload scientific operations are conducted according to the
observation scenarios or feasible combinations of the defined ten
science cases whenever they are compatible with spacecraft and ground
segment resources.
 
Payload observation scenarios:
 
I   Observation scenario
1   Pericenter observation
2   Off-pericenter observation
3   Apocenter global spectral-imaging by VIRTIS
4   VeRa bi-static sounding
5   SPICAV stellar occultation
6   SPICAV/SOIR solar occultation
7   Limb observation
8   VeRa Earth radio occultation
9   VeRa solar superior and inferior conjunction
10  Venus Gravity Anomaly by VeRA
 
Data downlink is performed during daily station passes. It is assumed
that during the station pass science observations do not interfere
with the Earth pointing. Under nominal conditions the station passes
is such that an average of 8.5 hours continuous is available daily
for stored data downlink. An average bandwidth of ca 7 kbps is
allocated to the downlink of stored spacecraft telemetry, assuming a
continuous generation rate of 2.5 kbps throughout the 24 hours for
spacecraft housekeeping telemetry. Radio Science (VeRa) observations
are conducted for Earth occultations with the spacecraft inertially
fixed, for short periods when the line of sight between spacecraft
HGA antenna and Earth ground station pass through the Venus
atmosphere. In support of dual frequency measurements (X/S-band)
above and beyond the Cebreros 35 m (X-band) occasional use is made of
the New Norcia 35 m and DSN 34 and 70 m ground stations (S/X-band).
As far as possible, the orbit phasing will be such that SC entry and
exit of Earth occultation will occur during NNO passes. During the
VeRa radio occultation the spacecraft is required to perform a slew
manoeuvre to compensate for ray bending due to atmospheric
refraction.
 
Attitude and Orbit Control System
=================================
 
The characteristics of the mission and the fact that the spacecraft
has fixed High Gain Antennas and a single rigidly-mounted main engine
means that there are demanding manoeuvering requirements.
 
Attitude ascertainment is provided by two Star Trackers (STTs) which
in turn are supported by redundant Inertial Measurement Units (IMUs),
and a Sun Acquisition Sensor (SAS). Attitude control is established
by a reaction wheel assembly supported by the attitude thruster
system.
 
Star Trackers
-------------
The autonomous star tracker with its extensive star catalogue ensures
that accurate attitude estimation can be achieved in almost any
position. It is the main optical sensor of the AOCS and is used at
the end of the attitude acquisition following each manoeuvre to
acquire the 3-axis pointing required for almost all nominal
operations. The star tracker includes a star pattern-recognition
function and can perform attitude acquisition autonomously.
Venus Express has two star trackers aligned with an angle of 30
degrees of arc between their optical axes for operational redundancy
and to ensure that one can always see a recognizable region of the
sky.
 
Inertial Measurement Units
--------------------------
Each of the two IMUs has a set of three gyros and three
accelerometers aligned along three orthogonal axes. The AOCS can use
either the three gyros of the same IMU or any combination of three
gyros among the total of six. Only a full set of accelerometers from
one single IMU is used; they are essential to improve the accuracy of
manoeuvres performed with the main engine. The gyros are used during
attitude acquisition phases for rate control, during observation and
communication phases to ensure the required pointing performance and
during the trajectory correction manoeuvres for control robustness
and failure detection. The non-mechanical technology removes the
possibility of mechanical failure during the mission.
 
Sun Acquisition Sensor
----------------------
Two redundant SASs mounted on the spacecraft central body ensure
pointing in the Sun Acquisition Mode at the time of first acquisition
after launch or any subsequent reacquisition in the case of an FDIR
activity following an onboard failure. The Mars Express sensors were
modified, using different solar cells with ceramic backing in order
to cope with the thermal environment at Venus.
 
Reaction Wheel Assembly
-----------------------
The reaction wheels are used for most of the attitude manoeuvres for
specific activities such as Earth communication and scientific
observations; they provide flexibility and reduce overall propellant
consumption. The angular momentum of the wheels has to be carefully
managed from the ground; regular off-loading keeps the wheel speeds
within performance limits. The RSA comprises four individual wheels
in a skewed configuration to manage the spacecraft momentum in all
three axes. Although nominally all four wheels are used for
operations, this configuration, which is identical to Mars Express,
allows full performance with any three-wheel configuration.
 
AOCS Modes
----------
The AOCS includes several modes for attitude acquisition/
reacquisition, the nominal scientific mission and orbit control.
 
The attitude acquisition and reacquisition sequence has two basic
modes:
1) the Sun Acquisition Mode, pointing the X-axis and the solar array
towards the Sun in order to guarantee power.
2) the Safe/Hold Mode, which completes the acquisition phase and
provides the final 3-axis pointing, with one High Gain Antenna
pointing towards the Earth to guarantee telemetry and telecommanding.
 
Trajectory correction manoeuvres are performed using two modes:
1) the Orbit Control Mode, for small corrections using the attitude
thrusters;
2) the Main Engine Boost Mode, for major manoeuvres using the main
engine;
 
To ensure a smooth transition between the thruster-controlled modes
and wheel-controlled modes there is also:
1) a Thruster Transition Mode
 
Data Handling Subsystem
=======================
 
The Data Management System (DMS) performs all the data handling
functions for the spacecraft, including:
1) telecommand distribution throughout the spacecraft;
2) telemetry data collection from the spacecraft and data storage;
3) overall supervision and monitoring of the spacecraft and payload
functions and health status;
4) timing functions, including the distributions of time and
synchronization information.
 
The DMS is based on a dual-processor architecture embedding standard
communication links. The DMS includes four identical processor
modules, located in two fully redundant Control & Data Management
Units (CDMSs). One processor module is dedicated to the DMS software
(in charge of the management of the platform subsystems), while the
other is allocated to the AOCS software (in charge of acquisition and
control of all platform sensors, actuators and Solar Array Driving
Mechanism (SADM)).
 
The data handling architecture is organized around the two CDMUs.
They are in charge of controlling ground command reception and
execution, onboard housekeeping and science data telemetry storage
and formatting for transmission. Onboard data management, control-law
processing and execution of onboard control procedures are also part
of their function. Each CDMU features two MA3-1750 processor modules,
each processing either DMS or AOCS software. A builtin failure
operational reconfiguration module ensures system-level Failure
Detection, Isolation and Recovery integrity and autonomously
reconfigures the CDMU processor units as necessary. The CDMUs
communicate directly with the Dual Band Transponder that is part of
the RF Communications System.
 
Three other units are part of the data handling subsystem:
1) the Remote Terminal Unit (RTU) is the interface between the DMS
processor module and platform units (Power Control and Distributions
Units) and payloads;
2) the AOCS Interface Unit (AIU) is the interface between the AOCS
processor module and the sensors, actuators and solar array drive
electronics;
3) the Solid State Mass Memory (SSMM) is a file-organized mass memory
with 12 gigabit of storage that is used to store the housekeeping and
science data collected by the CDMU; it also collects science data
directly from the VIRTIS and VMC instruments.
 
The use of SSMM is dictated by the same store-and-forward concept
employed for Mars Express, meaning that every orbit is divided into
two principal phases: an observation phase, where the instruments are
pointed towards Venus, and a communication phase where a HGA is
pointed towards the Earth. To support this, all scientific and
housekeeping telemetry are stored in the SSMM.
 
Failure Detection, Isolation and Recovery
=========================================
 
As a deep space mission, Venus Express requires a high level of
onboard autonomy because of the time needed for ground intervention
in the event of an onboard anomaly or the extended periods when
communications are not possible owing to the respective positions of
the Sun, Venus and Earth. The automatic FDIR function is largely
recurrent from Mars Express, with some adaptations.
 
The FDIR function handles any anomalies onboard with a first goal of
returning to the same spacecraft mode in order to preserve
operational integrity. If this is not achievable, then the priority
is to preserve spacecraft integrity and safety. In this case, the
spacecraft autonomously enters safe mode, which ensures that power is
available from the solar array, communication with Earth is available
for diagnostics and recovery, and all non-essential loads have been
switched off. In this way, spacecraft safety is ensured until
operators on Earth can identify and correct the anomaly and proceed
with the mission.
 

        