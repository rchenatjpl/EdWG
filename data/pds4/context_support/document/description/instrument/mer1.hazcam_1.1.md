
 
  Instrument Overview
  ===================
    Each MER has 4 Hazard Avoidance Cameras, 2 in the front and 2 in the
    rear.  The Hazcams have the exact same optical design as the EDLcam
    and the Navcams. The Hazcams will be used to take images of the
    landscape that will help the rover avoid any obstacles in the way of
    the traverse.
 
    The Hazcams are made of a detector head and an electronics box. The
    detector head houses a lens assembly and a Charge Coupled Device
    detector (CCD). The electronics box contains the CCD driver
    electronics, the 12-bit Analog to Digital Converter (ADC),
    camera/rover interface electronics, and a heater resistor that will
    keep the box above the minimum operating temperature of 218 K. The
    Hazcams use a broadband visible filter and produces 1024 x 1024
    pixel images.
 
    Information in this instrument description is taken from the Mars
    Exploration Rover Engineering Cameras paper[MAKIETAL2003]. See this
    paper for more details.
 
 
  Instrument Objectives
  =====================
    The chief objectives of the Hazcams are:
 
    1) to support the operation of the rover on the surface of Mars by
       acquiring images of the terrain and landscape,
 
    2) to acquire images for support of auto-navigation, IDD operations,
       and pointing of the Pancam and Mini-TES,
 
    3) to investigate the landing sites at cm/ pixel resolution,
 
    4) to acquire images of the terrain that will help identify evidence
       of water based on morphology of rocks and soil,
 
    5) to measure the distribution of rocks and soil around the rover as
       it moves from site to site,
 
    6) to calibrate and validate orbital remote sensing data, and
 
    7) to place rock and soil type encountered by the rover in a
       geological context.
 
 
  Calibration
  ===========
    The Hazcams have been calibrated over the flight range of
    temperatures. They were all calibrated with respect to: geometric
    flat field response, detector dark current, camera absolute
    responsivity, detector noise performance, and detector gain.
 
 
  Detectors
  =========
    The Front and Rear Hazcams uses an identical 1024 x 2048 pixel
    CCD with 12 micron-square pixels and a 100% optical fill factor.
    The CCDs operate in frame-transfer mode, dividing the detector
    into two regions.  One of the regions is a 1204 x 1204 pixel
    photosensitive imaging region where the image is recorded. The
    other region is a 1204 x 1204 shielded storage region where the
    recorded image is shifted and stored during detector readout. It
    takes 5.1 msec to transfer data from the imaging region to the
    storage region, and 5.4 seconds for readout of data from the
    storage region. Each CCD includes 32 non-imaging pixels in the
    serial readout registers, which allow the monitoring of the CCD
    electronics offset and detector noise performance. Both the
    Navcam and Hazcam CCD pixels have full well capacities of
    approximately 160,000 electrons and are digitized at 12 bits/
    pixel. The RMS read noise at cold temperatures (218 K) is
    approximately 20 electrons, and the detector systems have gain
    values of approximately 50 e-/DN, which results in a system with
    approximately .5 DN of RMS read noise.
 
    The absolute CCD quantum efficiency (QE) of the CCDs has been
    measured between 400 and 1000 nm at four operating temperatures
    ranging from 218 K and 278 K.  The QE of the MER CCDs is typical
    of a silicon CCD detector, with sensitivity peaking at 700 nm
    with a QE value of approximately 43%. The SNR of the detector
    system is essentially Poisson-limited because of its low readout
    noise and small dark current rates in the Martian operating
    envirionments.
 
 
  Electronics
  ===========
    The Hazcam CCDs use a 'clocked antiblooming' readout technique,
    instead of having anti-blooming circuitry. The proper choice
    of autoexposure parameters prevent the blooming effect.
 
    The Navcams also have the capability for onboard image processing.
    The Navcams can do pixel summation in which they sum the rows and
    columns of an image, returning the results in a one-dimensional
    array of 32-bit integers whose length is the image height. These are
    very useful when the spatial content of an image has relatively low
    scene entropy and the emphasis is on the radiometry. The flight
    software (FSW) can also calculate and return the histogram of an
    image, which can be useful for atmospheric observations. MER images
    can be spatially downsampled to a user-specified image size using
    one of a few techniques; nearest neighbor computation of the mean,
    computation of the mean with outlier rejection, and median
    averaging. The FSW also allows the option to downlink a subframed
    region of an image so full resolution can be downlinked at a lower
    data volume. The FSW is also capable of lossy and lossless
    compression of MER images. The rovers will use a ICER wavelet image
    compressor for the lossy and lossless compression.
 
 
  Filters
  =======
    The Hazcams use a combination of three filters (Schott OG590,
    KG5, and ND1.3) to create a red bandpass filter centered at
    650 nm and a FWHM of approximately 140 nm.
 
 
  Optics
  ======
    The Hazcams have f/15 cameras with a 5.58 nm focal length. The
    Hazcam optics are f-theta fisheye lenses with 124 x 124 degree
    horizontal/vertical field of view and a 180 degree diagonal field
    of view. They have an angular resolution at the center of the
    picture of 2.1 mrad/pixel. The nominal exposure time for a noontime
    image on Mars is approximately .25 seconds. This time is 50 times
    the frame transfer time of 5.1 ms. This ensures that the image
    signal is significantly than the image smear acquired during the
    frame transfer.
 
 
  Location
  ========
    The Hazcams are attached to a titanium bracket that is mounted on
    the outside of the Warm Electronics Box.

        