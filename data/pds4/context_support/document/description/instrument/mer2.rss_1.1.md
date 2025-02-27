
 
  Instrument Overview
  ===================
    The Mars Exploration Rover (MER) mission includes two spacecraft,
    Spirit (MER-2) and Opportunity (MER-1).  The MER Radio Science
    data consist of measurements of the Doppler shift of the rover
    radio signal as measured by the NASA Deep Space Network (DSN) and
    by the Mars Odyssey orbiter (ODY). The primary purpose of all
    equipment was collection of telemetry from the rovers, with
    Doppler measurements made for rover position determination as
    required and on a best efforts basis to support Radio Science.  The
    performance and calibration of both the spacecraft and tracking
    stations directly affected the radio science data accuracy, and
    they played a major role in determining the quality of the results.
    The MER part of the radio science instrument is described
    immediately below; that is followed by a description of the
    relevant ODY relay radio system and a description of the DSN
    (ground) part of the instrument.
 
 
  Instrument Overview - MER Spacecraft (Rover X-band)
  ===================================================
    For communications with Earth, the rovers include an X-band radio
    system, which receives signals sent from Earth tracking stations at
    a frequency near 7.2 GHz, and transmits to Earth at a frequency
    near 8.4 GHz. The X-band radio system includes several antennas on
    various parts of the spacecraft to support different parts of the
    mission. For surface operations, the primary antenna is a High Gain
    Antenna (HGA) which must be accurately pointed at Earth to
    communicate with Earth tracking stations. A low-gain antenna (LGA)
    was also available in case of problems pointing the HGA. All useful
    Radio Science data were taken with the HGA. [JPL-D21239]
 
    The Earth tracking stations measure the frequency of the radio
    signal received from the rovers as a measure of the relative
    velocity of the rovers with respect to Earth. In a simple one-way
    Doppler measurement, where the rover transmits and the Earth
    tracking station receives, the Doppler measurement accuracy is
    limited by the frequency stability of the reference oscillator on
    the rover, which is usually rather poor compared with the atomic
    frequency standards used in Earth tracking stations. In order to
    achieve high-quality Doppler measurements without requiring an
    atomic frequency standard on the rovers, the rover radio system is
    capable of operating in a mode (two-way or coherent) where  the
    frequency of the signal transmitted by the rover is made to be a
    fixed multiple of the frequency it receives from the Earth tracking
    station. In this case the measurement of the frequency shift made
    by the Earth tracking station is proportional to twice the
    line-of-sight velocity, with a Doppler shift occurring on both the
    Earth-to-rover signal and on the rover-to-Earth signal. The
    accuracy of such measurements is generally limited by dispersion
    introduced by electrons in the interplanetary medium (also referred
    to as solar plasma). A typical frequency measurement accuracy is
    ~ 5 mHz, corresponding to a line-of-sight velocity accuracy of
    about 0.1 mm/s, over a measurement integration time of 60 seconds.
 
    The electronics for generating the signals for transmission and
    for detection and lock to a received signal is designated the Radio
    Frequency Subsystem (RFS). The RFS includes a Solid-State Power
    Amplifier (SSPA), a Small-Deep-Space-Transponder (SDST), and
    coupler and switches for connections to the various antennas.
 
    Instrument Specifications - Spacecraft (Rover X-band)
    -----------------------------------------------------
      Instrument Id                  : RSSX
      Instrument Host Id             : MER2
      Instrument Name                : RADIO SCIENCE SUBSYSTEM
      Instrument Type                : RADIO SCIENCE
      Build Date                     : 2003
      Instrument Mass                : UNK
      Instrument Diameter, HGA       : 0.28 m
      Antenna type, HGA              : printed dipole array
      Transmit frequency             : 8439.444446 MHz
      Receive frequency              : 7183.118057 MHz
      Transmit gain                  : 24.8 dB
      Receive gain                   : 20.5 dB
      Polarization                   : Right-Hand Circular (RHCP)
      Transmit beamwidth             : 4.16 degree (2-sided 3 dB)
      Receive beamwidth              : 5.0 degree (2-sided 3-dB)
      Transmit power (SSPA)          : 5 W
      Instrument Length              : UNK
      Instrument Width               : UNK
      Instrument Height              : UNK
      Instrument Manufacturer Name   : General Dynamics/JPL
 
 
  Instrument Overview - Spacecraft (Rover UHF)
  ============================================
    Because of the large distance from Mars to Earth and the limited
    antenna size and power available to the rovers, the rovers include
    a radio system for transmitting data to spacecraft orbiting Mars.
    Because the orbiters generally have larger antennas and higher
    available power, they can relay a much larger amount of data to
    Earth than the rover could by transmitting directly to Earth.
    The local radio signal is at Ultra-High Frequency (UHF), with the
    rovers transmitting to the orbiters near 401 MHz, and the orbiters
    transmitting to the rovers near 437 MHz. As with the X-band radio
    system, the rovers are capable of operating in a mode (two-way or
    coherent) with the transmitted signal referenced to the signal
    received by the orbiter. The Mars Odyssey orbiter uses a simple
    system to measure the frequency of the signal received from the
    rovers compared with  the transmitted signal. The accuracy of the
    measurement is expected to be about 20 mHz, corresponding to a
    line-of-sight velocity accuracy of about 10 mm/s.
 
    The UHF radio subsystem consists of a low-gain antenna for
    transmission during entry, descent, and landing (EDL); a moderate
    gain antenna for use during rover surface operations; an antenna
    selection switch; a diplexer for separation of transmitted and
    received signals; and a transceiver for generation of transmission
    signals and detection of received signals. Because of the
    relatively long wavelength of UHF signals, the antenna used was a
    simple monopole with nominal nearly omni-directional pattern but
    with large deviations due to interactions with the rest of the
    rover structure. [JPL-D21240].
 
    The UHF radio receiver covers a fairly broad band around 437.1 MHz
    to be able to accept signals from a number of potential
    Mars-orbiting spacecraft; The MER 2 UHF transmit frequency is
    limited to a narrow channel to avoid potential interference with
    possible future nearby surface spacecraft.
 
    Instrument Specifications - Spacecraft (Rover UHF)
    --------------------------------------------------
      Instrument Id                  : RUHF
      Instrument Host Id             : MER2
      Instrument Name                : RADIO SCIENCE SUBSYSTEM
      Instrument Type                : RADIO SCIENCE
      Build Date                     : 2003
      Instrument Mass                : UNK
      Antenna type, RUHF             : monopole
      Transmit frequency             : 401.585625 MHz (to Odyssey)
      Receive frequency              : 437.1 MHz
      Transmit gain                  : 0 dB (nominal)
      Receive gain                   : 0 dB (Nominal) dB
      Polarization                   : Right-Hand Circular (RHCP)
      Transmit power (SSPA)          : 10 W
      Instrument Length              : UNK
      Instrument Width               : UNK
      Instrument Height              : UNK
      Instrument Manufacturer Name   : CMC Electronics/JPL
 
 
  Instrument Overview - Relay (Odyssey UHF)
  =========================================
    The Mars Odyssey orbiter includes a UHF radio system for  relay of
    commands from Earth to Mars surface vehicles and for relay of
    telemetry from surface vehicles to Earth. The Odyssey radio system
    is similar to the MER UHF and includes a nearly identical
    transceiver, with the transmission and reception frequencies
    reversed from those of the MER vehicles.
 
    The Odyssey UHF radio system transmits a signal near 437.1 MHz to
    vehicles on the surface of Mars, such as MER 1 and MER 2, and
    receives signals back near 401 MHz. The ODY UHF radio measures the
    difference in frequency between its on-board reference and received
    carrier frequencies which provides a (Doppler) measure of the
    relative velocity of the surface vehicle.
 
    The measurement is made by counting the (integer) number of zero-
    crossings of the difference frequency plus a the remaining fraction
    of a cycle over a 5 second time interval. The count cannot
    distinguish whether the received frequency is higher or lower than
    the reference frequency. Thus the measurement is the absolute
    value of the difference of the received frequency minus the
    reference frequency.
 
    For Mars Odyssey, the only available reference frequency is
    401.584625 MHz. The frequency of the signal transmitted by ODY is
    a fixed multiple, 160/147, of the reference frequency. For the MER
    radio operating in coherent mode, the received frequency is
    multiplied by a fixed multiple, 147/160, to generate the signal
    transmitted back to the orbiter. For example, when ODY is directly
    overhead the orbiter, the ODY reference frequency and the signal
    frequency received from MER are the same and the measurement is
    zero, indicating zero velocity of the rover relative to ODY along
    the line of sight to the orbiter. In general, the absolute value of
    the relative velocity along the line of sight is (to first order in
    v/c) v = c/2 *F(measurement)/F(reference) where c is the speed of
    light.
 
    Instrument Specifications - Relay (Odyssey UHF)
    -----------------------------------------------
      Instrument Id                  : UHFR
      Instrument Host Id             : ODY
      Instrument Name                : RADIO SCIENCE SUBSYSTEM
      Instrument Type                : RADIO SCIENCE
      Build Date                     : 2001
      Instrument Mass                : UNK
      Antenna type                   : UNK
      Transmit frequency             : 437.1 MHz
      Receive frequency              : 401.6 MHz
      Transmit gain                  : 0 dB (nominal)
      Receive gain                   : 0 dB (Nominal) dB
      Polarization                   : Right-Hand Circular (RHCP)
      Transmit power (SSPA)          : 10 W
      Instrument Length              : UNK
      Instrument Width               : UNK
      Instrument Height              : UNK
      Instrument Manufacturer Name   : CMC Electronics/JPL
 
 
  Instrument Overview - DSN
  =========================
    Three Deep Space Communications Complexes (DSCCs) (near
    Barstow, CA; Canberra, Australia; and Madrid, Spain) comprise
    the DSN tracking network.  Each complex is equipped with
    several antennas [including at least one each 70-m, 34-m High
    Efficiency (HEF), and 34-m Beam WaveGuide (BWG)], associated
    electronics, and operational systems.  Primary activity
    at each complex is radiation of commands to and reception of
    telemetry data from active spacecraft.  Transmission and
    reception is possible in several radio-frequency bands, the
    most common being S-band (nominally a frequency of 2100-2300 MHz
    or a wavelength of 14.2-13.0 cm) and X-band (7100-8500 MHz or
    4.2-3.5 cm).  Transmitter output powers of up to 400 kw are
    available.
 
    Ground stations have the ability to transmit coded and uncoded
    waveforms which can be echoed by distant spacecraft.  Analysis
    of the received coding allows navigators to determine the
    distance to the spacecraft; analysis of Doppler shift on the
    carrier signal allows estimation of the line-of-sight
    spacecraft velocity.  Range and Doppler measurements are used
    to calculate the spacecraft trajectory and to infer gravity
    fields of objects near the spacecraft.
 
    Ground stations can record spacecraft signals that have
    propagated through or been scattered from target media.
    Measurements of signal parameters after wave interactions with
    surfaces, atmospheres, rings, and plasmas are used to infer
    physical and electrical properties of the target.
 
    Principal investigators vary from experiment to experiment.
    See the corresponding section of the spacecraft instrument
    description or the data set description for specifics.
 
    The Deep Space Network is managed by the Jet Propulsion
    Laboratory of the California Institute of Technology for the
    U.S.  National Aeronautics and Space Administration.
    Specifications include:
 
    Instrument Id                  : RSS
    Instrument Host Id             : DSN
    Pi Pds User Id                 : N/A
    Instrument Name                : RADIO SCIENCE SUBSYSTEM
    Instrument Type                : RADIO SCIENCE
    Build Date                     : N/A
    Instrument Mass                : N/A
    Instrument Length              : N/A
    Instrument Width               : N/A
    Instrument Height              : N/A
    Instrument Manufacturer Name   : N/A
 
    For more information on the Deep Space Network and its use in
    radio science see reports by [ASMAR&RENZETTI1993],
    [ASMAR&HERRERA1993], and [ASMARETAL1995].  For design
    specifications on DSN subsystems see [DSN810-5].
 
 
    Subsystems - DSN
    ----------------
      The Deep Space Communications Complexes (DSCCs) are an integral
      part of Radio Science instrumentation, along with the spacecraft
      Radio Frequency Subsystem.  Their system performance directly
      determines the degree of success of Radio Science
      investigations, and their system calibration determines the
      degree of accuracy in the results of the experiments.  The
      following paragraphs describe the functions performed by the
      individual subsystems of a DSCC.  This material has been adapted
      from [ASMAR&HERRERA1993];   for additional information, see
      [DSN810-5].
 
      Each DSCC includes a set of antennas, a Signal Processing
      Center (SPC), and communication links to the Jet Propulsion
      Laboratory (JPL).  The general configuration is illustrated
      below; antennas (Deep Space Stations, or DSS -- a term carried
      over from earlier times when antennas were individually
      instrumented) are listed in the table.
 
          --------   --------   --------   --------   --------
         | DSS 25 | | DSS 27 | | DSS 14 | | DSS 15 | | DSS 16 |
         |34-m BWG| |34-m HSB| |  70-m  | |34-m HEF| |  26-m  |
          --------   --------   --------   --------   --------
              |            |     |             |          |
              |            v     v             |          v
              |           ---------            |     ---------
               --------->|GOLDSTONE|<----------     |EARTH/ORB|
                         | SPC  10 |<-------------->|   LINK  |
                          ---------                  ---------
                         |   SPC   |<-------------->|   26-M  |
                         |  COMM   |         ------>|   COMM  |
                          ---------         |        ---------
                              |             |            |
                              v             |            v
             ------       ---------         |        ---------
            | NOCC |<--->|   JPL   |<-------        |         |
             ------      | CENTRAL |                |   GSFC  |
             ------      |   COMM  |                | NASCOMM |
            | MCCC |<--->| TERMINAL|<-------------->|         |
             ------       ---------                  ---------
                                                      ^     ^
                                                      |     |
                   CANBERRA (SPC 40) <----------------      |
                                                            |
                     MADRID (SPC 60) <----------------------
 
                          GOLDSTONE     CANBERRA      MADRID
             Antenna        SPC 10       SPC 40       SPC 60
            --------      ---------     --------     --------
            26-m            DSS 16       DSS 46       DSS 66
            34-m HEF        DSS 15       DSS 45       DSS 65
            34-m BWG        DSS 24       DSS 34       DSS 54
                            DSS 25                    DSS 55
                            DSS 26
            34-m HSB        DSS 27
                            DSS 28
            70-m            DSS 14       DSS 43       DSS 63
            Developmental   DSS 13
 
 
      Subsystem interconnections at each DSCC are shown in the
      diagram below, and they are described in the sections that
      follow.  The Monitor and Control Subsystem is connected to all
      other subsystems; the Test Support Subsystem can be.
 
       -----------   ------------------   ---------   ---------
      |TRANSMITTER| |                  | | TRACKING| | COMMAND |
      | SUBSYSTEM |-| RECEIVER/EXCITER |-|SUBSYSTEM|-|SUBSYSTEM|-
       -----------  |                  |  ---------   ---------  |
             |      |     SUBSYSTEM    |       |           |     |
       -----------  |                  |  ---------------------  |
      | MICROWAVE | |                  | |      TELEMETRY      | |
      | SUBSYSTEM |-|                  |-|      SUBSYSTEM      |-
       -----------   ------------------   ---------------------  |
             |                                                   |
       -----------    -----------    ---------   --------------  |
      |  ANTENNA  |  |  MONITOR  |  |   TEST  | |    DIGITAL   | |
      | SUBSYSTEM |  |AND CONTROL|  | SUPPORT | |COMMUNICATIONS|-
       -----------   | SUBSYSTEM |  |SUBSYSTEM| |   SUBSYSTEM  |
                      -----------    ---------   --------------
 
 
    DSCC Monitor and Control Subsystem
    ----------------------------------
      The DSCC Monitor and Control Subsystem (DMC) is part of the
      Monitor and Control System (MON) which also includes the
      ground communications Central Communications Terminal and the
      Network Operations Control Center (NOCC) Monitor and Control
      Subsystem.  The DMC is the center of activity at a DSCC.  The
      DMC receives and archives most of the information from the
      NOCC needed by the various DSCC subsystems during their
      operation.  Control of most of the DSCC subsystems, as well
      as the handling and displaying of any responses to control
      directives and configuration and status information received
      from each of the subsystems, is done through the DMC.  The
      effect of this is to centralize the control, display, and
      archiving functions necessary to operate a DSCC.
      Communication among the various subsystems is done using a
      Local Area Network (LAN) hooked up to each subsystem via a
      network interface unit (NIU).
 
      DMC operations are divided into two separate areas: the
      Complex Monitor and Control (CMC) and the Link Monitor and
      Control (LMC).  The primary purpose of the CMC processor for
      Radio Science support is to receive and store all predict
      sets transmitted from NOCC such as Radio Science, antenna
      pointing, tracking, receiver, and uplink predict sets and
      then, at a later time, to distribute them to the appropriate
      subsystems via the LAN.  Those predict sets can be stored in
      the CMC for a maximum of three days under normal conditions.
      The CMC also receives, processes, and displays event/alarm
      messages; maintains an operator log; and produces tape labels
      for the DSP.  Assignment and configuration of the LMCs is
      done through the CMC; to a limited degree the CMC can perform
      some of the functions performed by the LMC.  There are two
      CMCs (one on-line and one backup) and three LMCs at each DSCC
      The backup CMC can function as an additional LMC if
      necessary.
 
      The LMC processor provides the operator interface for monitor
      and control of a link -- a group of equipment required to
      support a spacecraft pass.  For Radio Science, a link might
      include the DSCC Spectrum Processing Subsystem (DSP) (which,
      in turn, can control the SSI), or the Tracking Subsystem.
      The LMC also maintains an operator log which includes
      operator directives and subsystem responses.  One important
      Radio Science specific function that the LMC performs is
      receipt and transmission of the system temperature and signal
      level data from the PPM for display at the LMC console and
      for inclusion in Monitor blocks.  These blocks are recorded
      on magnetic tape as well as appearing in the Mission Control
      and Computing Center (MCCC) displays.  The LMC is required to
      operate without interruption for the duration of the Radio
      Science data acquisition period.
 
      The Area Routing Assembly (ARA), which is part of the Digital
      Communications Subsystem, controls all data communication
      between the stations and JPL.  The ARA receives all required
      data and status messages from the LMC/CMC and can record them
      to tape as well as transmit them to JPL via data lines.  The
      ARA also receives predicts and other data from JPL and passes
      them on to the CMC.
 
 
    DSCC Antenna Mechanical Subsystem
    ---------------------------------
      Multi-mission Radio Science activities require support from
      the 70-m, 34-m HEF, and 34-m BWG antenna subnets.  The
      antennas at each DSCC function as large-aperture collectors
      which, by double reflection, cause the incoming radio
      frequency (RF) energy to enter the feed horns.  The large
      collecting surface of the antenna focuses the incoming energy
      onto a subreflector, which is adjustable in both axial and
      angular position.  These adjustments are made to correct for
      gravitational deformation of the antenna as it moves between
      zenith and the horizon; the deformation can be as large as
      5 cm.  The subreflector adjustments optimize the channeling
      of energy from the primary reflector to the subreflector
      and then to the feed horns.  The 70-m and 34-m HEF antennas
      have 'shaped' primary and secondary reflectors, with forms
      that are modified paraboloids.  This customization allows
      more uniform illumination of one reflector by another.  The
      BWG reflector shape is ellipsoidal.
 
      On the 70-m antennas, the subreflector directs
      received energy from the antenna onto a dichroic plate, a
      device which reflects S-band energy to the S-band feed horn
      and passes X-band energy through to the X-band feed horn.  In
      the 34-m HEF, there is one 'common aperture feed,' which
      accepts both frequencies without requiring a dichroic plate.
      In the 34-m BWG, a series of small mirrors (approximately 2.5
      meters in diameter) directs microwave energy from the
      subreflector region to a collection area at the base of
      the antenna -- typically in a pedestal room.  A retractable
      dichroic reflector separates S- and X-band on some BWG
      antennas or X- and Ka-band on others.  RF energy to be
      transmitted into space by the horns is focused by the
      reflectors into narrow cylindrical beams, pointed with high
      precision (either to the dichroic plate or directly to the
      subreflector) by a series of drive motors and gear trains
      that can rotate the movable components and their support
      structures.
 
      The different antennas can be pointed by several means.  Two
      pointing modes commonly used during tracking passes are
      CONSCAN and 'blind pointing.' With CONSCAN enabled and a
      closed loop receiver locked to a spacecraft signal, the
      system tracks the radio source by conically scanning around
      its position in the sky.  Pointing angle adjustments are
      computed from signal strength information (feedback) supplied
      by the receiver.  In this mode the Antenna Pointing Assembly
      (APA) generates a circular scan pattern which is sent to the
      Antenna Control System (ACS).  The ACS adds the scan pattern
      to the corrected pointing angle predicts.  Software in the
      receiver-exciter controller computes the received signal
      level and sends it to the APA.  The correlation of scan
      position with the received signal level variations allows the
      APA to compute offset changes which are sent to the ACS.
      Thus, within the capability of the closed-loop control
      system, the scan center is pointed precisely at the apparent
      direction of the spacecraft signal source.  An additional
      function of the APA is to provide antenna position angles and
      residuals, antenna control mode/status information, and
      predict-correction parameters to the Area Routing Assembly
      (ARA) via the LAN, which then sends this information to JPL
      via the Ground Communications Facility (GCF) for antenna
      status monitoring.
 
      During periods when excessive signal level dynamics or low
      received signal levels are expected (e.g., during an
      occultation experiment), CONSCAN should not be used.  Under
      these conditions, blind pointing (CONSCAN OFF) is used, and
      pointing angle adjustments are based on a predetermined
      Systematic Error Correction (SEC) model.
 
      Independent of CONSCAN state, subreflector motion in at least
      the z-axis may introduce phase variations into the received
      Radio Science data.  For that reason, during certain
      experiments, the subreflector in the 70-m and 34-m HEFs may
      be frozen in the z-axis at a position (often based on
      elevation angle) selected to minimize phase change and signal
      degradation.  This can be done via Operator Control Inputs
      (OCIs) from the LMC to the Subreflector Controller (SRC)
      which resides in the alidade room of the antennas.  The SRC
      passes the commands to motors that drive the subreflector to
      the desired position.
 
      Pointing angles for all antenna types are computed by
      the NOCC Support System (NSS) from an ephemeris provided by
      the flight project.  These predicts are received and archived
      by the CMC.  Before each track, they are transferred to the
      APA, which transforms the direction cosines of the predicts
      into AZ-EL coordinates.  The LMC operator then downloads the
      antenna predict points to the antenna-mounted ACS computer
      along with a selected SEC model.  The pointing predicts
      consist of time-tagged AZ-EL points at selected time intervals
      along with polynomial coefficients for interpolation between
      points.
 
      The ACS automatically interpolates the predict points,
      corrects the pointing predicts for refraction and
      subreflector position, and adds the proper systematic error
      correction and any manually entered antenna offsets.  The ACS
      then sends angular position commands for each axis at the
      rate of one per second.  In the 70-m and 34-m HEF, rate
      commands are generated from the position commands at the
      servo controller and are subsequently used to steer the
      antenna.
 
      When not using binary predicts (the routine mode for
      spacecraft tracking), the antennas can be pointed using
      'planetary mode' -- a simpler mode which uses right ascension
      (RA) and declination (DEC) values.  These change very slowly
      with respect to the celestial frame.  Values are provided to
      the station in text form for manual entry.  The ACS
      quadratically interpolates among three RA and DEC points
      which are on one-day centers.
 
      A third pointing mode -- sidereal -- is available for
      tracking radio sources fixed with respect to the celestial
      frame.
 
      Regardless of the pointing mode being used, a 70-m antenna
      has a special high-accuracy pointing capability called
      'precision' mode.  A pointing control loop derives the
      main AZ-EL pointing servo drive error signals from a two-
      axis autocollimator mounted on the Intermediate Reference
      Structure.  The autocollimator projects a light beam to a
      precision mirror mounted on the Master Equatorial drive
      system, a much smaller structure, independent of the main
      antenna, which is exactly positioned in HA and DEC with shaft
      encoders.  The autocollimator detects elevation/cross-
      elevation errors between the two reference surfaces by
      measuring the angular displacement of the reflected light
      beam.  This error is compensated for in the antenna servo by
      moving the antenna in the appropriate AZ-EL direction.
      Pointing accuracies of 0.004 degrees (15 arc seconds) are
      possible in 'precision' mode.  The 'precision' mode is not
      available on 34-m antennas -- nor is it needed, since their
      beamwidths are twice as large as on the 70-m antennas.
 
 
    DSCC Antenna Microwave Subsystem
    --------------------------------
      70-m Antennas: Each 70-m antenna has three feed cones
      installed in a structure at the center of the main reflector.
      The feeds are positioned 120 degrees apart on a circle.
      Selection of the feed is made by rotation of the
      subreflector.  A dichroic mirror assembly, half on the S-band
      cone and half on the X-band cone, permits simultaneous use of
      the S- and X-band frequencies.  The third cone is devoted to
      R&D and more specialized work.
 
      The Antenna Microwave Subsystem (AMS) accepts the received S-
      and X-band signals at the feed horn and transmits them
      through polarizer plates to an orthomode transducer.  The
      polarizer plates are adjusted so that the signals are
      directed to a pair of redundant amplifiers for each
      frequency, thus allowing simultaneous reception of signals in
      two orthogonal polarizations.  For S-band these are two Block
      IVA S-band Traveling Wave Masers (TWMs); for X-band the
      amplifiers are Block IIA TWMs.
 
      34-m HEF Antennas:  The 34-m HEF uses a single feed for both
      S- and X-band.  Simultaneous S- and X-band receive as well as
      X-band transmit is possible thanks to the presence of an S/X
      'combiner' which acts as a diplexer.  For S-band, RCP or LCP
      is user selected through a switch so neither a polarizer nor
      an orthomode transducer is needed.  X-band amplification
      options include two Block II TWMs or an HEMT Low Noise
      Amplifier (LNA).  S-band amplification is provided by an FET
      LNA.
 
      34-m BWG Antennas: These antennas use feeds and low-noise
      amplifiers (LNA) in the pedestal room, which can be switched
      in and out as needed.  Typically the following modes are
      available:
 
         1. downlink non-diplexed path (RCP or LCP) to LNA-1, with
            uplink in the opposite circular polarization;
 
         2. downlink non-diplexed path (RCP or LCP) to LNA-2, with
            uplink in the opposite circular polarization
 
         3. downlink diplexed path (RCP or LCP) to LNA-1, with
            uplink in the same circular polarization
 
         4. downlink diplexed path (RCP or LCP) to LNA-2, with
            uplink in the same circular polarization
 
      For BWG antennas with dual-band capabilities (e.g., DSS 25)
      and dual LNAs, each of the above four modes can be used in a
      single-frequency or dual-frequency configuration.  Thus, for
      antennas with the most complete capabilities, there are
      sixteen possible ways to receive at a single frequency
      (2 polarizations, 2 waveguide path choices, 2 LNAs, and 2
      bands).
 
 
    DSCC Receiver-Exciter Subsystem
    -------------------------------
      The Receiver-Exciter Subsystem is composed of three groups of
      equipment: the closed-loop receiver group, the open-loop
      receiver group, and the RF monitor group.  This subsystem is
      controlled by the Receiver-Exciter Controller (REC) which
      communicates directly with the DMC for predicts and OCI
      reception and status reporting.
 
      The exciter generates the S-band signal (or X-band for the
      34-m HEF only) which is provided to the Transmitter Subsystem
      for the spacecraft uplink signal.  It is tunable under
      command of the Digitally Controlled Oscillator (DCO) which
      receives predicts from the Metric Data Assembly (MDA).
 
      The diplexer in the signal path between the transmitter and
      the feed horn for all three antennas (used for simultaneous
      transmission and reception) may be configured such that it is
      out of the received signal path (in listen-only or bypass
      mode) in order to improve the signal-to-noise ratio in the
      receiver system.
 
      Closed Loop Receivers: The Block V receiver-exciter at the
      70-m stations allows for two receiver channels, each capable
      of L-Band (e.g., 1668 MHz frequency or 18 cm wavelength),
      S-band, or X-band reception, and an S-band exciter for
      generation of uplink signals through the low-power or
      high-power transmitter.
 
      The closed-loop receivers provide the capability for rapid
      acquisition of a spacecraft signal and telemetry lockup.  In
      order to accomplish acquisition within a short time, the
      receivers are predict driven to search for, acquire, and
      track the downlink automatically.  Rapid acquisition
      precludes manual tuning though that remains as a backup
      capability.  The subsystem utilizes FFT analyzers for rapid
      acquisition.  The predicts are NSS generated, transmitted to
      the CMC which sends them to the Receiver-Exciter Subsystem
      where two sets can be stored.  The receiver starts
      acquisition at uplink time plus one round-trip-light-time or
      at operator specified times.  The receivers may also be
      operated from the LMC without a local operator attending
      them.  The receivers send performance and status data,
      displays, and event messages to the LMC.
 
      Either the exciter synthesizer signal or the simulation
      (SIM) synthesizer signal is used as the reference for the
      Doppler extractor in the closed-loop receiver systems,
      depending on the spacecraft being tracked (and Project
      guidelines).  The SIM synthesizer is not ramped; instead it
      uses one constant frequency, the Track Synthesizer Frequency
      (TSF), which is an average frequency for the entire pass.
 
      The closed-loop receiver AGC loop can be configured to one
      of three settings: narrow, medium, or wide.  It will be
      configured such that the expected amplitude changes are
      accommodated with minimum distortion.  The loop bandwidth
      (2BLo) will be configured such that the expected phase
      changes can be accommodated while maintaining the best
      possible loop SNR.
 
      Open-Loop Receivers: The Radio Science Open-Loop Receiver
      (OLR) is a dedicated four channel, narrow-band receiver which
      provides amplified and downconverted video band signals to
      the DSCC Spectrum Processing Subsystem (DSP); it sometimes
      goes by the designation 'RIV'.
 
      The OLR utilizes a fixed first Local Oscillator (LO) frequency
      and a tunable second LO frequency to minimize phase
      noise and improve frequency stability.  The OLR consists of
      an RF-to-IF downconverter located at the feed , an IF
      selection switch (IVC), and a Radio Science IF-VF
      downconverter (RIV) located in the SPC.  The RF-IF
      downconverters in the 70-m antennas are equipped for four IF
      channels: S-RCP, S-LCP, X-RCP, and X-LCP.  The 34-m HEF
      stations are equipped with a two-channel RF-IF: S-band and
      X-band.  The 34-m BWG stations vary in their capabilities.
      The IVC switches the IF input among the antennas.
 
      The RIV contains the tunable second LO, a set of video
      bandpass filters, IF attenuators, and a controller (RIC).
      The LO tuning is done via DSP control of the POCA/PLO
      combination based on a predict set.  The POCA is a
      Programmable Oscillator Control Assembly and the PLO is a
      Programmable Local Oscillator (commonly called the DANA
      synthesizer).  The bandpass filters are selectable via the
      DSP.  The RIC provides an interface between the DSP and the
      RIV.  It is controlled from the LMC via the DSP.  The RIC
      selects the filter and attenuator settings and provides
      monitor data to the DSP.  The RIC could also be manually
      controlled from the front panel in case the electronic
      interface to the DSP is lost.
 
      RF Monitor -- SSI and PPM: The RF monitor group of the
      Receiver-Exciter Subsystem provides spectral measurements
      using the Spectral Signal Indicator (SSI) and measurements of
      the received channel system temperature and spacecraft signal
      level using the Precision Power Monitor (PPM).
 
      The SSI provides a local display of the received signal
      spectrum at a dedicated terminal at the DSCC and routes these
      same data to the DSP which routes them to NOCC for remote
      display at JPL for real-time monitoring and RIV/DSP
      configuration verification.  These displays are used to
      validate Radio Science Subsystem data at the DSS, NOCC, and
      Mission Support Areas.  The SSI configuration is controlled
      by the DSP and a duplicate of the SSI spectrum appears on the
      LMC via the DSP.  During real-time operations the SSI data
      also serve as a quick-look science data type for Radio
      Science experiments.
 
      The PPM measures system noise temperatures (SNT) using a
      Noise Adding Radiometer (NAR) and downlink signal levels
      using the Signal Level Estimator (SLE).  The PPM accepts its
      input from the closed-loop receiver.  The SNT is measured by
      injecting known amounts of noise power into the signal path
      and comparing the total power with the noise injection 'on'
      against the total power with the noise injection 'off.' That
      operation is based on the fact that receiver noise power is
      directly proportional to temperature; thus measuring the
      relative increase in noise power due to the presence of a
      calibrated thermal noise source allows direct calculation of
      SNT.  Signal level is measured by calculating an FFT to
      estimate the SNR between the signal level and the receiver
      noise floor where the power is known from the SNT
      measurements.
 
      There is one PPM controller at the SPC which is used to
      control all SNT measurements.  The SNT integration time can
      be selected to represent the time required for a measurement
      of 30K to have a one-sigma uncertainty of 0.3K or 1%.
 
 
    DSCC Transmitter Subsystem
    --------------------------
      The Transmitter Subsystem accepts the S-band frequency
      exciter signal from the Receiver-Exciter Subsystem exciter
      and amplifies it to the required transmit output level.  The
      amplified signal is routed via the diplexer through the feed
      horn to the antenna and then focused and beamed to the
      spacecraft.
 
      The Transmitter Subsystem power capabilities range from 18 kw
      to 400 kw.  Power levels above 18 kw are available only at
      70-m stations.
 
 
    DSCC Tracking Subsystem
    -----------------------
      The Tracking Subsystem primary functions are to acquire and
      maintain communications with the spacecraft and to generate
      and format radiometric data containing Doppler and range.
 
      The DSCC Tracking Subsystem (DTK) receives the carrier
      signals and ranging spectra from the Receiver-Exciter
      Subsystem.  The Doppler cycle counts are counted, formatted,
      and transmitted to JPL in real time.  Ranging data are also
      transmitted to JPL in real time.  Also contained in these
      blocks is the AGC information from the Receiver-Exciter
      Subsystem.  The Radio Metric Data Conditioning Team (RMDCT)
      at JPL produces an Archival Tracking Data File (ATDF) which
      contains Doppler and ranging data.
 
      In addition, the Tracking Subsystem receives from the CMC
      frequency predicts (used to compute frequency residuals and
      noise estimates), receiver tuning predicts (used to tune the
      closed-loop receivers), and uplink tuning predicts (used to
      tune the exciter).  From the LMC, it receives configuration
      and control directives as well as configuration and status
      information on the transmitter, microwave, and frequency and
      timing subsystems.
 
      The Metric Data Assembly (MDA) controls all of the DTK
      functions supporting the uplink and downlink activities.  The
      MDA receives uplink predicts and controls the uplink tuning
      by commanding the DCO.  The MDA also controls the Sequential
      Ranging Assembly (SRA).  It formats the Doppler and range
      measurements and provides them to the GCF for transmission to
      NOCC.
 
      The Sequential Ranging Assembly (SRA) measures the round trip
      light time (RTLT) of a radio signal traveling from a ground
      tracking station to a spacecraft and back.  From the RTLT,
      phase, and Doppler data, the spacecraft range can be
      determined.  A coded signal is modulated on an uplink carrier
      and transmitted to the spacecraft where it is detected and
      transponded back to the ground station.  As a result, the
      signal received at the tracking station is delayed by its
      round trip through space and shifted in frequency by the
      Doppler effect due to the relative motion between the
      spacecraft and the tracking station on Earth.
 
 
    DSCC Frequency and Timing Subsystem
    -----------------------------------
      The Frequency and Timing Subsystem (FTS) provides all
      frequency and timing references required by the other DSCC
      subsystems.  It contains four frequency standards of which
      one is prime and the other three are backups.  Selection of
      the prime standard is done via the CMC.  Of these four
      standards, two are hydrogen masers followed by clean-up loops
      (CUL) and two are cesium standards.  These four standards all
      feed the Coherent Reference Generator (CRG) which provides
      the frequency references used by the rest of the complex.  It
      also provides the frequency reference to the Master Clock
      Assembly (MCA) which in turn provides time to the Time
      Insertion and Distribution Assembly (TID) which provides UTC
      and SIM-time to the complex.
 
      JPL's ability to monitor the FTS at each DSCC is limited to
      the MDA calculated Doppler pseudo-residuals, the Doppler
      noise, the SSI, and to a system which uses the Global
      Positioning System (GPS).  GPS receivers at each DSCC receive
      a one-pulse-per-second pulse from the station's (hydrogen
      maser referenced) FTS and a pulse from a GPS satellite at
      scheduled times.  After compensating for the satellite signal
      delay, the timing offset is reported to JPL where a database
      is kept.  The clock offsets stored in the JPL database are
      given in microseconds; each entry is a mean reading of
      measurements from several GPS satellites and a time tag
      associated with the mean reading.  The clock offsets provided
      include those of SPC 10 relative to UTC (NIST), SPC 40
      relative to SPC 10, etc.
 
 
  Optics - DSN
  ============
    Performance of DSN ground stations depends primarily on size of
    the antenna and capabilities of electronics.  These are
    summarized in the following set of tables.  Note that 64-m
    antennas were upgraded to 70-m between 1986 and 1989.
    Beamwidth is half-power full angular width.  Polarization is
    circular; L denotes left circular polarization (LCP), and R
    denotes right circular polarization (RCP).
 
                         DSS S-Band Characteristics
 
                                       70-m     34-m     34-m
         Transmit                                BWG      HEF
         --------                     -----    -----    -----
         Frequency (MHz)              2110-    2025-     N/A
                                       2120     2120
         Wavelength (m)               0.142    0.142     N/A
         Ant Gain (dBi)                62.7     56.1     N/A
         Beamwidth (deg)              0.119      N/A     N/A
         Polarization                L or R   L or R     N/A
         Tx Power (kW)               20-400       20     N/A
 
         Receive
         -------
         Frequency (MHz)              2270-    2270-    2200-
                                       2300     2300     2300
         Wavelength (m)               0.131    0.131    0.131
         Ant Gain (dBi)                63.3     56.7     56.0
         Beamwidth (deg)              0.108      N/A     0.24
         Polarization                 L & R   L or R   L or R
         System Temp (K)                 20       31       38
 
                         DSS X-Band Characteristics
 
                                       70-m     34-m     34-m
         Transmit                                BWG      HEF
         --------                     -----    -----    -----
         Frequency (MHz)               8495    7145-    7145-
                                                7190     7190
         Wavelength (m)               0.035    0.042    0.042
         Ant Gain (dBi)                74.2     66.9       67
         Beamwidth (deg)                         N/A    0.074
         Polarization                L or R   L or R   L or R
         Tx Power (kW)                  360       20       20
 
         Receive
         -------
         Frequency (MHz)              8400-    8400-    8400-
                                       8500     8500     8500
         Wavelength (m)               0.036    0.036    0.036
         Ant Gain (dBi)                74.2     68.1     68.3
         Beamwidth (deg)              0.031      N/A    0.063
         Polarization                 L & R    L & R    L & R
         System Temp (K)                 20       30       20
 
         NB: X-band 70-m transmitting parameters are given
             at 8495 MHz, the frequency used by the Goldstone
             planetary radar system.  For telecommunications, the
             transmitting frequency would be in the range 7145-7190
             MHz, the power would typically be 20 kW, and the gain
             would be about 72.6 dB (70-m antenna).  When ground
             transmitters are used in spacecraft radio science
             experiments, the details of transmitter and antenna
             performance rarely impact the results.
 
  Detectors - DSN
  ===============
 
    DSCC Closed-Loop Receivers
    --------------------------
      Nominal carrier tracking loop threshold noise bandwidth at
      both S- and X-band is 10 Hz.  Coherent (two-way) closed-loop
      system stability is shown in the table below:
 
          integration time            Doppler uncertainty
               (secs)               (one sigma, microns/sec)
               ------               ------------------------
                  10                            50
                  60                            20
                1000                             4
 
 
  Calibration - DSN
  =================
    Calibrations of hardware systems are carried out periodically
    by DSN personnel; these ensure that systems operate at required
    performance levels -- for example, that antenna patterns,
    receiver gain, propagation delays, and Doppler uncertainties
    meet specifications.  No information on specific calibration
    activities is available.  Nominal performance specifications
    are shown in the tables above.  Additional information may be
    available in [DSN810-5].
 
    Prior to each tracking pass, station operators perform a series
    of calibrations to ensure that systems meet specifications for
    that operational period.  Included in these calibrations is
    measurement of receiver system temperature in the configuration
    to be employed during the pass.  Results of these calibrations
    are recorded in (hard copy) Controller's Logs for each pass.
 
    The nominal procedure for initializing open-loop receiver
    attenuator settings is described below.  In cases where widely
    varying signal levels are expected, the procedure may be
    modified in advance or real-time adjustments may be made to
    attenuator settings.
 
 
  Operational Considerations - DSN
  ================================
    The DSN is a complex and dynamic 'instrument.' Its performance
    for Radio Science depends on a number of factors from equipment
    configuration to meteorological conditions.  No specific
    information on 'operational considerations' can be given here.
 
 
  Operational Modes - DSN
  =======================
 
    DSCC Antenna Mechanical Subsystem
    ---------------------------------
      Pointing of DSCC antennas may be carried out in several ways.
      For details see the subsection 'DSCC Antenna Mechanical
      Subsystem' in the 'Subsystem' section.  Binary pointing is
      the preferred mode for tracking spacecraft; pointing
      predicts are provided, and the antenna simply follows those.
      With CONSCAN, the antenna scans conically about the optimum
      pointing direction, using closed-loop receiver signal
      strength estimates as feedback.  In planetary mode, the
      system interpolates from three (slowly changing) RA-DEC
      target coordinates; this is 'blind' pointing since there is
      no feedback from a detected signal.  In sidereal mode, the
      antenna tracks a fixed point on the celestial sphere.  In
      'precision' mode, the antenna pointing is adjusted using an
      optical feedback system.  It is possible on most antennas to
      freeze z-axis motion of the subreflector to minimize phase
      changes in the received signal.
 
 
    Closed-Loop Receiver AGC Loop
    -----------------------------
      The closed-loop receiver AGC loop can be configured to one of
      three settings: narrow, medium, or wide.  Ordinarily it is
      configured so that expected signal amplitude changes are
      accommodated with minimum distortion.  The loop bandwidth is
      ordinarily configured so that expected phase changes can be
      accommodated while maintaining the best possible loop SNR.
 
 
    Coherent vs. Non-Coherent Operation
    -----------------------------------
      The frequency of the signal transmitted from the spacecraft
      can generally be controlled in two ways -- by locking to a
      signal received from a ground station or by locking to an
      on-board oscillator.  These are known as the coherent (or
      'two-way') and non-coherent ('one-way') modes, respectively.
      Mode selection is made at the spacecraft, based on commands
      received from the ground.  When operating in the coherent
      mode, the transponder carrier frequency is derived from the
      received uplink carrier frequency with a 'turn-around ratio'
      typically of 240/221.  In the non-coherent mode, the
      downlink carrier frequency is derived from the spacecraft
      on-board crystal-controlled oscillator.  Either closed-loop
      or open-loop receivers (or both) can be used with either
      spacecraft frequency reference mode.  Closed-loop reception
      in two-way mode is usually preferred for routine tracking.
      Occasionally the spacecraft operates coherently while two
      ground stations receive the 'downlink' signal; this is
      sometimes known as the 'three-way' mode.
 
 
  DSN Station Locations
  =====================
 
                          Geocentric  Geocentric  Geocentric
    Station                 x (m)       y (km)        z (km)
    ---------            ----------- ------------ -------------
    Goldstone
      DSS 13 (34-m R&D)  -2351112.491  -4655530.714  +3660912.787
      DSS 14 (70-m)      -2353621.251  -4641341.542  +3677052.370
      DSS 15 (34-m HEF)  -2353538.790  -4641649.507  +3676670.043
      DSS 24 (34-m BWG)  -2354906.495  -4646840.128  +3669242.317
      DSS 25 (34-m BWG)  -2355022.066  -4646953.636  +3669040.895
      DSS 26 (34-m BWG)  -2354890.967  -4647166.925  +3668872.212
 
    Canberra
      DSS 34 (34-m BWG)  -4461146.756  +2682439.293  -3674393.542
      DSS 43 (70-m)      -4460894.585  +2682361.554  -3674748.580
      DSS 45 (34-m HEF)  -4460935.250  +2682765.710  -3674381.402
 
    Madrid
      DSS 54 (34-m BWG)  +4849434.555  -0360724.108  +4114618.643
      DSS 63 (70-m)      +4849092.647  -0360180.569  +4115109.113
      DSS 65 (34-m HEF)  +4849336.730  -0360488.859  +4114748.775
 
 
  Measurement Parameters - DSN
  ============================
 
    Closed-Loop System
    ------------------
      Closed-loop data are recorded in Archival Tracking Data Files
      (ATDFs), as well as certain secondary products such as the
      Orbit Data File (ODF).  The ATDF Tracking Logical Record
      contains 150 entries including status information and
      measurements of ranging, Doppler, and signal strength.
 
 
  ACRONYMS AND ABBREVIATIONS - DSN
  ================================
    ACS      Antenna Control System
    ADC      Analog-to-Digital Converter
    AGC      Automatic Gain Control
    AMS      Antenna Microwave System
    APA      Antenna Pointing Assembly
    ARA      Area Routing Assembly
    ATDF     Archival Tracking Data File
    AUX      Auxiliary
    AZ       Azimuth
    bps      bits per second
    BWG      Beam WaveGuide (antenna)
    CDU      Command Detector Unit
    CMC      Complex Monitor and Control
    CONSCAN  Conical Scanning (antenna pointing mode)
    CRG      Coherent Reference Generator
    CUL      Clean-up Loop
    DANA     a type of frequency synthesizer
    dB       deciBel
    dBi      dB relative to isotropic
    dBm      dB relative to one milliwatt
    DCO      Digitally Controlled Oscillator
    DEC      Declination
    deg      degree
    DMC      DSCC Monitor and Control Subsystem
    DOR      Differential One-way Ranging
    DSCC     Deep Space Communications Complex
    DSN      Deep Space Network
    DSP      DSCC Spectrum Processing Subsystem
    DSS      Deep Space Station
    DTK      DSCC Tracking Subsystem
    E        east
    EIRP     Effective Isotropic Radiated Power
    EL       Elevation
    FET      Field Effect Transistor
    FFT      Fast Fourier Transform
    FTS      Frequency and Timing Subsystem
    GCF      Ground Communications Facility
    GHz      Gigahertz
    GPS      Global Positioning System
    HA       Hour Angle
    HEF      High-Efficiency (as in 34-m HEF antennas)
    HEMT     High Electron Mobility Transistor (amplifier)
    HGA      High-Gain Antenna
    HSB      High-Speed BWG
    IF       Intermediate Frequency
    IVC      IF Selection Switch
    JPL      Jet Propulsion Laboratory
    K        Kelvin
    Ka-Band  approximately 32 GHz
    KaBLE    Ka-Band Link Experiment
    kbps     kilobits per second
    kHz      kiloHertz
    km       kilometer
    kW       kilowatt
    LAN      Local Area Network
    LCP      Left-Circularly Polarized
    LGR      Low-Gain Receive (antenna)
    LGT      Low-Gain Transmit (antenna)
    LMA      Lockheed Martin Astronautics
    LMC      Link Monitor and Control
    LNA      Low-Noise Amplifier
    LO       Local Oscillator
    m        meters
    MCA      Master Clock Assembly
    MCCC     Mission Control and Computing Center
    MDA      Metric Data Assembly
    MPF      Mars Pathfinder
    MHz      Megahertz
    MON      Monitor and Control System
    MOT      Mars Observer Transponder
    MSA      Mission Support Area
    N        north
    NAR      Noise Adding Radiometer
    NBOC     Narrow-Band Occultation Converter
    NIST     SPC 10 time relative to UTC
    NIU      Network Interface Unit
    NOCC     Network Operations and Control System
    NRV      NOCC Radio Science/VLBI Display Subsystem
    NSS      NOCC Support System
    OCI      Operator Control Input
    ODF      Orbit Data File
    ODR      Original Data Record
    ODS      Original Data Stream
    ODY      Mars Odyssey Orbiter
    OLR      Open Loop Receiver
    OSC      Oscillator
    PDS      Planetary Data System
    POCA     Programmable Oscillator Control Assembly
    PPM      Precision Power Monitor
    RA       Right Ascension
    REC      Receiver-Exciter Controller
    RCP      Right-Circularly Polarized
    RF       Radio Frequency
    RIC      RIV Controller
    RIV      Radio Science IF-VF Converter Assembly
    RMDCT    Radio Metric Data Conditioning Team
    RMS      Root Mean Square
    RSS      Radio Science Subsystem
    RTLT     Round-Trip Light Time
    S-band   approximately 2100-2300 MHz
    sec      second
    SEC      System Error Correction
    SIM      Simulation
    SLE      Signal Level Estimator
    SNR      Signal-to-Noise Ratio
    SNT      System Noise Temperature
    SOE      Sequence of Events
    SPA      Spectrum Processing Assembly
    SPC      Signal Processing Center
    sps      samples per second
    SRA      Sequential Ranging Assembly
    SRC      Sub-Reflector Controller
    SSI      Spectral Signal Indicator
    TID      Time Insertion and Distribution Assembly
    TLM      Telemetry
    TSF      Tracking Synthesizer Frequency
    TWM      Traveling Wave Maser
    TWNC     Two-Way Non-Coherent
    TWTA     Traveling Wave Tube Amplifier
    UHF      Ultra High Frequency
    UNK      unknown
    USO      UltraStable Oscillator
    UTC      Universal Coordinated Time
    VCO      Voltage-Controlled Oscillator
    VF       Video Frequency
    X-band   approximately 7800-8500 MHz

        