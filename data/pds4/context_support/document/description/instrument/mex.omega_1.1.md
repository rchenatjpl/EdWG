
 
  Instrument Overview
  ===================
    OMEGA is a mapping spectrometer working both in the visible and
    the infrared spectral ranges.  It is made of two co-aligned
    channels, one working in the 0.38 to 1.05 micrometers visible and
    near infrared range (VNIR channel), the other in the 0.93 to 5.1
    micrometers short wavelength infrared range (SWIR channel).  The
    data products constitute three-dimensional (X,Y,lambda) image-
    cubes, with two spatial and one spectral dimensions.  The VNIR
    channel uses a bi- dimensional CCD detector, operated in a
    pushbroom mode.  Its telescope acquires at once in its focal plane
    one cross-track line corresponding to the entire 8.8 degrees FOV,
    defined by an entrance slit; the second dimension of the image is
    provided by the motion of the S/C.  Each line is spectrally
    dispersed along the columns of the array, the slit being imaged
    through a concave holographic grating. The SWIR channel operates
    in the whiskbroom mode: each imaged pixel is acquired at once by
    an IR telescope; a scanning mirror, in front of the telescope,
    permits to acquire crosstrack swaths of 16 up to 128 pixels width,
    for a maximum FOV of 8.8 degrees, thus matching the VNIR FOV,
    while the S/C motion provides the second spatial dimension. The
    imaged pixel is focused by the telescope on a slit, followed by a
    collimator.  The beam is then split towards two separated
    spectrometers, to acquire the IR spectrum of each resolved pixel
    onto two InSb linear arrays of 128 spectels each, from 0.93 to
    2.73 micrometers and from 2.55 to 5.1 micrometers respectively.
    Each array is cooled down 70K by a dedicated cryocooler, while the
    entire spectrometer is cooled down 190 K by a conductive link to a
    passive radiator.  The typical IR integration time, defined by the
    S/C ground track velocity and the spatial sampling chosen, is 5
    msec.  The corresponding VNIR integration times are 100 to 800 ms,
    depending on the swath width, thus the altitude.  With such
    integration times, SNR > 100, over the entire spectral range, is
    the specification.
 
    OMEGA is made of two distinct units:
 
    - a Camera unit (OMEGA-C) with the VNIR and SWIR spectrographs,
      their associated electrical devices, and one electronics
      assembly for the control of the camera.  All units are
      integrated onto a common base plate; its mass is 23.8 kg.
 
    - a Main Electronics module (OMEGA-ME), for the data processing
      and the general management of the instrument; its mass is
      5.1 kg.
 
    VNIR spectrograph
    -----------------
      VNIR is made of two optical subsystems: a focusing telescope
      with its focal plane on a slit, and a spectrometer, that spreads
      the slit image in the spectral dimension.  It provides image
      data in the spectral range 0.38 to 1.05 micrometers achieving a
      maximum spatial sampling of 0.4 mrad and a maximum spectral
      sampling of 50 Angstrom. A refractive telescope focuses the
      image on a slit placed on the Rowland circle of an aberration
      corrected concave holographic grating mirror.  This element
      reflects and disperses the light on a CCD detector tangent to
      the Rowland circle.  The detector used is the TH7863 frame
      transfer CCD produced by Thomson.  The chosen grating mirror can
      create a flat image onto the focal plane.  This property allows
      to match very well the flat detector matrix to the grating,
      without other optical components.  A CCD frame is then composed
      of N rows each containing an image of the slit at a given
      wavelength, and M columns each containing the spectrum of a
      point along the slit. The bi-dimensional image of the surface is
      obtained by the pushbroom technique, in which the spacecraft
      movement along its orbit performs a scan of the slit across the
      planetary surface.  The electrical signal from the detector is
      amplified and then digitized by a fast 12 bit A/D converter;
      after conversion, all data are processed within
      the OMEGA-ME.
 
      In order to decrease the detector noise, VNIR is cooled down 190
      K by conduction to the SWIR mechanical unit.  The choice of
      refractive over reflective optics was made because of the large
      (8.8 degrees) field of view requirement.  The telescope has a 6
      elements objective similar to that of a modern commercial
      photographic camera.  The shape of the elements and the types of
      optical glass were chosen to obtain the best chromatic
      aberration corrections over the entire spectral range.  The last
      element serves as a field lens which matches the entire
      objective with the grating to avoid light losses. To avoid
      stress in the lenses at the working temperature, the two
      doublets are not cemented.  The two glasses, FK54 and fused
      silica, have very different expansion coefficients of 8 and 0.55
      x 10E-6/K at room temperature.  The entrance aperture of 15.6 mm
      is defined by a diaphragm between the two doublets.
 
      An aberration corrected concave holographic grating is placed 142.7
      mm from the entrance slit (which is in the focal plane of the
      telescope).  The grating is tilted to form the spectrum at an
      angle of roughly 6 degrees from the optical axis.  This angle
      does not allow CCD insertion near the entrance without beam
      obscuration; therefore, a folding mirror deflects the beam
      toward the side of the assembly, where the CCD can be mounted
      with ample clearance.  The zero order spectrum, at 4.5 degrees
      from the folded optical axis (lying in the y-z plane) is
      directed into a light trap to prevent degradation of the image.
      The first order spectrum ranges in angle from 6 degrees at
      lambda = 0.35 micrometers to 10 degrees for lambda = 1.05
      micrometers.  The second and higher order spectra can, in
      principle, also degrade the data. Its contribution depends both
      on the grating efficiency, and the spectral distribution of the
      incident radiation.  For this reason, a dedicated filter is
      mounted, in front of the detector.  The concave, spherical,
      holographic grating in a Rowland mounting - where the entrance
      slit and the spectrum are on radii of curvature of the grating -
      makes the spectrometer compact, light, and simple.  In fact, no
      collimator or camera lens is required and the spectrometer has
      only one element. Moreover, the focal plane image can be flat,
      to match the planar CCD sensors. Since the concave holographic
      grating is obtained by recording a perfect optical pattern with
      groove spacing absolutely constant, it has no ghosts. Stray
      light has also a much lower level than the best ruled gratings.
      Therefore, concave holographic gratings generally have a much
      higher signal to noise ratio than classically ruled gratings.
 
      The optical performances have been computed by ray tracing.  In
      the focal plane the spot diagram is about the pixel size (23x23
      microns). For off-axis propagation (4.4 degrees off-axis), the
      total spot size is about 2 pixels in the sagittal direction.
      More precisely, on axis and at 0.7 micrometers, 98.8 % of the
      energy falls within a 23x23 micron pixel; at 4.4 degrees off-
      axis and lambda = 0.4 micrometers, 74 % of the energy falls
      within a CCD element.  When the light propagates off-axis, the
      spot size is smaller for the shorter wavelengths.
 
      The Pattern Generator (PG) determines the CCD integration time,
      and generates the timing signals necessary to transfer an image
      from the light sensitive area to the masked zone and then to the
      output shift register of the CCD.  The output of the CCD is then
      amplified and converted by a fast 12 bit A/D converter under
      control of the PG. The timing of the instrument imposes a
      relatively high frequency for CCD operation.  In fact, depending
      on the distance from the planet and hence on the spacecraft
      speed, the time TR between consecutive frames can be chosen as:
      100, 200, 400 or 800 ms.  During the TR period the integration,
      readout and data transmission processes must occur.  To save
      time, integration and transmission of the previous frame are
      overlapped.  Because the maximum data value which can be
      transmitted during TR is limited to 12288 bytes, it is not
      possible to read the total frame of 384x288 pixels,
      corresponding to 110592 bytes.  We are forced to read only a
      sub-frame, or to reduce the number of pixels by summing them on
      chip.  The combination of different scientific requirements,
      integration times and hardware limitations led us to the
      definition of 40 operation modes, which can be selected through
      commands sent to the spacecraft, ranging from the nominal
      (spatial x spectral) mode (128x96 with summation of 3x3 pixels),
      to the high spectral resolution mode (64x144), to the high speed
      mode (16x96).  Summation along columns and rows will decrease
      the spatial and spectral resolution, but increases signal-to-
      noise ratio considerably.  The implementation of mode 16x74 is
      the most critical due to the short time available to complete
      all the operations (TR = 100 ms).  For this reason the Pattern
      Generator provides two values for the pixel readout frequency: f
      slow= 500 kHz when the pixel voltage has to be digitized and
      ffast = 4 MHz when the pixel is simply read from the CCD output
      register without any digital conversion.
 
    SWIR Spectrograph
    -----------------
      The IR channel is constituted of a telescope and its fore-
      optics, a beam splitter and two spectrometers, each with its
      detector array actively cooled.  The telescope is a Cassegrain
      type one with a 200 mm focal length, a f/4 aperture, leading to
      a 1.2 mrad (4.1 arcmin) IFOV, and a 15 arcmin free field of view
      (including the positioning tolerances).  The distance between
      the primary and the secondary mirrors is 51 mm; that between the
      secondary mirror and the image plane is 82 mm.  In front of the
      telescope, a fore-optics system has the primary goal of
      providing a cross-track scanning of the IFOV.  It includes two
      mirrors, a moving and a fixed one.  The total scanning angle is
      +/- 4.4 degrees (FOV = 128 IFOV), and is adjusted to the OMEGA
      viewing direction.  The control of the scanning mechanism is
      performed by a dedicated FPGA-based electronic sub- system.
 
      Focused by the telescope on an entrance slit, through a shutter,
      the beam is first collimated, then separated, by a dichroic
      filter with its cut-off wavelength at 2.7 micrometres towards
      two spectrometers, operating in the following spectral ranges:
      0.93 to 2.73 micrometers and 2.55 to 5.1 micrometers.  Each
      spectrometer includes a blazed grating working at its first
      order, and an optical reflective system, then a field mirror and
      a refractive refocusing system which gives a large aperture on
      the detection block (f/1.6): it images the spectrum onto a 128
      elements InSb linear array, cooled down a temperature of < 80K,
      and multiplexed by a charge transfer device.  Sets of filters
      are implemented in front of the detector to reject the
      contribution of other orders from the grating.
 
      The InSb photodiodes have been manufactured by SAT.  The
      dimensions       of each photosensitive element is 90 micron x
      120 micron, with a pitch of 120 micron.  All elements of the
      focal planes are hybridized on a ceramic with two electric
      circuit layers to connect the elements together.  The ceramic is
      glued on a titanium base plate and covered with a titanium
      closure, which includes the filters.  An internal calibration
      source is implemented, to control potential shifts of the
      overall spectrometer transmission, and to calibrate the relative
      response of each pixel.  It is made of a tungsten lamp, operated
      as a black body which can be power heated at different
      temperatures.  The calibration beam is reflected towards the
      spectrometer by diffusion on the back side of the entrance slit.
 
      SWIR requires an accurate thermal control, at three levels:
 
        - the IR detectors must be cooled down a temperature of < 80 K,
          controlled with an accuracy better than 0.1K.  This is done by
          connecting them (copper heat link) to two cryocoolers, one for
          each array: they consist of Inframetrics 13000 series integral
          Stirling cycle coolers.  Their guaranteed lifetimes are > 2500
          hours.  They are controlled by dedicated electronics;
 
        - the spectrometer must be cooled down to 190 K, in order both to
          allow the detectors to reach their required operational
          temperature (< 80 K), and to minimize the thermal background.
          This is achieved by conductive coupling (heat pipes) to a 'low
          temperature' radiator, provided by the S/C;
 
        - the electronics and the cryocoolers heads must be coupled
          (copper links) to a 'high temperature' (280 K) radiator to
          dissipate their energy.
 
    OMEGA-ME Unit
    -------------
      The OMEGA main electronics is designed to power and control the
      instrument, to acquire and compress all scientific data on line,
      and to interface with the S/C telecommand/telemetry system.  The
      entire system is cold redundant.  Within OMEGA-ME, the Command
      and Data Processing Unit(CDPU) has the following tasks:
 
      - acquisition of all scientific data from VNIR and SWIR;
      - formatting for real time data compression
      - wavelet based data compression, followed by formatting of
        processed data
      - reception and formatting of HK data
      - forward all data to the S/C telemetry system
 
      The CDPU is based on a TSC21020 Temic processor, and integrated,
      together with a 6Mbyte SRAM, into a 3D packaged highly
      miniaturized cube, inherited from a CIVA/Rosetta development.

        