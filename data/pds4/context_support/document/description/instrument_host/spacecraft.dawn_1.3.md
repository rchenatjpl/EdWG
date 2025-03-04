
 
      Instrument Host Overview
      ========================
 
The Dawn spacecraft is an ion-propelled spacecraft capable of
visiting and stopping at multiple targets in the Main Asteroid Belt.
Most of the spacecraft design was provided by Orbital Sciences
Corporation (Orbital), and the Jet Propulsion Laboratory (JPL)
provided the ion propulsion system (IPS) and parts of the
electrical power system and telecommunications system.  Orbital
was responsible for overall assembly, including integration of
instruments, system-level tests, and launch operations.  JPL is
responsible for mission operations.
 
The IPS is an expanded version of the system operated extensively on
Deep Space 1 (DS1).  The spacecraft design benefits from inheritance
from previous projects at Orbital and the JPL.  The mechanical design is
based on Orbital's Star-2 series, and the avionics draw from the
LEOStar-2 series.
 
There is significant redundancy throughout the design, and the
mission can be accomplished in the presence of most credible
single faults.
 
A complete description of the Dawn spacecraft may be found in
Rayman et al. (2006), from which most of the information in this file
was taken.
 
 
      System Description
      ==================
 
Ion Propulsion System
---------------------
 
The core of the structure is a graphite composite cylinder.
The hydrazine and xenon (Xe) tanks mount inside the cylinder, which
provides a load path directly to the launch vehicle interface.  The
Xe tank, titanium overwrapped with composite, has a capacity of 425
kg.  To provide reliability in expending that much propellant, the
spacecraft carries three ion thrusters.  The thruster design is
qualified for a throughput of about 150 kg.  Each 30-cm diameter
thruster is mounted to a two-axis gimbal to allow for migration of
the flight system's center of mass during the mission and to allow
the attitude control system (ACS) to use the IPS to control attitude
when the IPS is thrusting.  The IPS system includes two sets of
interface and control electronics and two power processing units,
although no more than one thruster will be operated at a time.
 
Attitude Control System and Reaction Control System
---------------------------------------------------
 
In its normal cruise mode, ACS estimates attitudes and rates with a
star tracker.  The estimation is augmented with mechanical gyros in
some ACS modes, including during science data acquisition.  The star
trackers and the gyros are mounted on the +z panel to minimize
mechanical alignment errors between the sensors and FC and VIR.
Coarse Sun Sensors (CSS), providing 4-pi steradian coverage, are used
for rough attitude determination and for fault protection.  All
attitude sensors are fully redundant.
 
ACS controls the articulation of the solar arrays and the basebody
to assure that the arrays are normal to the Sun-spacecraft line.
ACS can be commanded to use the reaction control system (RCS) or
reaction wheels to control the attitude.  Either type of actuator
can be used in combination with the IPS for attitude control during
IPS thrusting.
 
The hydrazine-based RCS is used by ACS for direct control of attitude
or for desaturation of the reaction wheels.  In addition, some
hydrazine is allocated for a contingency orbit-control maneuver at
the asteroids in the event there is insufficient time to achieve the
required delta-v with the low-thrust IPS.  To date, no scenarios for
this contingency have been identified.  The titanium hydrazine
tank capacity is 45.5 kg.  RCS has two independent strings, each with
six 0.9 N thrusters.  Each string has pairs of thrusters pointed in
+x, -x, and -z, with the last pair used for the contingency trajectory
control.
 
Electrical Power System and Thermal Control System
--------------------------------------------------
 
Because of Dawn's uniquely high delta-v requirements, much of the
spacecraft design is driven by the resulting need to maximize the
power available to the IPS.  When the flight system is at Ceres at
a heliocentric range of 3 AU, the electrical power system (EPS) has
to provide sufficient power to operate the IPS.  Therefore the
spacecraft has two large solar arrays which together provide 10.3 kW
at 1 AU and 1.3 kW at Dawn's maximum heliocentric distance of 3 AU
(Ceres' aphelion).  Each of the two solar arrays has 18 square meters
of InGaP/InGaAs/Ge triple-junction cells.  The arrays are articulated
around their long axis.
 
Because the IPS requires high-voltage power, the flight system has
two power buses.  The EPS delivers most of the IPS power at
80-140 V, and the rest of the flight system (including some IPS
components) receives power at 22-35 V.  A 35 Ah NiH2 battery,
sized to provide energy during launch, supplements the low-voltage
bus during IPS thrusting to cover transients in the flight system's
power consumption.
 
Apart from the IPS, the thermal control system (TCS) is the largest
consumer of power, requiring 200 W during IPS thrusting at 3 AU.
Ammonia based heat pipes embedded in the y panels aid in distributing
the heat, and louvers reduce thermal power requirements under cold
conditions.  Because the solar arrays are always maintained normal
to the Sun-spacecraft line, the sun will be in the plane of the y
panels.  Most components are mounted on these panels to take advantage
of the relatively uniform thermal environment.
 
Command and Data Handling System
--------------------------------
 
The Command and Data Handling System (CDHS) is based on a RAD6000
processor running sofware written in C running in VxWorks.  CDHS
also provides 8 Gb of mass memory for engineering and scientific
data.  The system receives telemetry from all ACS sensors and includes
drivers for all ACS actuators except the IPS thruster gimbals.  Most
components communicate over a Mil-Std-1553 data bus, although GRaND
uses a RS-422 serial interface.
 
The flight software incorporates virtual machine language (VML),
currently in use on Mars Odyssey, Mars Reconnaissance Orbiter,
and the Spitzer Space Telescope.  VML allows conditionals and complex
logic in command sequencing.  VML is used for all commanding
during the mission, although in order to rely on only the most basic
functions, fault protection does not use it.
 
CDHS supports uplink data rates from 7.8 b/s to 2.0 kb/s and downlink
data rates from 10 b/s to 124 kb/s using a rate 1/6 turbo code,
implemented as recommended by the Consultative Committee for Space
Data Systems.
 
Telecommunications System
-------------------------
 
The telecommunications system (Telecom) operates in X-band for uplink
and downlink.  It is based on the Small Deep Space Transponder,
validated on DS1 and used on the majority of NASA missions beyond the
moon since Mars Odyssey.  Radiating 100 W, the travelling wave tube
amplifiers are identical to those in use on Mars Reconnaissance
Orbiter.  An unarticulated 1.52 m high gain antenna (HGA) is on the
spacecraft's +x axis, and near-hemispherical (7 dBi) low gain
antennas (LGAs) are aligned with +x, +z, and -z.  The system is
configured to always use only one of the four antennas at a time.
 
 
Instrument Mounting Geometry
----------------------------
 
The figure below represents the Dawn spacecraft with the -y panel
facing the viewer.  GRaND and the FCs are mounted on the +z panel
and VIR is mounted on the -x panel.  All instruments are mounted
so the centers of their fields of view are aligned with the
spacecraft's +z axis.  The high gain antenna is mounted to the
+x panel.  One IPS thruster is mounted at the -z panel and the other
two are on their own panels, one canted towards -x and the other toward
+x.  The thrusters are about 48 degrees from -z.  The two solar panels
extend from the +y and -y panels.
 
 
                               +X
 
                           /\  High Gain Antenna
                  -------------------
                   \                /
                    \              /
                   --------------------------/\
                ___|                        |  \
          GRaND |  |                        |_/_   Ion propulsion
                |  |                        |   |  thrusters
                |__|                        |   |
       Z          _|            o           |   |    -Z
              FC |_|                        |   |
                   |                        |___|
                   |                        | \
                   |                        |  /
                    -------------------------\/
               VIR |         |
                   |_________|
                               -X
 
 
      References
      ==========
 
Rayman, M.D., T.C. Fraschetti, C.A. Raymond, and C.T. Russell, Dawn:
A mission in development for exploration of main belt asteroids Vesta
and Ceres, Acta Astronautica 58, 605-616, 2006.

        