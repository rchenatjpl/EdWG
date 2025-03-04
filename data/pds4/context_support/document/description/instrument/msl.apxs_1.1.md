
 
 
  Instrument Overview
  ===================
    The APXS (Alpha-Particle X-ray Spectrometer) for MSL is an
    improved version of the APXS that flew successfully on Pathfinder
    and the Mars Exploration Rovers Spirit and Opportunity
    [RIEDERETAL1997A, RIEDERETAL1997B, RIEDERETAL2003,
    GELLERETAL2006]. The MSL APXS takes advantage of a combination of
    the terrestrial standard methods Particle-Induced X-ray Emission
    (PIXE) and X-ray Fluorescence (XRF) to determine elemental chemistry.
    It uses curium-244 sources for X-ray spectroscopy to determine the
    abundance of major elements down to trace elements from sodium to
    bromine and beyond.
 
    The instrument consists of a main electronics unit in the rover's
    body and a sensor head mounted on the robotic arm. Measurements
    are taken by deploying the sensor head towards a desired sample,
    placing the sensor head in contact or hovering typically less than
    2 cm away, and measuring the emitted X-ray spectrum for 15 minutes
    to 3 hours without the need of further interaction by the rover.
    At the end of the measurement, the rover retrieves the science
    data of 32 kilobytes, containing up to 13 consecutively taken
    spectra and engineering data. The internal APXS software splits
    the total measurement into equal time slots with an adjustable
    cycle time parameter. This allows us to check for repeatability
    and to select spectra with sufficient spectral quality.
 
    The MSL APXS can activate an internal Peltier cooler for the X-ray
    detector chip. This results in a sufficient spectral resolution
    (FWHM) of below 200 eV at 6.4 keV below ~ -5 deg C and best FWHM of <
    150 eV below ~ -15 deg C environmental temperature. Compared to the
    APXS on MER, where the best FWHM was reached at temperatures below
    ~ -45 deg C, this allows a significantly larger operational time
    window for APXS analysis.
 
    The MSL APXS has approximately 3 times the sensitivity for low Z
    (atomic number) elements and approximately 6 times for higher Z
    elements than the MER APXS. A full analysis with detection limits
    of 100 ppm for Ni and ~ 20 ppm for Br now requires 3 hours, while
    quick look analysis for major and minor elements at ~ 0.5%
    abundance, such as Na, Mg, Al, Si, Ca, Fe, or S, can be done in 10
    minutes or less.
 
    On MER, the elements detected by the APXS in rock and soil samples
    are typically Na, Mg, Al, Si, P, S, Cl, K, Ca, Ti, Cr, Mn, Fe, Ni,
    Zn, and Br [RIEDERETAL2004] [GELLERTETAL2006].
    Elevated levels of Ge, Ga, Pb, and Rb were found in some of the
    MER samples [CLARKETAL2007].
 
    The sampled area is about 1.7 cm in diameter when the instrument
    is in contact with the sample. A standoff results in gradually
    lower intensity and an increased diameter of the measured spot.
    Low Z element X-rays stem from the topmost 5 microns of the
    sample, higher Z elements like Fe are detected from the upper ~50
    microns. Sample preparation is not needed; the APXS results
    average the composition over the sampled area and the oxide
    abundances measured are renormalized to 100%. However, on MSL, a
    dust removal tool (brush) is available to remove loose material
    from a rock surface before making an APXS measurement.
 
    The major improvements and changes compared to the MER APXS are:
 
        * Improved sensitivity by a factor 3 giving full analysis
          within ~3 hours
        * Additional improved sensitivity for high Z elements by
          increased X-ray source strength
        * Operable during Martian day by using Peltier cooler for the
          X-ray detector
        * Basaltic calibration target mounted on the rover (on the
          robotic arm azimuth actuator housing), dedicated for the APXS
        * No alpha channel (no Rutherford Backscattering spectroscopy)
        * Compressed short duration X-ray spectra ( ~10 seconds ) can
          be used to steer the arm movement in a 'proximity mode'
 
 
    Principal Investigator
    ----------------------
      The APXS Principal Investigator is Ralf Gellert, University of
      Guelph, Canada.  The MSL APXS is funded by the Canadian Space
      Agency, with MDA Corporation as prime subcontractor. Funding for
      the science team comes from CSA, NASA, and the University of
      Guelph.
 
 
  Scientific Objectives
  =====================
    The main objective of the APXS is to characterize the geological
    context of the rover surroundings and to investigate the processes
    that formed the rocks and soils. The high precision and low
    detection limits, especially for salt forming elements like S, Cl,
    and Br, allow identification of local anomalies and guided in-situ
    sample selection for the analytical instruments of MSL. The rover
    observation tray for processed samples allows the APXS to
    provide additional characterization of the samples collected and
    prepared for the analytical instruments, connecting the analytical
    instrument results with the in-situ samples. MSL sample
    preparation with the brush allows in-situ APXS investigations
    of thin alteration rinds or near-surface layers or veins which
    cannot be collected by the drill for the analytical instruments.
    Another important aspect of the APXS investigation is to
    relate the chemical composition of the MSL landing site and the
    results from the MSL payload to what has been found by the
    previous landed missions, which used similar X-ray spectroscopy
    methods.
 
    The elemental data can be used to extract normative mineralogy
    either from scratch or using constraints from the mineralogy
    provided by CheMin. A newly developed method [CAMPBELLETAL2008]
    using the backscattered peaks of the primary X-ray radiation
    allows detection of X-ray invisible compounds like bound water or
    carbonates, if present in significant amounts ( greater than ~5%
    by weight).
 
  Calibration
  ===========
    The APXS was fully calibrated using standard geological
    samples in the laboratory. An onboard basaltic rock slab,
    surrounded by a nickel plate, is used periodically to check
    the performance and calibration of the instrument. The data
    analysis is theoretically well understood and delivers unambiguous
    element identification and accuracy on the order of ~10%, mainly
    limited by microscopic sample heterogeneity (i.e., grain size
    effects). The APXS data analysis is fast and allows a quick
    turnaround of results used for tactical rover operations.
 
  Operational Considerations
  ==========================
    The APXS instrument showed an abnormal behavior on Mars, unseen in the
    lab during calibration and not seen in any other APXS instrument so far.
    In some integrations the instrument stopped counting any real x-ray
    counts in the midst of the data acquisition. If this happens the last
    sub-spectra don't contain real events, only artificial counts around the
    lowest detectable energy channel. This behavior, dubbed 'lockup', is
    currently under investigation. After any powercycle, the effect is gone.
    To mitigate the loss of scientific data, for longer data acquisitions
    the integration is therefore split into two integrations with a power
    cycle in the middle. This is to mitigate the risk that all data is
    lost if the lockup happens early in a single integration.

        