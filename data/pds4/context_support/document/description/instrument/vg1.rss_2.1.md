
 
    Instrument Overview
    ===================
      Voyager Radio Science investigations at the giant planets
      utilized instrumentation with elements both on the spacecraft
      and at the DSN.  Much of this was shared equipment, being used
      for routine telecommunications as well as for Radio Science.
      The performance and calibration of both the spacecraft and
      tracking stations directly affected the radio science data
      accuracy, and they played a major role in determining the
      quality of the results.  The spacecraft part of the radio
      science instrument is described immediately below; in most
      cases, the description applies equally well to both Voyager 1
      and Voyager 2 and it applies throughout the Voyager mission.  
      The description of the DSN (ground) part of the instrument may
      be found in DSN context products.  
 
    Instrument Specifications
    =========================
      The Voyager spacecraft telecommunications subsystem served as
      part of a radio science subsystem for investigations of the
      giant planets.  Many details of the subsystem are unknown; its
      'build date' is taken to be 1977-09-05, the launch date for
      Voyager 1.  
 
      Instrument Id                 : RSS-VG1S
      Instrument Host Id            : VG1
      Pi Pds User Id                : UNK
      Instrument Name               : RADIO SCIENCE SUBSYSTEM
      Instrument Type               : RADIO SCIENCE
      Build Date                    : 1977-09-05
      Instrument Mass               : UNK
      Instrument Length             : UNK
      Instrument Width              : UNK
      Instrument Height             : UNK
      Instrument Manufacturer Name  : UNK
 
    Instrument Overview
    ===================
      The spacecraft radio system was constructed around a redundant
      pair of transponders.  Each transponder was equipped with an
      S-band receiver (2115 MHz nominal frequency) and transmitters
      at both S-band (2295 MHz nominal) and X-band (8415 MHz nominal).
      Compared with S-band, X-band was less sensitive to plasma effects
      by a factor of about 10; use of both frequencies coherently on
      the 'downlink' allowed estimation of plasma content along the
      radio path.  Use of X-band also significantly improved the
      quality of radio tracking data for gravity investigations.
 
      The transponder generated downlink signals in either 'coherent'
      or 'non-coherent' modes, also known as 'two-way' and 'one-way',
      respectively.  When operating in the coherent mode, the
      transmitted carrier frequency was derived coherently from the
      received uplink carrier frequency with a 'turn-around ratio' of
      240/221 at S-band and (11/3)*240/221 at X-band.
 
      In non-coherent mode the transmitted frequency was controlled
      by an on-board oscillator; the X- and S-band remained coherent
      in the ratio 11/3.  A single Ultra-Stable Oscillator (USO) was
      used during radio occultations; it provided stabilities
      several orders of magnitude better than the conventional
      crystal oscillators, which were part of each transponder.
 
      Stability of the Voyager USO was specified in terms of its
      Allan Deviation -- the fractional frequency deviation from
      linear drift.  Over 10 minute periods, the Allan
      Deviation ranged from 10**-12 to 4 10**-12 for integrations of
      1-10 sec.  Long-term fractional drift of the oscillator was
      about 5 10**-11 per day.  Although the oscillator was hardened,
      there were discontinuities in the drift when the spacecraft
      passed through the radiation belts of the outer planets.
      Equivalent X-band microwave frequencies for the Voyager 1 USO
      during key events were:
                     8,414,995,272.530 Hz (Titan occultation)
                     8,414,995,272.376 Hz (Saturn occultation)
      Multiplying by 3/11 yields the S-band frequency.
 
      Traveling wave tube or solid state amplifiers boosted the
      transponder output.  Output powers of 9 and 26  watts could
      be selected at S-band; the choices at X-band were 12 and 22
      watts.
 
      The signals were radiated via a 3.66 m diameter parabolic high
      gain antenna (HGA).  The transmit boresight gain of the HGA was
      36 dB at S-band and 47 dB at X-band.  The half-power
      half-width of the antenna beam was 0.32 degrees at X-band and
      1.1 degrees at S-band.  Transmit polarization was right-hand
      circular at S-band and either right- or left-hand circular at
      X-band.  A Low-Gain Antenna (LGA) was mounted on the feed
      structure of the HGA and radiated approximately uniformly over
      the hemisphere into which the HGA pointed.  It was used during
      maneuvers, spacecraft anomalies, and at other times when the
      HGA was not appropriate.
 
      For receiving, the S-band HGA gain was 35 dB at 2115 MHz and the
      polarization was right-hand circular.  The receiving system
      noise temperature was approximately 2000 K, the carrier tracking
      loop bandwidth was 18 Hz, and the ranging channel noise
      bandwidth was 1.5 MHz.
 
    Operational Considerations
    ==========================
      Descriptions given here are for nominal performance.  The
      spacecraft transponder system comprised redundant units,
      each with slightly different characteristics.  As the
      transponder units ages, their performance changed slightly.
      More importantly, the performance for radio science depended
      on operational factors such as the modulation state for the
      transmitters, which cannot be predicted in advance.  The
      performance also depended on factors which were not always
      under the control of the Voyager Project.
 
      Spacecraft receivers were designed to lock to the uplink
      signal.  Without locking, Doppler effects -- resulting from
      relative motion of the spacecraft and ground station -- could
      result in loss of the radio link as the frequency of the
      received signal drifted.  A series of failures in the Voyager 2
      receivers left that transponder unable to track the uplink 
      signal.  Beginning in April 1978, Doppler shifts were predicted 
      and the uplink carrier was tuned so that Voyager 2 would see what
      appeared to be a signal at constant frequency (to an accuracy of 
      100 Hz.  There were no such problems with Voyager 1.
 
      During deep occultations by the giant planets, the bending angle
      resulting from refraction exceeded 10 degrees in some cases --
      well beyond the half power beamwidth of the spacecraft antenna.
      In those cases, the pointing of the HGA was adjusted so that
      it followed a 'virtual' Earth and maximum signal strength could
      be sustained.  These 'limb-track' maneuvers were critically
      dependent on accurate timing during the encounter.  To protect
      against Voyager 1 timing errors at Titan (primarily from
      uncertainties in the radius and position of the satellite),
      no limb-track was attempted during ingress, and a fixed
      antenna offset was used during egress.  Fortunately, timing was
      accurate enough that useful data were obtained from each event.
 
      Although the spacecraft radioisotope thermoelectric generators
      were not dependent on solar flux for power, their output decayed
      as the Voyager spacecraft moved outward through the solar
      system.  During encounters with the outer planets, caution was
      required in budgeting power and the high-power mode could not
      be used for the radio transmitters.
 
    Calibration Description
    =======================
      Prior to and during some encounter sequences, the spacecraft
      was commanded to execute a 'mini-ASCAL' maneuver.  The HGA was
      moved slightly above the Earth line then slightly below the
      Earth line.  The procedure was repeated to the left and right
      of the Earth line so that a 'cross-hair' pattern was mapped
      out.  During the maneuver, the amplitude of the carrier
      signal was measured carefully.  Analysis of the results
      showed whether the HGA was pointed accurately and, if not,
      allowed estimation of the error magnitude and direction.
 
      Prior to and after encounters, the spacecraft frequency
      reference was switched to the USO for several hours and the
      carrier signal was monitored using equipment at the DSN.
      These 'USO Tests' were used to calibrate the frequency and
      frequency drift of the USO.  USO tests were particularly
      important before and after the spacecraft entered a severe
      radiation environment since the radiation typically damaged
      the crystal and changed its characteristics slightly.
 
    Platform Mounting Descriptions
    ==============================
      The centerline of the bus was the roll axis of the
      spacecraft; it also served as the z-axis of the spacecraft
      coordinate system with the high-gain antenna (HGA) boresight
      defining the negative z-direction.  The HGA boresight was
      also defined as cone angle 0 degrees and as azimuth 180
      degrees, elevation 7 degrees.  The Low-Gain Antenna (LGA)
      was mounted on the feed structure of the HGA and radiated
      approximately uniformly over the hemisphere into which the
      HGA pointed.
 
    Instrument Section / Operating Mode Descriptions
    ================================================
      The Voyager radio system consisted of two sections, which
      could be operated in the following modes:
 
      Section      Mode
      -------------------------------------------
      Oscillator   two-way (coherent)
                   one-way (non-coherent)
      RF output    low-gain antenna
                   high-gain antenna
 
      Selected parameters describing NASA Standard Transponder (NST)
      performance are listed below:
 
      Oscillator Parameters:                    S-Band     X-Band
         Two-Way Transponder Turnaround Ratio  240/221    880/221
         One-Way Transmit Frequency (MHz)        2296.      8415.
         Nominal Wavelength (cm)                13.06       3.56
 
      RF Output parameters:                     S-Band     X-Band
         RF Power Output (w)                   9 or 26    12 or 22
         Low-Gain Antenna:
           Half-Power Half Beamwidth (deg)        UNK
           Gain (dBi)                             UNK
           EIRP (dBm)                             UNK
           Polarization                         Circular
         High-Gain Antenna:
           Half-Power Half-Beamwidth (deg)        1.1       0.32
           Gain (dBi)                              36        47
           Polarization                           RCP    RCP or LCP
 
    ACRONYMS AND ABBREVIATIONS
    ==========================
      dB       decibel
      dBi      dB relative to isotropic
      dBm      dB relative to one milliwatt
      deg      degree
      DSN      Deep Space Network
      JPL      Jet Propulsion Laboratory
      K        Kelvin
      LCP      Left-Circularly Polarized
      MHz      Megahertz
      RCP      Right-Circularly Polarized
      RF       Radio Frequency
      S-band   approximately 2100-2300 MHz
      sec      second
      SLE      Signal Level Estimator
      UNK      unknown
      X-band   approximately 7800-8500 MHz
      
    