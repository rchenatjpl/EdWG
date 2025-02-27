
 
INSTRUMENT OVERVIEW
===================
 
The instrument was designed, built and tested by an international
partnership, led by NASA Goddard Space Flight Center (GSFC) and
including the CEN/Saclay and Observatoire de Paris-Meudon in France,
Queen Mary and Westfield College of the University of London, the
University of Oxford, and the Universitat Karlsruhe, Germany.
The principal investigator is M. Flasar (GSFC).
 
The final design has evolved considerably since the original
conception (KUNDEETAL1996). A description of the flight model of
the instrument is given here; the reader is referred to technical
publications in the literature (CALCUTTETAL1992, KUNDEETAL1996)
for further technical details.
 
Telescopes:                    Primary                 Secondary
----------
 
Diameter (cm):                   50.8                     7.6
F-number:                                    F/6
 
Interferometers:                Mid-IR                  Far-IR
---------------
 
Type:                          Michelson                Polarising
Spectral Range (cm-1):          10--600                 600--1400
Spectral Resolution (\cm ):     0.5--20                 0.5--20
Integration time (s):           50--2                   50--2
 
Focal Planes:*          FP1             FP3             FP4
------------
 
Spectral Range:         10--600         600--1100        1100-1400
Detectors:              Thermopile      Photoconductive Photovoltaic
                        (dual)         (1X10 array)     (1X10 array)
Pixel FOV (mrad):       4.3             0.27             0.27
Pixel A_Omega (cm^2):   2.4X10^-2       1.5X10^-4        1.5X10^-4
Peak D-star
(cm Hz^{1/2} W^{-1}):   4X10^{9}        2X10^{10}        7X10^{11}
Temperature (K):        170             74--92           74--92
 
CIRS Instrument Technical Specification.
*In the original proposal, the far-IR was covered by two focal planes, with
FP1 covering 10--300 cm-1 and FP2 covering 300--600 cm-1. These were
later combined into a single focal plane 1, covering the full range
10--600 cm-1.
 
The table summarises the principal instrument parameters.
The optics assembly is comprised of a telescope,
relay optics, and a pair of interferometers, covering the
mid and far-IR spectral regions. Both interferometers share a common
scan mechanism, as does a reference interferometer which controls
the sampling rate and mirror movement. The other main components of
CIRS are the detectors, the electronics assembly, and the passive
radiative cooler. The entire instrument is maintained at 170K, except
for the mid-IR detectors which are at ~80K.
 
The berylium telescope is a Cassegrain type, consisting of a
50.8 cm F/6 paraboloidal primary and a 7.6 cm hyperboloidal
secondary, the same sizes as used by the Voyager Infrared Interferometer
Spectrometer (IRIS). The primary mirror has a gold-enhanced
surface for low-scattering. The beam then passes to two
field stops, where one part of the field is relayed to the far-IR
interferometer and the other to the mid-IR interferometer, via
collimators and folding mirrors (see figures cirs_optics and
cirs_mechanical). A shutter may be commanded into the light path of the
mid-IR fore-optics for internal calibration.
 
The far-infrared interferometer (FIR) is of the Martin-Puplett type
(MARTIN&PUPLETT1969), which uses wire-grid polarisers to split, recombine
and analyse the radiation. This technique takes advantage of nearly
ideal-response wire-grid polarisers, which have reflection and
transmission co-efficients approaching 100% for both linear planes
of polarisation, and over a wide spectral range. The 2-micron centre
to centre wire spacing used in CIRS gives good response from
0--300 cm-1 and then decreasing response to 600 cm-1. The far-infrared
focal plane assembly (FP1) uses two thermopile detectors to measure
the final transmitted and reflected beams at the polariser-analyser,
however if one fails the interferometer can still operate, albeit with
a lower efficiency.
 
The 4.3 mrad diameter field of view (FOV) of the FIR detector
is the same as the IRIS detector. CIRS represents an improvement however in
terms of spectral range (10--200 cm-1 now being accessible) and
also in throughput, due to the greater efficiency of the polarising grids
over conventional mirrors in the far-IR.
 
The mid-infrared interferometer (MIR) is a conventional
Michelson design which has a KBr beamsplitter and cube-corner
retroreflectors. A germanium lens focuses the recombined beams onto
the mid-IR focal plane, which covers the range 600--1400 cm-1
using two photodetector arrays. The FP3 array of 1X10
photoconductive detectors measures from 600--1100 cm-1, which
includes prominent bands of acetylene, ethane, propane and
nitriles. The FP4 array of 1X10 photovoltaic detectors
covers 1100--1400 cm-1. This range includes the important 1304 cm-1
band of methane.
 
CIRS sensitivity is improved substantially over the IRIS
instrument in the MIR due to the use of cooled HgCdTe detectors
rather than a thermopile. The mid-infrared focal plane is
thermally isolated from the rest of the instrument by a tripod of
low-conductance titanium alloy supports. At the rear of the focal
plane, a flexible copper link connects to a cold finger, which extends from
the passive radiative cooler. This patch is of aluminium honeycomb
painted with conductive black paint, which radiates to a 2-pi field
of view of deep space.
 
The temperature of the mid-IR focal plane can be set via ground control
to temperatures between 70 and 90K, by balancing the cooling effect of
the patch with the application of a small heater, to an accuracy of 0.1K.
 
This improved sensitivity allows for a much smaller FOV: each pixel
has a 0.273 mrad square field of view, (c.f. Voyager IRIS 4.3 mrad)
although the response across this field is not flat. The spatial
response is given elsewhere in the documentation (CIRS_FOV_Overview.pdf).
This much smaller FOV allows for much higher spatial resolution on
the limb than IRIS, with a resolution of less than one scale height
in the stratospheres of both Saturn and Titan.
 
The relative sizes and alignment of the FIR and MIR fields of view is
depicted in figure (cirs-fov). Due to constraints on the
available mass for electronics, the ten detectors on each of the mid-IR
focal planes may not be used at once. Instead, five from each array
can be used simultaneously, in one of four modes (see figure modes):
odd detectors, even detectors, reduced field of view
(centre detectors only), or reduced resolution mode. This allows
considerable versatility in operation.
 
Both the FIR and the MIR interferometers share a common scan
mechanism and Reference Interferometer (RI), which is a red light
laser (785 nm) diode source. This provides
the reference fringes used to create timing signals for data
logging, and for feedback control of the mirror speed.
The scan time is set in units of 1/8 second (=1
RTI) from 2--52s, which takes the mechanism to the
maximum mirror travel distance of 1.04cm. The scan time controls the
spectral resolution, from 20--0.5 cm-1.
 
CIRS also provides an option for co-adding two consecutive interferograms
in an on-board buffer before downlink, which halves the data rate. To enable
this, the zero path difference (ZPD) of each interferogram must be
determined on board, which requires an additional white light
interferogram to be produced for reference. A white light source is
provided in the RI for this purpose, which is an LED of centre
wavelength 870nm and FWHM 70nm, and shares the optics with the
laser.
 
Decontamination heaters are also provided which can increase the
instrument temperature to ~270K to drive off contaminants which
may have condensed on the optics or detectors.

        