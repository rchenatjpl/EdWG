
The Galileo Magnetometer description comes from the Space
Science Reviews instrument paper which is reproduced here
with permission from Kluwer Academic Publishers, Dordecht,
Boston, London (KIVELSONETAL1992). Three appendices to the original
article are provided at the end of the description that
describe changes to the flight software and data acquisition
in the Phase 2 mission (low gain antenna mission),
some of the in-flight anomalies that have occurred
and their resolutions, and the MAG command dictionary.
 
          THE GALILEO MAGNETOMETER
 
Abstract
 
The Galileo Orbiter carries a complement of fields and
particles instruments designed to provide data needed to
shed light on the structure and dynamical variations of the
jovian magnetosphere.  Many questions remain regarding the
temporal and spatial properties of the magnetospheric
magnetic field, how the magnetic field maintains corotation
of the embedded plasma and the circumstances under which
corotation breaks down, the nature of magnetic perturbations
that transport plasma across magnetic shells in different
parts of the system, and the electromagnetic properties of
the jovian moons and how they interact with the
magnetospheric plasma.  Critical to answering these closely
related questions are measurements of the dc and low
frequency magnetic field.  The Galileo Orbiter carries a
fluxgate magnetometer designed to provide the sensitive
measurements required for this purpose.  In this paper, the
magnetometer is described.  The instrument has two boom-
mounted, three-axis sensor assemblies.  Flipper mechanisms
are included in each sensor assembly for the purpose of
offset calibration.  The microprocessor controlled data
handling system produces calibrated despun data that can be
used directly without further processing.  A memory system
stores data for those periods when the spacecraft telemetry
is not active.  This memory system can also be used for
storing high time-resolution snapshots of data.
 
Introduction
 
The jovian magnetosphere envelopes the planet in a vast
cocoon around which the solar wind is deflected in its
outward flow from the sun.  The magnetic field of the planet
itself brings order to the plasma contained in the
magnetosphere, constraining the ions and electrons to move
in orbits imposed by electromagnetic forces.
 
In the 1970's, four spacecraft: Pioneer 10 and 11, and
Voyager 1 and 2 traveled through the magnetosphere of
Jupiter and provided information on the properties of the
charged particles and the fields within it.  These missions
showed that the magnitude of the magnetic dipole moment is
4.3 RJ3 x 10-4 T, or 4.3 x 105 nT at the level of the cloud
tops near the equator.  This is an order of magnitude larger
than the magnetic field at the terrestrial surface.  As at
Earth, the jovian plasma contains ions of solar wind origin
and ions of ionospheric origin.  Unique to Jupiter is the
large population of heavy ions whose source is the galilean
moon, Io; these ions form a torus of relatively high plasma
density near Io's orbit but they also diffuse out to form an
important component of the plasma present throughout the
magnetosphere.  The heavy ions, spun up to corotation
velocity by magnetic (jxB) forces imposed by field-aligned
currents flowing between the ionosphere and the
magnetosphere, carry cross-field currents that distort the
magnetic field into a disk-like geometry at large distances.
 
Although many features of the magnetosphere were identified
by the first four spacecraft to make measurements within it,
there are still many puzzles.  For example, it is not clear
how the plasma, whose ultimate source is Io, is transported
through the magnetosphere.  Over large spatial regions, the
magnetic field imposes corotation, but it is thought that
corotation breaks down at large distances in the evening
sector, and possibly more generally when new plasma is added
at an unusually large rate.  The system appears to display
large scale temporal changes, but it is not clear whether
the changes are internally or externally driven and the time
scales for changes are not understood.  The Galileo mission
will provide new data with which it will be possible to map
the jovian magnetosphere, monitor magnetospheric dynamics,
and investigate magnetosphere-ionosphere coupling.  The
presence of Jupiter's large moons perturbs the plasma, and
Galileo spacecraft investigations of the plasma interaction
with the satellites will yield information about properties
of both the plasma and the moons themselves.  For example,
during the flyby of Io it will be possible to determine
whether or not Io has an internally generated magnetic field
(Kivelson et al., 1979).  By remaining within the
magnetosphere for years instead of weeks (as for a flyby
mission), the Galileo Orbiter will be able to study the
structure and the time variability of the system on both
large and small scales.  Finally, the spacecraft will make
measurements in the magnetotail near the midnight meridian
where it may be possible to find evidence of a planetary
wind flowing away from Jupiter.
 
The lengthy (six year) interval of interplanetary cruise
will also provide opportunities for carrying out scientific
investigations.  During the flyby of Venus in 1990,
particles and fields instruments on the spacecraft will
acquire data of great value to the study of the cloud-
covered planet.  The magnetometer will, in particular,
provide data on the temporal variations of the solar wind
that will be studied in conjunction with data from the
Pioneer Venus Orbiter to provide insight into the time
constants for transport of plasma and fields through the
ionosphere of Venus.  Studies of pick-up ions and of the
electromagnetic signals from lightning on Venus will also be
carried out.  During the flybys of Earth whose magnetic
properties are well-known, the accuracy of the instrument
measurements will be assessed and data will be available for
coordinated studies with spacecraft operating in Earth
orbit.  During the interplanetary cruise period, the solar
wind will be monitored.  Galileo measurements will provide a
valuable baseline for the study of the large scale structure
and evolution of the solar wind.  For this purpose,
comparison with the data of the Ulysses spacecraft which
will be in the solar wind at different distances and
latitudes will be of special interest.
 
For all of these science objectives, the measurements of the
magnetic field and of its low frequency variations are
fundamental.  In addition to providing data of direct
importance for scientific investigations, the magnetometer
performs a critical service function, providing the
reference direction essential to the meaningful analysis of
the plasma and energetic charged particle measurements.  As
the interpretation of all fields and particle measurements
relies on knowledge of the magnetic field direction and/or
magnitude, it is essential that physically meaningful data
from the magnetometer be available without delay following
the transmission of data from the spacecraft.
 
To develop the magnetometer instrument and a data-processing
system that provides scientifically useful data, and to
carry out scientific investigations based on the data, a
team of experts has been assembled.  Table I lists the
principal team members and their responsibilities.
 
The magnetometer has been designed to provide highly
accurate and stable measurements of field vectors over an
exceptionally broad dynamic range from the low values
characteristic of the distant solar wind and the distant
magnetotail (~0.1 to 1 nT) to values larger than the largest
anticipated (~6x103 nT) near closest approach to Jupiter.
So that small perturbations can be measured with great
accuracy, the stray field of all spacecraft systems were
constrained to produce less than 0.1 nT magnetic
perturbations at the outboard sensor.  Knowledge of sensor
orientation will be better than 0.l degrees.
 
The design of the magnetometer on the Galileo Orbiter
incorporates several innovations that will enhance the
scientific value of the measured data.  In particular, the
Galileo magnetometer can provide calibrated data in 'despun
coordinates' using on-board data-processing.  Such data can
be used by investigators immediately upon receipt without
further delay for data analysis.  The magnetometer also
provides for storage of time-averaged data.  Thus, even
during intervals when the spacecraft is not transmitting
data to Earth, a complete record of magnetic field data will
exist.  In addition, the instrument was designed and built
to meet standards of signal fidelity and reliability as
strict as any ever previously imposed on a spacecraft
magnetometer.
 
The design of the Galileo magnetometer, therefore, presented
many challenges.  The requirement of high sensitivity is
difficult to achieve on a complex spacecraft.  Reliability,
essential because of the prolonged duration of the mission
with a six year cruise preceding the beginning of the two-
year mission, posed additional problems.  Special
requirements on the data coverage and format required
development of a new approach to data-handling capabilities
as noted above.
 
Critical Aspects of the Instrument Design
 
The design challenges described in the introduction were met
in a variety of ways.  We chose to fly a boom-mounted dual
triaxial fluxgate magnetometer with ring core sensors in a
flipper assembly.  The electronics unit housed within the
spacecraft contains the drive and sense electronics of the
sensors, analogue-to-digital converters, a microprocessor,
and power conditioning and control circuitry.
 
The sensors in each triad are oriented so that
one is closely aligned along the spin axis of the spacecraft
and two sensors lie with orthogonal orientations in the
spacecraft spin plane.  The individual sensors contain drive
and sense coils surrounding a magnetically permeable core.
Currents in the drive coils drive the permeable core into
saturation twice during each drive cycle, symmetrically
positive and negative.  An external field breaks the
symmetry of the periodic core saturation, and sense coils
detect the resultant harmonics of the drive frequency.  The
amplitudes of the even harmonics are proportional to the
component of the ambient magnetic field along the axis of
the sense coils.  The instrument senses the second harmonic
signal, i.e. the harmonic of largest amplitude.  A feedback
current that nulls the external field is applied to a coil
around the sensor so that the core operates in a zero field
condition.  Thus, the amplitude of the feedback current is
proportional to the component of the external field along
the sensor axis.  The data system senses the analogue
voltage proportional to the feedback current and converts it
to a digital signal which is transmitted to earth.
 
We chose a fluxgate magnetometer because of its low power
and its robustness, as well as because our laboratory has
had experience on many missions with successful fluxgate
operation.  The ring core sensor was chosen because of its
proven stability and low noise.  The flipper assembly was
included so that the sensor along the spin axis can
periodically be rotated into the spin plane where its zero
level can be checked.  This feature also offers some
redundancy.  If the sensor along the spin axis were to cease
operation, one of the two sensors could be rotated 9Oo to
replace it.  Then the three vector components could still be
measured, albeit only once per spin period.
 
The need for extreme sensitivity was recognized not only in
the instrument design but also in the design of the
spacecraft which has a long boom to isolate the primary set
of sensors from the magnetic fields generated by the complex
spacecraft and its subsystems.  A second set of sensors
located 1/3 of the way down the boom was incorporated to
assist in the identification of spacecraft fields.
Spacecraft fields will decrease in magnitude with distance
from the spacecraft and will often be related to specific
spacecraft activities.  Such magnetic fields can be
characterized to first order by using data from both the
inboard and outboard sensors if it is assumed that the field
sources are localized dipoles; the data can then be
corrected by removing the contributions of locally-generated
fields.
 
The sensitivity of the magnetometer is needed not merely to
measure small magnetic fields but also to measure small
variations of the field in a large background magnetic
field.  This requirement cannot be met with an instrument
that has low fractional resolution in any one range but many
operating ranges; instead the instrument must have both a
large dynamic range and high resolution.  This need was met
by using a high precision A/D converter with l2-bit
digitization and l5-bit accuracy.  Averaging data with this
accuracy prior to telemetry increases the effective
resolution of the measurements.  Our careful plans for
achieving high sensitivity could be frustrated by the
presence of significant sources of oscillating spacecraft
fields in the bandwidth of the magnetometer.  A careful
program of magnetic testing, shielding, compensation and
proper cable design for the entire spacecraft was undertaken
to insure spacecraft magnetic cleanliness and thus to
preserve magnetometer sensitivity.
 
The requirement for extreme reliability was met in several
ways.  Of course, the highest reliability parts were used
and to the extent possible, the circuitry is insensitive to
single part failures.  The use of separate inner and outer
sensor assemblies adds some redundancy and so does the
flipper, as mentioned above.  In addition to guarding
against failure, one also has to be aware of changes in
instrument operation.  As the spacecraft spins, the gains
and relative phases of the sensors in the spin plane can be
intercompared.  The flipper can be used to bring the spin
axis-aligned sensor into the spin plane so its gain and
phase can also be determined.  An internal calibrate signal
referenced to the instrument's A/D converter is also
included.  This signal reveals any changes in the operation
of the analog portion of the magnetometer.  The pointing of
the sensors may change during the mission because the
sensors are mounted on the end of a very long boom whose
orientation may be temperature sensitive and may be affected
by spacecraft maneuvers.  Corrections for such changes can
be made by using the clearly measurable magnetic signal
produced by a fixed coil (called the MAG Cal Coil) mounted
on the side of the spacecraft at the end of the boom, as we
discuss in a section on instrument calibration.
 
The requirements of reliability and sensitivity motivated
the design of the analog portion of the instrument as
described above.  The design of the digital portion of the
magnetometer was equally challenging.  In many respects the
design problems are similar to those found in building a
high fidelity sound system.  Signal fidelity must be
preserved.  To preserve the signal, two aliasing problems
must be addressed before the signals are transmitted.
First, signals outside the telemetry bandwidth, as given by
the Nyquist frequency (half the sample rate), must not enter
the analog to digital converter.  This is accomplished by
analog filtering before digitization.  Secondly, on a
spinning spacecraft, signals in the ambient medium polarized
clockwise and counterclockwise about the spin axis are
detected at different frequencies. Depending on signal
conditioning in the telemetry process, the amplitude and
phase relationship of these two circular components of a
single ambient signal can be altered.  We minimize this
problem by on-board despinning.
 
The service function of the magnetometer requires that
pertinent data be readily available to other experimenters.
Our solution is to calculate physically meaningful data on-
board the spacecraft and put those data into the telemetry
stream.  As mentioned above, to preserve signal fidelity we
decided to despin our data on-board, so the high time-
resolution despun data required by other spacecraft
instruments are readily available.  We note that in order to
obtain accurate despun data, the instrument operation must
be monitored carefully and calibration constants in the
instrument memory updated as necessary.  We also average the
despun vector data over approximately 30 second intervals
and transmit this information in the subcommutated data.
When these data arrive at Earth, they can be immediately
displayed and used by all experimenters without further
computer processing.  This feature supports rapid analysis
of the data both for mission planning purposes and for
public information purposes.
 
Finally, the scientific requirement for continuous data in
the face of possible intermittent spacecraft tracking led us
to store 200 vectors of averaged data for later
transmission.  The available storage registers also permit
us to use the full bandwidth of the magnetometer to store
limited intervals (7 seconds per hour) of 30 samples per
second data that we call snapshots for later transmission.
The snapshot memory can store 210 vectors.
 
In short, the design requirements for the Galileo mission
were met with the development of a very sophisticated
magnetometer with redundancy, cross-checks, internal
computational power and data storage.  The magnetometer has
its own digital and analog electronics and power supplies,
located in electronics bay number three of the Orbiter.  It
is the two flipper assemblies and their ring core sensors
that are mounted on a boom or 'astromast' which is deployed
from a canister mounted on the science boom.  Below we
describe in more detail these various subassemblies, the
instrument modes, calibration methods, and the on-board data
processing.
 
Sensors
 
The basic sensors are ring core fluxgate sensors similar to
those described by Gordon and Brown (1972).  Each sensor
assembly contains three orthogonally mounted fluxgate
sensors and a flipping mechanism.  The flipper mechanism
rotates two of the sensors so that the non-spinning sensor
parallel to the spacecraft spin axis may be exchanged with
one of those mounted in the spin plane of the spacecraft.
As mentioned above, such an exchange of sensor positions
provides data for determination of the offset of the sensor
parallel to the spacecraft spin axis.
 
The flipping mechanism is similar in design to that
developed at NASA Ames Research center and used on Explorer
35, Pioneer 9, ISEE 1 and 2, and UK-AMPTE.  The mechanism
uses electrically heated bi-metallic springs and a series of
levers to rotate the sensor shaft by 9Oo and back again.
 
The outboard sensor, mounted at the end of a deployable
boom, is located 11.03 meters from the spacecraft spin axis.
The inboard sensor is mounted on the same boom at a distance
of 6.87 meters from the spacecraft spin axis.
 
The outboard sensors have dynamic ranges of +32 nT and +512
nT.  The inboard sensors have dynamic ranges of +512 nT and
+16,384 nT.  The magnetometer to be operated, i.e. inboard
or outboard and the desired dynamic range are selected by
commands from the earth.
 
Electronics
 
The electronic system is constructed of semiconductor
circuits that will withstand the radiation environment of
the Jovian magnetosphere.  The analog circuits are
constructed on double-sided printed circuit boards with
plated-through holes.  The data system is constructed on
planar stitchwire circuit cards.  The electronic circuit
cards are mounted on a standard subchassis shelf which is
mounted in the Galileo electronic bay.  The physical
characteristics of the system are given in Table II.
 
The electronics unit contains an analog circuit board for
each of the six fluxgate sensors.  These circuits provide
sensor excitation currents, amplification, filtering, and
second harmonic detection.  The magnetometer circuits are
somewhat similar to those used for the Pioneer Venus
Magnetometer, reported by Snare and Means (1977).  Changes
were made to adapt the circuits to radiation-tolerant
semiconductors and to reduce power consumption.  The output
of each circuit is an analog voltage that is linear with the
measured magnetic field at the sensor.  The data system
contained in the electronics unit is microprocessor
controlled.
 
The central processor (CPU), read only memory (ROM) and the
random access memories (RAM), form a standard configuration
microprocessor system using the 1802 family of integrated
circuits.  The hardware multiplier is a separate logic
circuit that performs 8 bit multiplications at a high rate
thus enhancing the capability of the microprocessor to
process data rapidly.  The flipper control, analog power
control, and internal calibrate circuits are switches that
are set by the microprocessor in response to ground
commands.  The power regulator and memory 'keep alive'
circuit are power conditioning circuits that receive power
from the spacecraft's alternating current power bus.  The
multiplexer, analog to digital converter (MUX-ADC) collects
analog data under microprocessor control from the
magnetometer circuits and from internal monitors of voltage
and temperatures.
 
Magnetometer Commands and Modes of Instrument Operation
 
Commands can be sent to the spacecraft to control instrument
operation.  Table III lists the commands and the frequency
with which routine commands will be sent.  Interactive
commands are those that affect other subsystems on the
spacecraft whereas non-interactive commands are internal to
the MAG subsystem.  Critical commands are those which select
either the inboard or outboard sensor to make the
measurements and determine whether the high gain (low range)
or low gain (high range) measurements are desired.  These
selections are made by specific command, not selected
automatically, in order to avoid a situation where changes
in instrument mode are made in the middle of an important
measurement.  The selection of optimal averaging or snapshot
mode determines which sort of data will be stored in the
instrument buffer (see the discussion of these modes in the
section on data processing).  The memory load provides an
updated table for the coordinate transformation that
converts measurements into absolute field vectors in a
specified orthogonal coordinate system.  The remaining
commands are related to special procedures that give the
parameters needed to convert measurements into absolute
field values in a known coordinate system.  They are
discussed in the next section.
 
The instrument processes data in two ways.  In normal
operation, the data processor demodulates the data to remove
the effect of spacecraft spin and resolves it into an
orthogonal system before transmitting the averages to the
spacecraft data system.  This process is described in
greater detail below.  Alternatively, direct measurements
from each sensor can be sampled and averaged in even
increments of time for transmission to the spacecraft data
system.  The latter method would require `despinning' of the
data on the ground and would be used only as a backup
procedure or for instrument calibration as discussed below.
 
Determination of Instrument Offsets, Sensor Orientation and
Gain
 
The internal calibrate signals drive prescribed currents
through internal coils around the sensors and are used to
determine instrument gain.  In addition, the measurements
must be corrected for slight misalignment of the sensors
from the nominal orthogonal orientations.  For this purpose,
the data are used without despinning.  A small amplitude
modulation at the spacecraft spin period of the field in the
sensor nominally aligned with the spin axis indicates
misalignment.   The measurements can readily be corrected to
remove the oscillatory signal and obtain the true spin-axis
component of the ambient field.  Sensors precisely in the
spin plane will record fields modulated at the spacecraft
spin frequency.  If offsets have been corrected and stray
spacecraft fields are negligible, such signals average to
zero over integral numbers of spins.  Any non-vanishing
average field in the sensors nominally in the spin plane can
be attributed to the rotation of spin plane sensors out of
the spin plane.  By confirming that this spin average is
proportional to the component of B along the spin-axis, it
is possible to confirm that corrections for offsets and
stray fields from the spinning part of the spacecraft have
been made properly.  The data can then be corrected to yield
the spin plane components of the ambient field.  If the
sensors in the spin plane are perpendicular to one another,
the signals are in quadrature.  Misalignment within the spin
plane results in phase shifts.  They can be readily
identified and the data further corrected.  The procedure
outlined here provides components of the field along three
orthogonal directions, but the absolute orientation of the
axes in the spin plane remains uncertain.  The remaining
uncertainty is removed by measurement of a reference signal
that identifies a direction within the spin plane.  The
signal is produced by a coil rigidly mounted on the
spacecraft.
 
The MAG calcoil (MCC) is mounted at the center of the lower
(+z) edge of the boom with its axis aligned with the center
line of the boom axis.  It is a 20inx18in roughly rectangular
coil of 117 turns.  During MAG Cal Coil calibrations, the
coil is driven at one of several selected frequencies with a
peak-to-peak amplitude of 4.5 nT; (at 0.5 and 0.75 Hz the
signal is a square wave, and at 1.5 Hz it is switched on for
2/3 of each cycle).  Because the frequency is known, the
signal can be identified even if the field is not entirely
quiet.  The flexible choice of frequency allows for the
possibility of noise sources on the spacecraft that may make
it undesirable to operate in certain frequency bands.  All
else being equal, higher frequencies are desirable because
natural background noise falls off with increasing
frequencies.  The MCC signal defines a reference direction
in space, thus providing the required information to allow
the sensor orientations to be well constrained.
 
The above procedure must be carried out for each sensor
triad and for both flip positions of the sensor triad.
 
Fields produced by systems mounted on the despun part of the
spacecraft cannot readily be differentiated from ambient
fields.  A special procedure has been designed to permit
measurements of the magnetic signal of the despun portion of
the spacecraft.  Starting in dual spin mode, the relative
spin rate of the despun portion of the spacecraft is
gradually reduced until the spacecraft is in all-spin mode
and the procedure is reversed until the spacecraft is once
again in the dual spin mode.  The procedure takes
approximately four hours.  The procedure is initiated by the
constant slew command and will be carried out once per orbit
at Jupiter.
 
Finally, offsets in the instrument itself can be identified
by measurements made in the known field of the Earth's
magnetosphere.  This will be possible during the initial
post-launch period and during the two subsequent flybys of
Earth.  Standard methods of identifying offsets through
statistical analysis of tangential discontinuities in the
solar wind will also be used.
 
On-board Data Processing
 
The system uses a 12 bit analog-to-digital converter that
has been trimmed such that each bit is accurate to at least
1/4 of the value of the least significant bit.  The data,
sampled at 30 samples/s, are averaged to provide l6-bit
words; tests have demonstrated that these words are accurate
to the l5th bit.  This filtering is performed by the
microprocessor system using a recursive filter.  The
recursive filter algorithm is of the form,
 
 
            Oi = Oi-1 - K Oi-1 + K Ii                    (1)
 
 
where Oi, is the value calculated at measurement i and Ii.
is the value read in at measurement i.  The value of K is
set at 1/4 for the filter.  This filter gives a transfer
function of the form,
 
 
                             pOc
            T(f) =      ---------------------            (2)
                      (1 + pOc) - exp(-ipf/fn)
 
 
The relationship of K in equation 1 to Oc of equation 2 is
given by the  expression,
 
                            pOc
                    K =    ---------                     (3)
                         1 + pOc
 
where Oc = fc/fn, and fn = Nyquist frequency = DT/2, fc =
the filter corner frequency and DT is the data sampling
interval, (1/30)s.  Next the data are corrected by
subtracting the sensor offsets from the data and multiplying
the data by a coordinate transformation matrix.  This matrix
contains sensor gain and pointing information.  The
correction routine yields accurate data at 3 vectors each
2/3 second in true spacecraft coordinates. The information
for the corrections, i.e. offsets and matrix values, is
computed on the ground and sent via the command system as a
direct memory load to the microprocessor memory.
 
To obtain magnetic field data in inertial (I) coordinates,
the data are despun by multiplying the spinning spacecraft
(sc) Bx and By by sine and cosine functions generated from
spacecraft roll information.
 
          BxI = Bxsc cos q - Bysc sin q                 (4)
 
          ByI = Bxsc sin q + Bysc cos q                 (5)
 
          BzI = Bzsc                                    (6)
 
The angle q, the spacecraft roll angle, is measured from the
projection onto the spacecraft spin plane of a southward
pointing vector normal to the ecliptic plane.  Therefore, in
inertial coordinates positive BxI points south, normal to
the ecliptic plane, positive ByI lies in the ecliptic plane
in the sense of Jupiter's orbital motion and positive BzI is
in the anti-earth direction.  The spacecraft coordinates are
defined with the spin axis +z pointing in the anti-earth
direction, the magnetometer boom is the +y axis and the +x
axis completes the right hand triad as shown in Fig. 2.
 
The main data output, i.e. 3 vectors, each 2/3 second, may
be commanded to be either in spacecraft coordinates or to be
despun data in inertial coordinates.
 
The despun data are again filtered, and 2 vectors each
minute are provided in the subcommutated data.  These
subcommutated despun data are provided continuously, even
when the main instrument output data are provided in
spacecraft coordinates.
 
For periods of up to a week during the cruise mode on the
journey to Jupiter, the data system may not be collecting
data from the science instruments.  During this time, the
magnetometer will be left on.  The despun data will be
averaged over times longer than the basic 30 second
intervals and stored in memory.  The averaging constant, K
in equation 1, can be set by a command such that the memory
will contain time and attitude information in addition to
200 evenly spaced data points for the period between
telemetry readouts.  This mode of operation is referred to
as the optimal averaging mode.
 
The instrument memory can alternatively be used for
recording high speed data at 30 samples per second.  This
mode, called the snapshot, will be used for trying to
capture transient events such as shocks or to increase the
Nyquist frequency of the magnetometer measurements in order
to provide a continuous spectrum of plasma waves from DC to
frequencies that overlap the lowest PWS frequency band.  The
snapshot data come from the output of the digital averager
at 30 samples per second.  By inverting the operation of
equation 1, the original unfiltered input data can be
retrieved.  For the snapshot mode, the time interval
separating digitized values of x, y and z data is greater
than or equal to 200 microseconds and the time lapse between
successive samples of any axis is 33.3 milliseconds.  The
buffer memory which contains 210 48-bit vectors and a time
record is continuously read out at 16 words per minute.
This memory readout appears in the subcommutated data.
 
Data Format
 
The data format contains three vector sets of x, y, z
samples and a subcommutator word.  Each word is 16 bits in
length and the readout provides 160 bits each 2/3 of a
second for a total readout of 240 bps.  The time interval
between the first and second, and second and third vectors
is 233 milliseconds.  The time interval between the third
vector and the first vector of the next minor frame is 200
milliseconds.  Because of odd timing intervals, this slight
asymmetry of sampling could not be avoided.  However, a
method of correcting for the non-uniform sampling of the
data has been devised to remove the undesirable features of
non-uniform sampling when necessary for refined analysis.
The approach is to break the non-equispaced time series of n
elements into three equispaced time series of lower time
resolution (666 milliseconds).  The elements of the three
series are composed of elements 3i-2, 3i-1, or 3i,
respectively, where i=1,2,...,n/3.  Each series is Fourier
transformed.  The concept of frequency folding is used to
relate these Fourier transforms to the transform of an
equispaced time series of 222 milliseconds resolution.  The
procedure requires the inversion of a set of 6x6 equations.
Inverse Fourier transformation then produces the desired
equispaced time series.
 
The subcommutated data consist of 91 words, corresponding to
a data rate of (60 2/3s)-1.  The subcommutator contains 2
readouts of despun averaged data, 16 words of stored buffer
data; the remainder is housekeeping information to determine
the status of the instrument.  Included in the housekeeping
data are various power supply voltages, a readout of all
commands, matrix values and all memory-stored constants that
are transferred to the instrument from the command system,
and memory checksums.
 
Performance
 
The magnetometer sensors and sensor electronics have been
selected to achieve the lowest noise possible.  However, as
is true with many magnetometers, the limiting factors in
instrument noise are the digitization noise of the analog-to-
digital converter and electronic noise. The technique of
averaging 12 bit data to obtain 16 bit words was used on
magnetometers for ISEE 1 and 2 and successfully reduced
digitization noise as described further by Russell (1978).
 
Table IV shows the resolution for each dynamic range of the
magnetometer.  The third column displays the calculated
digitization noise for the 16 bit average.  The measured
noise is essentially the same as the calculated digitization
noise for the +512 and the +32 nT range.  For the larger
dynamic range of +16,384 nT, the electronic noise of the
system raises the measured noise above the digitization
noise by approximately one half decade.  In this range, one
nT corresponds to 300 mV which is well below the electronic
noise of the circuits.
 
Acknowledgements
 
At UCLA we are grateful to F.R. George and D. Dearborn who
did the preliminary circuit design and final calibrations,
and K. K. Khurana and R. J. Walker who provided expert
advice on many instrument-related issues.  Excellent low
noise sensors were supplied by R. Lundsten of Naval Surface
Weapons Center, White Oak.  The final design, packaging and
fabrication was skillfully directed by D. Frankel and R.
Mack of Westinghouse.  We benefited much from the advice of
M. Larson of the Office of Naval Research and Ulrika
Williamson, Douglas Clay, Maria Etchetgaray, Ralph Parish,
and Howard Eyerly of JPL.
 
____________________________________________________________
     TABLE I.  Magnetometer Team
____________________________________________________________
 
Principal Investigator              Margaret G. Kivelson
 
Co-Investigators                    Paul J. Coleman
                                    Krishan K. Khurana
                                    Charles F. Kennel
                                    Robert L. Mc Pherron
                                    Christopher T. Russell
                                    David J. Southwood
                                    Raymond J. Walker
 
Project Engineers                   Robert C. Snare
                                    Joseph D. Means
 
Project Computer Specialists        Neal Cline
                                    Steven Joy
                                    Todd King
 
Project Science Support             Krishan K. Khurana
 
____________________________________________________________
     TABLE II. Instrument characteristics.
____________________________________________________________
 
Sensors
 
     Mass                     0.72 kg
     Dimensions                8.1 cm (diameter),
                              16.0 cm (length)
     Power                    4.35 W for 4 minutes to
                                     activate flip
 
Electronics
 
     Mass                     3.98 kg
     Volume                   14.6 x 17.8 x 4l.8 (cm)3
     Power                         3.9 W
 
Dynamic Range
 
     Inboard magnetometer     +512 nT and +16,384 nT
     Outboard magnetometer    +32 nT and +512 nT
 
____________________________________________________________
               TABLE III. Instrument Commands
____________________________________________________________
 
 
      INSTRUMENT MODE          TIME or FREQUENCY
 
Interactive Commands
      Instrument power on/off  On prior to boom deployment
 
      Flipper power on/off     start/end flipper checks
 
      Flip right, Flip left    for flipper checks
      Flip (a toggle           (affects power consumption
                                when activated)
 
Non-Interactive Commands
 
      Inboard power on/off     few/orbit
      Outboard power on/off
 
      Inboard/Outboard         few/orbit
      sensor select
 
      Hi range/low range       few/orbit
      select
 
      Despin select (on/off)   on change of sensor,
                               flip position,
                               gain, averaging
                               interval
 
      Optimal averaging        when no real time or
      (on/off)                 taped low rate data
 
      Snapshot mode            off/on command
      (on/off)                 every ~40 minutes
 
      Memory load              as needed to update
                               the coordinate
                               transform matrix/
                               averaging interval
 
      Internal calibration     weekly during cruise
      coil signal (on/off)     twice per orbit at
                               Jupiter
 
 
Interactive (Calibration) Commands using Programmed Sequences
 
      Offset checks            weekly
      Flipping sensors
 
      Constant slew            once/orbit
 
      MAG Cal Coil (on/off)    following major
                               engine burns and
                               twice per orbit at
                               Jupiter
 
____________________________________________________________
           TABLE IV. Instrument Noise Performance
____________________________________________________________
| Range  |   Measured    | Digitization|     Measured      |
| (nT)   |Resolution (nT)|   Noise     |  Noise (nT^2/Hz)  |
|        | 12bit | 16bit |  (nT^2/Hz)  |  1Hz   | 0.01 Hz  |
|________|_______|_______|_____________|________|__________|
|        |       |       |             |        |          |
|+16384  |   8   |  1/2  |  1.9x10-2   | 1x10-1 | < 1x10-1 |
|        |       |       |             |        |          |
|  +512  | 1/4   | 1/64  |  5.8x10-4   | 1x10-3 | < 4x10-2 |
|        |       |       |             |        |          |
|   +32  | 1/64  | 1/1024|  3.6x10-5   | 5x10-5 | < 2x10-2 |
___________________________________________________________
 
 
REFERENCES
 
      Gordon, D.I., and Brown, R.E.: 1972, IEEE Transactions
      on Magnetics, MAG-8, 76-82.
 
      Kivelson, M. G., Slavin, J. A., and Southwood, D. J.:
      1979,  Science, 205, 491.
 
      Russell, C.T.: 1978, IEEE Transactions on Geoscience
      Electronics, GE-l6(3).
 
      Snare, R.C., and Means, J.D.: 1977, IEEE Transactions
      on Magnetics, MAG-l3(5).
 
APPENDIX 1 - Phase 2 changes to the MAG instrument
 
   The main difference between the phase 1 and phase 2 missions
is the creation of the Real-Time Science (RTS) data type. Real
time data are low time resolution data acquired primarily by the
fields and particles instruments during the orbital cruise
associated with the magnetospheric survey. The magnetometer required
no special reprogramming to allow for the creation of variable rate
RTS data. The optimal averager section of the instrument already
provided this capability. When the optimal averager is turned 'off',
it continuously averages the data in place at MAG memory address
4800 (HEX). The spacecraft Command and Data System (CDS) was
simply programmed to support MAG RTS data acquisition by collecting
data from that address. The CDS was modified to pickup MAG data
vectors (6 bytes) at a data rate that automatically varied
with telemetry format. When a new telemetry format was commanded,
CDS would complete the current average cycle, close out the
current MAG RTS data packet, and then set the optimal averager filter
constant and CDS pickup rate to the appropriate values for the new
telemetry rate. Short packets created by rate changes always contain
an explicit time tag, otherwise time tags are sent once every 5
packets, each full packet containing 20 vectors.
 
The magnetometer was allocated an RTS base configuration of 2 bits
per second (bps) and higher data rates when the telemetry could
support them. RTS data and the use of the optimal averager function
of the instrument can not be used simultaneously. Both modes of
operation use the same code, however RTS data is always created at
address 4800 while the optimal averager steps up into higher address
space after each average is complete. Table 5 lists the telemetry
formats with MAG data rates and other sampling parameters.
 
____________________________________________________________
Table 5         MAG RTS Telemetry Rates
____________________________________________________________
 
format    bps mf/samp  sec/samp  filter con    corner freq (Hz)
____________________________________________________________
A,B,C,D    2     36       24     1000 (HEX)         1/34
E          4     18       12     1000               1/34
F          6     12        9     2000               1/17
G          8      9        6     2000               1/17
H         10      6        4     2000               1/17
I         12      4        2.67  2000               1/17
 
The MAG instrument was reprogrammed for phase 2 to allow the rapid
return of snapshot data. Snapshot data would normally have been
returned in the LRS (Low Rate Science) data stream approximately once
every 45 minutes.  In order to look for high frequency magnetic
fluctuations, many snapshots needed to be acquired during the
relatively short (typically 45 min) LPW (LRS plus PWS in the golay
bits) recordings. In order to make room in the recorded data format for
the rapid return of snapshot data, one magnetic vector per minor frame
was sacrificed. The data that is stored in the MAG internal memory
buffer, is moved into the CDS pickup location of that 3rd vector each
minor frame. The remaining 2 vectors per minor frame that are acquired
are evenly sampled every 1/3 second in phase 2 operations. This
programming change allows either snapshot or optimal averager data to
be returned quickly with only a slight reduction in LPW data rate.
 
 
The magnetometer has only 2 kb of program data space. In order to be
able to add new code to support this 'accelerated snapshot mode', some
existing code had to be sacrificed. The high speed onboard despinning
algorithm was deleted to make the required space. The onboard
despinning mode was tested but never used operationally during the
phase 1 mission.
 
In the phase 2 mission, the snapshot ON command has a new meaning.
The new command takes a snapshot immediately, and then takes one
snapshot every modulo 3 of the spacecraft clock frame counter (RIM)
until an 'off' command is received. Since the snapshot writes
to the entire data buffer, including address 4800, the use of the
snapshot badly corrupts the RTS data. The accelerated snapshot mode
can not used when RTS data are considered to be critical.
 
 
APPENDIX 2 - MAG Commands
 
 
Downlink bits are an extremely precious commodity in the phase 2
mission. With this fact in mind, most science instrument teams
elected to use their reduced downlink for data return sacrificing
a lot of engineering and instrument housekeeping data. In order to
be able to properly interpret much of the raw data, the sequence of
commands, and the timing of those commands becomes critical
information. The following is a brief listing of the actual MAG
commands as they appear in the uplink sequences, plus a few CDS
commands that impact MAG data return and/or timing. MAG is instrument
number 35, the CDS is number 6, and the spacecraft power system is 40.
 
 
35A,   35AR   (MAG power on, off respectively)
35KA,  35KAR  (MAG memory keep alive power on, off respectively)
35DML         (Mag direct memory load)
35IS,  35ISR  (MAG inboard sensor on, off respectively)
35US,  35USR  (MAG outboard sensor on, off respectively)
35ISL, 35ISH  (MAG inboard sensor range low, high respectively)
35USL, 35USH  (MAG outboard sensor range low, high respectively)
35AV,  35AVR  (MAG optimal averager on, off respectively)
35SS,  35SSR  (MAG snapshot on, off respectively)
35F,   35FR   (MAG flipper power on, off respectively)
35IFL, 35IFR  (MAG inboard sensor flip left, right respectively)
35UFL, 35UFR  (MAG outboard sensor flip left, right respectively)
35IC,  35ICR  (MAG internal calibration coil on, off respectively)
 
40CP,  40CPR  (MAG external calibration coil on, off respectively)
 
6TMSED        (telemetry format, sets RTS rate for MAG when selected**)
6TMREC        (record mode format change)
6RCSET,6RCCLR (record rate change coverage on, off respectively)
6RCSEL,6RCDSL (record select, deselect respectively)
6RTSL, 6RTDS  (RTS select and deselect respectively)
 
 
** see appendix 1, table 5
 
The 35DML command is generally directed to high memory (4E80 HEX) where
it is processed by the instrument on the next major frame boundary. The
contents are surrounded by the flag value A5A5. The values between the
flags are 2 bytes (HEX) each and are in the order scale, avg const, avg
rate, gain 1-3, offset 1-3, matrix (1,1), (1,2),... (3,3). A typical
35DML command looks something like:
 
 
03483012:28:0 96-169/00:29:30.200
              CMD,35DML,272MA4D,,96-169/00:29:30.200,
 
4E80,A5,A5,04,00,01,00,00,03,3D,F2,3E,C0,3E,31,F4,39,09,5A,
              D0,D8,FF,FA,F8,F8,7F,FE,7F,FC,FC,E8,FF,EB,00,74,7F,FD,04,
              DD,A5,A5; << DIRECT MEMORY LOAD >>;
 
where
   sclk    = 03483012:28:0       (parameters would update at
                                  03483013:00:0)
   scet    = 96-169/00:29:30.200
   scale   = 0400
   gains   = 3DF2, 3EC0, 3E31 (sensor 1, 2, 3)
   offsets = F439, 095A, D0D8 (sensor 1, 2, 3)
   matrix  = FFFA  F8F8  7FFE
             7FFC  FCE8  FFEB
             0074  7FFD  04DD
 
 
 
 
Any 35DML command to addresses less than 4800 are acted upon
immediately. These commands are not 'protected' by the A5A5 flag pair.
Gains, offsets, and the matrix are stored contiguously in memory
beginning at address 4714. Offset updates are commonly implemented this
way directly to address 471A. The optimal averager filter (updated by
CDS during RTS data acquisition) constant is located at memory address
4766 and the decimate factor at 4768. The MAG executor code resides in
address between 4000 and 46FF. 35DML commands to this address space are
flight software loads or patches.
 
 
APPENDIX 3 - In-flight Anomalies, Commanding Errors, and other
             problems that impacted data acquisition and continuity.
 
1989
 
   Oct 21 Instrument saturated. Large CME event occurred
      just after launch while the instrument was configured in
      the 32 nT mode. This event raised the IMF field strength
      above the measurable level. Solar wind data inside 2 AU
      collected in the 512 nT mode as a result of this data loss.
      Data saturation lasted only a few hours but this event
      impacted the way the instrument was used for the next
      several years.
 
1990
 
   Jan 24 Spacecraft safing event, MAG powered off for
      seventeen days while s/c engineers analyzed the error.
      Star scanner anomaly, bad star map determined to be culprit.
 
   June Instrument programming error detected, stack
      overflow. Optimal averager data for May/June/July wholly
      or partially corrupted. Instrument power cycled to reset
      stacks. Patch created and sent to the MAG instrument after
      the Earth 1 flyby in Jan 1991.
 
1991
 
   HGA failed to deploy. MAG powered off several times for
      'cold turns' as the s/c engineers tried to 'walk the stuck
      pins' out.
 
   Debris in the spin bearing assembly (SBA) caused shorts in
      the s/c that led to 3 s/c safing events. Each of these events
      resulted in the loss of at least 1 MRO and typically 4-10 days
      of data.
 
1993
 
   Bus resets (4 during June/July) caused the s/c to safe and
      MAG data to be lost. In August, 17 days before the Ida
      encounter, there was another s/c safing attributed to debris
      wear in the SBA.
 
1994
 
   DMS memory cell error during return of the Ida images. Data
       lost while anomaly analyzed by s/c engineers.
 
1995
 
   Probe checkout and release sequence. MAG not allowed to
       acquire data during this period in July
 
   DMS anomaly (tape sticking to heads). Several MAG MRO's lost
       when the Jupiter approach sequence was cancelled in Oct.
       High resolution data near Io and outbound after JOI reduced.
       Anomaly resolution includes limiting tape motion across
       heads to only the central portion of the tape. Usable tape
       reduced by about 25%. New flight rules were established that
       change how data can be put on and read off the tape which
       reduce reading/writing efficiency but reduce chance of complete
       system failure.
 
1996
 
   Data not acquired until early March while probe data
       returned.
 
   In flight load of phase 2 software in May resulted in the loss
       of several weeks of optimal averager data.
 
   RTS data was shutdown after initial checkout in June so that
       downlink could be used to return Io data.
 
   June Phase 2 MAG programming error detected, data acquired with
       uneven time sampling. No data lost, flight software patched
       after G2 encounter.
 
   July MAG commanding error loaded DML for incorrect flip state,
       several days of optimal averager data lost.
 
   July MAG flip anomaly, instrument too cold, did not flip in
       8 RIMs. All flips after this event kept the flipper
       power on for a minimum of 12 RIMs by reissuing the 'on'
       command to reset countdown timer. Several weeks of data lost.
 
   August  s/c safing do to too many DAC commands in buffer. CDS
       unable to keep up and timing lock lost.
 
   Nov/Dec Galileo approaching Jupiter near superior conjunction,
       telemetry lockup problems cause gaps in some of the inbound
       to Jupiter MRO data.
 
 1997
 
   Jan 25, MAG single event upset near perijove in the J5
       orbit. Instrument stopped acquiring data until error
       detected and corrected. MAG memory patched and instrument
       restarted on Feb 28. Europa 6 encounter lost.
 
   April MAG offset anomaly. The magnetometer suddenly changed zero
       levels by 1-3 nT in all 3 sensors. Reason for this jump is
       still unknown. Ground data processing removes the effects of
       this problem.
 
   April MAG flip anomaly. The inboard magnetometer apparently
       changed flip states (left to right) without being commanded
       to do so. As part of the phase 2 mission, redundant flip
       commands were dropped so several days of data were lost
       when the instrument was commanded to the inboard sensor.
       This anomaly appears unrelated to the flip anomaly in G1.
       A temperature increase at the inboard sensor was observed
       when the outboard sensor was commanded to flip right a week
       or so earlier. It is believed that somehow, both the inboard
       and outboard sensors flipped at this time. Impact: MAG stopped
       using its flippers after this anomaly. MAG flipped one more
       time during C10 to configure the instrument for GEM. The
       inboard, flip right mode used from G7-C10 is not as well
       calibrated as the flip left mode.
 
    Dec MAG instrument saturated near Europa C/A. Data were recoverable
       during ground processing.

        