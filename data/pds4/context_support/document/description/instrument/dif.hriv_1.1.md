
 
 
  Instrument Overview
  ===================
    The High Resolution Imager (HRI) consists of a long-focal-length
    telescope with a dichroic beam splitter located in front of the focal
    plane that reflects visible light (0.3 to 1.0 microns) through a
    filter wheel to a CCD for direct, optical imaging.  The beam splitter
    transmits the near-infrared light (1 to 5 microns) to a 2-prism
    spectrometer.  For convenience, we consider these as two separate
    instruments, HRIV (High Resolution Visible CCD) and HRII (High
    Resolution IR spectrometer), sharing the telescope since the two focal
    planes operate in parallel asynchronously.
 
    The HRI telescope is a classical Cassegrain design with the following
    parameters:
 
      Primary aperture        : 30.0 cm diameter, round
      Primary focal ratio     :  4.5
      Secondary Obscuration   :  9.7 cm diameter, round
      Secondary magnification :  7.8x (net Cassegrain focal length 10.5 m)
      Back focal distance     : 30.0 cm
 
    The dichroic beam-splitter has equal transmission and reflection
    occurring at about 1.05 microns.  The filter wheel contains two clear
    apertures and seven filters.  Five of the filters are roughly 100
    nanometers in bandwidth, centered at 450, 550, 650, 750, and 850
    nanometers.  The shortest-wavelength filter is effectively a
    short-wavelength pass filter starting at 400 nanometers and limited to
    about 340 nanometers on the short end by the rapid decline in
    beamsplitter reflectivity.   The longest wavelength filter is a
    long-pass filter starting at 900 nanometers that uses the CCD response
    to define the long-wavelength cutoff at about 960 nanometers.  Filter
    transmission profiles are illustrated by Hampton, et al. (2005)
    [HAMPTONETAL2005] and provided in the calibrated science data sets
    for the Deep Impact and EPOXI missions.
 
    The detector is a 1024 x 1024 split-frame, frame-transfer CCD with
    21-micron-square pixels, with each quadrant read out through a
    separate amplifier.  The electronics allows readout of centered
    sub-frames in multiples of 2:  64x64, 128x128, and so on, with or
    without rows of overscan.  Transfer time, to move the two halves of
    the image from the exposing area to the two shielded areas, is about
    5.2 milliseconds.  Readout time for a full frame is 1.8 seconds.
 
    The HRIV instrument in full-frame 1024 x 1024 mode has the following
    field-of-view characteristics:
 
      Pixel Size     :   21 micrometers
      Pixel FOV      :  2.0 microradians or 0.41253 arcseconds
      Instrument FOV :  2.0 milliradians or 0.118 degrees
      Surface Scale  :  1.4 meters/pixel at 700 kilometers
 
    The HRIV instrument includes an internal stimulator lamp for
    calibrating between the four quadrants of the CCD.  The lamp is not a
    standard calibrator.  One of its in-flight uses is to improve the
    photometry from the EPOXI exoplanet transit observations.
 
    The three instruments on the flyby spacecraft, HRIV, HRII (High-
    Resolution IR Imaging Spectrometer) and MRI (Medium-Resolution
    Visible CCD), are mounted on a separate instrument platform
    together with the star trackers.  The three instruments are
    nominally co-aligned as described by Klaasen, et al. (2008)
    [KLAASENETAL2006].
 
    For a detailed discussion of the instrument and how it was used during
    the Deep Impact mission, see Hampton, et al. (2005) [HAMPTONETAL2005]
    and Klaasen, et al. (2005) [KLAASENETAL2005].  For the EPOXI mission,
    the HRII instrument imaged transits of known extrasolar planets, Earth
    and Mars as remotely-sensed planets, and comet 103P/Hartley 2.
 
 
  Instrument Calibration
  ======================
    The HRIV instrument was originally calibrated by using in-flight data
    acquired during Deep Impact as well as pre-launch data taken during
    thermal-vacuum tests (TV2 and TV4) performed in 2002 and 2003.
    In-flight calibrations continued through the EPOXI mission to monitor
    performance and to provide additional data for refining the calibration
    pipeline.  Instrument calibration for Deep Impact is discussed by
    Klaasen, et al. (2008) [KLAASENETAL2006]; instrument calibration for
    EPOXI is discussed by Klaasen, et al. (2013) [KLAASENETAL2011].
 
    The two central rows of the CCD are physically 1/6-pixel narrower
    and collect only 5/6 of the charge of a normal row (Klaasen, et al.,
    2008 [KLAASENETAL2006]; Klaasen, et al., 2013 [KLAASENETAL2011]).
    However, the data pipeline reconstructs images with uniform row
    spacing, which introduces a 1/3-pixel extension at the center of the
    raw and calibrated image arrays.  Thus for two features on either
    side of the midpoint line outside of the two central rows, the
    vertical component of the true angular separation between those
    features is one-third of a pixel less than their measured separation
    in the reconstructed image.  As for all geometric distortions,
    correction of this 1/3-pixel extension will require resampling of
    the image and an attendant loss in spatial resolution.  The data
    pipeline process does not perform this correction in order to
    preserve the best spatial resolution.  However, it does correct for
    the 1/6 decrease of signal in the two central rows by the flat-field
    division so that the pixels in those two rows have the correct scene
    radiance in the calibrated images.  Thus, the surface brightness
    measurement is preserved anywhere in the geometrically distorted but
    calibrated images.  Point source or disk-integrated photometric
    measurements using aperture photometry that includes these central
    rows will be slightly distorted unless special adjustments are made,
    such as subtracting 1/6-pixel worth of signal to the two central
    rows and adjusting for the geometric distortion in the calibrated
    images, as described in Appendix A of Belton, et al. (2011)
    [BELTONETAL2011].  An alternative method that corrects for the
    1/3-pixel extension was developed for Hartley 2 photometry and is
    described in the dataset DIF-C-MRI-5-EPOXI-HARTLEY2-PHOTOM-V1.0.
 
 
  Flight Performance
  ==================
    The HRIV instrument generally performed as expected during flight.
    However, images of stars acquired early in the Deep Impact mission
    indicated the HRI telescope was out of focus.  An analysis showed the
    focus was forward of the CCD, so bakeouts were performed in late
    February and early March 2005 to improve the focus.  The bakeouts
    reduced the defocus from 1.0 cm to 0.6 cm, which caused the width of
    star images to decrease from about 12 pixels to about 9 pixels.  Star
    images continued to have a three-fold symmetry (six points) resulting
    from the three-point mounting of the primary and secondary mirrors.
    Most of the expected resolution can be regained by applying algorithms
    to deconvolve the HRIV images as described by Lindler, et al. (2007)
    [LINDLERETAL2007] and Lindler, et al. (2013) [LINDLERETAL2013].
    The EPOXI mission takes advantage of the poor focus characteristic
    which increases the point spread function of measurements, enabling
    high-precision photometry of known extrasolar planetary systems.  For
    a detailed discussion about the focus of the HRI telescope, see
    Klaasen, et al. (2008) [KLAASENETAL2006] and Lindler, et al. (2007)
    [LINDLERETAL2007].  During the EPOXI mission, new target-specific point
    spread functions (PSFs) were produced from data acquired in 2008 of
    exoplanet transit targets such as GJ 436 and stellar calibrators such
    as Canopus.  See Barry, et al., (2010) [BARRYETAL2010] for more
    information.  These PSFs are archived as a data set in the PDS:
    DIF-CAL-HRIV-6-EPOXI-STELLAR-PSFS-V1.0.
 
    Calibration data acquired throughout EPOXI showed changes to the flat
    fields, the electronic crosstalk between the CCD quadrants, and the
    response of the filters since Deep Impact in 2005.  Therefore new
    calibration files and constants were incorporated into the calibration
    pipeline for EPOXI processing; additional improvements such as stripe
    removal are discussed by Klaasen, et al. (2013) [KLAASENETAL2011].
 
 
  This instrument description was originally provided by Dr. Michael A'Hearn
  for the Deep Impact mission, then updated as the EPOXI mission progressed.

        