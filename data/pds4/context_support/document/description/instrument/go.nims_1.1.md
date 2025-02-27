
 
  Instrument Overview
  ===================
    The Galileo Near Infrared Mapping Spectrometer is described by
    Carlson et al, 1992 [CARLSONETAL1992].  A major subset of the
    instrument description in the reference appears on all NIMS CDs in
    the [DOCUMENT.NIMSINST] directory.
 
    NIMS is an imaging spectrometer capable of obtaining measurements in
    the 0.7 to 5.2 micron region.  The spectral resolution is .0125
    microns at wavelengths below 1 micron, and .0250 micron at
    wavelengths above 1 micron.  The instantaneous field of view is
    approximately 0.5 x 0.5 milliradians.  Instrument cycle times vary
    from about 1/60 second to 8 2/3 seconds.
 
    The instrument has 17 detectors, permitting 17 near-simultaneous
    measurements which are spaced approximately evenly across the
    wavelength region.  The dispersion element is a dual-blaze grating
    which may be stepped to obtain additional 17 wavelength sets, with
    small wavelength offsets from previous measurements.  Various
    grating step sizes and initial grating offsets are possible.  For a
    nominal instrument grating cycle (12 steps), the instrument can
    measure 204 wavelengths across the 0.7-5.2 micron region in 4 1/3
    seconds.  There are four commandable gain ranges for all detectors
    except the last three, which have automatic gain ranging with two
    gains.
 
    The instrument acquires spatial information by utilizing motions of
    the spacecraft scan platform, 'pushbroom imaging',  and motions of
    a secondary mirror.  The secondary mirror moves in a direction
    perpendicular to the mounting plate and sweeps out 20 pixels
    yielding an effective field of view of 10 milliradians over the
    mirror sweep time (1/3 second).  The order of acquisition is
    detector (17 at a time), mirror position (20, alternately down and
    up), grating position (0 to 24 steps).
 
 
  Scientific Objectives
  =====================
    Measurement of the composition of the Jovian atmosphere and the
    composition of the surfaces of the Galilean satellites.
 
 
  Calibration
  ===========
 
    Flight calibrations
    -------------------
      Flatfield radiometric calibration target operated at about 300 K.
 
      Solar illuminated photometric calibration target of sandblasted
      aluminum.
 
      Dark Levels.
 
      Stars.
 
 
    Ground calibrations
    -------------------
      Wavelength calibration based on Hg 5461 angstrom line
      (in multiple orders) and a laboratory grating spectrometer.
 
      Detector spatial response (two-dimensional) based on knife-edge
      sources.
 
      Blackbody calibration.
 
      NIST FEL lamp calibration.
 
      Measurement of instrument response sensitivity to temperature.
 
 
  Operational Considerations
  ==========================
    Rate of motion of target body through field of view must be
    carefully coordinated with instrument mode.
 
    Target motion in spacecraft cone direction preferred.
 
    Focal plane must be operated at temperatures below 88K.
 
    Radiator must be kept clean, and cannot view warm sources for any
    length of time.
 
    Boresight must not be pointed closer than 12 degrees to sun.
 
 
  Detectors
  =========
    Seventeen individual photovoltaic diodes, tantalum shield.
 
       2 Silicon  0.7 - 1.0 microns.
 
       15 InSb     1.0 - 5.2 microns.
 
 
  Electronics
  ===========
    Seventeen channel signal chain.
 
    Multilayer circuit boards.
 
    Ten-bit digitization.
 
    RCA 1802-based control processor with 1.5K of RAM, 1.5K of ROM.
 
 
  Filters
  =======
    Order blocking interference filters, placed on focal plane array.
 
 
  Optics
  ======
    Ritchey-Chretien telescope, 22.8 cm diameter, f/3.5, 800 mm focal
    length.
 
    Operating temperature about 150 K.
 
    Etendue 1.1 x 10^-4 cm^2 steradian.
 
 
  Spectrometer
  ============
    39 lines per mm plane grating spectrometer.
 
    400 mm focal length, f/3.5, Dall-Kirkham collimator.
 
    200 mm focal length, f/1.8, flat-field camera.
 
    Bipartite diffraction grating, 30% blazed for 1.9 u, 70% blazed
    for 3.8 u.
 
    Operating temperature about 150 K.
 
 
  Mounting Offsets
  ================
    Co-aligned with SSI, UVS and PPR instruments.
 
    Offset from imaging instrument (SSI) 0.25 x 0.25 mrad
    (see I-kernel).
 
 
  Field of View
  =============
    IFOV = 0.5x0.5 milliradians.
 
    Nominal FOV = 10x0.5 milliradians (in 1/3 second).
 
 
  Data Rates
  ==========
    11.52 kbits/second (nominal, from instrument).
 
 
  Data modes
  ==========
 
    Instrument modes
    ----------------
 
      mode      cycle_time    wavelengths_per_cycle
 
      Long      8 2/3 sec            408
      Full      4 1/3 sec            204
      Short     2 1/3 sec            102
      Bandedge  1 1/3 sec             34
      Fixed       1/3 sec             17
 
      During Jupiter operations, any combination of sampled wavelengths
      may be returned.
 
 
    Telemetry modes (Jupiter operations)
    ------------------------------------
      MPW      11.520 kbits/sec to tape
      LPU       6.168 kbits/sec to tape
      LNR       2.592 kbits/sec to tape
 
      Actual downlink rate of recorded data depends on on-board
      compression and editing of data but will probably not exceed
      60-80 bits/sec.
 
      RT8      10 bits/sec to ground for occasional realtime data return

        