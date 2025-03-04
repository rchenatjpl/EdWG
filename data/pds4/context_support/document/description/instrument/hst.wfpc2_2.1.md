
 
 
  Instrument Overview
  ===================
    The information in this document is taken from [BURROWS1994].
 
    The original Wide Field and Planetary Camera (WF/PC-1) was a two-
    dimensional spectrophotometer with rudimentary polarimetric and
    transmission-grating capabilities. WF/PC-1 was launched aboard the
    HST in April 1990 and was central to the discovery and
    characterization of the spherical aberration in HST. It was
    replaced in December 1993 by a second Wide Field and Planetary
    Camera (WFPC2) which is described in detail in this document.  The
    original Wide Field and Planetary Camera (WF/PC-1) imaged the
    center of the field of the Hubble Space Telescope (HST).  The
    instrument was designed to operate from 1150 A to 11000 A with a
    resolution of 0.1 arcseconds per pixel (Wide Field camera, F/12.9)
    or 0.043 arcseconds per pixel (Planetary Camera, F/30), each
    camera mode using an array of four 800 x 800 CCD detectors.  The
    development and construction of the WF/PC-1 was led by Prof. J. A.
    Westphal, Principal Investigator (PI), of the California Institute
    of Technology.  The Investigation Definition Team (IDT) also
    included J.E. Gunn (deputy PI), W.A. Baum, A.D. Code, D.G. Currie,
    G.E. Danielson, T.F. Kelsall, J.A. Kristian, C.R. Lynds, P.K.
    Seidelmann, and B.A. Smith. The instrument was built at the Jet
    Propulsion Laboratory, Caltech (JPL).
 
    NASA decided to build a second Wide Field and Planetary Camera
    (WFPC2) at JPL as a backup clone of the WF/PC-1 because of its
    important role in the overall HST mission.  This second version of
    the WF/PC was in the early stages of construction at JPL at the
    time of HST launch.  A modification of the internal WF/PC optics
    could correct for the spherical aberration and restore most of the
    originally expected performance.  As a result, it was decided to
    incorporate the correction within WFPC2 and to accelerate its
    development. The original Wide Field/Planetary Camera (WF/PC1) was
    replaced by WFPC2 on the STS-61 shuttle mission in December 1993.
 
    Instrument ID                   : WFPC2
    Instrument Host ID              : HST
    Pi PDS User Id                  : JTRAUGER
    Instrument Name                 : Wide Field Planetary Camera 2
    Instrument Type                 : CCD Camera
    Build Date                      : 1993-05-01
    Instrument Mass                 : UNK
    Instrument Length               : 2.44
    Instrument Width                : 1.22
    Instrument Height               : 0.46
    Instrument Manufacturer Name    : Jet Propulsion Laboratory
 
 
  Principal Investigator
  ======================
    The Principal Investigator for WFPC2 is Dr. J.T. Trauger of
    JPL.  The IDT members are C.J. Burrows, J. Clarke, D. Crisp,
    J. Gallagher, R.E. Griffiths, J.J. Hester, J. Hoessel, J.
    Holtzman, J. Mould, and J.A. Westphal.
 
 
  Scientific Objectives
  =====================
    The scientific objectives of the WFPC2 are to provide
    photometrically and geometrically accurate, multi-band images
    of astronomical objects over a relatively wide field-of-view
    (FOV), with high angular resolution across a broad range of
    wavelengths.  WFPC2 meets or exceeds the photometric
    performance of WF/PC-1 in most areas.  Nominally, the
    requirement is 1% photometric accuracy in all filters, which is
    essentially a requirement that the relative response in all
    800x800 pixels per CCD be known to a precision of 1% in
    flat-field images taken through each of the 48 science filters.
    Success in this area is dependent on the stability of all
    elements in the optical train particularly the CCDs, filters
    and calibration channel.  The recovery of the point spread
    function is essential to all science programs being conducted
    with the WFPC2, because it allows one to both go deeper than
    ground based imagery and to resolve smaller scale structure
    with higher reliability and dynamic range.
 
 
  Calibration
  ===========
    Standard calibration observations are obtained and maintained
    in the HST archive at the STScI, and can be obtained by
    external users using StarView.  This includes those flat field,
    dark and bias frames needed to operate the Post Observation
    Data Processing System (PODPS; usually just called the
    'pipeline'), a photometric calibration derived from standard
    star observations and the measured filter profiles, and derived
    determinations of the plate scale, distortion, and so on.  The
    first set of these calibrations were provided to the STScI by
    the WFPC2 IDT from the Servicing Mission Observatory
    Verification (SMOV) and System Level Thermal Vacuum (SLTV)
    testing periods, and will be maintained and updated thereafter
    by the STScI with initial assistance from the IDT as part of
    the long term calibration program.
 
 
  Operational Considerations
  ==========================
    The WFPC2 field of view is divided and distributed into four
    cameras by a fixed four-faceted pyramid mirror near the HST
    focal plane.  Three of these are F/12.9 Wide Field cameras
    (WFC), and the remaining one is an F/28.3 Planetary camera
    (PC).  There are thus four sets of relay optics and CCD sensors
    in WFPC2, rather than the eight in WF/PC-1, which had two
    independent field formats.  The pyramid rotation mechanism has
    been eliminated, and all four cameras are now in the locations
    that were occupied in WF/PC-1 by the wide field camera relays.
    These positions are denoted PC1, WF2, WF3, and WF4.
 
 
  Detectors
  =========
    The WFPC2 CCDs are thick, front-side illuminated devices made
    by Loral.  They support multi-pinned phase (MPP) operation
    which eliminates quantum efficiency hysteresis.  They have a
    Lumogen phosphor coating to give UV sensitivity.  WF/PC-1 CCDs
    were thinned, backside illuminated devices with a coronene
    phosphor.  The resulting differences may be summarized as
    follows:
 
    Read noise: WFPC2 CCDs have lower read noise (about 5e- rms)
                than WF/PC-1 CCDs (13 e- rms) which improves their
                faint object and UV imaging capabilities.
 
    Dark noise: Inverted phase operation yields lower dark noise for
                WFPC2 CCDs. They are presently being operated at
                -77C and yet the median dark current is about 0.016
                electrons/pixel/sec. This is 10C warmer than the
                WF/PC-1 devices and helps in reducing the build-up
                of contaminants on the CCD windows. If they end up
                being operated colder the dark current reduces by a
                factor of 3 for every 10C temperature drop.
 
    Flat field: WFPC2 CCDs have a more uniform pixel to pixel
                response (<2% pixel to pixel non-uniformity) which
                will improve the photometric calibration.
 
     Pre-Flash: Charge traps are present at the current operating
                temperature. However, by cooling the devices
                further, it is expected that they will become
                negligible for WFPC2 CCDs. Pre-flash exposures will
                then not be required. This would avoid the increase
                in background noise, and decrease in operational
                efficiency that results from a preflash.
 
   Gain switch: Two CCD gains are available with WFPC2, a 7e-/DN
                channel which saturates at about 27000e- (4096 DN
                with a bias of about 300 DN) and a 14e-/DN channel
                which saturates at about 53000e-. The Loral devices
                have a large full well capacity (of 80-100,000
                electrons) and are linear up to the saturation level
                in both channels.
 
           DQE: The Loral devices have intrinsically lower QE above
                4800A (and up to about 6500A) than thinned, backside
                illuminated wafers which have no attenuation by
                frontside electrode structures. On the other hand,
                the improved phosphorescent coating leads to higher
                DQE below 4800A. The peak DQE in the optical is 40%
                at 7000A while in the UV (1100-4000A) the DQE is
                10-15%.
 
   Image Purge: The residual image resulting from a 100x (or more)
                full-well over-exposure is well below the read noise
                within 30 minutes, removing the need for CCD image
                purging after observations of particularly bright
                objects. The Loral devices bleed almost exclusively
                along the columns.
 
  Quantization: The systematic Analog to Digital converter errors
                that were present in the low order bits on WF/PC-1
                have been largely eliminated, contributing to a
                lower effective read noise.
 
           QEH: Quantum Efficiency Hysteresis (QEH) is not a
                significant problem in the Loral CCDs because they
                are frontside illuminated and use MPP operation. The
                absence of any significant QEH means that the
                devices do not need to be UV-flooded and so the
                chips can be warmed for decontamination purposes
                without needing to maintain the UV-flood.
 
  Detector MTF: The Loral devices do suffer from low detector MTF
                perhaps caused by scattering in the frontside
                electrode structure. The effect is to blur images
                and decrease the limiting magnitude by about 0.5
                magnitudes.
 
 
  Electronics
  ===========
    The CCD camera electronics system is essentially the same
    design as that flown on WF/PC-1 with the exception of changes
    made to implement the different clock pattern for MPP inverted
    phase operation.  Changes in circuit timing have also been made
    to correct the problem of ADC conversion errors.
 
 
  Filters
  =======
    A set of 48 filters are included in WFPC2, with the following
    features:
 
      1. It approximately replicates the WF/PC-1 'UBVRI' photometry
         series.
      2. The broad-band filter series is extended into the far UV.
      3. There is a new Stromgren series.
      4. A Wood's filter is included for far-UV imaging without a red
         leak.
      5. There is a 1% bandpass linear ramp filter series covering
         3700-9800A.
      6. The narrow-band series is more uniformly specified and better
         calibrated.
 
    The filters are mounted in the Selectable Optical Filter
    Assembly (SOFA) between the shutter and the reflecting pyramid.
    The SOFA contains 12 filter wheels, each of which has 4 filters
    and a clear 'home' position.  Wheel number 1 is located closest
    to the shutter.  The categories of simple filters (F) are
    long-pass (LP), wide (W), medium (M), and narrow (N).  Most of
    these filters are either flat single substrates or sandwiches.
 
    The filter complement includes two solar blind Wood's filters
    F160AW and F160BW.  F160BW will be used in all science
    observations because the other filter has some large pinholes
    that lead to significant red leak.
 
    In addition to the above complement of broad and narrow band
    filters WFPC2 features a set of three specialized quadrant
    (quad or Q) filters in which each quadrant corresponds to a
    facet of the pyramid, and therefore to a distinct camera relay.
    There is one quad containing four narrow-band, redshifted [OII]
    filters with central wavelengths from 3763-3986A, one quad with
    four polarizing elements (POL) with polarization angles, 0, 45,
    90 and 135 degrees, and one quad with four methane (CH4) band
    filters with central wavelengths from 5433-8929A.  The
    polarizer quad filter, can be crossed with any other filter
    over the wavelength range from 2800A to 8000A, with the
    exception of the Methane Quad and Redshifted [OII] Quad which
    share the same wheel.
 
 
  Optics
  ======
    The central portion of the OTA F/24 beam is intercepted by a
    steerable pick-off mirror attached to the WFPC2 and is diverted
    through an open entry port into the instrument.  The entry port
    is not sealed with an afocal MgF2 window as it was in WF/PC-1.
    The beam then passes through a shutter and filters.  A total of
    48 spectral elements and polarizers are contained in an
    assembly of 12 filter wheels.  Then the light falls onto a
    shallow-angle, four-faceted pyramid located at the aberrated
    OTA focus, each face of the pyramid being a concave spherical
    surface.  The pyramid divides the OTA image of the sky into
    four parts.  After leaving the pyramid, each quarter of the
    full field-of-view is relayed by an optical flat to a
    cassegrain relay that forms a second field image on a
    charge-coupled device (CCD) of 800x800 pixels.  Each detector
    is housed in a cell that is sealed by a MgF2 window.  This
    window is figured to serve as a field flattener.
 
    The aberrated HST wavefront is corrected by introducing an
    equal but opposite error in each of the four cassegrain relays.
    An image of the HST primary mirror is formed on the secondary
    mirrors in the cassegrain relays.  The previously flat fold
    mirror in the PC channel has a small curvature to ensure this,
    and this is why the magnification is changed from F/30 to
    F/28.3 in the PC.  The spherical aberration from the
    telescope's primary mirror is corrected on these secondary
    mirrors, which are extremely aspheric.  The point spread
    function is then close to that originally expected for WF/PC-1.
 
 
  Operational Modes
  =================
    The CCDs and their associated signal chains have read-out noise
    levels (in the absence of signal shot noise or interference) of
    approximately 5 e-.  The WF/PC-1 CCD read noise was effectively
    15-20 e-, since there were additional contributions above the
    nominal 13 e- resulting from 'missing codes' in the ADC and the
    preflash exposure.
 
    The conversion factors from detected electrons (QE * number of
    incident photons) to data numbers (DN) are tabulated below, as
    are read noise and linearity.  Note that all calculations of
    sensitivity in this manual assume gains of 7 and 14 for two
    gain channels, choices very close to the measured gains.
 
               Gain     PC1             WF3
               ======================================
      Noise     '7'     5.24+-0.30      5.22+-0.28
               '14'     7.02+-0.41      6.99+-0.38
               --------------------------------------
      Gain      '7'     7.12+-0.41      6.90+-0.32
               '14'    13.99+-0.63     13.95+-0.63
               --------------------------------------
      Gamma     '7'    1.0015+-0.0006  1.0020+-0.0006
               '14'    1.0004+-0.0001  1.0032+-0.0006
               --------------------------------------

        