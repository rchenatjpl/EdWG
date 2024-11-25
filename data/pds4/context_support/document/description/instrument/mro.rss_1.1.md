
 
    Instrument Overview
    ===================
 
      Radio science investigations utilize instrumentation with
      elements both on a spacecraft and at ground stations -- in
      this case, at the NASA Deep Space Network (DSN).
      The spacecraft part of the radio
      science instrument is described immediately below; that is
      followed by a description of the DSN (ground) part of the
      instrument.  For more information about the
      Mars Reconnaissance Orbiter, see [TAYLORETAL2006].
 
 
    Instrument Specifications - Spacecraft
    ======================================
 
      Instrument Id                  : RSS
      Instrument Host Id             : MRO
      Pi Pds User Id                 : UNK
      Instrument Name                : RADIO SCIENCE SUBSYSTEM
      Instrument Type                : RADIO SCIENCE
      Build Date                     : UNK
      Instrument Mass                : UNK
      Instrument Length              : UNK
      Instrument Width               : UNK
      Instrument Height              : UNK
      Instrument Manufacturer Name   : UNK
 
 
    Instrument Overview - Spacecraft
    ================================
      The MRO telecommunications system was designed to
      transmit at X- and Ka-Band. Ka-band doppler data are
      currently not available.
 
      The spacecraft also carried redundant ultra-high frequency
      (UHF) transceivers for communication and relay with future
      missions. Since the UHF equipment was not used for radio
      science, it is not described here.
 
      MRO is the second Mars orbiter ever to carry an Ultra-Stable
      Oscillator (USO).  The first orbiter was MGS which carried
      the top of the line USO with stability on the order of 1E-13
      (over 10 to 100 seconds) for the purpose of occultation
      Radio Science.  The MRO USO is a different design; it is a
      dual-oven resonator from the manufacturer (and this has the
      heritage of the Voyager and Galileo USOs). The MRO stability
      is on the order of 1E-12 (over 10 to 100 seconds) and was
      added to the spacecraft in support of the Electra Payload for
      proximity communications at UHF frequencies. The USO
      output frequency is ~76.72 MHz and has one output line to
      the Electra Payload and a second line to the X-band
      transponder.  With the latter, the transponder can be
      configured to the one-way non-coherent mode using the USO
      as the reference signal.  The USO mass is under 900 g.  Its
      daily aging rate is approximated to be 5E-11 over a 24-hour
      period (after a 30-day warm up period after powering the USO).
      The USO phase noise (at its output frequency, must be scaled to
      X-band for transponder output) is -90 dBc at 1 Hz offset
      and -120 dBc at 100 Hz offset.
 
 
    Science Objectives
    ==================
      The radio tracking data will be used to
      improve knowledge of the Mars gravity field, both the
      static and the time-variable components. Analysis of the
      radio tracking data can also provide estimates of the
      atmospheric density at the spacecraft altitudes. The
      analysis of the interplanetary tracking data (both
      range data and VLBI) to MRO can be used to improve the
      modelling of the orbit of the planet Mars in future
      versions of the solar system planetary ephemerides.
      Two different types of radio science experiments were
      conducted with MRO: radio tracking experiments in
      which the magnitude and direction of the planet's
      gravity field were derived from the Doppler (and,
      sometimes, ranging) measurements, and radio propagation
      experiments in which signal modulation detected on Earth
      could be attributed to properties of the medium.
 
      Gravity Measurements
      --------------------
 
        Measurement of the gravity field provides significant
        constraints on inferences about the interior structure of
        Mars.  Precise, detailed study of the spacecraft motion
        in Mars orbit can yield the mass distribution of the
        planet.
 
        Studies of the gravity field emphasize both the global
        field and local characteristics of the field.  The first
        task is to determine the global field.  Doppler and range
        tracking measurements yield accurate spacecraft trajectory
        solutions.  Simultaneously with reconstruction of the
        spacecraft orbit, observation equations for field
        coefficients and a small number of ancillary parameters
        can be solved.  This type of gravity field solution is
        essential for characterizing tectonic phenomena and can
        also be used to study localized features.
 
        'Short-arc' line-of-sight Doppler tracking measurements
        obtained when the Earth-to-spacecraft line-of-sight is
        within a few degrees of the orbit plane provide the
        highest resolution of local features.  The results from
        this type of observation typically are presented as
        contoured acceleration profiles of specific features
        (e.g., craters, volcanoes, etc.) or line-of-sight
        acceleration maps of specific regions.  The high spatial
        resolution of these products makes them especially useful
        to geophysicists for study of features in the size range
        of 300 to 1,000 km.  Because of the relative simplicity
        of the data analysis, results can be available very soon
        after the data are collected.
 
      Radio Occultation Measurements
      ------------------------------
        Atmospheric measurements by the method of radio
        occultation contribute to an improved understanding of
        structure, circulation, dynamics, and transport in the
        atmosphere of Mars.  These results are based on detailed
        analysis of the radio signal received from MRO as it
        entered and exited occultation by the planet.
 
        Retrieval of atmospheric profiles requires coherent
        samples of the radio signal that has propagated through
        the atmosphere, plus accurate knowledge of the antenna
        pointing and the spacecraft trajectory.  The latter
        can be obtained from the pointing (CK) and trajectory
        (SPK) files in this data set.
 
        The spatial and temporal coverage in the radio occultation
        experiments are determined by the geometry of the
        spacecraft orbit and the dates and times at which
        occultation data were acquired.
 
 
    Operational Considerations - Spacecraft
    =======================================
      The data available for radio science commence after the
      end of aerobraking in August 2006. Both two-way and one-way
      ramped Doppler are available, although it should be noted
      that the MRO UltraStable Oscillator is not quite of the
      same quality as on Mars Global Surveyor.  The spacecraft
      is tracking usually on average for two passes per day, with
      extra passes added to support further spacecraft downlink
      requirements. Ramped range observations are also available
      albeit at a much smaller rate than for the Doppler (anywhere
      from 20 to 60 range observations are available in typical
      two-three day arcs). These range observations may be used
      to improve the Mars planetary ephemerides similiar to
      what is described in KONOPLIVETAL[2006].
 
 
      The high gain antenna articulates to maintain its orientation
      with the Earth in order to prevent any iterruption to the
      acquistion of science data. This means the motion of the HGA
      must be modelled to fully remove the spurious signals due to
      the motion of the high gain antenna about the spacecraft
      center of mass.
 
      The spacecraft periodically performs angular momentum
      desaturation maneuvers. These maneuvers desaturate the
      momentum wheels where momentum has built up
      due to disturbance torques acting on the spacecraft.
      On MRO, these maneuvers occur approximately every two to three
      days, and the times of these AMD maneuvers are detailed
      in the spacecraft small force files (part of the MRO raw data
      archive).
 
      The spacecraft periodically performs maneuvers to maintain
      its ground track or for other science considerations. For example,
      MRO conducted several maneuvers in order to optimize its
      viewing geometry for the landing of the Mars Phoenix lander
      on the Northern Hemisphere of Mars in early 2008. The times of the
      maneuvers are listed in the maneuver performance data files,
      listed in the raw data archive.
 
      The spacecraft mass varies as a consequence of fuel consumption
      due to the orbit maneuvers and due to the AMD maneuvers. The spacecraft
      mass used in the orbit determination analyses is provided in the
      mpdf files, and in periodic updates supplied by the MRO Navigation
      Team.
 
 
         List of Maneuvers
         -----------------
         Name      Date            New SC     Maneuver Delta-V
                                   Mass (kg)
 
         ABX       2006-08-22 01:18   1382.6
         OAINC1    2006-08-31 16:26   1367.97
         OA2       2006-09-06 00:23   1359.03
         INC2      2006-11-06 22:59   1324.64
         OA3       2006-12-05 02:33   1320.18
         OA4       2007-12-05 02:50   1319.83
         OTM1      2007-02-07 17:43   1317.45    71.1 mm/s
         OTM2      2007-04-18 16:08   1315.66   130.2 mm/s
         OTM3      2007-05-23 16:45   1315.01   112.8 mm/s
         OTM4      2007-06-27 17:22   1314.59   123.0 mm/s
         OTM5      2007-07-25 17:40   1313.46   224.8 mm/s
         OTM6      2007-08-22 16:07   1312.24   141.6 mm/s
         OTM7      2007-09-19 16:26   1311.57    81.6 mm/s
         OTM8      2007-10-31 17:30   1310.53   192.5 mm/s
         OTM9      2007-12-12 16:33   1308.9     76.5 mm/s
         OSM1      2008-02-06 16:21   1306.8    152.0 mm/s
         OSM2      2008-04-30 16:44   1303.1    122.3 mm/s
         OTM10     2008-06-25 16:34             248.5 mm/s
         OTM11     2008-10-15 17:05             107.8 mm/s
 [OTM & OSTM DeltaV magnitudes and times taken from
  MRO Navigation Team Weekly Status Report, Dated October 24, 2008,
  Author: Dolan E. Highsmith, JPL; Other information from
  Maneuver Performance Data Files (MPDF) for MRO, and
  other  Nav Team Reports to the MRO Project]
 
     MRO experienced several anomalies over the course of its mapping
     mission, which caused in interruption of its science data collection,
     including the radio science data.
     These safe mode events are identified by interruptions in the
     flow of telemetry and hence the availability of c-kernels
     (attitude information) for the spacecraft. Generally, the
     practice is to omit tracking data from the geopotential solutions
     from the safe mode periods. These safe mode events are infrequent
     and have occurred only a few times since MRO entered low altitude
     near-circular orbit about Mars in August 2006.
 
     MRO experienced an exceptional period of high drag from April to
     approximately June to July 2007.
     The high drag in part coincided with the location of Mars near
     perihelion, and the initiation of the Mars dust storm season.
 
 
    Calibration Description - Spacecraft
    ====================================
      All measurements below were made during the Prelaunch Phase of
      The mission.
 
 
    Platform Mounting Descriptions - Spacecraft
    ===========================================
 
    Investigators
    =============
    M. Zuber, F. Lemoine, D. Smith, A. Konopliv, S. Smrekar, A. Asmar.
 
    Instrument Section / Operating Mode Descriptions - Spacecraft
    =============================================================
 
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
      most common being S-band (nominally a frequency of 2100-2300
      MHz or a wavelength of 14.2-13.0 cm) and X-band (7100-8500 MHz
      or 4.2-3.5 cm).  Transmitter output powers of up to 400 kW are
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
      radio science see reports by [ASMAR&RENZETTI1993]
      and [ASMARETAL1995].  For design
      specifications on DSN subsystems see [DSN810-5].
 
    Subsystems - DSN
    ================
      The Deep Space Communications Complexes (DSCCs) are an integral
      part of Radio Science instrumentation, along with the
      spacecraft Radio Frequency Subsystem.  Their system performance
      directly determines the degree of success of Radio Science
      investigations, and their system calibration determines the
      degree of accuracy in the results of the experiments.  The
      following paragraphs describe the functions performed by the
      individual subsystems of a DSCC.  This material has been
      adapted from [ASMARETAL1995] and [JPLD-16765]; for additional
      information, consult [DSN810-5].
 
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
                            DSS 25
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
        consist of time-tagged AZ-EL points at selected time
        intervals along with polynomial coefficients for
        interpolation between points.
 
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
        The Receiver-Exciter Subsystem is composed of two groups of
        equipment: the closed-loop receiver group and the open-loop
        receiver group.  This subsystem is controlled by the
        Receiver-Exciter Controller (REC) which communicates
        directly with the DMC for predicts and OCI reception and
        status reporting.
 
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
 
        Open-Loop Receivers (OLR):  The OLR utilized a fixed first
        Local Oscillator (LO) frequency and a tunable second LO
        frequency to minimize phase noise and improve frequency
        stability.  The OLR consisted of an RF-to-IF downconverter
        located at the feed , an IF selection switch (IFS), and a
        Radio Science Receiver (RSR).  The RF-IF downconverters
        in the 70-m antennas were equipped for four IF channels:
        S-RCP, S-LCP, X-RCP, and X-LCP.  The 34-m HEF stations
        were equipped with a two-channel RF-IF: S-band and X-band.
        The IFS switched the IF input among the antennas.
 
 
      DSCC Transmitter Subsystem
      --------------------------
        The Transmitter Subsystem accepts the S-band frequency
        exciter signal from the Receiver-Exciter Subsystem exciter
        and amplifies it to the required transmit output level.  The
        amplified signal is routed via the diplexer through the feed
        horn to the antenna and then focused and beamed to the
        spacecraft.
 
        The Transmitter Subsystem power capabilities range from 18 kW
        to 400 kW.  Power levels above 18 kW are available only at
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
        at JPL produces a Tracking and Navigation Service File (TNF),
        which contains Doppler and ranging data.
 
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
 
 
      Radio Science Receiver (RSR)
      ----------------------------
        A radio frequency (RF) spacecraft signal at S-band, X-band,
        or Ka-band is captured by a receiving antenna on Earth, down
        converted to an intermediate frequency (IF) near 300 MHz and
        then fed via a distribution network to one input of an IF
        Selector Switch (IFS).  The IFS allows each RSR to select any
        of the available input signals for its RSR Digitizer (DIG).
        Within the RSR the digitized signal is then passed to the
        Digitial Down Converter (DDC), VME Data Processor (VDP), and
        Data Processor (DP) [JPLD-16765].
 
        \       -----------      ------      -----      -----   -----
         \     | RF  TO IF |    |      |----|     |    |     | |     |
          |----|    DOWN   |----|      |----|     |----| DIG | |  DP |
         /     | CONVERTER |    |      |----|     |    |     | |     |
        /       -----------     |  IF  |----| IFS |     -----   -----
        ANTENNA               --| DIST |----|     |       |       |
                300 MHz IF    --|      | .. |     |     -----   -----
                FROM OTHER    --|      |----|     |    |     | |     |
                 ANTENNAS     --|      |     -----     | DDC | | VDP |
                                 ------                |     | |     |
                                                        -----   -----
                                                          |       |
                                                           -------
 
        In the DIG the IF signal is passed through a programmable
        attenuator, adjusted to provide the proper level to the
        Analog to Digital Converter (ADC).  The attenuated signal is
        then passed through a Band Pass Filter (BPF) which selects a
        frequency band in the range 265-375 MHz.  The filtered output
        from the BPF is then mixed with a 256 MHz Local Oscillator
        (LO), low pass filtered (LPF), and sampled by the ADC.  The
        output of the ADC is a stream of 8-bit real samples at 256
        Msamples/second (Msps).  DIG timing is derived from the
        station FTS 5 MHz clock and 1 pulse per second (1PPS)
        reference; the DIG generates a 256 MHz clock signal for later
        processing.  The 1PPS signal marks the data sample taken at
        the start of each second.
 
        The DDC selects one 16 MHz subchannel from the possible 128
        MHz bandwidth available from the DIG by using Finite Impulse
        Response (FIR) filters with revolving banks of filter
        coefficients.  The sample stream from the DIG is separated
        into eight decimated streams, each of which is fed into two
        sets of FIR filters.  One set of filters produces in-phase
        (I) 8-bit data while the other produces quadrature-phase (Q)
        8-bit data.  The center frequency of the desired 16 MHz
        channel is adjustable in 1 MHz steps and is usually chosen to
        be near the spacecraft carrier frequency.  After combining
        the I and Q sample streams, the DDC feeds the samples to the
        VDP.  The DDC also converts the 256 MHz data clock and 1PPS
        signals into a msec time code, which is also passed to the
        VDP.
 
        The VDP contains a quadruply-redundant set of custom boards
        which are controlled by a real-time control computer (RT).
        Each set of boards comprises a numerically controlled
        oscillator (NCO), a complex multiplier, a decimating FIR
        filter, and a data packer.  The 16 Msps complex samples
        from the DDC are digitally mixed with the NCO signal in the
        complex multiplier.  The NCO phase and frequency are updated
        every millisecond by the RT and are selected so that the
        center frequency of the desired portion of the 16 MHz channel
        is down-converted to 0 Hz.  The RT uses polynomials derived
        from frequency predictions.  The output of the complex
        multiplier is sent to the decimating FIR filter where its
        bandwidth and sample rate are reduced (see table below).  The
        decimating FIR filter also allows adjustment of the
        sub-channel gain to take full advantage of the dynamic range
        available in the hardware.  The data packer truncates samples
        to 1, 2, 4, 8, or 16 bits by dropping the least significant
        bits and packs them into 32-bit data words.  Q-samples are
        packed into the first 16 bits of the word, and I-samples into
        the least significant 16 bits (see below).  In 'narrow band'
        operation all four sets of sets of custom boards can be
        supported simultaneously.  In 'medium band' operation no more
        than two channels can be supported simultaneously.  In
        'wide band' operation, only one sub-channel can be recorded.
 
        |============================================================|
        |         RSR Sample Rates and Sample Sizes Supported        |
        |================+=======+======+=================+==========|
        |    Category    |  Rate | Size |    Data Rate    |Rec Length|
        |                | (ksps)|(bits)|(bytes/s) (rec/s)|  (bytes) |
        |================+=======+======+=========+=======+==========|
        |Narrow Band (NB)|     1 |   8  |    2000 |    1  |    2000  |
        |                |     2 |   8  |    4000 |    1  |    4000  |
        |                |     4 |   8  |    8000 |    1  |    8000  |
        |                |     8 |   8  |   16000 |    1  |   16000  |
        |                |    16 |   8  |   32000 |    2  |   16000  |
        |                |    25 |   8  |   50000 |    2  |   25000  |
        |                |    50 |   8  |  100000 |    4  |   25000  |
        |                |   100 |   8  |  200000 |   10  |   20000  |
        |                |     1 |  16  |    4000 |    1  |    4000  |
        |                |     2 |  16  |    8000 |    1  |    8000  |
        |                |     4 |  16  |   16000 |    1  |   16000  |
        |                |     8 |  16  |   32000 |    2  |   16000  |
        |                |    16 |  16  |   64000 |    4  |   16000  |
        |                |    25 |  16  |  100000 |    4  |   25000  |
        |                |    50 |  16  |  200000 |   10  |   20000  |
        |                |   100 |  16  |  400000 |   20  |   20000  |
        |Medium Band (MB)|   250 |   1  |   62500 |    5  |   12500  |
        |                |   500 |   1  |  125000 |    5  |   25000  |
        |                |  1000 |   1  |  250000 |   10  |   25000  |
        |                |  2000 |   1  |  500000 |   20  |   25000  |
        |                |  4000 |   1  | 1000000 |   40  |   25000  |
        |                |   250 |   2  |  125000 |    5  |   25000  |
        |                |   500 |   2  |  250000 |   10  |   25000  |
        |                |  1000 |   2  |  500000 |   20  |   25000  |
        |                |  2000 |   2  | 1000000 |   40  |   25000  |
        |                |  4000 |   2  | 2000000 |  100  |   20000  |
        |                |   250 |   4  |  250000 |   10  |   25000  |
        |                |   500 |   4  |  500000 |   20  |   25000  |
        |                |  1000 |   4  | 1000000 |   40  |   25000  |
        |                |  2000 |   4  | 2000000 |  100  |   20000  |
        |                |   250 |   8  |  500000 |   20  |   25000  |
        |                |   500 |   8  | 1000000 |   40  |   25000  |
        |                |  1000 |   8  | 2000000 |  100  |   20000  |
        |Wide Band (WB)  |  8000 |   1  | 2000000 |  100  |   20000  |
        |                | 16000 |   1  | 4000000 |  200  |   20000  |
        |                |  8000 |   2  | 4000000 |  200  |   20000  |
        |============================================================|
 
        |============================================================|
        |                        Sample Packing                      |
        |=================+==========================================|
        | Bits per Sample |  Contents of 32-bit Packed Data Register |
        |=================+==========================================|
        |         16      |     (Q1),(I1)                            |
        |          8      |     (Q2,Q1),(I2,I1)                      |
        |          4      |     (Q4,Q3,Q2,Q1),(I4,I3,I2,I1)          |
        |          2      |     (Q8,Q7,...Q1),(I8,I7,...I1)          |
        |          1      |     (Q16,Q15,...Q1),(I16,I15,...I1)      |
        |============================================================|
 
        Once per second the RT sends the accumulated data records from
        each sub-channel to the Data Processor (DP) over a 100 Mbit/s
        ethernet connection.  In addition to the samples, each data
        record includes header information such as time tags and NCO
        frequency and phase that are necessary for analysis.  The DP
        processes the data records to provide monitor data, such as
        power spectra.  If recording has been enabled, the records
        are stored by the DP.
 
        NCO Phase and Frequency
        -----------------------
          At the start of each DSN pass, the RSR is provided with a
          file containing a list of predicted frequencies. Using
          these points, the RT computes expected sky frequencies at
          the beginning, middle, and end of each one second time
          interval. Based on the local oscillator frequencies
          selected and any offsets entered, the RT computes the
          coefficients of a frequency polynomial fitted to the DDC
          channel frequencies at these three times.  The RT also
          computes a phase polynomial by integrating the frequency
          polynomial and matching phases at the one second
          boundaries.
 
          The phase and frequency of the VDP NCO's are computed every
          millisecond (000-999) from the polynomial coefficients as
          follows:
 
              nco_phase(msec) = phase_coef_1 +
                                phase_coef_2 * (msec/1000) +
                                phase_coef_3 * (msec/1000)**2 +
                                phase_coef_4 * (msec/1000)**3
 
              nco_freq(msec)  = freq_coef_1 +
                                freq_coef_2 * ((msec + 0.5)/1000) +
                                freq_coef_3 * ((msec + 0.5)/1000)**2
 
          The sky frequency may be reconstructed using
 
                  sky_freq = RF_to_IF_LO +
                             DDC_LO -
                             nco_freq +
                             reside_freq
 
            where  RF_to_IF_LO  is the down conversion from the
                                microwave frequency to IF (bytes
                                42-43 in the data record header)
                   DDC_LO       is the down-conversion applied in the
                                DIG and DDC (bytes 40-41 in the data
                                record header)
                   Resid_Freq   is the frequency of the signal in the
                                VDP output
 
 
    Detectors - DSN
    ===============
      Nominal carrier tracking loop threshold noise bandwidth at
      X-band is 10 Hz.  Coherent (two-way) closed-loop
      system stability is shown in the table below:
 
            integration time            Doppler uncertainty
                 (secs)               (one sigma, microns/sec)
                 ------               ------------------------
                    10                            50
                    60                            20
                  1000                             4
 
      For the open-loop subsystem, signal detection is done in
      software.
 
 
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
 
 
      DSCC Receiver-Exciter Subsystem
      -------------------------------
        The diplexer in the signal path between the transmitter and
        the feed horns on all antennas may be configured so
        that it is out of the received signal path in order to
        improve the signal-to-noise ratio in the receiver system.
        This is known as the 'listen-only' or 'bypass' mode.
 
 
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
        typically of 880/749.  In the non-coherent mode, the
        downlink carrier frequency is derived from the spacecraft
        on-board crystal-controlled oscillator.  Either closed-loop
        or open-loop receivers (or both) can be used with either
        spacecraft frequency reference mode.  Closed-loop reception
        in two-way mode is usually preferred for routine tracking.
        Occasionally the spacecraft operates coherently while two
        ground stations receive the 'downlink' signal; this is
        sometimes known as the 'three-way' mode.
 
 
    Location - DSN
    ==============
      Station locations are documented in [GEO-10REVD].  Geocentric
      coordinates are summarized here.
 
                            Geocentric  Geocentric  Geocentric
      Station              Radius (km) Latitude (N) Longitude (E)
      ---------            ----------- ------------ -------------
      Goldstone
        DSS 13 (34-m R&D)  6372.125125  35.0660185   243.2055430
        DSS 14 (70-m)      6371.993286  35.2443527   243.1104638
        DSS 15 (34-m HEF)  6371.966540  35.2403133   243.1128069
        DSS 24 (34-m BWG)  6371.973553  35.1585349   243.1252079
        DSS 25 (34-m BWG)  6371.983060  35.1562594   243.1246384
        DSS 26 (34-m BWG)  6371.993032  35.1543411   243.1269849
 
      Canberra
        DSS 34 (34-m BWG)  6371.693561 -35.2169868   148.9819620
        DSS 43 (70-m)      6371.689033 -35.2209234   148.9812650
        DSS 45 (34-m HEF)  6371.675906 -35.2169652   148.9776833
 
      Madrid
        DSS 45 (34-m BWG)  6370.025429  40.2357708   355.7459008
        DSS 63 (70-m)      6370.051221  40.2413537   355.7519890
        DSS 65 (34-m HEF)           (see next paragraph)
 
      The coordinates for DSS 65 until 1 February 2005 were
                           6370.021697  40.2373325   355.7485795
      In cartesian coordinates (x, y, z) this was
                 (+4849336.6176, -0360488.6349, +4114748.9218)
      Between February and September 2005, the antenna was
      physically moved to
                 (+4849339.6448, -0360427.6560, +4114750.7428)
 
 
    Measurement Parameters - DSN
    ============================
      Closed-loop data are recorded in Tracking and Navigation Service
      Files (TNFs), as well as certain secondary products such as the
      Orbit Data File (ODF).  The TNFs are comprised of SFDUs that
      have variable-length, variable-format records with mixed typing
      (i.e., can contain ASCII, integer, and floating-point items in
      a single record). These files all contain entries that include
      measurements of Doppler, Range, and signal strength, along with
      status and uplink frequency information.
 
 
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
      BPF      Band Pass Filter
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
      DDC      Digital Down Converter
      DEC      Declination
      deg      degree
      DIG      RSR Digitizer
      DMC      DSCC Monitor and Control Subsystem
      DOR      Differential One-way Ranging
      DP       Data Processor
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
      FIR      Finite impulse Response
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
      IFS      IF Selector Switch
      IVC      IF Selection Switch
      JPL      Jet Propulsion Laboratory
      K        Kelvin
      Ka-Band  approximately 32 GHz
      KaBLE    Ka-Band Link Experiment
      kbps     kilobits per second
      kHz      kilohertz
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
      LPF      Low Pass Filter
      m        meters
      MCA      Master Clock Assembly
      MCCC     Mission Control and Computing Center
      MDA      Metric Data Assembly
      MGS      Mars Global Surveyor
      MHz      Megahertz
      MOLA     Mars Orbiting Laser Altimeter
      MON      Monitor and Control System
      MOT      Mars Observer Transponder
      MSA      Mission Support Area
      N        north
      NAR      Noise Adding Radiometer
      NBOC     Narrow-Band Occultation Converter
      NCO      Numerically Controlled Oscillator
      NIST     SPC 10 time relative to UTC
      NIU      Network Interface Unit
      NOCC     Network Operations and Control System
      NRV      NOCC Radio Science/VLBI Display Subsystem
      NSS      NOCC Support System
      OCI      Operator Control Input
      ODF      Orbit Data File
      ODR      Original Data Record
      ODS      Original Data Stream
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
      RSR      Radio Science Receiver
      RSS      Radio Science Subsystem
      RT       Real-Time (control computer)
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
      TNF      Tracking and Navigation File
      TSF      Tracking Synthesizer Frequency
      TWM      Traveling Wave Maser
      TWNC     Two-Way Non-Coherent
      TWTA     Traveling Wave Tube Amplifier
      UNK      unknown
      USO      UltraStable Oscillator
      UTC      Universal Coordinated Time
      VCO      Voltage-Controlled Oscillator
      VDP      VME Data Processor
      VF       Video Frequency
      X-band   approximately 7800-8500 MHz

        