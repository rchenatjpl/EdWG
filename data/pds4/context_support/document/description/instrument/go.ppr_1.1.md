
 
Instrument Overview
===================
The Galileo Photopolarimeter Radiometer (PPR) is a multi-purpose and
multi-function instrument designed for both solar wavelength
photopolarimetry and thermal infrared sounding and radiation budget
measurements.  Mounted on the Galileo Orbiter scan platform along
with the SSI, NIMS, and UVS instruments, the PPR scene telescope has
a single circular field of view of 2.5 mrad and uses scan platform
slews and mosaic sequences to map out larger regions.  The wavelength
observed is determined by the position of a rotating filter wheel
with 32 equally spaced positions (numbered 0 through 31).  Positions
0 - 17 are used for three polarimetry wavelengths, 18 - 24 for seven
thermal radiometry bands, and 25 - 31 for seven photometry bands.
For the positions corresponding to polarimetry and photometry bands,
the scene flux is directed by a relay lens through a Wollaston prism
that splits the input into two orthogonally-polarized output beams,
which are then focused onto a pair of silicon photodiode detectors.
At each of the thermal radiometry positions, a chopper mirror
alternately directs the scene flux and the space-view reference flux
through the filter and then from an elliptical mirror on the back of
the filter wheel to a pyroelectric detector.  The PPR is a 5-kg
instrument with overall dimensions of 45 x 39 x 33 cm.
 
Scientific Objectives
=====================
The primary science objectives and anticipated results of the PPR
experiment are to:
 
  (1) determine the vertical and horizontal distribution of cloud and
      haze particles in the atmosphere of Jupiter, including their
      size, shape, and refractive index;
  (2) determine the energy budget of Jupiter and the variations in
      amount and spatial distribution of reflected solar radiation
      and emitted thermal radiation for Jupiter and its satellites,
      including the thermal structure of the atmosphere and the
      vertical distribution of absorbed solar radiation in the
      atmosphere of Jupiter;
  (3) measure and map the photometric, polarimetric, and radiometric
      properties of the major satellites of Jupiter.
 
Instrument Calibration
======================
Various preflight and inflight tests of the PPR are performed to
characterize the instrument performance and calibration.  Principal
preflight tests included radiometric calibration of solar wavelength
channels with standard lamps, polarization accuracy and instrumental
polarization determination using various sources with known
polarization, and radiometric calibration of thermal channels using
blackbody calibration units with controllable temperatures in a
thermal vacuum chamber environment.  Inflight radiometric calibration
is performed with a radiometric calibration target (RCT-PPR) that is
separately mounted on the spacecraft and viewed by the PPR at zero
cone angle.  The RCT is passively cooled to a nominal temperature
near 140 K, with the actual temperature monitored by two platinum
resistance thermometers connected to the instrument so that their
readouts can be included in the PPR science data stream.  A small
tungsten-filament lamp is mounted in the RCT interior with an
elliptically shaped, sapphire cover plate mounted such that its outer
surface approximately conforms to the inner conical surface of the
RCT.  When this lamp is commanded on, it serves as a radiometric and
polarimetric reference standard for the shortwave channels.  There is
a photometric calibration target on the spacecraft that can be viewed
by all the remote sensing instruments, thus providing a visible and
near-IR radiometric reference by solar illumination of its well-
characterized diffusely reflecting surface.  Along with the other
scan platform instruments, the PPR can use observations of relatively
brighter stars as flux standards in the visible and near infrared.
In addition, such observations are employed to characterize the off-
axis light rejection of the PPR optical system and to determine the
precise boresighting offsets between the scan platform instruments.
 
Operational Considerations
==========================
The PPR is designed so that it may be commanded to operate in several
different modes and with selectable configurations within each of
those modes.  The selected mode and configuration parameters control
the specific cycling of the filter wheel and thus the set of bands at
which measurements are acquired during a single cycle.  With such
flexibility in determining the operational mode, it is possible to
select a measurement cycle that is optimized for various spacecraft
scan platform slew rates as well as providing measurement sets other
than the default of cycling through all the PPR bands when science
objectives so dictate for particular targets or circumstances.
 
Basic instrument operational functions follow two very different
processes depending on whether the measurements are photopolarimetry
or thermal radiometry.  For polarimetry and photometry measurements,
the flux from the scene is collected by the scene-view telescope and
focused onto a circular field stop subtending 2.5 mrad.  Flux passed
by the field stop then is modified by passage through optical
elements located on the filter/retarder wheel.  At the polarimetry
positions, the flux passes through a halfwave retarder and a spectral
filter, while at photometry positions it passes only through a
filter.  The relay lens directs the flux through the Wollaston prism
which serves as a polarizing beam-splitter and produces two
spatially-separated and orthogonally-polarized output beams.  The
detector lenses focus these beams onto the two silicon photodiodes.
During polarimetry and photometry measurements, the chopper is kept
stationary and is positioned so as not to block the scene flux.  The
amplified detector outputs are converted to a pair of 12-bit samples
with dark-reading offsets of 190 DN.
 
During radiometry measurements, the chopper is operated at 30 Hz and
alternately directs the flux from the scene-view and space-view
telescopes through the field stop.  At each radiometry position, the
flux passed by a radiometry filter is reflected radially outward
from the filter/retarder wheel by means of an ellipsoidal mirror
(one mounted on the wheel at each of the seven radiometry positions).
The flux reflected by the ellipsoidal mirror is collected by a
condenser system consisting of a truncated conical reflector with a
small diamond lens mounted onto the small end of the cone.  The
focused, modulated flux is detected by a lithium tantalate
pyroelectric detector.  The alternate views from the scene-view and
space-view telescopes allow the scene radiance to be referenced to
the space background (approximately a 3 K blackbody).  There are four
optical elements designated as 'radiometric stops' that serve to
restrict the modulated flux reaching the detector to that received
from the scene or space, or from the internal instrument elements,
which are radiometrically balanced to first order.  These radiometric
stops, together with careful preflight calibration, temperature
monitoring of key optical elements, and an accurately-monitored, high
emittance inflight calibration target (the RCT-PPR), are key to
performing radiometrically useful measurements on a cool scene such
as Jupiter with the warm PPR instrument.  The amplified detector
output is converted to a 12-bit sample with a zero radiance level
offset of 1400 DN.  In radiometry, the second sample of the pair is
the 12-bit converted readout from one of ten thermistors monitoring
the temperatures of internal optical elements or one of the two
platinum resistance thermometers monitoring the RCT.  As radiometry
measurements are acquired, the instrument cycles through the twelve
temperature elements for the temperature data that are placed in the
second sample of the pair, with the instrument housekeeping status
identifying the specific element number.
 
It should be noted that for certain scan platform pointing directions
(below about 90 degrees cone angle), spacecraft booms on the spinning
part of the spacecraft sweep periodically through the fields of view
of all remote sensing experiments.  The user of such data should be
aware of these effects and remove them either by inspection from the
artificial variation of data caused by boom obscuration or by use of
a map of boom locations in spacecraft clock angle space.  The PPR can
be commanded to use a 'boom operation mode' in which the filter wheel
is fixed at a single position for an entire spacecraft spin period.
With this type of operation, the booms affect the same ranges of
sample numbers within the set of samples acquired during each spin
period.
 
Detectors
=========
Visible and Near-Infrared
-------------------------
DETECTOR_ID                    = VISIBLE
DETECTOR_TYPE                  = Si
MINIMUM_WAVELENGTH             = 0.36
MAXIMUM_WAVELENGTH             = 0.97
 
The PPR uses two silicon photodiodes for the visible and near-
infrared region (out to 0.97 micrometer).  For typical Jovian
radiances, the signal to noise ratio for the polarimetry channels
exceeds 2000 and for the photometry channels is greater than 1000
except for the 0.892 methane absorption band, which is approximately
400.  The Jovian albedo of Woodman et al. (1979, Icarus, v.37, 73)
was used to set polarimetry and photometry gain levels.
 
Thermal Infrared
----------------
DETECTOR_ID                    = IR
DETECTOR_TYPE                  = LiTaO3
MINIMUM_WAVELENGTH             = 0.3
MAXIMUM_WAVELENGTH             = 110
 
The PPR uses a lithium tantalate pyroelectric detector for the
thermal infrared sounding bands and for the broad-band bolometric
channels.  Sensitivity for the radiometry channels was affected by
low long-wavelength responsivity of the detector and low filter
transmission at several bands.  The signal to noise ratio for a 130 K
target was measured to be 30 at 17 micrometers; 20 at 21 micrometers;
41 at 27.5 micrometers; 12 at 37 micrometers; 33 at >42 micrometers;
and 460 for the solar plus thermal band with thermal input only.
 
Electronics
===========
The low power electronics for the PPR instrument retains much of the
radiation-proven circuitry from the predecessor instruments built
for the Pioneer missions, but most of the discrete control logic has
been replaced by a radiation-hard CMOS microprocessor system.  The
analog circuitry consists of two silicon photodiode polarimetry and
photometry channels, one pyroelectric radiometry channel, and an
analog multiplexer, which presents the three signal channels and the
temperature telemetry channels to the 12-bit analog to digital
converter.  The digital circuitry decodes the serial spacecraft
commands and formats the instrument signal and telemetry data for
transfer to the spacecraft via the command and data bus.  The digital
system also provides timing signals for analog channel and mechanism
controls.  The power subsystem conditions the 30 vdc spacecraft input
power and provides the necessary regulated and filtered voltages for
instrument operation.  This subsystem also contains the power driver
circuitry for the actuator controls and calibration lamp.
 
Optics
======
The PPR employs a 10-cm aperture scene-view telescope of
Cassegrainian Dall-Kirkham design, which gives excellent image
quality for the 2.5 mrad (0.143 degree) instantaneous field of view,
with the image quality being dominated by diffraction at the longer
wavelengths.  The alternating view of space for thermal radiometry
observations is via reflection from the chopper mirror and the planar
space-view telescope mirror.  Located on the filter/retarder wheel
are spectral filters used to define the required spectral bandpasses,
the halfwave retarders used for the polarization analysis of the
scene, and the ellipsoidal mirrors (on the back side of the wheel)
used to direct scene flux towards the radiometry detector.
 
Filters
=======
Filter Wheel   Measurement Function          Center       Bandwidth
  Position                                 Wavelength
                                          (micrometers) (micrometers)
---------------------------------------------------------------------
  1, 3, 5      Polarimetry                    0.9446         0.0108
  7, 9, 11     Polarimetry                    0.6785         0.0087
 13, 15, 17    Polarimetry                    0.410          0.060
     18        Radiometry, thermal           16.8            4.2
               sounding - channel A
     19        Radiometry, thermal           21.0            3.0
               sounding - channel B
     20        Radiometry, thermal           35.5            6.9
               sounding - channel D
     21        Radiometry, thermal           27.5            7.2
               sounding - channel C
     22        Radiometry, thermal            --            45-110
               sounding - channel E
     23        Radiometry, bolometric -       --             0.3-4.0
               solar
     24        Radiometry, bolometric -       --             0.3-110
               solar plus thermal
     25        Photometry, medium strength    0.6187         0.0070
               methane absorption band
     26        Photometry, continuum          0.6333         0.0086
     27        Photometry, weak ammonia       0.6480         0.0074
               absorption band
     28        Photometry, medium strength    0.7887         0.0119
               ammonia absorption band
     29        Photometry, continuum          0.8293         0.0119
     30        Photometry, weak methane       0.8403         0.0071
               absorption band
     31        Photometry, strong methane     0.8918         0.0111
               absorption band
 
Mounting Offset
===============
The PPR is mounted on the Galileo Orbiter scan platform, with its
scene telescope optical axis nominally coaligned with the view
optical axes of the SSI, NIMS, and UVS instruments.
 
Field of View
=============
The PPR instrument has a circular field of view, with a diameter of
2.5 mrad, or 0.143 degrees.
 
Parameters
==========
When the PPR is operating, it delivers an 18-byte science and
housekeeping data record to the spacecraft command and data handling
system every two-thirds of a second, i.e., once each minor frame of
the spacecraft clock.  The first six bytes of this record are
housekeeping data that completely specify the instrument status, both
commanded parameters and position within operational measurement mode
cycles.  The remaining twelve bytes are three sets of science data
sample pairs and their associated identifying parameters and parity
check bit.
 
Operational Modes
=================
The commanded state of the PPR includes the selection of one of five
basic operational modes: (1) cycle, (2) photopolarimetry plus
photometry, (3) photometry, (4) radiometry, and (5) position select.
In cycle mode, the PPR collects data at all of the photopolarimetry
(polarimetry), radiometry, and photometry filter positions.  Filter
wheel stepping is unidirectional from low to high filter position
number.  In photopolarimetry plus photometry mode, the filter wheel
stepping is unidirectional in the same manner as for cycle mode, but
data is collected only at the polarimetry and photometry filter
positions, with the instrument simply stepping through the radiometry
positions.  In the photometry mode, the PPR collects data only at the
photometry positions, using bidirectional stepping of the filter
wheel.  Note that this involves stepping not only through the
photometry positions, 25 - 31, but also positions 24 and 0 at which
the dark current level restoration (DC-restore) function is
performed.  In the radiometry mode, data is collected only at the
radiometry positions (18 - 24), using bidirectional stepping of the
filter wheel.  In the position select mode, the PPR collects data at
a single filter or a contiguous series of filter positions, with the
specific sequence determined by additional command parameters that
specify the starting filter position and the number of additional
positions (with choices of 0, 1, 2, and 5 additional positions).  If
more than one filter position is specified, then the filter wheel
steps through those positions in a bidirectional sequence.
 
Timing of the various PPR operations is based upon the same 30 Hz
clock used for the chopper mirror, i.e., a clock cycle of 33.3 msec.
The data sample integration period for polarimetry and photometry
filter positions is 7 clock cycles and for radiometry positions is 14
clock cycles.  Stepping the filter wheel between adjacent positions
requires 6 clock cycles.  In cycle mode, the start-up of the chopper
at filter wheel position 18 to begin radiometry sampling and its
stopping sequence at position 24 require 49 clock cycles.
 
Various command parameters control the specific nature of the
sequence within each of the PPR modes.  In addition to the programmed
filter position and the number of additional filter positions that
control the range of positions at which data are collected in the
position select mode, these parameters are as follows.
GAIN STEP PP/PH:  Selects gain setting for photopolarimetry and
photometry channels from among 16 levels, with each being separated
from adjacent levels by a factor of approximately 1.4.
 
GAIN STEP RAD:  Selects gain setting for radiometry channel from
among four levels, with each being a factor of 2 greater than the
next lower level.
 
NUMBER OF SAMPLES:  Selects the number of samples of data to be
accumulated at each active filter wheel position before stepping to
the next filter, with the choices being 1, 4, 16, and 256 samples.
In position select mode, the commanded number of samples is used as
the number of cycles of position select operation occurring between
DC-restore sequences (if the DC-restore parameter is commanded on).
 
NUMBER OF SAMPLES MULTIPLIER:  Selects the multiplier for number of
samples at radiometry positions as either 1 or 4.  So if the number
of samples were specified as 16 and the number of samples multiplier
were 4, then 16 samples would be accumulated at each polarimetry and
photometry position and 64 samples at each radiometry position.  The
maximum number of samples is limited to 256.  A multiplexed function
of this parameter is that when the external cal lamp is activated,
the multiplier selects the lamp to be on for just six samples if it
is set at 1 and keeps the lamp on for all the samples acquired during
the spin period if it is set at 4.
 
CAL LAMP:  Enables or inhibits the preprogrammed calibrator lamp
operation depending on whether the command bit is 1 or 0,
respectively.  Enables the external cal lamp if it is set at 1 and if
the boom sequence operation parameter is enabled as well.
 
DC-RESTORE:  Initiates special DC-restore cycle in position select
mode or under boom sequence operation wherein the filter wheel is
stepped to the appropriate DC-restore filter wheel position, the DC-
restoration function is performed followed by readout of a single
dark level sample, and the filter wheel is returned to the next
position of the sequence of the selected mode.
 
BOOM SEQUENCE OPERATION:  Stepping of the filter wheel between
adjacent functional positions is initiated once per spacecraft spin
period based upon PPR receipt of spin period data and spin reference
signal from the spacecraft.  The external cal lamp in the RCT is
enabled only in boom sequence operation and if the cal lamp parameter
is also set to enabled.
 
TEMPERATURE RANGE SELECT:  Selects the initial high or low range for
thermistor temperature sensors.  If the thermistor output is out-of-
range for the selected case, instrument software automatically
switches the range for that particular thermistor readout.
 
Because of the differences in time required for specific steps of the
instrument operation, the various operational modes of the PPR result
in the generation of the 18-byte science data records at variable
rates.  Those rates range from just slightly slower than that at
which the spacecraft performs the readout of those records (viz.,
once each minor frame, or two-thirds of a second) to a rate that is
approximately three times slower.  Accordingly, the PPR design uses
two internal 18-byte buffers that are alternately filled, with one
buffer being active, or in the state of being filled, and the other
containing the previous 18 bytes of science data for the sequence.
At the time of the each spacecraft readout of PPR data, it is only
the non-active buffer that is presented and placed into the telemetry
stream, and whenever that buffer has been previously transferred, the
PPR sets a flag in the housekeeping data of that record to indicate
that it is a 'repeat' record.  Thus, the PPR data stream in general
contains redundant data in the form of these repeat records.  As a
consequence, the spacecraft event times and scan platform pointing
angles that are 'attached' to each minor frame in the spacecraft
telemetry correspond to a variably later time than that at which the
actual data samples in the PPR science data record for that minor
frame were acquired.  The basic PPR data reduction software accounts
for the specific operational modes and adjusts these times and scan
platform pointing angles to provide accurate values for each of the
three sample pairs within the 18-byte science records.
 
 
      Russell, E.E., F.G. Brown, R.A. Chandos, W.C. Fincher,
      L.F. Kubel, A.A. Lacis, and L.T. Travis,
      Galileo Photopolarimeter/Radiometer Experiment,
      Space Sci. Rev. 60 p. 531-563, 1992.
 
      Hunten, D.M., L. Colin and J.E. Hansen,
      Atmospheric Science on the Galileo Mission,
      Space Sci.  Rev.,  44, 191-240,  1986
 
      Johnson, T.V., C.M. Yeates and R. Young,
      Space Science Reviews Volume on Galileo Mission Overview,
      Space Sci. Rev.,  60,  3-21,  1992

        