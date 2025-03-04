
 
    Instrument Overview
    ===================
      The Mars Global Surveyor (MGS) Radio Science investigations
      utilized instrumentation with elements on the spacecraft and
      at the NASA Deep Space Network (DSN).  Much of this was
      shared equipment, being used for routine telecommunications
      as well as for Radio Science.  The performance and
      calibration of both the spacecraft and tracking stations
      directly affected the radio science data accuracy, and they
      played a major role in determining the quality of the
      results.  The spacecraft part of the radio science
      instrument is described immediately below; that is followed
      by a description of the DSN (ground) part of the instrument.
 
 
    Instrument Specifications - Spacecraft
    ======================================
      The Mars Global Surveyor spacecraft telecommunications
      subsystem served as part of a radio science subsystem for
      investigations of Mars.  Many details of the subsystem are
      unknown; its 'build date' is taken to be 1994-10-12, which
      was during the Prelaunch Phase of the Mars Global Surveyor
      mission.
 
      Instrument Id                  : RSS
      Instrument Host Id             : MGS
      Pi Pds User Id                 : UNK
      Instrument Name                : RADIO SCIENCE SUBSYSTEM
      Instrument Type                : RADIO SCIENCE
      Build Date                     : 1994-10-12
      Instrument Mass                : UNK
      Instrument Length              : UNK
      Instrument Width               : UNK
      Instrument Height              : UNK
      Instrument Manufacturer Name   : UNK
 
 
    Instrument Overview - Spacecraft
    ================================
      The spacecraft radio system was constructed around a
      redundant pair of X-band Mars Observer Transponders (MOT).
      Other components included two redundant Low-Gain Receive
      antennas (LGR); two redundant Low-Gain Transmit antennas
      (LGT); two redundant Command Detector Units (CDU); two
      redundant Traveling Wave Tube Amplifiers (TWTA); a single
      high-gain antenna (HGA); a single UltraStable Oscillator
      (USO); miscellaneous cables, connectors, waveguides, and
      switches; and a Ka-band Link Experiment (KaBLE).
 
      The X-band capability reduced plasma effects on radio
      signals by a factor of 10 compared with previous S-band
      systems, but absence of a dual-frequency capability (both
      S- and X-band) meant that plasma effects could not be
      estimated and removed from radio data.
 
      The spacecraft was capable of X-band uplink commanding and
      simultaneous X-band downlink telemetry.  The MOT generated a
      downlink signal in either a 'coherent' or a 'non-coherent'
      mode, also known as the 'two-way' and 'one-way' modes,
      respectively.  When operating in the coherent mode, the MOT
      behaved as a conventional transponder; its transmitted
      carrier frequency was derived coherently from the received
      uplink carrier frequency with a 'turn-around ratio' of
      880/749.  The nominal coherent downlink frequency was
      8417716050 Hz.
 
      In the non-coherent mode, the downlink carrier frequency was
      derived from one of the spacecraft's on-board crystal-
      controlled oscillators.  After warm-up, the 'auxiliary'
      oscillator (AUX OSC) frequency was estimated to be
      8417700000. Hz.  A temperature-controlled UltraStable
      Oscillator (USO) was used as the frequency reference during
      one-way Radio Science observations.  Representative USO
      frequencies (at X-Band) are shown in the table below:
 
      Earth Receive Date and Time  Frequency (Hz)   Drift (Hz/s)
      ---------------------------  --------------  -------------
            1997-270T07:23:52      8423152969.720   +1.8560E-06
            1998-049T02:19:38      8423152989.927   +1.5034E-06
            1999-095T14:55:53      8423153024.367   +4.5321E-07
            2000-001T05:54:53      8423153036.279   +3.7603E-07
            2001-001T04:43:45      8423153045.552   +2.3561E-07
            2003-001T05:25:58      8423153056.611   +1.1274E-07
            2005-001T01:26:05      8423153062.908   +8.9172E-08
 
      A Traveling Wave Tube Amplifier (TWTA), driven at
      saturation, amplified the MOT output before the signals
      were radiated via (nominally) the 1.5 m diameter parabolic
      high gain antenna (HGA).  During Inner Cruise, maneuvers,
      and spacecraft anomalies the TWTA output was fed to a low-
      gain transmitting antenna.  Nominal Effective Isotropic
      Radiated Power (EIRP) for both high- and low-gain antennas
      is shown below:
 
        Quantity                  Units     HGA          LGT
                                         (Mapping) (Inner Cruise)
        ------------------------  -----  --------- --------------
        RF Power Output            dBm     44.23        44.23
        Transmitter Circuit Loss   dB      -0.97        -1.37
        Boresight Antenna Gain     dBi     38.72         6.90
        Antenna Pointing Loss      dB      -0.30        -4.60
                                           -----        -----
             EIRP toward Earth     dB      81.68        45.16
 
      The strength of a spacecraft carrier signal, and thus the
      quality of the radio science data, depends on its modulation
      state.  Mars Global Surveyor telemetry data were sent to
      Earth at rates between 10 bits per second (bps) and 75
      kilobits per second (kbps).  Minimum Pt/No ratio (total
      signal power to receiver noise in 1 Hz bandwidth) was 43 dB
      during Inner Cruise with LGT1 transmitting to a 34-m HEF
      on the ground; this would support a data rate of at least 8
      kbps.  For Outer Cruise Pt/No began at 76 dB and dropped
      monotonically to 50 dB, the latter supporting a data rate
      of 43 kbps.  During Mapping, Pt/No varied between 47 dB and
      64 dB, allowing data rates to 34-m HEF antennas of at least
      21 kbps.
 
      The HGA consisted of a 1.5-meter Cassegrain reflector system
      with a dual-frequency (X- and Ka-band) feed horn.
      Reflector, subreflector, and struts were spares from the
      Mars Observer mission.  The feed horn was a new Lockheed
      Martin Astronautics (LMA) design consisting of co-located
      X- and Ka-band elements.  A radome fabricated of reinforced
      germanium-coated Kapton covered the entire HGA aperture to
      protect the system from the predicted aerobraking thermal
      environment.  TWTAs and associated components were enclosed
      and mounted on the back of the HGA structure.
 
      The HGA structure was mounted at the end of a 2-meter boom
      with two gimbals to control azimuth and elevation pointing.
      Certain parts of the sky were not visible with the HGA, but
      pointing toward Earth was possible from all parts of the
      orbit (see important exceptions described in the section
      'Operational Considerations - Spacecraft' below).  The HGA
      azimuth gimbal was used during Mapping to track the slowly
      changing seasonal (apparent) motion of the Earth.  The HGA
      elevation gimbal rotated at orbital rate to track the Earth
      and was rewound every orbit during Earth occultation.  The
      orbital rate was 0.051 deg/sec, and the rewind rate was
      0.12 deg/sec.  Stepper motors controlled both gimbals. Step
      size was 0.009375 deg; the stepping rate of approximately
      5 per second was visible as a 5 Hz modulation in open-loop
      Radio Science data collected after HGA deployment.
 
      HGA performance is defined in terms of gain and beamwidth.
      The table below summarizes some of those data.  Beamwidth is
      half-power, full-width, one-way.  Nominal polarization is
      right-hand circular in all cases.
 
       Quantity             X-Band     X-Band     Ka-Band Downlink
                            Uplink    Downlink
       --------             ------ ------- ------ ------- --------
       Frequency Reference    N/A  AUX OSC   USO  AUX OSC    USO
                                   or  VCO
       Frequency     (MHz)  7164.6  8417.7 8423.1 31987.3  32008.0
       Beamwidth     (deg)   1.717   1.546  1.546   0.375    0.375
       Axial Ratio   (dB)      1.0     1.0    1.0     1.0      1.0
       Measured Gain (dBi)   37.43   39.10  38.72   49.14    48.99
 
      Low-gain antennas were light-weight, low-cost microstrip
      patch antennas derived from earlier missile and spacecraft
      programs.  Their performance is summarized below.  Axial
      ratio is defined over +/- 85 degrees from boresight.
      Beamwidth is half-power, full-width, one-way.  Nominal
      polarization is right-hand circular in all cases.
 
       Quantity                X-Band Uplink     X-Band Downlink
       --------                -------------     ---------------
       Center Frequency (MHz)       7200               8400
       Bandwidth        (MHz)        45                 50
       Axial Ratio      (dB)         <8                 <8
       Beamwidth        (deg)        80                 80
       Gain             (dBi)       6.3                6.9
 
      More information can be found in the MGS Telecommunications
      System Operations Reference Handbook [JPLD-14027].
 
 
    Science Objectives
    ==================
      Two different types of radio science experiments were
      conducted with Mars Global Surveyor: radio tracking
      experiments in which the magnitude and direction of the
      planet's gravity field were derived from the Doppler (and,
      sometimes, ranging) measurements, and radio propagation
      experiments in which signal modulation detected on Earth
      could be attributed to properties of the medium.  Several
      variations of the radio propagation experiments were carried
      out including radio occultations by the atmosphere of Mars
      and scattering from its surface.  Measurements were also
      obtained when the radio wave passed through the solar corona.
 
 
      Gravity Measurements
      --------------------
        Measurement of the gravity field provides significant
        constraints on inferences about the interior structure of
        Mars.  Precise, detailed study of the spacecraft motion
        in Mars orbit can yield the mass distribution of the
        planet.  Topographic data obtained by the Mars Orbiting
        Laser Altimeter (MOLA) forms a critical adjunct to these
        measurements since only after the gravitational effects
        are adjusted for topography can the gravity anomalies be
        interpreted geophysically.
 
        Studies of the gravity field emphasize both the global
        field and local characteristics of the field.  The first
        task is to determine the global field.  Doppler and range
        tracking measurements yield accurate spacecraft trajectory
        solutions.  Simultaneously with reconstruction of the
        spacecraft orbit, observation equations for field
        coefficients and a small number of ancillary parameters
        can be solved.  This type of gravity field solution is
        essential for characterizing tectonic phenomena and can
        also be used to study localized features.  An early
        gravity model based on MGS data was presented by
        [SMITHETAL1999].  Later versions were described in
        [LEMOINEETAL2001] and [YUANETAL2001].
 
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
 
        A by-product of the gravity field analysis is information
        on the density structure of the upper atmosphere
        [TRACADISETAL2001].
 
 
      Radio Occultation Measurements
      ------------------------------
        Atmospheric measurements by the method of radio
        occultation contribute to an improved understanding of
        structure, circulation, dynamics, and transport in the
        atmosphere of Mars.  These results are based on detailed
        analysis of the radio signal received from MGS as it
        entered and exited occultation by the planet.  Two phases
        of the atmospheric investigation may be defined.  The
        first is to obtain vertical profiles of atmospheric
        structure with emphasis on investigation of large-scale
        phenomena.  The second is to concentrate on studies of
        scintillations in the signal, which provide information
        on smaller scale variations -- e.g, turbulence.
 
        Retrieval of atmospheric profiles requires coherent
        samples of the radio signal that has propagated through
        the atmosphere, plus accurate knowledge of the antenna
        pointing and the spacecraft trajectory.  The latter was
        obtained first from the MGS Navigation Team and later
        from high quality orbits derived by the Team's own
        gravity investigators.  Initial solutions from MGS
        occultations provided atmospheric structure -- temperature
        and pressure vs. absolute radius -- to altitudes as high
        as about 50 km from the surface [HINSONETAL1999].
 
        The spatial and temporal coverage in the radio occultation
        experiments are determined by the geometry of the
        spacecraft orbit and the dates and times at which
        occultation data were acquired.  Since radio occultation
        experiments were conducted on a regular basis using a
        polar orbit, there was extensive occultation coverage at
        high northern and southern latitudes (e.g., beyond 60
        degrees).  Often several occultations were observed in
        succession in each hemisphere at time spacings of less
        than two hours.  Later in the primary mission, as the
        orbit appeared to drift from edge-on to nearly broadside
        as viewed from Earth, occultation points moved toward the
        equator and the entry/exit angle approached grazing.
        For several months in 1999, there were no occultations at
        all.  More than 21000 neutral atmosphere profiles had
        been derived from MGS radio occultations by the end of
        the mission.
 
        No scintillations which could be attributed to turbulence
        were detected in the occultation data.
 
        It is also possible to retrieve profiles of electron
        density in the ionosphere from occultation data.  When
        the density is high enough, it reduces the refractive
        index of the medium (where the neutral atmosphere
        increases the refractive index) causing the radio wave
        phase to be advanced.  The methods for retrieval are
        somewhat different since hydrostatic equilibrium cannot
        be assumed in the plasma.  5600 electron density
        profiles were derived from MGS data, mostly near the
        terminator [BOUGHERETAL2001][BOUGHERETAL2004]
        [WITHERSETAL2005].
 
 
      Bistatic Surface Scattering Measurements
      ------------------------------------------
        For a few seconds before and after geometrical occultation
        the HGA illuminated a small strip of surface as well as
        the atmosphere.  Under some circumstances, an echo could be
        observed from the surface.  For smooth surfaces, the echo
        properties (particular the strength) could be related to the
        surface dielectric constant through the Fresnel reflection
        equations.  For rougher surfaces, diffraction and surface
        wave phenomena may play a role.  Surface echoes were
        sought during most occultation events and several thousand
        were studied in some detail [TYLERETAL2001].
 
        The spacecraft telecommunications antenna could also be
        pointed toward the surface of the planet.  The strength
        of the scattered signal from the illuminated area could
        then be interpreted in terms of the dielectric constant
        of the surface through the Fresnel equations; the
        frequency dispersion of the signal could be related to the
        texture of the surface at the reflecting point.  One such
        experiment was conducted over the Mars Polar Lander/Deep
        Space 2 site in May 2000 [SIMPSON&TYLER2001].
 
        For some surface materials, the Fresnel equations do not
        apply; most of the signal penetrates the surface and is
        scattered by the volume below.  Clean water ice is known
        to have these properties, and has been postulated as the
        cause of anomalous scattering from the Galilean satellites
        of Jupiter and from polar deposits on both Mercury and
        Mars.  Interpreting such observations quantitatively is not
        straightforward, but Mars Global Surveyor had the
        potential for collecting such data in a bistatic geometry,
        providing additional insight on the surface structure
        and properties.  Although such observations were sought,
        none were ever scheduled.
 
 
      Search for Gravitational Waves
      ------------------------------
        During the MGS Cruise Phase, nearly continuous radio
        tracking of the spacecraft was conducted.  At the same time
        an effort was made to keep on-board spacecraft activity to
        a minimum.  The objective during this period was to search
        for evidence that gravitational waves were passing through
        the solar system while the spacecraft was at maximum
        separation from known massive bodies.  A gravitational wave
        was expected to change the position and motion of the
        spacecraft, the Earth, or both.  Two-way tracking was used;
        both closed-loop and open-loop data were collected, the
        latter being more sensitive but also more voluminous.  Sources
        of gravitational waves have been postulated outside the solar
        system [ANDERSONETAL1993][ESTABROOKETAL1995], but no
        unambiguous detection of such radiation has ever been made.
 
 
      Solar Scintillation and Faraday Rotation Experiments
      ----------------------------------------------------
        Solar scintillation and Faraday rotation experiments are
        conducted to improve our understanding of the structure
        and dynamics of the solar corona and wind.  Because Mars
        orbits the Sun, spacecraft like MGS are transported behind
        the solar disk, as seen from Earth.  Radio waves
        propagating between MGS and Earth stations are refracted
        and scattered (scintillation) by the solar plasma
        [WOO1993].  Intensity fluctuations can be related to
        fluctuations in electron density along the path, while
        Doppler or phase scintillations can be related to both
        electron density fluctuations and also the speed of the
        solar wind.  Many plasma effects decrease as the
        square of the radio frequency; scintillations are about an
        order of magnitude stronger at X-band than Ka-band.
        The first solar conjunction observed with MGS was on
        12 May 1998; more data were collected and archived two
        years later [BARBINIS2001].
 
 
    Operational Considerations - Spacecraft
    =======================================
      Descriptions given above are for nominal performance.  The
      spacecraft transponder system comprised redundant units,
      each with slightly different characteristics.  As
      transponder units age, their performance changes slightly.
      More importantly, the performance for radio science depended
      on operational factors such as the modulation state for the
      transmitters, which cannot be predicted in advance.  The
      performance also depended on factors which were not always
      under the control of the Mars Global Surveyor Project.
 
      Early in the Mapping phase, the HGA assembly encountered an
      obstruction.  Two gimbals allowed the HGA to point toward
      Earth; the elevation gimbal rotated the HGA in the orbit
      plane, and the azimuth gimbal pointed the HGA out of the orbit
      plane at the Earth 'beta' angle.  The obstruction prevented
      the azimuth gimbal from pointing at any beta angle less than
      41.5 deg.  After the anomaly (1999-04-15) and until the beta
      angle exceeded 41.5 deg (1999-05-06), the spacecraft was
      operated in the Fixed High Gain Antenna (FHGA) configuration.
      The Earth beta angle dropped below 41.5 deg again in February
      2000 and remained there until June 2001, during which the
      spacecraft was operated in the 'Beta Supplement' mode.
 
      In Beta Supplement the spacecraft was oriented so that the
      azimuth gimbal could be set to the supplement of the beta angle;
      the elevation gimbal was flipped.  The supplement to the beta
      angle ranged from 139 to 183 deg during the second year of
      Mapping.  But there was physical interference between the HGA
      and its boom; and HGA rewinds, which normally occurred while
      the spacecraft was occulted, now took place on the 'front'
      side of the planet.  The boom interference precluded collection
      of occultation egress measurements during most of Mapping; the
      HGA rewind reduced the amount of nearside radio tracking that
      could be captured.
 
      During normal operations, the spacecraft sensed solar
      eclipses; a pre-programmed timing offset initiated onboard
      radio occultation activities so that orbit prediction errors
      would not affect collection of occultation data.  During Beta
      Supplement, all occultation times were derived from the MGS
      Navigation Team Orbit Propagation and Timing Geometry file;
      when the OPTG predicted occultation time was in error by more
      than about 40 s, occultation data were lost (for example on
      2001-02-06 and 2001-02-07).
 
      The HGA azimuth obstruction mysteriously disappeared during a
      'safe' mode event which ended on 2005-09-28.  After testing,
      the spacecraft was allowed to fly in its normal (non-Beta
      Supplement) configuration for the remainder of the mission.
      And, when other restrictions were not imposed, occultations
      at both ingress and egress were recorded.
 
 
    Calibration Description - Spacecraft
    ====================================
      No information available.
 
 
    Platform Mounting Descriptions - Spacecraft
    ===========================================
      Origin of the spacecraft reference frame was located at the
      intersection of the spacecraft/launch vehicle interface
      plane and the spacecraft central axis -- that is, at the
      bottom of the propulsion unit nozzle. The spacecraft +Z axis
      was along the spacecraft central axis and normal to the
      nadir equipment deck; the main engine was aimed in the -Z
      direction.  The +X axis vector was in the direction of the
      velocity vector during Mapping.  +X was also in the
      direction of the HGA boresight during Cruise, and the HGA
      boom was mounted to the +X panel of the propulsion module.
      The +Y axis completed an orthogonal rectangular coordinate
      system.  The +/-Y axes defined generally the deployment
      directions of the solar panels.  The solar cells themselves
      were on the -Z sides of the panels.
 
      The primary LGT was mounted on the TWTA enclosure, which
      was mounted on the rim of the HGA reflector; its boresight
      was aligned with the HGA boresight, which was in the +X
      direction until HGA deployment.  The backup (LGT2) was also
      mounted on the TWTA enclosure; its boresight was aligned at
      a cant angle approximately 160 degrees away from the shared
      boresights of the HGA and LGT1. This angle was chosen to
      minimize the consequences of a gimbal failure once HGA
      articulation began after deployment of the HGA boom in the
      mapping orbit.  LGT2 was not used prior to HGA deployment
      because its orientation and proximity to the nadir payload
      deck would lead to irradiation of the payload instruments
      while the HGA was in its stowed position.  One LGR was
      mounted on the -X panel of the equipment module; the other
      was on the +X side of the propulsion module.
 
      The five MGS antennas -- HGA, primary and backup low-gain
      transmitting antennas (LGT1 and LGT2, respectively) and
      low-gain antennas for receiving on the +X and -X sides of
      the spacecraft (LGR1 and LGR2, respectively) are shown
      below in their stowed (pre-HGA deployment) configuration.
      Note that dimensions are given in inches; one inch (1 in)
      equals 0.0254 meters.
 
        -Y Side View:
 
                            ^ S/C +Z Axis
                            |
                            |
                            |  +39.318 in
                            |<----------->|
                            |             |
                            | +39.318 in  |
                            |<--------->| |
                            |           | |
                            | +20.72 in | |
                            |<-->|      | |
                   -25.81 in|
                    |<----->|  LGT2 __LGT1
                    |       |    @=|  |=@   ----------------
                    |       |      |  | __               ^
                    |       |      |__|/  |              |
                    | +-----------+   /   |              |
                    | |           |  /    |              |+81.46 in
                    | |           | /     |              |
                    | |           ||      |              |
             LGR2   | |           ||  HGA | ------       |
              ----- @=|           ||      |     ^        |
                ^     |-----------| \     |     |        |
                |     |           |  \    |     |        |
                |     |               \   |     |        |
                |     |     +31.75 in  \__|     |        |
                |     |     |<----->|           |        |
                |     |     |       | LGR1      |+66.15  |
                |     |           |=@ ---       |   in   |
                |     +----+-+----+    ^        |        |
                |+49.94   / | \        |+17.56  |        |
                |   in   /  |  \       |   in   |        |
                v       /   |   \      v        v        v
              -------- +----o----+  ------------------------>
                            | S/C Frame                S/C +X Axis
                            |   Origin
 
 
        Top View:
 
                            ^ S/C +Y Axis
                            |
                            |           __
                                 LGR1  /  |      |
                      +-----------+   /   |      v
                 |    |           |=@/ ------------
             0 in|    | S/C Frame | /     |      |+5.29 in
                 v    |  Origin   ||  HGA |      |
               ---- @=|     o     ||__    | ------------  --->
                 ^  LGR2          ||  |   |  ^   ^    ^   S/C +X Axis
                 |    |           ||  |   |  |        |
                      |           ||  |   |  |-28.18  |
                      +----+-+----+|  |   |  |   in   |-30.05 in
                                   |  |\__|  v        |
                                   |  |=@   ---       v
                                 @=|__| ---------------------
                               LGT2    LGT1
 
 
      The geometrical center of the HGA (coordinates given below)
      is taken to be the geometric center of the HGA reflector rim.
      This is not the phase center of the HGA.
 
      The geometric and phase centers of the low-gain antennas are
      taken to be at the centers of the 1.45 x 1.45 in square-shaped
      active elements of each antenna.
 
                           MGS Antenna Center Locations
                          (inches)              (meters)
                      X      Y      Z        X      Y      Z
                   ------ ------ ------   ------ ------ ------
           HGA     39.318   0.00  66.15    0.999  0.000  1.680
           LGT1    39.318 -28.18  81.46    0.999 -0.716  2.069
           LGT2    20.72  -30.05  81.56    0.526 -0.763  2.072
           LGR1    31.75    5.29  17.56    0.806  0.134  0.446
           LGR2   -25.81    0.00  49.94   -0.655  0.000  1.268
 
 
    Investigators
    =============
      Team Leader for the MGS Radio Science Team was G. Leonard
      Tyler of Stanford University.  Members of the Team
      conducting atmospheric investigations were David P. Hinson
      and Richard Woo.  Members conducting gravity investigations
      were Georges Balmino, William L. Sjogren, and David E.
      Smith.  John Armstrong (gravitational waves), Michael Flasar
      (atmospheres), and Richard Simpson (surface scattering) were
      selected as Participating Scientists.
 
 
    Instrument Section / Operating Mode Descriptions - Spacecraft
    =============================================================
      Redundant components (LGR, LGT, MOT, CDU, and TWTA) could
      be configured as desired.  Each configuration had slightly
      different performance, but the quantitative differences are
      unknown.
 
      Each Mars Observer Transponder (MOT)  responded to the
      the following commands:
 
       Command          Function
       -------          --------
       USO Enable       If MOT is in two-way noncoherent mode,
                         selects USO as downlink frequency
                         reference;
                        If MOT is in two-way coherent mode,
                         implements automatic transfer from VCO
                         to USO whenever on-board receiver loses
                         phase lock on uplink signal.
       USO Inhibit      If MOT is in two-way noncoherent mode,
                         selects AUX OSC as downlink frequency
                         reference;
                        If MOT is in two-way coherent mode,
                         implements automatic transfer from VCO
                         to AUX OSC whenever on-board receiver
                         loses phase lock on uplink signal.
       Ranging ON       Enables the ranging signal path to the
                         X-band phase demodulator
       Ranging OFF      Disables the ranging signal path to the
                         X-band phase demodulator
       DOR ON           Enables DOR generator, using downlink
                         frequency source to derive DOR tones
       DOR OFF          Disables DOR generator
       TWNC ON          Forces downlink frequency source to be
                         non-coherent (AUX OSC or USO),
                         independent of receiver lock status
       TWNC OFF         If on-board receiver is phase-locked to
                         uplink signal, forces downlink to be
                         generated from uplink
                        If on-board receiver is NOT phase-locked
                         to uplink, provides automatic transfer
                         to selected downlink frequency source
                         (AUX OSC or USO)
       TLM ON           Enables telemetry signal path to X-band
                         phase demodulator
       TLM OFF          Disables telemetry signal path to X-band
                         phase demodulator
 
 
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
      4.2-3.5 cm).  Transmitter output powers of up to 400 kW are
      available.
 
      Ground stations have the ability to transmit coded and uncoded
      waveforms which can be echoed by distant spacecraft.  Analysis
      of the received coding allows navigators to determine the
      distance to the spacecraft; analysis of Doppler shift on the
      carrier signal allows estimation of the line-of-sight
      spacecraft velocity.  Range and Doppler measurements are used
      to calculate the spacecraft trajectory and to infer gravity
      fields of objects near the spacecraft.  Very Long Baseline
      Interferometry (VLBI) techniques can be applied to determine
      the position of the spacecraft in the plane of the sky.  Use
      of VLBI became more common, especially for pre-encounter
      navigation, after loss of the Mars Climate Orbiter on
      23 September 1999.
 
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
 
      The DSN and its subsystems evolved over the 10+ year lifetime
      of the MGS mission.  Electronic (real-time) distribution of
      data superseded use of magnetic tape, and most subsystems were
      at least upgraded if not entirely replaced.  Changes critical
      to understanding collection and handling of radio science data
      are reflected in this document.  The reader should be aware,
      however, that details may be missing and that subsystems not
      central to radio science activities may be described more as
      they existed in the late 1990's rather than as they were at
      the end of science data collection in 2006.
 
      For more information on the Deep Space Network and its use in
      radio science see reports by [ASMAR&RENZETTI1993],
      [ASMAR&HERRERA1993], and [ASMARETAL1995].  For design
      specifications on DSN subsystems see [DSN810-5].  For DSN use
      with MGS Radio Science see [TYLERETAL1992], [TYLERETAL2001],
      and [JPLD-14027].
 
 
    Subsystems - DSN
    ================
      The Deep Space Communications Complexes (DSCCs) are an integral
      part of Radio Science instrumentation, along with the spacecraft
      Radio Frequency Subsystem.  Their system performance directly
      determines the degree of success of Radio Science
      investigations, and their system calibration determines the
      degree of accuracy in the results of the experiments.  The
      following paragraphs describe the functions performed by the
      individual subsystems of a DSCC.  This material has been adapted
      from [ASMAR&HERRERA1993] and [JPLD-14027]; for additional
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
 
        Open-Loop Receivers: Prior to December 2001 the Radio Science
        Open-Loop Receiver (OLR) was a dedicated four channel,
        narrow-band receiver which provided amplified and
        downconverted video band signals to the DSCC Spectrum
        Processing Subsystem (DSP); it sometimes was known as the
        'RIV'.  Beginning in mid-2001 for tests and starting in
        December 2001 for routine operations, open loop data were
        acquired using a new digital system -- the Radio Science
        Receiver (RSR) -- which is described below under
        'Electronics - DSN.'
 
        The OLR utilized a fixed first Local Oscillator (LO) frequency
        and a tunable second LO frequency to minimize phase
        noise and improve frequency stability.  The OLR consisted of
        an RF-to-IF downconverter located at the feed , an IF
        selection switch (IVC), and a Radio Science IF-VF
        downconverter (RIV) located in the SPC.  The RF-IF
        downconverters in the 70-m antennas were equipped for four IF
        channels: S-RCP, S-LCP, X-RCP, and X-LCP.  The 34-m HEF
        stations were equipped with a two-channel RF-IF: S-band and
        X-band.  The 34-m BWG stations varied in their capabilities.
        The IVC switched the IF input among the antennas.
 
        The RIV contained the tunable second LO, a set of video
        bandpass filters, IF attenuators, and a controller (RIC).
        The LO tuning was done via DSP control of the POCA/PLO
        combination based on a predict set.  The POCA was a
        Programmable Oscillator Control Assembly and the PLO was a
        Programmable Local Oscillator (commonly called the DANA
        synthesizer).  The bandpass filters were selectable via the
        DSP.  The RIC provided an interface between the DSP and the
        RIV.  It was controlled from the LMC via the DSP.  The RIC
        selected the filter and attenuator settings and provided
        monitor data to the DSP.  The RIC could also be manually
        controlled from the front panel in case the electronic
        interface to the DSP was lost.
 
        RF Monitor -- SSI and PPM: The RF monitor group of the
        Receiver-Exciter Subsystem provided spectral measurements
        using the Spectral Signal Indicator (SSI) and measurements of
        the received channel system temperature and spacecraft signal
        level using the Precision Power Monitor (PPM).
 
        The SSI provided a local display of the received signal
        spectrum at a dedicated terminal at the DSCC and routed these
        same data to the DSP which routed them to NOCC for remote
        display at JPL for real-time monitoring and RIV/DSP
        configuration verification.  These displays were used to
        validate Radio Science Subsystem data at the DSS, NOCC, and
        Mission Support Areas.  The SSI configuration was controlled
        by the DSP and a duplicate of the SSI spectrum appeared on
        the LMC via the DSP.  During real-time operations the SSI
        data also served as a quick-look science data type for Radio
        Science experiments.
 
        The PPM measured system noise temperatures (SNT) using a
        Noise Adding Radiometer (NAR) and downlink signal levels
        using the Signal Level Estimator (SLE).  The PPM accepted its
        input from the closed-loop receiver.  The SNT was measured by
        injecting known amounts of noise power into the signal path
        and comparing the total power with the noise injection 'on'
        against the total power with the noise injection 'off.' That
        operation was based on the fact that receiver noise power is
        directly proportional to temperature; thus measuring the
        relative increase in noise power due to the presence of a
        calibrated thermal noise source allowed direct calculation of
        SNT.  Signal level was measured by calculating an FFT to
        estimate the SNR between the signal level and the receiver
        noise floor where the power was known from the SNT
        measurements.
 
        There was one PPM controller at the SPC which was used to
        control all SNT measurements.  The SNT integration time
        could be selected to represent the time required for a
        measurement of 30K to have a one-sigma uncertainty of 0.3K
        or 1%.
 
        When the DSP was replaced by the RSR in late 2001, many of
        the SSI and PPM functions were absorbed into the RSR.  SNT
        calibration because part of the DSN Monitor function.
 
 
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
        at JPL produces an archival form of these products for later
        analysis.
 
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
 
 
      DSCC Spectrum Processing Subsystem (DSP)
      ----------------------------------------
        Until it was decommissioned in early 2002 the DSCC Spectrum
        Processing Subsystem (DSP) located at the SPC digitized and
        recorded the narrowband output data from the RIV.  It
        consisted of a Narrow Band Occultation Converter
        (NBOC) containing Analog-to-Digital Converters (ADCs), a
        ModComp CLASSIC computer processor called the Spectrum
        Processing Assembly (SPA), and several magnetic tape drives.
        Magnetic tapes containing DSP output were known as Original
        Data Records (ODRs).  Electronic near real-time data
        transmission (known as an Original Data Stream, or ODS) was
        the default for Mars Global Surveyor.
 
        The DSP was originally operated through the LMC.  During
        1996-97 a remote operations capability was developed by the
        JPL Radio Science Systems Group so that the DSP could be
        operated from JPL.
 
        Using the SPA-Radioscience (SPA-R) software, the DSP allowed
        for real-time frequency and time offsets (while in RUN mode)
        and, if necessary, snap tuning between the two frequency
        ranges transmitted by the spacecraft: coherent and
        non-coherent.  The DSP received Radio Science frequency
        predicts from the CMC, allowed for multiple predict set
        archiving (up to 60 sets) at the SPA, and allowed for manual
        predict generation and editing.  It accepted configuration and
        control data from the LMC (or remote operations console),
        provided display data to the LMC (or remote operations
        console), and transmitted the signal spectra from the SSI as
        well as status information to NOCC and the Project Mission
        Support Area (MSA) via the GCF data lines.  The DSP recorded
        the digitized narrowband samples and the supporting header
        information (i.e., time tags, POCA frequencies, etc.) on
        9-track magnetic tapes in 6250 or 1600 bpi GCR format and/or
        on a local disk for later transmission to JPL.
 
        Through the DSP-RIC interface the DSP controlled the RIV
        filter selection and attenuation levels.  It also received
        RIV performance monitoring via the RIC.  In case of failure
        of the DSP-RIC interface, the RIV could be controlled
        manually from the front panel.
 
        All the RIV and DSP control parameters and configuration
        directives were stored in the SPA in a macro-like file called
        an 'experiment directive' table.  A number of default
        directives existed in the DSP for the major Radio Science
        experiments.  Operators could create their own table entries.
 
        Items such as verification of the configuration of the prime
        open-loop recording subsystem, the selection of the required
        predict sets, and proper system performance prior to the
        recording periods were checked in real-time at JPL via the
        NOCC displays using primarily the remote SSI display at NOCC
        and the NRV displays.  Because of this, transmission of the
        DSP/SSI monitor information was enabled prior to the start of
        recording.  The specific run time and tape recording times
        were identified in the Sequence of Events (SOE) and/or DSN
        Keyword File.
 
        The DSP could be used to duplicate ODRs.  It also had the
        capability to play back a certain section of the recorded
        data after conclusion of the recording periods.
 
 
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
      Performance of DSN ground stations depends primarily on size
      of the antenna and capabilities of electronics.  These are
      summarized in the following set of tables.  Beamwidth is
      half-power full angular width.  Polarization is circular;
      L denotes left circular polarization (LCP), and R denotes
      right circular polarization (RCP).
 
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
 
 
    Electronics - DSN
    =================
 
      DSCC Open-Loop Receiver (RIV) (valid until late 2001)
      -----------------------------------------------------
        The open loop receiver block diagram shown below was for the
        RIV system at 70-m and 34-m HEF and BWG antenna sites until
        late in 2001, when it was superseded by the Radio Science
        Receiver (RSR) (see below).  Input signals at both S- and
        X-band were mixed to approximately 300 MHz by fixed-frequency
        local oscillators near the antenna feed.  Based on a tuning
        prediction file, the POCA controlled the DANA synthesizer,
        the output of which (after multiplication) mixed the 300 MHz
        IF to 50 MHz for amplification.  These signals in turn were
        down converted and passed through additional filters until
        they yielded output with bandwidths up to 45 kHz.  The Output
        was digitally sampled and either written to magnetic tape or
        electronically transferred for further analysis.
 
          S-Band                                          X-Band
         2295 MHz                                        8415 MHz
          Input                                            Input
            |                                                |
            v                                                v
           ---     ---                              ---     ---
          | X |<--|x20|<--100 MHz        100 MHz-->|x81|-->| X |
           ---     ---                              ---     ---
            |                                                |
         295|                                                |315
         MHz|                                                |MHz
            v                                                v
           ---     --                 33.1818       ---     ---
          | X |<--|x3|<------           MHz ------>|x11|-->| X |
           ---     --        |115          |        ---     ---
            |                |MHz          |                 |
            |                |             |                 |
          50|      71.8181  ---           ---                |50
         MHz|         MHz->| X |         | X |<-10MHz        |MHz
            v               ---           ---                v
           ---               ^             ^                ---
          | X |<--60 MHz     |             |      60 MHz-->| X |
           ---               |   approx    |                ---
            |        9.9     | 43.1818 MHz |      9.9        |
            |        MHz      -------------       MHz        |
            |         |             ^              |         |
          10|         v             |              v         |10
         MHz|        ---       ----------         ---        |MHz
            |------>| X |     |   DANA   |       | X |<------|
            |        ---      |Synthesizr|        ---        |
            |         |        ----------          |         |
            v         v             ^              v         v
         -------   -------          |           -------   -------
        |Filters| |Filters|    ----------      |Filters| |Filters|
        |3,4,5,6| |  1,2  |   |   POCA   |     |  1,2  | |3,4,5,6|
         -------   -------    |Controller|      -------   -------
            |         |        ----------          |         |
          10|         |0.1                      0.1|         |10
         MHz|         |MHz                      MHz|         |MHz
            v         v                            v         v
           ---       ---                          ---       ---
10 MHz -->| X |     | X |<------ 0.1 MHz ------->| X |     | X |<--
           ---       ---                          ---       ---    |
            |         |                            |         |  10 MHz
            v         v                            v         v
         Output     Output                      Output     Output
 
 
        Reconstruction of the antenna frequency from the frequency of
        the signal in the recorded data could be achieved through use
        of one of the following formulas.  Filters are defined below.
 
   FSant=3*SYN+1.95*10^9+3*(790/11)*10^6+Frec        (Filter 4)
        =3*SYN+1.95*10^9+3*(790/11)*10^6-Fsamp+Frec  (Filters 1-3,5,6)
 
   FXant=11*SYN + 7.940*10^9 +   Fsamp - Frec        (Filter 4)
        =11*SYN + 7.940*10^9 - 3*Fsamp + Frec        (Filters 1,2,3,6)
 
       where
           FSant,FXant  are the antenna frequencies of the incoming
                         signals at S and X bands, respectively,
           SYN          is the output frequency of the DANA
                         synthesizer, commonly labeled the readback
                         POCA frequency on data tapes,
           Fsamp        is the effective sampling rate of the digital
                         samples, and
           Frec         is the apparent signal frequency in a spectrum
                              reconstructed from the digital samples.
 
              NB: For many of the filter choices (see below) the
                  Output is that of a bandpass filter.  The sampling
                  rates in the table below are sufficient for the
                  bandwidth but not the absolute maximum frequency,
                  and aliasing results.  The reconstruction
                  expressions above are appropriate ONLY when the
                  sample rate shown in the tables below is used.
 
      Radio Science Receiver (RSR) (used after mid-2001)
      --------------------------------------------------
 
        The Radio Science Receiver (RSR) was tested for Mars Global
        Surveyor starting in mid-2001 and then used routinely for MGS
        open loop data collection beginning in December 2001.  For
        more information, see [JPLD-16765].
 
        A radio frequency (RF) spacecraft signal at S-band, X-band,
        or Ka-band is captured by a receiving antenna on Earth, down
        converted to an intermediate frequency (IF) near 300 MHz and
        then fed via a distribution network to one input of an IF
        Selector Switch (IFS).  The IFS allows each RSR to select any
        of the available input signals for its RSR Digitizer (DIG).
        Within the RSR the digitized signal is then passed to the
        Digital Down Converter (DDC), VME Data Processor (VDP), and
        Data Processor (DP).
 
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
        attenuator, adjusted to provide the proper level to the Analog
        to Digital Converter (ADC).  The attenuated signal is then
        passed through a Band Pass Filter (BPF) which selects a
        frequency band in the range 265-375 MHz.  The filtered output
        from the BPF is then mixed with a 256 MHz Local Oscillator
        (LO), low pass filtered (LPF), and sampled by the ADC.  The
        output of the ADC is a stream of 8-bit real samples at 256
        Msamples/second (Msps).  DIG timing is derived from the
        station FTS 5 MHz clock and 1 pulse per second (1PPS)
        reference; the DIG generates a 256 MHz clock signal for later
        processing.  The 1 PPS signal marks the data sample taken at
        the start of each second.
 
        The DDC selects one 16 MHz subchannel from the possible 128
        MHz bandwidth available from the DIG by using Finite Impulse
        Response (FIR) filters with revolving banks of filter
        coefficients.  The sample stream from the DIG is separated
        into eight decimated streams, each of which is fed into two
        sets of FIR filters.  One set of filters produces in-phase (I)
        8-bit data while the other produces quadrature-phase (Q) 8-bit
        data.  The center frequency of the desired 16 MHz channel is
        adjustable in 1 MHz steps and is usually chosen to be near the
        spacecraft carrier frequency.  After combining the I and Q
        sample streams, the DDC feeds the samples to the VDP.  The DDC
        also converts the 256 MHz data clock and 1PPS signals into a
        msec time code, which is also passed to the VDP.
 
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
        operation all four sets of custom boards can be
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
        power spectra.  If recording has been enabled, the records are
        stored by the DP.
 
        NCO Phase and Frequency
        -----------------------
          At the start of each DSN pass, the RSR is provided with a
          file containing a list of predicted frequencies. Using these
          points, the RT computes expected sky frequencies at the
          beginning, middle, and end of each one second time interval.
          Based on the local oscillator frequencies selected and any
          offsets entered, the RT computes the coefficients of a
          frequency polynomial fitted to the DDC channel frequencies
          at these three times.  The RT also computes a phase
          polynomial by integrating the frequency polynomial and
          matching phases at the one second boundaries.
 
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
                             resid_freq
 
            where  RF_to_IF_LO  is the down conversion from the
                                microwave frequency to IF (bytes 42-43
                                in the data record header)
                   DDC_LO       is the down-conversion applied in the
                                DIG and DDC (bytes 40-41 in the data
                                record header)
                   resid_Freq   is the frequency of the signal in the
                                VDP output
 
 
    Filters - DSN
    =============
 
      DSCC Open-Loop Receiver (RIV)
      -----------------------------
        Nominal filter center frequencies and bandwidths for the RIV
        Receivers are shown in the table below.  Recommended sampling
        rates are also given.
 
                            S-Band                    X-Band
                   ------------------------  -------------------------
                   Output   3 dB   Sampling  Output   3 dB    Sampling
         Filter    Center   Band     Rate    Center   Band      Rate
                    Freq    Width            Freq     Width
                    (Hz)    (Hz)     (sps)   (Hz)     (Hz)      (sps)
         ------    ------  ------  --------  ------  ------   --------
            1         150      82      200      550      82        200
            2         750     415     1000     2750     415       1000
            3        3750    2000     5000    13750    2000       5000
            4        1023    1700     5000     3750    6250      15000
            5       75000   45000   100000   275000   45000     100000
            6       37500   20000    50000   137500   20000      50000
 
 
    Detectors - DSN
    ===============
 
      DSCC Open-Loop Receivers
      ------------------------
        Open-loop receiver output is detected in software by the
        radio science investigator.
 
 
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
 
 
      Open-Loop Receiver Attenuation Calibration
      ------------------------------------------
        The open-loop receiver attenuator calibrations are performed
        to establish the output of the open-loop receivers at a level
        that will not saturate the analog-to-digital converters.  To
        achieve this, the calibration is done using a test signal
        generated by the exciter/translator that is set to the peak
        predicted signal level for the upcoming pass.  Then the
        output level of the receiver's video band spectrum envelope
        is adjusted to the level determined by equation (3) below (to
        five-sigma).  Note that the SNR in equation (2) is in dB
        while the SNR in equation (3) is linear.
 
          Pn = -198.6 + 10*log(SNT) + 10*log(1.2*Fbw)              (1)
 
          SNR = Ps - Pn                               (SNR in dB)  (2)
 
          Vrms = sqrt(SNR + 1)/[1 + 0.283*sqrt(SNR)]  (SNR linear) (3)
 
           where    Fbw = receiver filter bandwidth (Hz)
                    Pn  = receiver noise power (dBm)
                    Ps  = signal power (dBm)
                    SNT = system noise temperature (K)
                    SNR = predicted signal-to-noise ratio
 
 
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
 
 
      Closed-Loop vs. Open-Loop Reception
      -----------------------------------
        Radio Science data can be collected in two modes: closed-
        loop, in which a phase-locked loop receiver tracks the
        spacecraft signal, or open-loop, in which a receiver samples
        and records a band within which the desired signal presumably
        resides.  Closed-loop data are collected using Closed-Loop
        Receivers, and open-loop data are collected using Open-Loop
        Receivers in conjunction with the DSCC Spectrum Processing
        Subsystem (DSP).  See the Subsystems section for further
        information.
 
 
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
 
 
      DSCC Spectrum Processing Subsystem (DSP)
      ----------------------------------------
        The DSP can operate in four sampling modes with from 1 to 4
        input signals.  Input channels are assigned to ADC inputs
        during DSP configuration.  Modes and sampling rates are
        summarized in the tables below:
 
        Mode   Analog-to-Digital Operation
        ----   ----------------------------
          1    4 signals, each sampled by a single ADC
          2    1 signal, sampled sequentially by 4 ADCs
          3    2 signals, each sampled sequentially by 2 ADCs
          4    2 signals, the first sampled by ADC #1 and the second
                           sampled sequentially at 3 times the rate
                            by ADCs #2-4
 
             8-bit Samples               12-bit  Samples
            Sampling  Rates              Sampling  Rates
         (samples/sec per ADC)        (samples/sec per ADC)
         ---------------------        ---------------------
                 50000
                 31250
                 25000
                 15625
                 12500
                 10000                        10000
                  6250
                  5000                         5000
                  4000
                  3125
                  2500
                                               2000
                  1250
                  1000                         1000
                   500
                   400
                   250
                   200                          200
 
        Input to each ADC is identified in header records by a Signal
        Channel Number (J1 - J4).  Nominal channel assignments are
        shown below.
 
             Signal Channel Number        Receiver
                                           Channel
             ---------------------      -------------
                      J1                    X-RCP
                      J2                    S-RCP
                      J3                    X-LCP
                      J4                    S-LCP
 
 
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
 
      Open-Loop System
      ----------------
        Output from the Open-Loop Receivers (OLRs), as sampled and
        recorded for later analysis, is a stream of 8- to 16-bit
        quantized voltage samples.  The nominal input to the
        Analog-to-Digital Converters (ADCs) is +/-10 volts, but the
        precise scaling between input voltages and output digitized
        samples is usually irrelevant for analysis; the digital
        data are generally referenced to a known noise or signal
        level within the data stream itself -- for example, the
        thermal noise output of the radio receivers which has a
        known system noise temperature (SNT).  Raw samples
        comprise the data block in each output record; a header
        record contains ancillary information such as:
 
         time tag for the first sample in the data block
         RMS values of receiver signal levels and ADC outputs
         local oscillator (e.g., POCA) frequency and drift rate
 
 
      Closed-Loop System
      ------------------
        Through early 2003 closed-loop data were recorded in Archival
        Tracking Data Files (ATDFs), as well as certain secondary
        products such as the Orbit Data File (ODF).  The ATDF Tracking
        Logical Record contained 150 entries including status
        information and measurements of ranging, Doppler, and signal
        strength.  Starting in December 2002 the Network
        Simplification Plan (NSP) brought in a new phase-based
        closed-loop system with both higher precision and higher
        accuracy.  Nearly 20 different record formats were defined
        under the umbrella of the new Tracking and Navigation File
        (TNF).  Ground stations were converted one at a time so that
        ATDF production ended with one pass and TNF production began
        on the next.
 
 
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
      FIR      Finite Impulse Response
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
      NIST     SPC 10 time relative to UTC
      NIU      Network Interface Unit
      NOCC     Network Operations and Control System
      NRV      NOCC Radio Science/VLBI Display Subsystem
      NSP      Network Simplification Plan
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
      VLBI     Very Long Baseline Interferometry
      VCO      Voltage-Controlled Oscillator
      VF       Video Frequency
      X-band   approximately 7800-8500 MHz

        