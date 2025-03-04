
 
  Instrument Host Overview
  ========================
    For most Voyager experiments, data were collected by
    instruments on the spacecraft.  Those data were then relayed
    via the telemetry system to stations of the NASA Deep Space
    Network (DSN) on Earth.  Radio Science experiments (such as
    radio occultations) required that DSN hardware also participate
    in data acquisition.  The following sections provide an
    overview first of the spacecraft and then of the DSN ground
    system as both supported Voyager science activities.
 
 
  Instrument Host Overview - Spacecraft
  =====================================
    The Voyager 1 and Voyager 2 spacecraft were identical and were
    built by the Jet Propulsion Laboratory (JPL).  With a mass of
    815 kilograms, each carried its own power, propulsion, and
    communications systems and its own science instruments.
    Spacecraft electrical power was supplied by Radioisotope
    Thermoelectric Generators (RTGs) that produced about 400 watts.
    The Attitude and Articulation Control Subsystem (AACS),
    Computer Command Subsystem (CCS), and Flight Data Subsystem
    (FDS) managed spacecraft operations.  Thrusters and gyros
    provided physical propulsion and attitude control.
    Communications between the spacecraft and Earth were carried
    out via a high-gain radio antenna using both S-band and X-band
    frequencies at data rates as high as 115.2 kilobits per second.
    A Digital Tape Recorder (DTR) could save up to 500 million bits
    when no Earth station was available for real-time data
    transmission.  Voyager control systems could record sets of
    several thousand instructions, allowing autonomous operation
    for days or weeks at a time.  More information on the
    spacecraft can be found in [MORRISON1982], [KOHLHASE1989], and
    [JPLPD618-128].
 
    The spacecraft itself was built around its 'bus' -- a decagonal
    prism, which was about 2 meters in diameter and about 60 cm
    deep.  Each of the ten sides of the bus was associated with a
    'bay' containing engineering systems or science instrument
    electronics.  Bay 1, for example, contained the radio
    transmitter.  The High-Gain Antenna (HGA) was mounted to the
    end of the bus facing Earth.  The bays were numbered 1 through
    10 in a clockwise direction when viewed from Earth.  Extending
    away from the bus were three booms: a science boom and scan
    platform to which most instruments were mounted, a magnetometer
    boom, and a boom to which the RTGs were mounted.
 
 
    Spacecraft Coordinate System
    ----------------------------
      The centerline of the bus was the roll axis of the
      spacecraft; it also served as the z-axis of the spacecraft
      coordinate system with the high-gain antenna (HGA) boresight
      defining the negative z-direction.  The HGA boresight was
      also defined as cone angle 0 degrees and as azimuth 180
      degrees, elevation 7 degrees.  The science boom, supporting
      the scan platform, extended in the general direction of
      positive y; this boom was also defined as being at cone angle
      90 degrees, clock angle 215 degrees and at azimuth 180
      degrees, elevation 97 degrees.  A boom supporting the RTGs
      was mounted on the bus in generally the negative y direction.
      The positive y-axis (yaw axis) of the spacecraft coordinate
      system passed through Bay 3; the negative y-axis passed
      through Bay 8.  The x-axis (pitch axis) was in a direction
      which defined a right-handed rectangular coordinate system.
      The positive x-axis was at cone angle 90 degrees, clock angle
      305 degrees (azimuth 270 degrees, elevation 90 degrees).
 
 
    Telecommunications Subsystem
    ----------------------------
      The high-gain antenna was mounted to the spacecraft bus,
      pointing in the negative z-direction.  It was a parabolic
      reflector 3.7 meters in diameter with a feed that permitted
      simultaneous operation at both S-band (13 cm wavelength) and
      X-band (3.6 cm).  The half-power full-width of the antenna
      beam was 0.6 degrees at X-band and 2.3 degrees at S-band.
      The Low-Gain Antenna (LGA) was mounted on the feed structure
      of the HGA and radiated approximately uniformly over the
      hemisphere into which the HGA pointed.
 
      The Telecommunications Subsystem (TCS) electronics included a
      redundant pair of transponders, meaning that a failed
      functional unit in one transponder could be bypassed by
      swapping to the redundant unit.  The TCS could transmit
      science data on the X-band link at rates between 4.8 and
      115.2 kilobits per second and engineering data on the S-band
      link at 40 bits per second.  It could receive instructions
      sent (uplinked) from ground stations at a rate of 16 bits per
      second.  Commands were extracted from the uplink signal by
      the Command Detector Unit (CDU) and were then sent to the
      Computer Command Subsystem (CCS).
 
      Spacecraft receivers were designed to lock to the uplink
      signal.  Without locking, Doppler effects -- resulting from
      relative motion of the spacecraft and ground station -- could
      result in loss of the radio link as the frequency of the
      received signal drifted.
 
 
    Attitude and Articulation Control Subsystem
    -------------------------------------------
      The Attitude and Articulation Control Subsystem (AACS)
      provided three-axis-stabilized control so that the spacecraft
      could maintain a fixed orientation in space.  Attitude
      control was accomplished using gyroscopes or by celestial
      reference.  The AACS also controlled motion of the scan
      platform, upon which the four 'remote sensing' instruments
      were mounted.
 
      Gyro control was used in special situations (e.g., trajectory
      corrections and solar conjunctions) for periods of up to
      several days.  The inertial reference unit operated with
      tuned rotor gyros having an uncalibrated drift rate of less
      than 0.5 degrees per hour and a calibrated drift rate of less
      than 0.05 degrees per hour.
 
      Celestial control was based on viewing the Sun (through a
      sensor mounted on the high-gain antenna) and a single bright
      star (through a second sensor named the Canopus Star Tracker,
      after the star used most frequently as the reference).  When
      the spacecraft attitude drifted by more than a small amount
      from the reference objects, the AACS fired small thrusters
      which returned the spacecraft to the proper orientation.  The
      Sun sensor was an optical potentiometer with a cadmium
      sulfide detector; its error was less than 0.01 degrees and
      its limit cycle was +/-0.05 degrees.  The Canopus Star
      Tracker was an image dissector tube with a cesium detector,
      an error of less than 0.01 degree, and a limit cycle of
      +/-0.05 degrees.
 
      Redundant (backup) sun sensors, star trackers, and computers
      were also part of the AACS.  The non-redundant portions of
      the AACS were those controlling the pointing of the
      instrument scan platform, which had two degrees of freedom --
      elevation and azimuth (see below).
 
 
    Propulsion Subsystem
    --------------------
      The propulsion system was part of the AACS and consisted of
      16 hydrazine thrusters.  These thrusters were also used to
      control the three-axis stabilization of the spacecraft.  Two
      thrusters on opposite sides of the spacecraft were used to
      perform positive roll turns around the +Z axis.  Two
      oppositely pointed thrusters were used to perform negative
      roll turns.  One thruster was used to perform positive yaw
      turns (around the +Y axis) and one was used to perform
      negative yaw turns.  One thruster was used to perform
      positive pitch turns (around the +X axis) and one was used to
      perform negative pitch turns.  A backup hydrazine system was
      connected to a redundant set of eight thrusters.
 
 
    Power Subsystem
    ---------------
      Spacecraft power was provided by three Radioisotope
      Thermoelectric Generators (RTGs) mounted on a boom in the
      negative y-direction.  At Launch the three RTGs converted
      7000 watts of heat into 475 watts of electrical power.  RTG
      electrical output decreased by about 7 watts per year because
      of decay of the plutonium dioxide fissionable material and
      degradation of the silicon-germanium thermocouples.  The
      difference between available electrical power and the power
      required to operate spacecraft subsystems was called the
      'power margin.' Voyager Project guidelines required a power
      margin of at least 12 watts to guard against electrical
      transients and miscalculations; excess electrical power was
      dissipated as heat in a shunt radiator.
 
 
    Data Storage Subsystem
    ----------------------
      The Digital Tape Recorder (DTR) was used to store data when
      real-time communications with Earth were either not possible
      or not scheduled.  The DTR recorded data on eight tracks;
      rates were 115.2 kilobits per second (record only), 21.6
      kilobits per second (playback only), and 7.2 kilobits per
      second (record and playback).  Capacity of each track was 12
      images or equivalent.
 
 
    Computer Command Subsystem
    --------------------------
      The Computer Command Subsystem (CCS) consisted of two
      identical computer processors, their software algorithms, and
      associated electronic hardware.  The CCS was the central
      controller of the spacecraft.  During most of the Voyager
      mission the two CCS computers on each spacecraft were used
      non-redundantly to increase the command and processing
      capability of the spacecraft.
 
 
    Flight Data Subsystem
    ---------------------
      The Flight Data Subsystem (FDS) consisted of two
      reprogrammable digital computers and associated encoding
      hardware.  The FDS collected and formatted science and
      engineering telemetry data for transmission to Earth.
      Convolutional coding was imposed on all data transmitted from
      the spacecraft.  Additionally, both Golay encoding and Reed-
      Solomon encoding were available for use on spacecraft data.
      Data compression was also performed within the FDS.
 
 
    Science Boom
    ------------
      The Voyager science instrument boom carried the plasma
      detector, cosmic ray detector and the low energy charged
      particle detector.  The scan platform was mounted on the
      science boom.
 
 
    Scan Platform
    -------------
      Four instruments (Imaging, PhotoPolarimeter, Infra-Red
      Interferometric Spectrometer, and Ultra Violet Spectrometer)
      were mounted on the scan platform, which could be slewed by
      motors and gears (called actuators).  Elevation of the scan
      platform was measured with respect to a plane slightly offset
      (by approximately 7 degrees) from the spacecraft x-z plane;
      the spacecraft positive y-axis was at 97 degrees elevation
      (see Spacecraft Coordinate System above).  The scan platform
      azimuth reference was defined by the y-z plane, with zero
      azimuth being in the negative z-direction.  Drive actuators
      were controlled by fine feedback potentiometers; the error of
      each was less than 0.03 degrees, and the final pointing error
      of the scan platform was nominally +/-0.1 degrees (2-sigma
      per axis).  Subsequent analysis by the Navigation and
      Ancillary Information Facility (NAIF) at JPL has shown larger
      errors during at least the Jupiter and Saturn encounters.
      High rate slews were at 1 deg/sec, medium rate slews were at
      0.33 deg/sec, and low rate slews were at 0.08 deg/sec.
 
 
    Magnetometer Boom
    -----------------
      Two low-field magnetometers were mounted on a 13-meter-long
      boom that was unfurled and extended automatically after
      Launch.  One low-field magnetometer was mounted at the end of
      the boom and a second was mounted about 3 meters from the
      end.  Two high-field magnetometers were mounted at the base
      of the boom.
 
 
    Science Sensors
    ---------------
      Each Voyager spacecraft carried instrumentation to support
      eleven science investigations.  Target body (or remote
      sensing) instruments included:
 
      (1) Imaging Science Subsystem (ISS)
      (2) Photopolarimeter Subsystem (PPS)
      (3) Infrared Radiometer Interferometer Spectrometer (IRIS)
      (4) Ultraviolet Spectrometer (UVS)
 
      Fields, waves, and particles (or in situ) sensors included:
 
      (1) Plasma Subsystem (PLS)
      (2) Low-Energy Charged Particle (LECP)
      (3) Cosmic-Ray Subsystem (CRS)
      (4) Magnetic Fields (MAG)
      (5) Plasma Wave Subsystem (PWS)
      (6) Planetary Radio Astronomy (PRA)
 
      The Radio Science (RSS) investigation was carried out using
      the on-board and ground elements of the Telecommunications
      Subsystem (TCS).  More information on instrumentation for
      each of the science investigations can be found elsewhere.
 
 
  Instrument Host Overview - DSN
  ==============================
    Voyager Radio Science investigations utilized instrumentation
    with elements on both the spacecraft and at ground stations of
    the NASA Deep Space Network (DSN).  Much of this was shared
    equipment, used for routine telecommunications as well as for
    Radio Science.
 
    The DSN is a telecommunications facility managed by the Jet
    Propulsion Laboratory of the California Institute of Technology
    for NASA.  The primary function of the DSN is to provide
    two-way communications between the Earth and spacecraft
    exploring the solar system.  To carry out this function the DSN
    is equipped with high-power transmitters, low-noise amplifiers
    and receivers, and appropriate monitoring and control systems.
 
    During the Voyager era the DSN consisted of three complexes
    situated at approximately equally spaced longitudinal intervals
    around the globe at Goldstone (near Barstow, California),
    Robledo (near Madrid, Spain), and Tidbinbilla (near Canberra,
    Australia).  Two of the complexes are located in the northern
    hemisphere while the third is in the southern hemisphere.
 
    The network comprised several subnets, each of which included
    one antenna at each complex.  The subnets were defined
    according to the properties of their respective antennas.  Over
    the course of the Voyager Mission, those antennas were expanded
    and improved.  Nominal dimensions at the end (and beginning) of
    the Voyager Mission were: 70-m diameter (initially 64-m),
    standard 34-m diameter (initially 26-m), and high-efficiency
    34-m diameter (did not exist at beginning of Voyager).
 
    Additional ground equipment was provided by the Commonwealth
    Scientific and Industrial Research Organization (CSIRO) in
    Australia, the Institute of Space and Astronautical Science
    (ISAS) in Japan, and the National Radio Astronomy Observatory
    (NRAO) in the United States.  For the Voyager 2 encounters with
    Uranus and Neptune, the CSIRO 64-m diameter radio astronomy
    antenna near Parkes (Australia) was included in the receiving
    system for both telemetry and Radio Science.  For the Voyager 2
    encounter with Neptune, the ISAS 64-m diameter antenna near
    Usuda (Japan) was added for Radio Science and the NRAO Very
    Large Array (VLA) near Socorro (New Mexico) was added for
    telemetry.  The VLA consisted of 27 25-m antennas.  Parkes,
    Usuda, and the VLA were integrated with the permanent stations
    at Goldstone, Robledo, and Tidbinbilla by DSN personnel.
 
 
  Acronyms and Abbreviations
  ==========================
    AACS       Attitude and Articulation Control Subsystem
    CCS        Computer Command Subsystem
    CDU        Command Detector Unit
    CRS        Cosmic Ray (investigation) Subsystem
    CSIRO      Commonwealth Scientific and Industrial Research
               Organization
    DSN        Deep Space Network
    DTR        Digital Tape Recorder
    FDS        Flight Data Subsystem
    HGA        High-Gain Antenna
    IRIS       Infra-Red Interferometric Spectrometer
    ISAS       Institute for Space and Astronautical Science
    ISS        Imaging Science Subsystem
    JPL        Jet Propulsion Laboratory
    kbps       kilobits per second
    LECP       Low-Energy Charged Particle (investigation subsystem)
    LGA        Low-Gain Antenna
    MAG        Magnetometer (subsystem)
    NAIF       Navigation and Ancillary Information Facility
    NASA       National Aeronautics and Space Administration
    NRAO       National Radio Astronomy Observatory
    PLS        Plasma (science investigation) Subsystem
    PPS        PhotoPolarimeter Subsystem
    PRA        Planetary Radio Astronomy (investigation subsystem)
    PWS        Plasma Wave (investigation) Subsystem
    RSS        Radio Science Subsystem
    RTG        Radioisotopic Thermoelectric Generator
    TCS        TeleCommunications Subsystem
    UVS        Ultra-Violet Spectrometer
    VLA        Very Large Array

        