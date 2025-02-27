
 
  Instrument Overview
  ===================
    The Descent camera (DESCAM) is mounted on the
    lander radar bracket and is pointed downward during lander descent.
    It has the exact same optical design as the Navcams and Hazcams. The
    DESCAM will be used to take images of Mars as the lander is
    descending.
 
    The DESCAM is made of a detector head and an electronics box. The
    detector head houses a lens assembly and a Charge Coupled Device
    detector (CCD). The electronics box contains the CCD driver
    electronics, the 12-bit Analog to Digital Converter (ADC),
    camera/rover interface electronics, and a heater resistor that will
    keep the box above the minimum operating temperature of 218 K. The
    DESCAM uses a broadband visible filter and produces 1024 x 1024
    pixel images.
 
    Information in this instrument description is taken from the Mars
    Exploration Rover Engineering Cameras paper[MAKIETAL2003]. See this
    paper for more details.
 
 
  Instrument Objectives
  =====================
    The chief objective of the DESCAM is:
 
    1) to acquire images of Mars as the lander descends towards the
       surface.
 
 
  Calibration
  ===========
    The DESCAM has been calibrated over the flight range of
    temperatures. It was calibrated with respect to: geometric flat
    field response, detector dark current, camera absolute responsivity,
    detector noise performance, and detector gain.
 
 
  Detectors
  =========
    The DESCAM uses a 1024 x 2048-pixel CCD with 12 micron-square pixels
    and a 100% optical fill factor. The CCDs operate in frame-transfer
    mode, dividing the detector into two regions.  One of the regions
    is a 1204 x 1204 pixel photosensitive imaging region where the image
    is recorded. The other region is a 1204 x 1204 shielded storage
    region where the recorded image is shifted and stored during
    detector readout. It takes 5.1 msec to transfer data from the
    imaging region to the storage region, and 5.4 seconds for readout of
    data from the storage region. Each CCD includes 32 non-imaging
    pixels in the serial readout registers, which allow the monitoring
    of the CCD electronics offset and detector noise performance. The
    RMS read noise at cold temperatures (218 K) is approximately 20
    electrons, and the detector systems have gain values of
    approximately 50 e-/DN, which results in a system with approximately
    .5 DN of RMS read noise.
 
    The absolute CCD quantum efficiency (QE) of the CCDs has been
    measured between 400 and 1000 nm at four operating temperatures
    ranging from 218 K and 278 K.  The QE of the MER CCDs is typical of
    a silicon CCD detector, with sensitivity peaking at 700 nm with a QE
    value of approximately 43%. The SNR of the detector system is
    essentially Poisson-limited because of its low readout noise and
    small dark current rates in the Martian operating envirionments.
 
 
  Electronics
  ===========
    The DESCAM CCD uses a 'clocked antiblooming' readout technique,
    instead of having anti-blooming circuitry. The proper choice
    of autoexposure parameters prevent the blooming effect.
 
 
  Filters
  =======
    The DESCAM uses a broadband filter with the center at
    approximately 750 mn and a Full Width at Half Maximum (FWHM)
    of approximately 200 nm.
 
 
  Optics
  ======
    The DESCAM has a f/12 optical system with a 14.67 mm focal length.
    It has a 45 x 45 degree field of view, and a 60.7 degree diagonal
    field of view. The angular resolution at the center of the field of
    view is .82 mrad/pixel.
 
 
  Location
  ========
    The DESCAM is mounted on the lander radar bracket.

        