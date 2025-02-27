
 
Instrument Overview
===================
 
see [FULCHIGNONIETAL2002]
 
The Huygens Atmospheric Structure Instrument (HASI) is a multi-sensor package
designed to measure the physical quantities characterising Titan's atmosphere
during the Huygens probe entry, descent and at the surface.
The HASI experiment is divided into four subsystems: the accelerometers (ACC);
the deployable booms system (DBS); the stem (STUB) carrying the temperature
sensors, a Kiel probe pressure sampling inlet, an acoustic sensor and the data
processing unit (DPU). The HASI subsystems, their acronyms, the institutions
responsible for the management (together with the providers) and the elements
included are summarised in Table 1.
 
TABLE 1    HASI subsystems
------------------------------------------------------------------------------
Subsystem (Acronym)         Responsible institutions  Elements
                            (Providers)
------------------------------------------------------------------------------
Deployable Boom System (DBS) RSSD (LPCE/SSD)          PWA electrodes,
                                                      Boom Magnetic Actuators,
                                                    PWA preamplifiers (HASI-I)
 
Fixed stem (STUB)            UPD (UPD/FMI/IWF)        Temperature sensors,
                                                      PPI Kiel probe,
                                                      acoustic sensor
 
Accelerometers (ACC)         OU-UK (UKC)              Four accelerometers
 
Data Processing Unit (DPU)   OG (FMI/IWF/IAA/OG)      Electronics boards
 
Electrical Ground
Support Equipment            OG (UPD/OG)              EGSE
------------------------------------------------------------------------------
 
The scientific measurements are performed by four sensor packages: the
accelerometers (ACC), the temperature sensors (TEM), the Pressure Profile
Instrument (PPI) and the Permittivity, Wave and Altimetry package (PWA) (see
Table 2). TEM, PWA and PPI's Kiel probe are mounted externally and ACC is
attached to Huygens' experiment platform at the Probe's centre of gravity in
the entry configuration.
 
Table 2. HASI sensor packages.
------------------------------------------------------------------------------
Sensor package (Acronym)    Sensor type               Measured parameters
------------------------------------------------------------------------------
Accelerometers (ACC)         3-axes accelerometers   Atmospheric deceleration;
                             (1 X-servo &              Descent monitoring;
                                3 piezoresistive)      Response to impact
 
Pressure Profile          Kiel type pressure   Atmospheric pressure Instrument
(PPI)                          probe + capacitive     profile
                                  transducers
 
Temperature (TEM)               2 dual element        Atmospheric temperature
                                 Pt thermometers       profile
 
Permittivity, Wave           Mutual Impedance         Atmospheric electric
and Altimetry (PWA)          AC field measurement      conductivity;
                                                      Wave electric fields &
                                                       Lightning.
                             Relaxation Probe         Ion conductivity;
                                                      DC electric field.
                             Acoustic sensor          Acoustic noise due to
                                                      turbulences or storms.
                             Radar signal           Radar echoes below h=60 km
                              Processing (FFT)
 
------------------------------------------------------------------------------
 
 
Scientific Objectives
=====================
 
HASI scientific objectives are:
- Determine the atmospheric pressure and temperature profiles.
- Evaluate the density and molecular weight profiles.
- Determine the atmospheric electric conductivity and charge carrier profiles.
- Investigate ionisation processes.
- Survey wave electric fields and atmospheric lightning; analysis of
  quasi-static electric fields leading to storm formation.
- Detect acoustic noise due to turbulence or thunder storms.
- Characterize the roughness, mechanical and electrical properties of the
  surface material whatever its phase, solid or liquid.
 
HASI data will also contribute to the analysis of the atmospheric composition
and to provide information on the surface, whatever its phase: liquid or
solid. HASI will monitor the acceleration experienced by the probe during the
whole descent phase and will provide the only direct measurements of pressure
and temperature through sensors having access to the atmospheric flow.
Electrical measurements will be performed in order to characterise the
electric environment on Titan and to detect effects connected to electrical
processes, such as lightning and thunder. In situ measurements are essential
for the investigation of the atmospheric structure and dynamics. The
estimation of the temperature lapse rate can be used to identify the presence
of condensation and eventually clouds, to distinguish between saturated and
unsaturated, stable and conditionally stable regions. The variations in the
density, pressure and temperature profiles provide information on the
atmospheric stability and stratification, on the presence of winds, thermal
tides, waves and turbulence in the atmosphere. Moreover, the descent profile
can be derived from temperature and pressure data as a function of pressure
and altitude. The return signal of the Huygens altimeter radar is processed by
the HASI electronics, providing an independent estimation of altitude and
spectral analysis of the signal yields information on satellite's surface.
 
For a more detailed description of HASI scientific return see
[FULCHIGNONIETAL1997; FULCHIGNONIETAL2002]
 
Pressure, temperature and density profiles
------------------------------------------
 
 Entry phase
 -----------
HASI will be the only instrument operating during the entry phase. Information
on density, pressure and temperature in Titan's atmosphere, from an altitude
of about 2000 km down to about 190-170 km, during the high-speed entry phase,
relies primarily on the data collected by HASI's 3-axis accelerometer. The
atmosphere's density profile, rho(z), is proportional to the acceleration
along the flight path -a_s, through the equation:
 rho(z) = - (2 m a_s) / (C_D A V_r^2)                                     (1)
The vehicle mass m, the aerodynamical drag coefficient C_D and Huygens' cross
sectional area (A) are constants known from ground tests. V_r = V_i + V_atm
where V_i is the Probe's velocity in the inertial frame, V_atm represents the
contributions of the wind and atmospheric corotation, and V_r is the vehicle
velocity relative to the ambient atmosphere.
 
 Descent phase
 -------------
Following the maximum deceleration near 270 km, the descent phase begins in
the stratosphere at 170 km altitude when the Huygens pilot chute is deployed
and the thermal shield jettisoned. HASI booms are deployed and the sensors are
directly exposed to the ambient atmospheric flow.
During the parachute descent, nominally beginning at 170 km, pressure and
temperature will be measured directly by pressure and temperature sensors with
access to the unperturbed field outside of Huygens' boundary layer. Both the
measured temperature and pressure, T_meas and p_meas, could need dynamic
corrections:
 T_corr = T_meas - (r V_r^2) / (2 c_p)                                     (2)
 p_corr = p_meas - (rho V_r^2) / 2                                         (3)
where c_p is the specific heat constant pressure, V_r^2/2c_p is the
temperature increment from conversion of the kinetic energy to thermal energy
in the gas flow approaching the sensor, and r is the recovery factor (related
to the fraction of thermal energy actually experienced by temperature sensors
in laboratory calibrations). This relation are valid considering a ideal gas,
for real gas refer to PPI calibration folder.
 
 
Sensor Overview
=============================
 
Accelerometers (ACC)
--------------------
The Accelerometer subsystem (ACC) is placed at the centre of mass of the
descent module of the Probe. It consists of one highly sensitive single axis
accelerometer (X-servo) and three piezoresistive accelometer (X, Y, Z piezo),
their conditioning electronics and two temperature sensors (Temp1 and Temp2)
used for thermal compensation. The X-servo accelerometer output is amplified
providing two channels (HIGH and LOW gain).
Each channel has a switchable range (fine and coarse resolution) which is set
autonomously (FINE range set at startup and swithched on COARSE prior
saturation or anyhow after Tdata (T0+10s)). X-servo selection is performed
autonomously by checking the measured value against a setable threshold.
7 channels and relevant sampling:
- Xservo LOW gain at 100 Hz
- Xservo HIGH gain at 100 Hz
- Xpiezo at  50 Hz
- Ypiezo at  50 Hz
- Zpiezo at  50 Hz
- Temp 1 (Tservo) at   1.5625 Hz
- Temp 2 (Tpiezo) at   1.5625 Hz
 
Values are arithmetically averaged to produce lower sampling rates.
 
Table 3. ACC characteristics and performance
----------------------------------------------------------------------------
X-axis servo accelerometer    (along Probe path)
 High resolution setting
  Range: 2-20 mg
  Resolution: 1-10 ug
 Low resolution setting
  Range: 1.85-18.5 g
  Resolution: 0.9-9 mg
  Relative accuracy: 1 % of full scale
 
X/Y/Z-axis piezoresistive accelerometers
  Range: +- 20 g
  Resolution: +- 15 mg
----------------------------------------------------------------------------
 
Temperature sensors (TEM)
-------------------------
HASI temperature sensors are two redundant dual element platinum resistance
thermometers (TEM) mounted on the STUB in order to be appropriatelly located
and oriented with respect to the gas flow during the measurements.
Each TEM has a primary sensor (fine, F) directly exposed to the air flow and
a secondary sensor (coarse, C) which is annealed in glass of the supporting
frame and is used as spare unit in case of damage on the primary sensor.
Temperature measurement is performed by monitoring the resistance of TEM
sensors; the resistance of each TEM sensor is measured by a four wire
configuration.
Temperature measurements can be performed in HIGH and LOW resolution range
(60-110K for HIGH and 100-330K for LOW resolution ) by switching HIGH and
LOW gain channel. The range selection is performed by HASI S/W calculating
the rough resistor value and comparing against a setable threshold.
4 sensors:
- TEM1 fine (F1)
- TEM1 coarse (C1)
- TEM2 fine (F2)
- TEM2 coarse (C2)
 
Table 4. TEM characteristics and performance
----------------------------------------------------------------------------
Range (60-110K)
  Resolution                    0.02K
  FINE absolute accuracy        0.5K
  COARSE absolute accuracy      0.8K
 
Range (90-330K)
  Resolution                    0.07K
  FINE absolute accuracy        2K
  COARSE absolute accuracy      2K
----------------------------------------------------------------------------
 
 
Pressure Profile Instrument (PPI)
---------------------------------
The Pressure Profile Instrument includes sensors for measuring the atmospheric
pressure during descent and surface phase. The atmospheric flow is conveyed
through a Kiel probe, mounted on the STUB tip, inside the DPU where the
transducers and related electronics are located. The PPI sensors are 6
reference sensors and 18 transducers. The transducers are silicon capacitive
absolute pressure sensors (Barocap, 8), temperature capacitive sensors
(Thermocap, 3) and constant sensors (high stability capacitor, 7, used for
housekeeping) The sensors are organized in three blocks each having eight
frequency output channels.
The three blocks corresponds to different pressure sensibility range:
  low pressure        0-400 hPa     block 3, sensor P3.7 , P3.8 and T3.3
  medium pressure     0-1200 hPa    block 1, sensor P1.1, P1.6 , P1.8 and T1.3
  high pressure       0-1600 hPa  block2, sensor P2.1, P2.7, P2.8 p and T2.3
 
In total there are:
24 frequency channels:
1.1P          2.1P          3.1C
1.2R          2.2R          3.2R
1.3T          2.3T          3.3T
1.4C          2.4C          3.4C
1.5R          2.5R          3.5R
1.6P          2.6C          3.7P
1.7C          2.7P          3.8P
1.8P          2.8P
 
and 2 housekeeping voltages (HKV0 and HKV1 for pressure measurement
reconstruction).
 
Table 5. PPI characteristics and performance
----------------------------------------------------------------------------
Range: 0-1600 hPa
Resolution: 0.01hPa
Absolute accuracy: 1%
----------------------------------------------------------------------------
 
 
Permittivity, Wave and Altimetry (PWA) sensors
----------------------------------------------
The PWA sensors are 6 electrodes and an acoustic transducer. The electrodes
placed on the deployable booms (DBS) form a quadrupolar probe consisting of a
pair of mutual impedance transmitter (TX) and receiver (RX) to measure
atmospheric electric conductivity due to free electrons and detect wave
emission. The pair of electrodes placed at the tip of the booms are relaxation
probe for meauring ion electric conductivity and quasi-static electric field.
The acoustic sensor (ACU) is mounted on the STUB detect sound waves to
correlate with acoustic noise, turbulence and meteorological events.
The radar return signals of the Huygens Proximity Sensor, containing
information on surface properties and altitude, are processed also by HASI.
The radar signal is converted to 10KHz and filtered by the Radar Altimeter
Extension (RAE) board and passed to the PWA A/D converter and signal
processor. The radar input signals in HASI/PWA are the blanking signal and the
analogue intermediate frequency signal (echo signal). The PWA signal processor
performs FFT, digital integration and data packetising and controls the data
acquisition. The spectrum and altitude information of the radar return signal
are added to the HASI data stream.
Data products:
PWA-ACU
PWA-RP
PWA-MI
PWA-ACDC
PWA-RAE
 
 
The mutual impedance is measured by applying sine wave pulses of 0.2-20 V at
fixed frequencies (from 100 Hz up to 6 kHz after impact) on two TX electrodes.
The modulus and phase of the impedance are computed after analysis of the RX
electrodes' signal (with intelligent choice of TX driver range and RX
amplifier gain). The signal received by the dipoles is sampled at a rate of
12800 Hz; a statistical analysis and a Fast Fourier Transform can be performed
every 20 ms, yielding a 50 Hz spectral resolution in a 6.4 kHz bandwidth. The
receiving dipole and signal analyser will detect wave emissions in the
atmosphere. It is also intended to detect quasi-static electric fields with
amplitudes of up to several V/m using the two relaxation sensors.
The conductivity due to positive and possibly negative ions will be measured
in parallel with the relaxation sensors. Potentials will be applied between
the descent module and the sensors for 1 s every minute by closing switches;
the sensors and the vehicle return independently to their equilibrium
potentials when the switches open.
Measuring these potentials as a function of time (64 words in 59 s) will
confirm or disprove the existence of free electrons and yield the ion
conductivity. The relaxation electrodes are grounded at the end of the
measurement sequence. A microphone is mounted on the STUB for detecting
acoustic events.
 
 
Table 6. PWA characteristics and performance
----------------------------------------------------------------------------
Mutual Impedance
 Electron conductivities, ground conductivity
  Conductivity range:          10^-11 - 10^-7 /Ohm m
  Relative permittivity range: 1-100
  Time resolution:             2-3 s
 
AC field measurement
 Natural wave phenomena, e.g. lightning
Threshold:                   > 2 uV/m/Hz
  Dynamic range:               80 dB
  Frequency range:             0-10 kHz
 
DC field
 Atmospheric electricity, Schumann resonances
  Threshold:                   1 mV/m
  Range:                       1 mV/m - 30 V/m
  Dynamic range:               16 bit
 
Relaxation probe
 Ion-electron conductivities
  Conductivity range:          10^-15 - 10^-11 /Ohm m
  Accuracy time constant:      0.1 s
  Time resolution:             1 min
 
Acoustic
 Natural acoustic phenomena, e.g. thunder, rain, hail, surface waves
  Threshold:                   10 mPa
  Dynamic range:               90 dB
  Frequency range:             0-6 kHz
  Resolution, amplitude:       3%
              frequency:       50 Hz
              time:            1 s
----------------------------------------------------------------------------
Altimetry
 Surface structure, roughness
  Maximum range:               60 km
  Range resolution:            40 m @ 24 km
  S0 minimum:                  -10 dB @ 60 km
  S0 accuracy:                 1.5 dB
----------------------------------------------------------------------------
 
 
Operational modes and measurements
==================================
 
HASI mission phases
--------------------
ENTRY
from higher than 1270 km (~1900 km) to 170 km;
Tacc=Probe-ON +21min 30s to T0 (expected at 28 min)
 
DESCENT
from Tdata=T0+10s to surface
DESCENT 1st state from Tdata to TdataH=T0+2min 30s
DESCENT 2nd state from TdataH to Tradar=T0+32min
DESCENT 3rd state from Tradar to last km (~T0+2h12min)
IMPACT state from last km to surface (~T0+2h14min)
SURFACE state from ACC impact detection to link loss
 
Table 7. HASI timeline, probe events and related dynamic conditions during
mission (expected)
------------------------------------------------------------------------------
         Time    Mission     altitude  Vertical accel.
         (min)   time         (km)     velocity (m/s2)
                                         (m/s)
COAST  T0-22d    5mn                        Tsep Probe separation from Orbiter
        T0-18 mn                         Tp Probe power-up and CDMS activities
        T0-10 mn                                   Thasi HASI ON (17:46 preT0)
        T0-8 mn ~1900                                 Tacc  ACC sampling start
ENTRY   0.03    ~T0-5 mn       1260.8    6145.28   0.61                 Tentry
         2.7                   401.082   6114.32   11.031
         3.37                  229.334   3404.9    120.78              max acc
        4.13                   170.24    638.54    16.886
        4.42                   162.648   429.37    8.3181
DESCENT                                                    end of entry phase
        0.03                   162.063   307.91    24.196    T0
                                              descent device deployment begins
               T0+00.25s                    Pilot chute deployed and inflation
               T0+2.5s                                     Back cover release,
                                             main chute deployment & inflation
               T0+10s         157.3     192.6    12.363  Tdata, T&p sampling;
        0.5    T0+32.5s       157.452    99.63    2.469  Front shield jettison
        1      T0+1mn                                      DISR cover jettison
        1.05                   154.904    67.42    0.598       Td1
                                                1st BOOM release attempt start
        1.55                   153.002    62.06    0.255       Td1w
                                                1st BOOM release attempt end
        2.2                    150.658    59.72    0.113       Td2
                                                2nd BOOM release attempt start
        2.5                    149.775    59.08    0.086       TdataH
                                                PWA sampling (mode A) start
                T0+15mn        114.733    36.61    0.02  Main chute jettison,
                                             stabiliser deployment & inflation
        25.78                   74.906    44.58    0.049
        32.12                   61.372    27.49    0.028       Tradar
                                                    RADAR sampling, PWA mode C
        48.45                   42.103    14.71    0.007       tropopause
        75.12                   24.262    8.76     0.002       Tpmed
                                                       Medium p sampling start
        105.1                   11.034    6.29     0.001       Tphigh
                                                       High p sampling start
                                                                  PWA mode D
        134.5                   1.025     5.22         0  last km  IMPACT mode
SURFACE 138.1                   0         0            0       Tloss
                                                           Loss of radio link
 
 
Table 7.B HASI timeline, probe events and related altitude during mission at
Titan (as measured by HASI)
------------------------------------------------------------------------------
UTC         Mission Time  Mission Time          Event          h [km]
             (SPC Time)      [ms]
                                                HASI ON
9:01:17.372  4:19:44.500  15584500          first ACC pck    2787.013 T0-9min
                                            (after resets)
9:07:46.128  4:26:13.000  15973000        ACC range coarse   639.142
9:09:07.407  4:27:34.535  16054535             max acc      240.941 T0-73.340s
9:10:13.997  4:28:41.500  16121500               S0         162.420
                                 (CASU detection 10 m/s2)  ACCXservo=9.645m/s2
9:10:20.747  4:28:47.875  16127875      T0 (PDD firing)   160.098 T0=S0+6.375s
9:10:20.997  0:00:00.250     250     Pilot chute deployment   159.995 T0+0.25s
                                                & inflation
9:10:22.032  0:00:01.285    1285      Pilot chute ACC peak   159.888 T0+1.285s
9:10:23.247  0:00:02.500    2500       Back cover release,   159.745 T0+2.5s
                                main chute deploym. & inflation
9:10:25.232  0:00:04.485    4485       Main chute ACC peak   159.531 T0+4.485s
9:10:30.747  0:00:10.000   10000           Tdata             158.904 T0+10s
9:10:53.247  0:00:32.500   32500      frontshield jettison   156.421 T0+32.5s
9:11:20.747  0:01:00.000   60000 1st BOOM release attempt start  153.361 Td1
                                           MCA sequence
9:11:22.747  0:01:02.750   62750   1st BOOM release attempt end  153.040 Td1w
9:11:22.747  0:02:20.000  140000 2nd BOOM release attempt start  147.106 Td2
9:12:40.747  0:02:22.750  142750   2nd BOOM release attempt end  146.960
9:12:50.747  0:02:30:000  150000          PWA mode A  146.559 TdataH=T0+2.5min
9:25:20.747  0:15:00.000  900000      Main chute jettison,   112.893 T0+15min
                             stabiliser deployment & inflation
9:42:50.747 0:32:30.00 1950000 RADAR sampling,PWA mode C 60.992 Trad=T0+32.5m
10:25:27.747 1:15:07.200 4507200   PPI Medium p mode   26.050 Tpmed=T0+1:15:00
                                     (session B)
10.55.26.747 1:45:06.000 6306000    PPI High p mode   13.301 Tphigh=T0+1:45:00
                                     (session C)
11:16:22.998 2:05:57.749 7757749       PWA mode D           5.286   DDB 7 km*
11:34:56.997 2:24:36.250 8676250       last km              0.872   last km*
11:38:10.578 2:27:49.840 8869840     Impact detection        0       Timpact
12:10:20.747 3.00.00.000  10800000   autoreset/ last HASI data       SW reset
*correspondent UTC time derived from Huygens HK parameter S2013E_H3B
 
 
 ACC modes
 --------------------
For the acceleration there are two types of data: 'raw' data and statistics
data (obtained from average of 100 Hz sampling, on-board processing).
Channels readouts are summed in order to get the following sampling rate:
 
ACC Xservo       3.125 Hz        in ENTRY; from Tacc till T0+10 s
                 4.167 Hz         till T0+32 min
                 1.754 Hz         last km (~132 min) Impact detection
                                   and in Surface state
 
ACC X, Y, Z piezo   1.6129 Hz     in ENTRY and last km
                                  and in Surface state
Statistics         0.1 Hz          always, except in impact detection
 
ACC Servo & piezo Temperature 0.097 Hz  always, except in impact detection
 
Impact trace        (0.5 s before & 5.5 s after impact)
X piezo               200 Hz
Y piezo               200 Hz            transmitted after Timpact
Z piezo               200 Hz
 
p.s. NO ACC data are transmitted during impact phase
 
 
 TEM modes
 --------------------
All 4 TEM sensors are sampled every 5 s. The measurement sequence is the
following:
F1,C1, F2, C2.
Sampling rate:
1 Temperature point every 1.25s  (0.8 Hz)
but same sensor sampled every 5s (0.2Hz)
IMPACT STATE  only F1 and F2 are sampled
        1 Temperature point every 1.25s         (0.8 Hz)
        but same sensor sampled every 2.5s      (0.4Hz)
 
 
 PPI modes
 --------------------
DDB time   HASI time   PPI normal session
T0+10s     Tdata        A   Low pressure
T0+75'     Tpmed        B   Medium p sampling start
T0+105'    Tphigh       C   High p sampling start
 
Two pressure values every 2.3 s are produced.
PPI channels polling tables for normal and health check session are reported
in PPI calibration report.
 
 
 PWA modes
 --------------------
Phase       DDB time   HASI time  altitude range   PWA mode   measurements
Descent_2   T0+2.5'    Tdatah     ~60 km<h<160 km   mode A    AC_DC, MI, RP
Descent_3   T0+32'     Tradar       7 km<h<~60km    mode C    AC_DC&ACU, MI,
                                                              RAE, RP
Descent_3                           1 km<h<7km      mode D    AC_DC&ACU, MI,
                                                              RAE, RP
                                                       (no RP relay switching)
Impact                 last km       0 m<h<1km      mode D    AC_DC&ACU, MI,
                                                              RAE, RP
                                                       (no RP relay switching)
Surface                Timpact          0 m         mode G    AC_DC&ACU, MI
 
 
 HASI modes of operation (summary)
 -----------------------------------
Phase       ENTRY                DESCENT              IMPACT    SURFACE
Mode          -          1           2          3       -          -
   THASI  TACC     Tdata      TdataH    Tradar     1 km    Impact    Tloss
   17:46  21:30    00:10      02:30     32:00             detection
 
_______^____________|_________^__________^___|___|___^__________^___________^
DDBL   |         T0          |        |   Tmid Thigh   |      |           |
Time   |         Reset       |        | 1:15:00 1:45:00|      |           |
Altitude|        00:00
------------------------------------------------------------------------------
ACC   |3.125 Hz    |       4.167 Hz   |    1.754 Hz    |      |  1.754 Hz |
XSERVO|  0.1 Hz    |         0.1 Hz   |      0.1 Hz    |      |    0.1 Hz |
statistics
------|------------|-----------------------------------|------|-----------|
ACC   |1.6129Hz    |                                   |     |200Hz|      |
PIEZO |  0.1 Hz    |           0.1 Hz                  |     |     |0.1 Hz|
statistics
------|------------|-----------------------------------|------|-----------|
      |            |                                   |      |           |
TEM   |            |           0.8 Hz                  | 0.4 Hz |  0.8 Hz |
      |            |     0.2 Hz same sensor            |(0.2 Hz)| (0.2 Hz)|
------|------------|-----------------------------------|--------|---------|
      |            |                     |     |                          |
PPI   |            |       A             |  B  |            C             |
      |            |2 pressure every 2.3s|     |                          |
------|---------------|---------------|--------------|--------|-----------|
      |               |               |              |        |           |
PWA   |               |     Mode A    |     Mode C   | Mode D |  Mode G   |
------|---------------|---------------|--------------|--------|-----------|
 
ACC statistics average on samples @400 Hz
ACC PIEZO special buffer at 200 Hz, from Timpact-0.5s to Timpact+5.5s
ACC no data transmitted during impact phase (except for impact detection
trace)
TEM F1, C1, F2, C2 (F: fine, C: coarse); impact phase F1, F2 (only fine)
PPI measurement sequence provide 2 pressure point every 2.3s A: low pressure
range,
B: medium pressure range, C: high pressure
 
 
Telemetry
=========
 
Two telemetry channels carry HASI's data to Earth via the Orbiter. A double
data packet is transferred to HASI-DPU every 2 s. Each double packet consists
of 2x112 byte data. In total, about 10000 data packets will be transmitted
from HASI during the Probe's mission.
 
HASI S/W provides two independent telemetry queues: one dedicated to
each Huygens Command and Data Management Unit (CDMU). HASI handles TM
packets queues by the internal operating system, that allocate
dynamically the memory for the packets. The memory remains allocated
until the tM packet is discarded from the queue (TM queue capability
of about 130 packets).
Few seconds (about 132 s) after HASI power ON HASI telemetry starts
(both on CDMU-A and CDMU-B). Acquired data are transmitted redundant
on both CDMUs (with the exception for PWA science data, same packet
content is transmitted on both CDMU TM line, but only one chain is
considered valid). Till TdataH (T0+2.5 min) HASI data are trasmitted,
but remains stored in the memory. After TdataH (when the link between
Huygens probe and Cassini should be safelly established, stored
packets are retransmitted as original).
During entry phase, when HASI is the only operative instrument, in
order to cope with the  higher CDMS polling rate also copies of the
packets stored in the TM queues are re-transmitted.
 
HASI presents to the Huygens Probe Command and Data Management System
(CDMS) about 8-9 TM packets for CDMS cycle (16 s).
Each HASI telemetry packets is composed of a header containing packet
identification, sequence count and lenght. The first data contained
in the packets data field corresponds to the time stamp relevant to
the HASI mission time when the first value has been measured. The time
relevant to the single values contained within the data field is
computed according to their position (sensor sampling and packet
filling rate).Time relevant to each data value contained in the
telemetry packet is computed starting from the timestamp, according to
their position within the packets and from the sampling rate (constant).
 
 
HASI marks each telemetry packets with a timestamp relevant to the DDB time
when the first source data contained in the packet data field is created.
Timestamp resolution is a BCP count (125 ms); the resolution on this time
value is 1 LSB = 1ms.
 

        