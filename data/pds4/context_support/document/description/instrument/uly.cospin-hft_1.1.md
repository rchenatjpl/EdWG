
 
 
  (descriptions excerpted from [SIMPSONETAL1992A])
 
  Instrument Overview
  ===================
    The HFT is designed: (a) to provide measurements of protons,
    helium, and heavier particles when the fluxes are too intense
    for the larger telescopes, and (b) to provide an instrument
    with exceptional azimuthal resolution so that highly collimated
    field-aligned particle distributions can be measured if they
    are encountered, especially over the solar poles and in
    Jupiter's magnetosphere.
 
 
  Detectors
  =========
    The HFT, which is mounted on top of the HET, consists of a
    single 25 mm^2 x 18 [micro]m silicon surface-barrier detector,
    passively collimated by a fan-shaped aluminium collimator to
    give a viewing aperture of 17 [deg.] x 60 [deg.], with a
    geometrical factor of 0.033 cm^2-sr.  The collimator imposes a
    low-energy cut-off of 50 MeV for protons and 5 MeV for
    electrons incident from outside the viewing aperture.  The
    exposed surface of the detector carries an evaporated layer of
    aluminium 0.25 mg/cm^2 thick to exclude light and attenuate
    low-energy protons, which would cause serious pulse pile-up
    when the flux is large and the energy spectrum steep, as in the
    inner Jovian magnetosphere.  The absorber excludes protons
    below 80 KeV and electrons below 10 KeV.  There is a small
    sensitivity to directly incident sun light which slightly
    increases the detector leakage current when the instrument is
    viewing the Sun.  The thinness of the detector, the high
    discriminator levels, and the fast shaping time constants used
    in the electronics make the HFT very insensitive to electrons.
    The detector output is amplified and shaped using
    double-differentiation time constants of 100 ns to provide
    bipolar pulses that can be handled without excessive loss or
    base-line shift at rates up to 10^6 per second.
 
    Five discriminator channels (designated F[1] - F[5]) set at
    levels corresponding to energy depositions between 0.20 and
    36.0 MeV define the energy ranges given in Table 9.  The F[1]
    discriminator can be set by command to any one of 16 threshold
    levels between 0.20 and 4.3 MeV.  Alternatively, F[1] can be
    commanded into a stepping mode where the discriminator cycles
    continuously through the 16 levels at a rate of one step per
    data accumulation period (16 seconds at a telemetry data rate
    of 1024 bits/s).  The stepped mode has been selected for normal
    mission operations.  The F[2] discriminator can be set by
    command to two levels corresponding to 0.21 and 0.50 MeV,
    respectively.  Channels F[3], F[4], and F[5] are set at levels
    2.45, 8.36, and 36.0 MeV, respectively.  F[1] levels 0-2 and
    F[2] levels 0-1 respond primarily to protons.  F[1] levels 3-13
    and F[3] respond primarily to helium.  F[4] responds primarily
    to the CNO group.  F[5] responds primarily to S and the Fe
    group.  The F[2] output to the DPU can be scaled down by a
    factor four on command when it is expected that the rate may
    exceed the capability of the DPU interface unit, as during
    Jupiter encounter.
 
    The instrument includes an internal, dual range, 128-step pulse
    generator for in-flight calibration of the discriminator
    triggering levels.
 
    The instrument is mounted so that the collimator 'fan' plane
    lies parallel to the spacecraft spin axis.  The central axis of
    the detector and the collimator is set at an angle of 45 [deg.]
    with respect to the Earth-pointing end of the spin axis so that
    the aperture extends from a spacecraft polar angle of 15 [deg.]
    to 75 [deg.].  All HFT counting rate accumulation intervals are
    spin synchronized using the Ulysses spacecraft sun reference
    pulse.  Channels F[1] - F[5] are each accumulated for an
    integral number of spins every telemetry read out.  The output
    of channel F[2] is also sector accumulated using 32 sectors per
    spacecraft rotation (11.25 [deg.] per sector), which permits
    the recognition of highly collimated angular distributions with
    a resolution of ~= 20 [deg.].  To conserve storage and
    telemetry facilities, eight equispaced sectors are successively
    accumulated for an integral number of spacecraft rotations
    having a nominal average period of 32 spacecraft minor frames.
    During the period over the solar poles and during an adjacent
    18-month period, the angle between the assumed direction of the
    interplanetary magnetic field and the spin axis will lie in the
    range 40 [deg.] +/- 25 [deg.], so that the field direction will
    be included within the HFT aperture at some time during each
    spacecraft spin period.
 
 
  Operational Considerations
  ==========================
    At closest approach to Jupiter (~= 6 R[j]), from Pioneer 10/11
    and Voyager 1/2 reports we estimate the electron intensity > 10
    KeV to be ~= 10^8 cm^-2 s^-1 sr^-1, or 3 x 10^6 s^-1 within the
    acceptance angle of the telescope.  This is on average ~= 0.3
    particles per 100 ns, with an average deposit of 15 - 20 KeV
    per particle (the maximum energy deposit is ~= 60 KeV).  The
    high order of pile-up required to trigger the 200 KeV
    discriminator makes electron contamination of this channel
    unlikely.  Electron pile-up studies have been performed at NRC
    using a small electron accelerator facility.
 
    At L ~= 7 R[j] where the proton flux reaches a maximum, we
    estimate that for energies greater than a specified energy, E,
    and a dJ/dE [proportional to] E^-3 spectrum, the integral
    proton flux through the detector will be ~= 2 x 10^5 E^-2 cm^-2
    s^-1 sr^-1 at energies around 1 MeV.  If this energy dependence
    persists down to low energy (50 - 100 KeV), the proton pile-up
    would, in the absence of an absorber in front of the detector,
    saturate the 0.20 MeV discriminator, and this effect would be
    appreciable out to L = 10 - 12 (where L is the McIlwain
    parameter which is equivalent to R[j] at the equator).  The
    presence of the 0.25 mg/cm^2 Al absorber significantly extends
    the intensity range where proton pile-up is unimportant.
 
    Since the alpha particle discriminator F[3] is set at 2.2 times
    the maximum energy deposition by protons, it requires a three-
    fold proton pile-up to simulate an alpha.  At L = 7, the proton
    contamination of the F[3] alpha channel is estimated at less
    than 10% and for L > 9 it is negligible.  In interplanetary
    space, the highest counting rates expected at the lowest
    discriminator levels are in the 10^3 - 10^4 s^-1 range, well
    below the level where pile-up or loss is significant.
 
 
  In-flight Performance
  =====================
    The post-launch performance of the HFT has been nominal in all
    respects.  Except for calibration periods, the HFT has been
    operated with the F[1] discriminator in stepped mode and the
    F[2] discriminator set low.  Periodic spikes in the HFT
    detector current monitor channel were observed following
    instrument switch-on with a period of 4064 +/- 16 seconds.
    This effect is caused by sunlight incident on the detector.
    The period is a function of the HFT view cone, the spacecraft
    spin period and the 32 second sampling of the detector current.
    Some sensitivity to sunlight had been expected from bench tests
    prior to instrument delivery and it was a relief to find that
    the maximum observed amplitude (~ 80 nA) was well below the
    level which would cause any increase in system noise.
 
    It is possible to extend the proton and helium energy spectra
    derived from the other COSPIN sensors down to about 0.3
    MeV/nucleon using the F[1] stepped discriminator channel.
    Using an assumed spectral form for the proton and helium
    differential energy spectra, the free parameters are determined
    by a best fit to the 16 F[1] counting rates.  This analysis has
    been performed for the period ~ 1700 to 2400 UT on day 296 just
    after instrument switch-on and yields reasonably consistent
    flux values with the LET, HET, and KET.
 
 
  Measured Parameters
  ===================
    Table 9.  High flux telescope data channels.
 
    Name  Discr.  Prim.  Energy    Species    Avg. Time   Sectors
    Discr.  Part.  Range*    for Ener.  Resolution
    Level   Type  (MeV(/n))  Range      (s)
 
    J0     Z>=1  0.28-7.0   Protons
    J1     Z>=1  0.50-2.27  Protons
    J2     Z>=1  0.76-1.37  Protons    16/readout
    F1+    J4     Z>=2  0.36-3.9   Helium     256 for      --
    J6     Z>=2  0.51-2.26  Helium     same disc.
    J8     Z>=2  0.64-1.66  Helium     level
    J10    Z>=2  0.78-1.35  Helium
    F2     Lo     Z>=1  0.29-6.7   Protons     16          --
    Hi     Z>=1  0.55-1.95  Protons
    F2s             [same as for F2]           32   8 sampled from 32
    128          32
    F3            Z>=2  0.68-1.56  Helium      32          --
    F4            Z>=3  0.8-4.9    Carbon      64          --
    F5            Z>=12 0.8-34+    Iron        64          --
 
 
    + F1 steps through 15 discriminator levels in sequence in
      standard flight mode.
    * Energy ranges form range-energy relations.
 

        