
 
 
  Instrument Overview
  ===================
 
    The information in this document is taken from Gonzaga et al.
    (2005).  The Advanced Camera for Surveys (ACS), a
    third-generation instrument, was installed in the Hubble Space
    Telescope on March 7, 2002.  Its primary purpose is to increase
    HST imaging discovery efficiency by about a factor of 10, with a
    combination of detector area and quantum efficiency that
    surpasses previous instruments.  In addition, coronagraphic,
    polarimetric, and grism capabilities make this a versatile and
    powerful instrument.
 
    ACS is a versatile instrument that can be applied to a broad
    range of scientific programs. The three prime capabilities of ACS
    are:
      - Deep, wide-field imaging from visible to near-IR wavelengths.
      - High spatial resolution imaging from near-UV to near-IR
        wavelengths.
      - Solar blind UV imaging.
 
    ACS has three independent cameras that provide wide-field, high
    resolution, and ultraviolet imaging capabilities espectively,
    using a broad assortment of filters designed to address a large
    range of scientific goals.  The three channels are each optimized
    for a specific goal:
      - Wide Field Channel (WFC): 202 x 202 arcsecond field of view
        from 3500 A to 11,000 A, and peak efficiency of 48%
        (including the Optical Telescope Assembly (OTA)).  The plate
        scale of ~0.05 arcseconds/pixel provides critical sampling at
        11,600 A.
      - High Resolution Channel (HRC): 29 x 26 arcsecond field of
        view from 1700 A to 11,000 A, and peak efficiency of 29%.
        The plate scale of ~0.027 arcseconds/pixel provides critical
        sampling at 6300 A.
      - Solar Blind Channel (SBC): 35 x 31 arcsecond field of view
        from 1150 A to 1700 A, plate scale of ~0.032
        arcseconds/pixel, and peak efficiency of 7.5%.
 
  Calibration
  ===========
 
    The calibration accuracy is summarized in the table below.
 
   Attribute             WFC      HRC      SBC     Limiting factor
   ------------------------------------------------------------------
   Distortion solution  0.1 pix  0.1 pix  0.25 pix Calibration &
                                                   stability accuracy
                                                   of geometric
                                                   distortion
 
   Absolute astrometry  0.5-1 in 1 in     1 in     Guide Star Catalog
                                                   uncertainties
 
   Absolute photometry  3%       2%       5%       Absolute
                                                   calibration,
                                                   standards
 
   Relative photometry  1%       1%       2%       Flat-field or
   of the same star                                geometric
                                                   distortion
 
   Transformation to    0.02 m to SDSS    n/a      DQE curve
   standard magnitude   0.025 m to WFPC2           determination
   system               0.03 m to BVRI             Color terms
 
   Polarimetry          1%       1%       n/a
 
   Wavelength           20 A     12 A     1 pix    Accuracy of
                                                   dispersion
 
   Spectrophotometry    6%       10%      20%
   ------------------------------------------------------------------
 
 
  Detectors
  =========
 
    ACS uses the following detectors in each channel:
 
     - The WFC employs a mosaic of two 4096 x 2048 Scientific Imaging
       Technologies (SITe) CCDs.  The 15 x 15 um pixels provide ~0.05
       arcseconds/pixel spatial resolution, with critical sampling at
       11,600 A, resulting in a nominal 202 x 202 arcsecond field of
       view (FOV).  The spectral sensitivity of the WFC ranges from
       3500 A to 11,000 A, with a peak efficiency of 48% at ~7000 A
       (including OTA).
 
     - The HRC detector is a 1024 x 1024 SITe CCD, with 21 x 21
       micron pixels that provide ~0.028 x 0.025 arcsecond/pixel
       spatial resolution with critical sampling at 6300 A.  This
       gives the HRC a nominal 29 x 26 arcsecond field of view.  The
       spectral response of the HRC ranges from ~1700 A to 11,000 A,
       and it has a peak efficiency of 29% at ~6500 A (including OTA).
 
     - The SBC detector is a solar-blind CsI microchannel plate (MCP)
       with Multi-Anode Microchannel Array (MAMA) readout.  It has
       1024 x 1024 pixels, each 25 x 25 micron in size. This provides
       a spatial resolution of ~0.034 x 0.030 arcseconds/pixels,
       producing a nominal FOV of 35 x 31 arcseconds.  The SBC UV
       spectral response ranges from 1150 A to 1700 A with a peak
       efficiency of 7.5% at 1250 A.
 
  Filters
  =======
 
    ACS has three filter wheels: two shared by the WFC and HRC, and a
    separate wheel dedicated to the SBC.  The WFC/HRC filter wheels
    contain the major filter sets.  Each wheel also contains one clear
    WFC aperture and one clear HRC aperture (see Chapter 5 of Gonzaga
    et al. 2005 for more on filters).  Parallel WFC and HRC
    observations are possible for some filter combinations, unless
    the user disables this option, or if adding the parallel
    observations cannot be done due to timing considerations. Because
    the filter wheels are shared, it is not possible to independently
    select the filter for WFC and HRC parallel observations.  The
    filters used in ACS are summarized in the table below.
 
    Filter description                                Camera
    -----------------------------------------------------------------
    Broadband:
    Sloan Digital Sky Survey (SDSS): F475W, F625W,    WFC/HRC
    F775W, F850LP
    B, V, Medium V, Wide V, I: F435W, F555W, F550M,   WFC/HRC
    F606W, F814W
    Near-UV: F220W, F250W, F330W                      HRC
    No Filter: CLEAR                                  WFC/HRC
 
    Narrowband:
    Halpha (2%), [OIII] (1%), [NII] (1%): F658N,      WFC/HRC
    F502N, F660N
    NeV (3440 A): F344N                               HRC
    Methane (8920 A): F892N                           HRC/[WFC1]
 
    Ramp:
    2% bandpass (3700-10,700 A): FR388N, FR505N,      WFC/HRC
    FR656N
    2% bandpass (3700-10,700 A): FR423N, FR462N,      WFC
    FR716N, FR782N, FR853N, FR931N, FR1016N, FR551N,
    FR601N
    9% bandpass (3700-10,700 ): FR459M, FR914M       WFC/HRC
    9% bandpass (3700-10,700 ): FR647M               WFC
 
    Spectroscopic Grism:  G800L                       WFC/HRC
                  Prism: PR200L                       WFC/HRC
 
    Polarizers:
    Visible: (0, 60, 120): POL0V, POL60V, POL120V     HRC/[WFC1]
    Near-UV (0, 60, 120): POL0UV, POL60UV, POL120UV   HRC/[WFC1]
 
    Medium Band Lyman-Alpha: F122M                    SBC
 
    Long Pass:
    MgF2, CaF2, BaF2, Quartz, Fused Silica: F115LP,
    F125LP, F140LP, F150LP, F165LP                    SBC
 
    Prisms:  LiF, CaF2: PR110L, PR130L                SBC
    -----------------------------------------------------------------
 
  References
  ==========
 
   Gonzaga, S., et al. 2005, ACS Instrument Handbook, Version 6.0,
   Baltimore: STScI.

        