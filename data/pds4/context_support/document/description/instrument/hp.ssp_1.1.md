
 
 Instrument Overview
 ===================
 
The SSP experiment consists of nine separate sensors that are designed
to measure a wide range of physical properties of Titan's lower atmosphere,
surface, and sub-surface. By measuring a number of physical properties of
the surface it is expected that the SSP will be able to constrain the inferred
composition and structure of the Titan's near-surface environment.
Although the SSP is primarily designed to sense properties of the surface,
some of its sensors will also make measurements of the atmosphere along
the probe's entry path and will complement the data gathered by other
experiments on the Huygens probe.
 
 Science Objectives
 ==================
 
 Calibration Description
 =======================
A detailed description of the conversion of raw data into meaningful
quantities is given in the software user manual SSP_SUM.
Calibration tables can be
found in the CALIB directory on this volume.
 
 Instrument Manufacturers
 ========================
PSSRI, The Open University, Walton Hall, Milton Keynes (previously
University of Kent at Canterbury) is the lead Institute. Other
contributors include the Space Sciences Research Centre Warsaw,
the Rutherford Appleton Laboratory. See SSP_1177.PDF for details.
 
 Sensors Overview
 ================
 
 Accelerometer External (ACC-E)
 
The accelerometer subsystem is designed to characterise the immediate
surface of the landing site by recording the dynamic response of two
devices mounted in different positions on the probe.  One of the
sensors is designed to sense the force exerted
on a pylon that protrudes from the foredome aperture.  The force is
sensed by a piezoelectric ceramic element that is mounted between a
hemispherical titanium alloy head and the pylon shaft.  If Huygens lands
on a relatively uniform surface the ACC-E penetrometer will be smoothly
driven into the surface material until the probe's fore-dome strikes the
surface, bringing it to a halt.  During the impact process the ACC-E is
sampled at a rate of 10 kHz, giving it an effective depth resolution of
1 mm for a nominal mission impact speed of 5 m s-1.
 
 Accelerometer Internal (ACC-I)
 
A single commercially available accelerometer forms the second part of
the ACC sensor.  This device is mounted on a foot of the SSP electronics
box, which is fixed to the upper experiment platform. The ACC-I provides
information about the vertical non-static accelerations experienced by
the entire probe.
 
 Acoustic Properties Instrument - Sonar (API-S)
 
Like the ACC subsystem, the API has two separate parts.  The first of
these is an active sonar system (API-Sonar) mounted on the front of the
Top Hat cavity pointing downwards. This sensor will measure the
effective acoustic cross-section of the medium within its field of view
at a frequency of around 15kHz.  Each echo is sampled at a rate of 1kHz,
and during the final section of the probe's descent this sensor may be
able to provide information about the topography of the landing site
with a vertical precision of around 0.1 m.  In the case of a liquid
touchdown the API-S may also be able to provide lower bounds to the
depth of the liquid in which it has landed.
In the final few hundred metres of Huygens' trajectory the API-S will be
sufficiently close to the surface for it to detect the back-scattered
echo from the surface beneath it. Following the impact of the probe with
a liquid body the API-S will act as a depth sounder, using information
gathered from the Acoustic Properties Instrument-Velocimeter (API-V) on
the speed of sound in the medium.  In comparison to its atmospheric
operation the API-S operates with an increased efficiency when immersed
simply as a result of the medium's higher density and its better
acoustic coupling to the API-S.  Whilst afloat the API-S should be able
to record the depth of the liquid beneath the probe (up to a maximum
depth of 1000m).
 
 Acoustic Properties Instrument - Velocimeter (API-V)
 
The second portion of the API consists of a pair of piezoelectric
transducers mounted at the front surface of the Top Hat on either side
of the cavity. These sensors measure the speed of sound by transmitting,
and subsequently receiving, a brief 1 MHz acoustic signal.  The time
interval between transmission and reception is measured with a precision
of 250 ns and the separation of 0.125 m gives a speed resolution of 8 cm
s-1 when operating in gas at Titan's surface.  Throughout the descent
these sensors will be driven and subsequently sampled once a second,
giving a detailed profile of the speed of sound along the probe's
trajectory.  At least three other sensors in the probe's payload can
sense the atmospheric temperature, and thus the speed of sound will
yield the ratio of gamma (the ratio of specific heats) to m (mean molecular
mass). The next important contribution made by the API-V is at Titan's
surface in the event of the probe landing in a liquid body.  The speed
of sound is measured to a precision of 8 m s-1, a fidelity that
corresponds to a mixing ratio of 1.6 % for a methane / ethane ocean.
 
 Density Sensor (DEN)
 
Upon landing in a liquid the density of any fluid that makes its way
into the cavity of the SSP will be estimated by the DEN sensor.  This
instrument measures the upthrust applied by a liquid to a small buoyant
float which is attached to the SSP by a pair of epoxy beams that are
equipped with strain gauges.
In addition considerable scope remains for the detection of phenomena
that are secondary to the main role of the SSP.  For example,
immediately following the probe's impact with a liquid the DEN may
detect the periodic inflow and outflow of fluid from the SSP cavity.
Measurements of the rate at which this bobbing motion decays will place
constraints on the viscosity of the impacted liquid, a property that is
not directly measured by any sensor.
 
 Permittivity Sensor (PER)
 
In the event of a liquid landing the SSP will also be able to determine
a number of electrical properties of the fluid.  The PER device consists
of 22 stacked parallel plates, the capacitance of which is measured at a
number of different frequencies.  By briefly pulsing the sensor with DC
voltages the conductivity of the surrounding liquid may also be
ascertained, placing constraints on the population of dissolved ions (if
any) in the medium.  The PER also carries a thermometer in the form of a
silicon diode, which has a precision of better than 0.5 K.
 Although any probable Titan atmosphere has a relative permittivity that
is almost identical to 1, and therefore cannot be detected by PER, at
the tropopause (altitude 40 km) significant quantities of
methane/nitrogen may condense temporarily on the PER sensor. If
sufficient material collects on the PER some or all of the sensing
plates may be bridged and the condensate may thus be detected.
 
 Refractive Index Sensor (REF)
 
The REF sensor measures the refractive index of a liquid by using a
linear critical angle refractometer, the method and design of which is
discussed by Geake et al (1994).
This device consists of a section of a cylindrical
prism that can be illuminated by collimated sources (light guides fed by
light emitting diodes, LEDs, at 635 nm) that are both internal and
external to the prism.  When the REF is immersed in a medium of given
refractive index light striking the interface between the prism and the
liquid will experience a critical angle effect, in which case the light
is refracted or reflected. For both the internal and external
illumination only part of the beam is reflected or refracted onto the
detector, the remainder escaping or being reflected from the prism. A
512 element linear photodiode array is attached to one face of the prism
and this array is used to measure the resulting transition from light to
dark, the position of this transition, or cut-off, being linearly
related to the refractive index of the liquid. The sensor covers the
refractive index range 1.250 to 1.450 with a discrimination of 0.001.
The external light source is provided so that an estimate can be made of
the opacity of the ambient liquid, from a comparison of the illumination
profile received from the internal and external sources.
 
 Thermal Properties Sensor (THP)
 
The main role of the THP is to measure the thermal conductivity and
diffusivity of the ambient medium in the SSP cavity.  Along with the
Acoustic Properties Instrument (API), the THP is designed to sense
properties of both liquid and gaseous media, using two separate sets of
redundant hot wire sensors enclosed in cylindrical shields.  By applying
a known current for a fixed duration to the THP's sense wires in each of
the four cylindrical canisters the wires are made to act as regulated
heat sources.  This method is covered in detail by Healy et al. (1976).
 In the close confines of the wires' shields the transient heat pulse
thus generated is lost by conduction to the medium surrounding the wires
at a rate that is determined by the thermal properties of the material.
 Measurements of the wires' resistance as a function of time before and
after the heating pulse reveal the initial temperature of the medium and
its thermal properties.  Two diameters of platinum wire are used in the
THP, the thinner wires (10  m diameter) are sized for the relatively low
thermal conductivity of the atmosphere, and the thicker 25  m diameter
wires are only driven when the Huygens probe has reached the surface.
A THP measurement is made every minute throughout the atmospheric phase
of the descent and will therefore provide a relatively fine record of
the thermal properties of the atmosphere along Huygens' trajectory.
 
 Tiltmeter (TIL)
 
One of the important analyses to be carried out after arrival at Titan
is the reconstruction of the probe's motion, i.e. its trajectory,
attitude, swing and spin, as it falls through the atmosphere and then
subsequently during any post-impact dynamics.  Throughout Huygens'
descent particular aspects of the probe's motion will be measured with
varying precision by three separate experiments, Doppler Wind Experiment,
Huygens Atmospheric Structure Instrument (HASI), and SSP.  Of
these, TIL is the only device that provides unambiguous information
about the Huygens probe's attitude with respect to the local vertical
rather than its acceleration.  Two inclinometers are arranged to form an
orthogonal x-y pair inside the sensor housing which is attached to the
SSP electronics box.  During the probe's descent the TIL is sampled at a
rate of 1 Hz.
 
 
 Definition of SSP Operating Modes
 =================================
 
The SSP operating modes are defined as follows:
M0: Checkout / Diagnostic mode - not used during the real descent
M1: upper atmosphere mode
M2: mid atmosphere mode
M3: lower atmosphere mode
M4: proximity mode
M5: surface mode
M6: extended surface mode
M7: Checkout / Diagnostic mode - not used during the real descent
A functional breakdown of SSP's sensors is given in section 2.4
of the software user manual SSP_SUM.

        