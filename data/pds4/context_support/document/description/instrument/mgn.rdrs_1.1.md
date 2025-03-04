
 
 
    Instrument Specifications
    =========================
      The radar was manufactured by Hughes Aircraft Company and the
      'build date' is taken to be 1989-01-01.  The radar dimensions
      were 0.304 by 1.35 by 0.902 (height by length by width in
      meters) and the mass was 126.1 kg.
 
      Instrument Id                  : RDRS
      Instrument Host Id             : MGN
      Pi Pds User Id                 : GPETTENGILL
      Instrument Name                : RADAR SYSTEM
      Instrument Type                : RADAR
      Build Date                     : 1989-01-01
      Instrument Mass                : 126.100000
      Instrument Length              : 1.350000
      Instrument Width               : 0.902000
      Instrument Height              : 0.304000
      Instrument Manufacturer Name   : HUGHES AIRCRAFT
 
      For more information on the radar system see the papers by
      [JOHNSON1990] and [SAUNDERSETAL1990].
 
 
    Instrument Overview
    ===================
      The Magellan radar system included a 3.7 m diameter high gain
      antenna (HGA) for SAR and radiometry and a smaller fan-beam
      antenna (ALTA) for altimetry.  The system operated at 12.6 cm
      wavelength.  Common electronics were used in SAR, altimetry,
      and radiometry modes.  The SAR operated in a burst mode;
      altimetry and radiometry observations were interleaved with the
      SAR bursts.
 
      Between SAR bursts (typically several times a second) groups of
      altimeter pulses were transmitted from a dedicated fan-beam
      altimeter antenna directed toward the spacecraft's nadir.  The
      altimeter pulses were identical in waveform and bandwidth to
      the SAR pulses, resulting in a range accuracy of better than 15
      m.  The pulse-repetition rate and burst duration differed
      between the two modes.
 
      Radiometry data were obtained by spending a portion of the time
      between SAR bursts and after altimeter operation in a passive
      (receive-only) mode, with the HGA antenna capturing the
      microwave thermal emission from the planet.  Noise power within
      the 10-MHz receiver bandwidth was detected and accumulated for
      50 ms.  To reduce the sensitivity to receiver gain changes in
      this mode, the receiver was connected on alternate bursts first
      to a comparison dummy load at a known physical temperature and
      then to the HGA.  The short-term temperature resolution was
      about 2 K; the long-term absolute accuracy after calibration
      was about 20 K.
 
 
    Science Objectives
    ==================
      See MISSION_OBJECTIVES_SUMMARY under MISSION.
 
 
    Operational Considerations
    ==========================
      The Magellan radar system was used to acquire radar
      back-scatter (SAR) images, altimetry, and radiometry when the
      spacecraft was close to the planet.  Nominal operation extended
      from about 20 minutes before periapsis until about 20 minutes
      after periapsis.  In the SAR mode output from the radar
      receiver was sampled, blocks of samples were quantized using an
      adaptive procedure, and the results were stored on tape.  In
      the altimetry mode samples were recorded directly, without
      quantization.  Radiometry measurements were stored in the radar
      header records.  During most of the remainder of each orbit,
      the HGA was pointed toward Earth and the contents of the tape
      recorder were transmitted to a station of the DSN at
      approximately 270 kilobits/second.  SAR, altimetry, and
      radiometry data were then processed using ground software into
      images, altimetry profiles, estimates of backscatter
      coefficient, emissivity, and other quantities.
 
 
    Calibration Description
    =======================
      The radar was calibrated before flight using an active
      electronic target simulator [CUEVAS1989].
 
 
    Platform Mounting Descriptions
    ==============================
      The spacecraft +Z axis vector was in the nominal direction of
      the HGA boresight.  The +X axis vector was parallel to the
      nominal rotation axis of the solar panels.  The +Y axis vector
      formed a right-handed coordinate system and was in the nominal
      direction of the star scanner boresight.  The spacecraft
      velocity vector was in approximately the -Y direction when the
      spacecraft was oriented for left-looking SAR operation.  The
      nominal HGA polarization was linear in the y-direction.
 
      Cone Offset Angle              : 0.00
      Cross Cone Offset Angle        : 0.00
      Twist Offset Angle             : 0.00
 
      The altimetry antenna boresight was in the x-z plane 25 degrees
      from the +Z direction and 65 degrees from the +X direction.
      The altimetry antenna was aimed approximately toward nadir
      during nominal radar operation.  The altimetry antenna
      polarization was linear in the y-direction.
 
      The medium gain antenna boresight was 70 degrees from the +Z
      direction and 20 degrees from the -Y direction.  The low gain
      antenna was mounted on the back of the HGA feed; it's boresight
      was in the +Z direction and it had a hemispherical radiation
      pattern.
 
 
    Principal Investigator
    ======================
      The Principal Investigator for the radar instrument was Gordon
      H. Pettengill.
 
 
    Instrument Section / Operating Mode Descriptions
    ================================================
      The Magellan radar system consisted of the following sections,
      each of which operated in the following modes:
 
      Section      Mode
      -------------------------------------------
      SAR          Synthetic Aperture Radar (SAR)
      ALT          Altimetry
      RAD          Radiometry
 
 
      (1) SAR Characteristics
      -----------------------
        In the Synthetic Aperture Radar mode, the radar transmitted
        bursts of phase-modulated pulses through its high gain
        antenna.  Echo signals were captured by the antenna, sampled
        at the receiver output, and stored on tape after being
        quantized to reduce data volume.  Pulse repetition rate and
        incidence angle were chosen to meet a minimum signal-to-noise
        ratio requirement (8 dB) for image pixels after ground
        processing.  Multiple looks were used in processing to reduce
        speckle noise.  Incidence angles varied from about 13 degrees
        at the pole to about 44 degrees at periapsis during normal
        mapping operations (e.g., Cycle 1); but other 'look angle
        profiles' were used during the mission.
 
        Peak transmit power                 : 350 watts
        Transmitted pulse length            : 26.5 microsecs
        Pulse repetition frequency          : 4400-5800 per sec
        Time bandwidth product              : 60
        Inverse baud width                  : 2.26 MHz
        Data quantization (I and Q)         : 2 bits each
        Recorded data rate                  : 750 kilobits/sec
        Polarization (nominal)              : linear horizontal
        HGA half-power full beam width      : 2.2 deg (azimuth)
                                            : 2.5 deg (elev)
            one-way gain (from SAR RF port) : 35.7 dBi
        System temperature (viewing Venus)  : 1250 K
        Surface resolution (range)          : 120-360 m
                           (along track)    : 120-150 m
        Number of looks                     : 4 or more
        Swath width                         : 25 km (approx)
        Antenna look angle                  : 13-47 deg
        Incidence angle on surface          : 18-50 deg
 
        Data Path Type                      : RECORDED DATA
                                               PLAYBACK
        Instrument Power Consumption        : UNK
 
 
      (2) ALT Characteristics
      -----------------------
        After SAR bursts (typically several times a second) groups of
        altimeter pulses were transmitted from a dedicated fan beam
        altimeter antenna (ALTA) directed toward the spacecraft's
        nadir.  Output from the radar receiver was sampled, and the
        samples were stored on tape for transmission to Earth.
        During nominal left-looking SAR operation the ALTA pointed
        approximately 20 deg to the left of the spacecraft ground
        track at periapsis and about 10 deg to the right of the
        ground track near the north and south pole.
 
        Data quantization (I and Q)           : 4 bits each
        Recorded data rate                    : 35 kbs
        Polarization                          : linear
        ALTA half-power full beamwidth
                                 (along track): 11 deg
                                 (cross track): 31 deg
             one-way gain referenced to
                                  ALT RF port : 18.9 dBi
        ALTA offset from HGA                  : 25 deg
        Burst interval                        : 0.5-1.0 sec
              duration                        : 1.0 millisec
        Dynamic range                         : 30 dB (or more)
 
        Data Path Type                        : RECORDED DATA
                                                 PLAYBACK
        Instrument Power Consumption          : UNK
 
 
      (3) RAD Characteristics
      -----------------------
        Radiometry measurements were made by the radar receiver and
        HGA in a receive-only mode that was activated after the
        altimetry mode to record the level of microwave radiothermal
        emission from the planet.  Noise power within the 10-MHz
        receiver bandwidth was detected and accumulated for 50 ms.
        To reduce the sensitivity to receiver gain changes in this
        mode, the receiver was connected on alternate bursts first to
        a comparison dummy load at a known physical temperature and
        then to the HGA.  The short-term temperature resolution was
        about 2 K; the long-term absolute accuracy after calibration
        was about 20 K.  At several times during the mission,
        radiometry measurements were carried out using known cosmic
        radio sources.
 
        Receiver Bandwidth                  : 10 MHz
        Integration Time                    : 50 millisecs
        Polarization (nominal)              : linear horizontal
        Data Quantization                   : 12 bits
        Data Rate                           : 10-48 bits/sec
        HGA half-power full beam width      : 2.2 deg
        System temperature (viewing Venus)  : 1250 K
        Antenna look angle                  : 13-47 deg
        Incidence angle on surface          : 18-50 deg
        Surface resolution (along track)    : 15-120 km
                           (cross track)    : 20-125 km
 
        Data Path Type                : RECORDED DATA PLAYBACK
        Instrument Power Consumption  : UNK
 

        