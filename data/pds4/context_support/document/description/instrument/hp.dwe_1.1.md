
 
Instrument Overview
===================
 
See [BIRDETAL1997].
 
The Doppler Wind Experiment (DWE) is a high-precision tracking investigation
to determine wind direction and magnitudes in Titan's atmosphere. The prime
science objective, a height profile of the wind velocity, will be derived from
the Doppler shift of the Probe Relay Link (PRL) signal from the Huygens Probe
to the Cassini Orbiter.
------Update 06/04/01, RDR---------
Due to a flaw in the sequence to be executed by Cassini during
the Huygens mission, the Doppler shift could not be measured aboard Cassini.
It was, however, also measured on Earth [BIRDETAL2005].
The prime science objective was achieved using those data.
-------end of Update-------------
After correcting for all known Doppler shifts due to
orbit and propagation effects, the wind-induced motion of the Probe will be
determined to an accuracy of better than 1 m/s, from parachute deployment at
an altitude of ~ 160 km down to surface impact.
In addition to the measurements of drift motions due to winds, DWE is capable
of achieving two secondary scientific objectives:
  (a) measurement of Doppler fluctuations to determine the level and spectral
      index of turbulence and possible wave activity in Titan's atmosphere
  (b) measurement of Doppler and signal level modulation to monitor Probe
      descent dynamics, including its rotation rate and phase, parachute swing
      and post-impact status.
By achieving the first of these objectives, DWE will contribute, along with
Probe accelerometry and radio occultation measurements, to the assessment of
atmospheric turbulence associated with vertical wave propagation, the
buoyantly-driven surface layer or possible methane moist convection.
The second objective represents a potential DWE 'service' to other Probe
instruments to assist in the interpretation of their data. The known
Probe-Orbiter geometry enables a determination of directions on Titan from the
phase of the Doppler/amplitude modulation. The Probe's passively-controlled
spin rate will also be determined to a high degree of accuracy from the same
data. These precise measurements of velocity will be integrated to reconstruct
the descent flight path, thereby providing the most accurate determination of
the Probe's impact coordinates.
The most severe constraints on the accuracy of the DWE wind measurement are
trajectory errors and instability of the Probe oscillator used to generate the
PRL signal. Present assessments of these limitations indicate that a zonal
wind height profile u(z) can be recovered with a mean error delta u of less
than +-1 m/s. This can be achieved only with a sufficiently stable PRL signal
over the duration of the descent (delta f <~ 0.4 Hz at S-band) in order to
exclude contamination of the measurement by oscillator drift. The
transmitter's frequency stability is guaranteed by using an ultrastable
oscillator (USO) to generate the PRL carrier signal. In addition to this
transmitter USO (TUSO), it is necessary to incorporate an additional unit in
the receiver (RUSO) of the Probe Support Avionics (PSA) on the Cassini
Orbiter, where the frequency measurement is recorded.
 
 
Scientific Objectives
=====================
 
Expectations based on Voyager results
-------------------------------------
Almost all presently available information about Titan's atmospheric dynamics
and meteorology derives from Voyager 1's reconnaissance, with essential
contributions from the infrared interferometry spectrometer (IRIS) and radio
occultation (RSS) investigations [HANELETAL1981; TYLERETAL1981B].
Titan's vertical temperature-pressure structure, retrieved from Voyager RSS
data [LINDALETAL1983], is represented by the profile shown in Fig. 1. The
occultation data extend all the way to the surface, where the temperature is
approximately 97K (with a systematic uncertainty of about +-7K). Methane
clouds may form above a few kilometres, depending on the relative humidity
near the surface [TOONETAL1988]. The decrease of temperature with
altitude below 40 km implies the absorption of sunlight at the surface and a
weak tropospheric greenhouse. The radio occultation measurements indicate a
nearly adiabatic lapse rate below 3-4 km, consistent with the inferred
turbulent surface layer, but a statically stable profile above this height.
[HINSON&TYLER1983] have found evidence for vertically propagating gravity
waves at altitudes of 25-90 km, based on their analysis of radio occultation
scintillations.
The indirect inference of 100 m/s zonal cyclostrophic winds on Titan is based
primarily upon the latitudinal contrast of temperature at infrared sounding
levels observed by Voyager's IRIS [FLASARETAL1981; FLASAR&CONRATH1990].
As interpreted by the thermal wind equation under the assumption of
hydrostatic gradient-balanced flow, the vertical variation of the Coriolis
plus centripetal acceleration of the zonal velocity u is related to the
latitudinal temperature gradient dT/dlambda by
 
 d/dz^ [u^2 tan lambda + 2 u Omega a sin lambda] = -R d/dlambda [T / mu]  (1)
 
where z^ = ln(P0/P) is the vertical log-pressure coordinate with P0 the
surface pressure, lambda the latitude, a the planetary radius, Omega the
planetary rotation velocity, mu the mean molecular weight (mass per mole) of
the atmospheric gas, and R the gas constant. With the further plausible
assumption of relatively weak winds near the surface [ALLISON1992], the
thermal wind equation may be solved for the zonal velocity at all levels for
which there are vertically continuous observations of the horizontal
temperature gradient. The second term in the thermal wind equation (1) can be
neglected, except very close to the surface, because of the slow Titan angular
rotation. The resulting circulation is in cyclostrophic balance with
Omega a / u << 1. However, the direction of the zonal wind (prograde or
retrograde) cannot be uniquely determined from (1) under this condition.
The vertical integration of the thermal wind equation for the practical
inference of zonal motions requires the independent specification of the
velocity at one or more levels where the thermal gradient can be accurately
estimated. For sufficiently strong surface drag, the zonal velocity at the
bottom of the atmosphere may be assumed to be nearly zero. On this basis,
[FLASARETAL1981] estimated a zonal wind approaching
100 m/s in the upper stratosphere at a latitude of lambda = 45 deg.
Although Titan's thermal spectrum is partly convolved with variable aerosol
opacity, the 1304 cm^-1 region, which comes mainly from the 0.5 mbar pressure
level (~ 230 km), is presumed to be relatively free of these effects. Measured
brightness variations across the disc in this channel could thus be
interpreted as a real difference in kinetic temperature between low and high
latitudes of roughly 16K [FLASARETAL1981]. More recently, [FLASAR&CONRATH1990]
retrieved stratospheric temperatures from a combination of the
measured radiances at 1304 cm^-1  and the P and Q branches of methane at
1260-1292 cm^-1, essentially confirming the results of the earlier brightness
temperature analysis. The data also indicated a hemispheric asymmetry in
Titan's latitudinal temperature distribution at the time of the Voyager
encounters. [COUSTENIS1991] has performed an independent retrieval of the
latitudinal temperature structure as inferred from the 1304 cm^-1 channel,
with similar results. IRIS measurements for a second thermal sounding channel
at 200 cm^-1, corresponding to emission in the vicinity of 100 mbar (~40 km),
suggest that latitudinal thermal contrasts at this level may be less than
about 1K. Measurements for a third thermal channel at 530 cm^-1, corresponding
to emission near Titan's surface, were interpreted by [FLASARETAL1981] as
a latitudinal temperature difference of about 2K between the equator and 60
deg latitude. This interpretation has since been qualified, however, by the
study of [TOONETAL1988], who pointed out that stratospheric aerosols may
also contribute significantly to the brightness temperature at this
wavenumber. The apparent latitudinal contrast may thus be best interpreted as
a crude upper limit to actual variations in the kinetic temperature. A more
comprehensive review of the evidence supporting our contemporary model of
Titan's zonal winds has been compiled by [FLASARETAL1997].
As with Venus, the inferred cyclostrophic flow regime on Titan is not yet
understood, representing a fundamental unresolved problem in the theory of
atmospheric dynamics. The magnitudes of the meridional and vertical winds are
also quite speculative. Assuming the poleward advection of heat is balanced by
radiative cooling, [FLASARETAL1981] estimated a mean meridional motion of
v<=0.04 cm/s in the lower troposphere. Invoking continuity, the associated
mean vertical motion may be estimated as omega ~ vH/a <= 10^-3 cm/s, where
H ~ 20 km is the pressure scale height. It is possible that much stronger
vertical motions exist in locally turbulent regions of the atmosphere, such as
a methane thunderhead, but probably only over a relatively small fraction of
the total area. The associated depth of the Ekman planetary boundary layer
(PBL), where the surface winds are rotated and strongly sheared with
altitude until they match the thermal wind aloft, may be estimated as D_E ~
0.7 km [ALLISON1992]. Because the PBL mediates the transfer of angular
momentum from the surface to the atmosphere, it is an important target for
observational characterisation. With strong surface drag and a global
meridional thermal contrast no larger than assumed by [FLASARETAL1981],
the vertically integrated thermal wind equation implies a geostrophic regime
(Omega a/u >> 1) extending up to about 5 km altitude.
In view of the various gaps and uncertainties in the thermal structure data,
we cannot claim to know very much about the vertical and horizontal structure
of Titan's zonal wind. Assuming that at least the 1304 cm^-1 measurements from
Voyager's IRIS have been more or less correctly interpreted, however, it is
difficult to escape the conclusion that the thermal wind balance will involve
zonal motions of the order of (R DeltaT/mu)^0.5 ~ 70 m/s at stratospheric
levels. The direct observational confirmation of the inferred zonal
cyclostrophic motion of Titan's atmosphere by DWE will represent a fundamental
contribution to the study of planetary meteorology. If its conjectured analogy
to Venus is established, it would imply the probable ubiquity of atmospheric
superrotation as a robust feature of slowly rotating, differentially heated
planets.
 
Atmospheric model simulations
-----------------------------
Only recently has a general circulation model (GCM), originally developed for
the simulation of the terrestrial weather and climate, begun to be adapted
successfully to the study of atmospheric superrotation on Titan.
[DELGENIOETAL1993] have shown that the addition of an optically thick,
statically stable upper cloud layer to a terrestrial GCM, also modified with
a 16-day planetary rotation period, results in the generation of an
equilibrated zonal-mean flow of several tens of metres per second. Their
diagnosis of the responsible flux transports indicate that this regime is
supported by the horizontal mixing of quasi-barotropic eddies. Similar
results have also been obtained with a Titan GCM under development by
[HOURDINETAL1995]. Despite their preliminary state of development, these GCM
experiments lend some confidence to the indirect inference of superrotational
winds from the observations.
[ALLISONETAL1994] have argued that the GCM experiments as well as the
limited planetary observations are suggestive of the dynamical maintenance of
these circulations by efficient 'potential vorticity' mixing. In the implied
'ZPV' (zero potential vorticity) limit for stable zonal flow, the latitudinal
wind profile will be bounded by a maximum envelope of the form
 
 U_max = (U_e + Omega a) (cos lambda)^[(2/R_i)-1] - Omega a cos lambda   (2)
 
where R_i is the local Richardson number (the squared ratio of the
Brunt-Vaisala frequency to the vertical wind shear), and U_e is the zonal
velocity at the equator. Except where R_i is less than 2, this envelope
implies an increase in the maximum possible velocity with latitude, and can
therefore be expected to approximate the actual winds only between the equator
and the latitudes of the 'jet' maxima. The Titan zonal wind profile presented
by [HUBBARDETAL1993] is consistent with this prescribed envelope within 60
deg latitude, assuming a large value for the Richardson number, as appropriate
for the statically stable stratosphere. The combination of the vertical wind
shear measured by the Doppler Wind Experiment and the static stability
inferred from the Huygens Atmospheric Structure Instrument (HASI) will provide
an in situ determination for the vertical profile of R_i, which could then be
interpreted with the ZPV constraint for comparison with independent remote
sensing observations from the Cassini Orbiter.
 
Recent and future ground-based observations
-------------------------------------------
Some independent evidence for winds on Titan, based on ground-based stellar
occultation measurements, has been presented by [HUBBARDETAL1993]. Their
analysis of the indicated latitudinal deformation of isopycnic surfaces in the
stratosphere implies a zonal wind at the 0.25 mbar level varying from some 80
m/s near the equator to >170 m/s at 60 deg latitude. Another promising new
method for determining stratospheric wind motions is the IR heterodyne
observation of Titan's ethane emission at 841 cm^-1, which originates
primarily from the 1 mbar level.
Initial measurements of the differential Doppler shift between east and west
limb spectra indicate that the winds are prograde and have speeds of the order
of 80 m/s.
Fifty near-IR Titan images were obtained with the Hubble Space Telescope's
refurbished planetary camera (WF/PC2) during 4-18 October 1994 [SMITHETAL1994;
SMITHETAL1996]. A variety of continuum and methane filters were
employed with the goal of obtaining cloud-tracked drift speeds associated with
the differential motion of longitudinal structure of the type previously
observed at 970 nm by [SMITHETAL1992]. A global surface map compiled from
14 processed images covering nearly the full Titan rotation period reveals a
large bright feature in the leading hemisphere centred just south of the
equator. Although some structure in the unaveraged images is suggestive of
cloud features, attempts to derive cloud-tracked vectors have thus far proved
unsuccessful. Further observations, obtained during Saturn's opposition of
September/October 1995, are being evaluated [CALDWELLETAL1996].
The DWE will complement remote sensing observations of temperatures and winds
from the Cassini Orbiter. It will provide ground-truth corroboration of the
thermal wind retrievals from Composite Infrared Spectrometer (CIRS)
measurements, also providing a check on their assumed aerosol and cloud
opacities. The high vertical resolution of the DWE retrieval of vertical shear
near impact will provide an important characterisation of the surface boundary
layer unobtainable by thermal sounding. If the probe encounters sufficiently
vigorous turbulence or vertical wave propagation, variations of the Doppler
signal will provide information on the associated eddy momentum mixing and/or
planetary waves.
 
DWE Concept and Mission Planning
================================
 
Titan targeting
---------------
The geometrical configuration and sequence of events during descent are of
vital importance to DWE's execution. The present mission baseline
[LEBRETON&MATSON1997] plans Probe release on the Orbiter's first inbound
pass after Saturn Orbit Insertion (SOI). The nominal date for Probe descent
is 27 November 2004, some 150 days after SOI and >7 years after launch.
Titan, which orbits Saturn at a constant distance of 20.4 Saturn radii, is
very close to Saturn's noon meridian on this date.
Probe separation from the Orbiter occurs ~ 22 days before Titan encounter, at
which point the Probe is targeted for entry into Titan's atmosphere. The final
Orbiter Deflection Manoeuvre is performed 2 days after Probe separation,
targeting the Orbiter so that it will fly very nearly over the Probe but at a
safe 1500 km above Titan's surface. The Orbiter's closest approach is delayed
to about 4 h after the Probe's atmospheric entry. This Orbiter Delay Time
(ODT) is short enough to provide adequate margin of the PRL at the beginning
of descent (maximum range) and yet long enough to avoid Orbiter High Gain
Antenna (HGA) pointing problems toward the end of Huygens' mission (minimum
range).
The Probe's target is characterised by parameters in Titan's B-plane, defined
by the asymptotic Probe approach velocity. Aim points in
the B-plane are defined by the magnitude of the impact parameter vector B and
its associated azimuthal angle with respect to the T-axis. Equivalently, the
atmospheric entry angle gamma at a given altitude could be used instead of the
impact parameter B. This alternative was adopted for Huygens mission planning
purposes.
It is planned to target the Probe at an entry
angle gamma = 64 deg, and B-plane azimuth angle theta = -60 deg. The Probe
delivery accuracy (3 sigma) in the B-plane is given by the ellipse encircling
the tip of the target vector (theta = -60 deg, gamma = 64 deg). The
semi-major and semi-minor axes of the ellipse are 452 km in the horizontal
(longitudinal) direction and 59 km in the vertical (latitudinal),
respectively. The targeted value of gamma, defined as the angle between the
nadir direction and the Probe's velocity vector at a reference height of 1270
km, was selected to ensure a safe atmospheric entry and to guarantee
successful Probe radio communications via the PRL. The Probe's targeted
latitude is ~18 deg N.
------Update 06/04/01, RDR---------
After the discovery of a flaw in the radio system, it became necessary
to redesign the targeting strategy. See [LEBRETONETAL2005] for
more information.
-------end of Update--------------
Owing to the extreme elongation of the error ellipse in the horizontal
direction, dispersion in the entry angle is small for values of theta ~ -90
deg, but quite large for theta ~ 0 deg. In order to minimise entry angle
dispersion, Huygens' B-plane target azimuth was selected as theta = -80 deg in
the early stages of the mission planning process. Considerable trade-off
analyses, however, were conducted to address scientific preferences for the
impact latitude, solar zenith angle (SZA) and, specifically for DWE, the angle
between the east-west direction on Titan and the line-of-sight direction from
Probe to Orbiter. This angle, referred to as the Doppler Wind Component (DWC)
angle, was very unfavourable to DWE for theta = -80 deg. The cosine of the
angle DWC, which is the 'zonal wind projection' (ZWP) onto the PRL ray path,
regulates the magnitude of the Doppler shift from zonal winds.
A study of the DWE wind recovery algorithm under various Probe/Orbiter
geometries showed that a very good representation of the input wind was
derived for ZWP > 0.5. This is Region (a). Less precise,
but still satisfactory, recoveries could be obtained in Region (b), where
0.3 < ZWP < 0.5. The discrepancy between the input wind and the recovered
profile begins to increase dramatically, however, when ZWP < 0.3. The Region
(c), where the zonal wind recovery error became unacceptably large, was thus
declared a 'zone of avoidance' by DWE.
The original Huygens target with gamma = 64 deg, theta = -80 deg was, in fact,
located in Region (c). The DWE request to move the B-plane azimuth angle to
theta = -60 deg was granted after carefully reassessing the consequences for
the overall mission performance. Only a very small portion of the 3 sigma
targeting ellipse is now located in Region (c). The calculations of
ZWP were performed for the '100% nominal' input wind model (prograde, linearly
increasing from zero at the surface to 100 m/s at 200 km altitude;
[FLASARETAL1981]). Different contours are obtained for other wind models. A
prograde zonal wind significantly shifts the touchdown site to the east of the
Probe's atmospheric injection point, thereby improving the ZWP. The situation
is the reverse for retrograde winds, which tend to increase the recovery
errors. For all reasonable cases tested, however, the recovery algorithm never
becomes indeterminate (i.e. when ZWP --> 0).
 
Titan atmospheric descent: PRL Doppler effects
----------------------------------------------
As the Probe enters Titan's atmosphere, it is subjected to a severe
deceleration at ~ 250 km altitude that could be as high as 16.1 g. A parachute
is deployed near Mach 1.5, marking the beginning of the descent phase (time =
t0). After the Probe slows to subsonic velocity, the heat shield is jettisoned
(at t0+30 s) and the PRL is established for transmitting data to the Orbiter
(no later than t0+150 s). The large initial parachute is released at t0 + 15
min and replaced by a smaller drogue in order to decrease the descent
duration.
 
 Probe motion during descent
 ---------------------------
The Probe's motion in Titan's atmosphere is determined by the action of two
forces: gravity and wind drag. The acceleration due to wind drag a_d is taken
from [FLURY1986] to be:
 a_d = - (rho(z) / 2 C_B) V_PW V_PW^                                    (3)
where rho(z) is the atmospheric density, V_PW = V_P - V_W is the relative
velocity of the Probe with respect to the atmospheric wind, and C_B is the
ballistic coefficient (units: kg/m^2) defined by:
      C_B = m / (C_D A)                                                 (4)
with m = probe mass, C_D = drag coefficient, and A = effective probe area to
the flow.
The wind velocities in the (x, y, z) directions of a Cartesian coordinate
system on Titan's surface are given by:
  u = zonal wind                    (x-axis: positive towards east)
  v = meridional wind               (y-axis: positive towards north)
  w = vertical wind                 (z-axis: positive upwards)
The Probe's equation of motion during the Titan descent phase can thus be
written:
 xdotdot = - (rho / 2 C_B) V_PW (xdot-u)                                (5)
 ydotdot = - (rho / 2 C_B) V_PW (ydot-v)                                (6)
 zdotdot = - (rho / 2 C_B) V_PW (zdot-w) - g(z)                         (7)
where g(z) is Titan's gravitational acceleration, and
 V_PW = [(xdot-u)^2 + (ydot-v)^2 + (zdot-w)^2]^0.5                      (8)
The meridional and vertical winds, v and w, are assumed to be considerably
weaker than the zonal wind u. In this case, the latitude of the Probe (y
component) remains approximately constant. Knowing the Probe's velocity on
Titan, it is not difficult to determine the Doppler shift projected on to the
PRL ray path back to the Orbiter:
 Delta f = - (f / c) Delta V                                            (9)
where
 Delta V = (V_P - V_O) 'dot' DELTA                                     (10)
with
  V_P = Probe velocity wrt Titan centre
  V_O = Orbiter velocity wrt Titan centre
  DELTA = unit vector pointing from Orbiter to Probe
The vector DELTA defines the line-of-sight of the PRL. Delta V is negative
during descent, so that the received frequency is increased (blue shifted).
The PRL Doppler shift (9) is ~37.6 kHz for the nominal Orbiter starting
approach velocity of -5.53 km/s. The velocity of the Probe projected on to
the line-of-sight can be written:
 DELTA 'dot' V_P = V_1 + V_2 + V_3 + V_4                               (11)
where
 V_1 = xdot sin (alpha) cos (beta)                                     (12)
 V_2 = Omega (a + z) cos (lambda) sin (alpha) cos (beta)               (13)
 V_3 = ydot sin (alpha) sin (beta)                                     (14)
 V_4 = zdot cos (alpha)                                                (15)
Furthermore, we define the projection of the Orbiter velocity on to the
line-of-sight by:
 DELTA 'dot' V_O = V_5                                                 (16)
The angles alpha and beta define the direction from the Probe to the Orbiter
in a local Cartesian coordinate system on the Probe oriented along a natural
Titan coordinate grid (x-axis positive towards east; y-axis positive towards
north; z-axis positive upwards). The angle alpha, basically the zenith angle
of the Orbiter as seen from the Probe [OTT1991], is also sometimes
designated as the 'probe aspect angle' (PAA). The azimuthal angle beta of the
Probe-to-Orbiter line-of-sight is labelled the 'line-of-sight azimuth' (LOSA)
by some authors [ATKINSON1989; POLLACKETAL1992].
The term V_1 in (12), where the mean value of xdot ~ u, the drift velocity due
to zonal winds, is the quantity to be determined by DWE. This velocity is
co-aligned with the contribution V_2 in (13) due to Titan rotation. It is
assumed for simulation purposes that the rotation is synchronous with Titan's
orbital period (Omega a ~ 11.7 m/s). As noted above, the
relative importance of V_1, and thus the quality of the reconstructed wind
profile, is strongly dependent on the values of alpha and beta.
The term V_3 in (14), arising from meridional drift, should be small because
ydot is not expected to be important. The term V_4 in (15) contains the
vertical descent velocity zdot. This quantity can be obtained to a high degree
of accuracy either from the range rates deduced from the Probe's proximity
sensor data, or using measurements of temperature T and pressure P from HASI.
In the latter case, based on the assumption of hydrostatic equilibrium and
ideal gas behaviour, the descent velocity is determined from:
 zdot = - (H / P) dP/dt                                                (17)
where variations in H = RT/mu g, the atmospheric scale height, are assumed to
be negligible over the altitude range of Huygens' descent. The final error
associated with the determination of the reconstructed Probe descent velocity
is estimated to be of the order of 1%.
Knowing zdot(t) from the proximity sensor or from HASI measurements, it is
possible to reconstruct xdot(t) ~ u(t) from the PRL's Doppler shift (9). Using
in situ measurements of the density rho(z), we can then extract the exact
height profile u(z) from the motion equations (5) and (7). Comparative wind
measurements are expected near the surface from two independent sources on
board the Probe:
  - proximity sensor measurements using pendulum swing motion, or
  - inference of horizontal motion from the Descent Imager/Spectral Radiometer
    (DISR).
This would provide verification of the DWE height profile for the last few
data points before touchdown, when horizontal winds are likely to be weak. If
the Probe survives the surface impact and continues to transmit, further DWE
measurements might provide a frequency reference for zero wind. The
post-impact data are not necessarily a reliable calibration, however, because
the Probe oscillator may execute shock-induced frequency shifting at impact.
In addition to the derivation of a zonal wind height profile from the
large-scale drift, DWE may be able to provide valuable science and navigation
services from the small-scale variations in frequency as a by-product of the
analysis. Two such possibilities are:
  1. knowledge of the zonal wind velocity enables an extremely accurate
     reconstruction of the flight path during descent, and therefore the best
     possible determination of the impact coordinates on Titan
  2. rotational motion of the Probe during descent will produce a small
     modulation in the PRL frequency and signal level that will be exploited
     to derive the Probe's spin rate and spin phase, thereby effectively
     serving as a compass in the Titan landscape.
The amplitude of the Doppler modulation from the rotation is proportional to
the spin rate. The ultimate accuracy of the Doppler measurement, limited by
the clock digitisation of the PSA receivers, is 60 mHz. This accuracy
translates to an estimate of the spin rate error (1 sigma) of delta omega =
+-0.27/(omega tau)^0.5 rpm, where omega is the spin rate in rpm and tau is the
integration time in minutes. For a representative value of tau = 1 min, this
yields a relative error of 27 % just before impact, when the Probe spin rate
is expected to be ~1 rpm. The relative error is much smaller at higher
altitudes where the spin rate is greater (e.g. ~0.9% for omega = 10 rpm,
tau = 1 min). An improvement in this estimate from the Doppler data can be
achieved by including the signal level data. As the radiation pattern of the
Probe Transmitter Antenna (PTA) is asymmetric, the Probe's rotation phase can
be determined from the phase of the received signal level modulation. The
amplitude of the PTA's cyclic variation will be ~ +- 2 dB during each
rotation.
------Update 06/04/01, RDR---------
The time resolution of the Doppler data obtained on Earth is not
sufficient to derive a spin rate.
Instead, signal level measurements obtained from channel B on Cassini were
used.
-------end of Update--------------
 
 
 Vertical resolution: Probe response time
 ----------------------------------------
It is important to characterise the wind shear and turbulence in Titan's
atmosphere with DWE measurements of the smaller-scale Probe motion due to wind
gusts [STROBEL&SICARDY1997]. To a good approximation [ATKINSON1989], the
Probe response to a horizontal wind gust of magnitude u0, applied at time
t = 0, is given by:
 xdot(t) = u0 [1 - exp(-g t / V_T)]                                      (18)
where V_T is the terminal velocity determined from the force balance (7)
between gravity and the drag force (for zdotdot = 0) given by
 V_T ~ [(2mg) / (C_D A rho)]^0.5                                         (19)
Referring to (18), the Probe evidently adjusts itself to the wind on time
scales of the order of:
 tau = V_T / g                                                           (20)
The relaxation time constant tau at some level in the atmosphere is equal to
the ratio of the Probe terminal velocity V_T to the acceleration of gravity g
at that level. Both the descent velocity (19) and the Probe response time (20)
vary with atmospheric density as rho^-0.5.
If the Probe suddenly encounters a wind gust, the Probe horizontal velocity
will adjust itself to a factor (1 - e^-1), or about 63% of the gust velocity,
in a time equal to the time constant (20). In this time, the Probe has
descended through a distance
 l_min = V_T tau = V_T^2 / g                                             (21)
Wind shears contained within a spatial layer smaller than l_min will have
essentially no effect on the Probe. The spatial scale l_min thus represents
the minimum (vertical) size of atmospheric structure detectable by monitoring
the PRL Doppler profile. Invoking (19) and (20), it is seen that l_min is
inversely proportional to the atmospheric density and independent of g:
 l_min = 2 C_B / rho                                                     (22)
Using the Titan atmospheric pressures and densities from [LELLOUCHETAL1989],
the Probe descent velocity V_T, response time tau and minimum scale
sizes l_min are tabulated in Table 1, based on the nominal descent profile of
duration 135 min. Under the initially large parachute (C_B ~ 8 kg/m^2) in the
upper atmosphere (above ~ 115 km), the Probe motion will reflect atmospheric
structure with kilometre size scales. Near the surface, where C_B > 50 kg/m^2
and V_T is much smaller, the minimum detectable structure size is of the order
of 20 m.
 
Table 1. Probe descent velocity, response time and vertical resolution.
-----------------------------------------------------------------------------
 time    altitude     P     rho      C_B     V_T     tau     l_min
 (min)     (km)    (mbar) (kg/m^3) (kg/m^2) (m/s)    (s)      (m)
-----------------------------------------------------------------------------
   8       130        4    0.009      8     47.0    38.6     1815
  40        50       77    0.363     52     19.3    14.8      286
  82        20      487    2.19      53      8.0     6.0       48
 105        10      859    3.58      53      6.3     4.7       30
 120         5     1120    4.43      53      5.7     4.2       24
 135         0     1440    5.38      56      5.3     3.9       21
-----------------------------------------------------------------------------
 
Doppler wind recovery algorithm
-------------------------------
A robust zonal wind recovery algorithm for the Cassini-Huygens scenario has
been developed by [ATKINSONETAL1990]. Much of the formalism has been
carried over from the experience gained from a very similar DWE investigation
on Galileo [POLLACKETAL1992].
------Update 06/04/01, RDR---------
Another alternative algorithm has been developed by [DUTTAROY2002].
-------end of Update--------------
An essential prerequisite to application of the algorithm
------Update 06/04/01, RDR---------
developed by [ATKINSONETAL1990]
-------end of Update--------------
is an accurate reconstruction of the Probe-Orbiter relative
geometry. It is initially assumed that the Probe's position is not affected by
the integrated effect of the winds. Once a preliminary wind profile is
calculated, the Probe descent position can be updated to reflect the
integrated effect of the winds on the Probe descent longitude, and the wind
profile is recalculated with the new time-varying Probe longitudes. An
important assumption is that the zonal winds are dominant, with the possible
exception of the last few kilometres above the surface.
------Update 06/04/01, RDR---------
The algorithm developed by [DUTTAROY2002], on the other hand, determines
the zonal velocity and the corresponding longitude drift in one step.
-------end of Update--------------
The zonal wind profile derived from the DWE measurements on Galileo is a
relative (wind shear), rather than absolute, profile. This is because of the
rather large uncertainty in the actually transmitted frequency from the quartz
USO on the Galileo Probe. The 'constant' of the integration, i.e. a value of
the wind u_N at a specific time t_N, must be determined by independent means.
This problem does not exist with the Huygens DWE because the absolute
fractional frequency uncertainties inherent to the TUSO and RUSO are of the
order delta f/f ~ 2 x 10^-10.
Under these circumstances, the accuracy with which the zonal winds can be
recovered is determined by the imperfect knowledge of the Probe/Orbiter
trajectory. Of lesser importance are second-order Taylor, Doppler and Special
Relativistic terms that are usually dropped in order to keep the recovery
problem linear, and environmental effects due to S-band signal propagation
through a refracting, attenuating atmosphere (e.g. [BIRD1997]). Trajectory and
oscillator drift errors introduce a small time-varying component into the
Probe-Orbiter relative velocity that cannot be distinguished from atmospheric
winds. A detailed treatment of the effects of these various errors for the
recovery of the zonal wind height profile may be found in [ATKINSONETAL1990]
------Update 06/04/01, RDR---------
and [DUTTAROY2002].
-------end of Update--------------
 
In order to better understand the limitations of the recovery algorithm, we
numerically simulated the wind recoveries for a variety of different
trajectories, wind environments and errors. Here we summarise the results from
several of those simulations and compare the recovered wind profile to the
ideal case, where no frequency errors, trajectory uncertainties or anomalous
wind regions exist. In all cases the input wind profile is a 'Flasar-type'
model, a linearly increasing zonal wind with height, the direction and
magnitude of which are variable parameters of the simulation. The largest
error sources are those due to Probe entry longitude (0.7 deg), Probe entry
latitude (0.1 deg), Probe descent velocity (0.005 zdot) and the maximum
possible USO frequency drift (0.4 Hz in 2.5 h). The errors decrease during the
Probe descent - in these simulations constrained to be zero at Titan's
surface.
The touchdown longitude phi_td is located about 6 deg (260 km) east of the
entry longitude for the case with the nominal prograde wind profile. The
Probe's mean speed in its easterly drift is ~ 100 km/h (28 m/s). Since the
drift speed can be higher than the vertical descent velocity, the flight path
to the surface can become rather flat. As expected from (7), the vertical
descent time is only weakly dependent on the zonal wind u.
The quality of the wind recovery is summarised
in Table 2, which shows (a) the mean error in the determination of the zonal
wind over the height interval 0-100 km (delta u in m/s), and (b) the error in
the determination of the impact longitude (delta phi_td in degrees).
 
Table 2. Mean zonal wind and impact longitude errors.
------------------------------------------------------------------------------
Input wind model                delta u (m/s)        delta phi_td (deg)
------------------------------------------------------------------------------
  1 x prograde                     1.14                    0.48
  2 x prograde                     2.34                    0.22
  1 x retrograde                  -2.57                    1.23
  2 x retrograde                  -6.42                    1.96
------------------------------------------------------------------------------
 
Additional simulations verified that the wind recovery algorithm is not
affected by an input wind profile with a region of high shear, i.e. the wind
recovery is not limited to smooth and slowly varying horizontal winds. As
noted in the previous section, however, the detectability of fine wind
structure is limited by the Probe response time (20).
 
End-to-end measurement concept
------------------------------
DWE is the only Huygens investigation with 'science hardware' on both the
Probe and within the Probe Support Avionics (PSA) of the Probe Support
Equipment (PSE) on the Orbiter.
The DWE-TUSO on the Huygens Probe is the primary signal generator used to
drive the PRL of Transmitter A (Tx A). In case of failure, the driver signal
can be switched to an internal temperature-controlled quartz oscillator (TCXO)
with a frequency stability approximately 1000 times worse than the TUSO. The
choice of oscillators for Tx A will be made before Probe-Orbiter separation,
based on the performance of the TUSO and TCXO during the regular cruise phase
checkouts.
The 10 MHz output of the TUSO is upconverted to the PRL frequency of 2040 MHz,
at which point it is transmitted via one of two routes to PSA Receiver A (Rx
A) on the Orbiter. During cruise checkouts the signal is attenuated and sent
via the radio frequency built-in-test equipment (RF-BITE) across the Umbilical
Separation Mechanism (USM). During the Titan descent the signal is amplified
for free-space RF transmission via the PTA to the Cassini HGA. The centre
frequency of PSA Rx A is tuned to the nominal Tx A output frequency at 2040
MHz in checkout mode and is shifted by +38.5 kHz for descent mode.
All timing and signal generator requirements for Rx A are controlled by the
DWE-RUSO, which is virtually identical to the TUSO on the Probe. Similar to
the Probe side, switching to a back-up TCXO is possible in case the RUSO
fails. After downconversion, the PSA receiver phase locks onto the PRL signal,
the loop control being governed by a numerically-controlled oscillator (NCO).
The digitised values of the changes in NCO frequency required to maintain
phase lock, an 'NCO control word' of 20 bits, is written to the PSE
housekeeping (HK) data at 8 samples/s. The PRL signal level is monitored at
the same sample rate by recording the PSA receiver automatic gain control
(AGC; length 16 bits). The frequency resolution due to the data digitisation
is governed by the internal PSA receiver clock and is given as ~ 60 MHz, which
is very close to the least significant bit written into the NCO control word
(48 MHz). The range of Doppler shifts accomodated by the 20-bit NCO control
word is +-25 kHz (value corrected 06/04/01, RDR).
The NCO control word and AGC data are
routed to the solid state recorders on the NASA side of the Orbiter for later
playback to Earth. The 'redundant' data from PSA receiver B (Rx B) are
generated and received using standard TCXOs and thus not expected to yield
information about the Probe's drift motions. Nevertheless, these data will
also be recorded for the AGC information, thereby providing a control value
for comparison with the data from Rx A.
The only DWE data transmitted with the PRL telemetry are three temperature
measurements (8 bits each) and one bi-level lock status bit, which are
recorded every 16 s as part of the Probe housekeeping (HK) telemetry blocks.
The associated DWE 'bit rate' of these HK data is thus only ~ 1.6 bit/s.
Analogous HK-data are recorded at 25 bit/s on the PSE side from the RUSO. The
quantities comprising DWE science data, the NCO control word for the frequency
and the AGC for the signal level of the PRL are recorded at 288 bit/s.
Assuming these data are recorded for the longest possible Huygens mission of 3
h (including 30 min on the surface), the total amount of cumulated DWE data
for one chain will be ~425 kbyte. The Tx/Rx chain B, to be analysed primarily
for its AGC information (no RUSO data), will generate another ~391 kbyte.
Noting that these data will be stored redundantly for later playback to Earth,
we arrive at a grand total for the DWE data volume of 1.632 Mbyte.
The TUSO will be powered up before Titan atmospheric entry at the time t0 - 17
min 46 s, in order that it be given sufficient warm-up time to achieve the
required frequency stability. The RUSO, which will be turned on at t0 - 30
min, is less critical because of its comparatively safe location onboard the
Orbiter. The DWE-USO frequency stability will be monitored during the
regularly scheduled Probe cruise checkouts en route to Saturn. The last such
rehearsal will occur during the initial Saturn orbit, about 10 days before
Probe separation.
 
DWE Instrumentation: Ultrastable Oscillator (USO)
=================================================
 
Transmitter and receiver USO programmes
---------------------------------------
Two ultrastable oscillators, a TUSO for the transmitter on Huygens and a RUSO
for the receiver on Cassini, have been constructed as identical units within
one and the same USO programme in order to minimise costs. The contractor for
this work is Daimler-Benz Aerospace (DASA), Satellite Systems Division, in
Ottobrunn, Germany. The DASA design concept is based on a space-qualified
rubidium oscillator Physics Package supplied by Ball Efratom Elektronik GmbH.
The TUSO/RUSO combination represents the first use of rubidium oscillators on
a deep space planetary mission.
A total of six USO models have been built. The single Structural, Thermal and
Pyrotechnic Model (STPM) was delivered for system testing on schedule in April
1994. The two Electrical Models (EM), one TUSO and one RUSO, were delivered in
November 1994 to the System AIV (Assembly, Integration and Verification)
Program at DASA. Three interchangable units of flight standard (FM) have been
fabricated: one TUSO FM, one RUSO FM and one Qualification Flight Spare (QFS,
a refurbished unit used for qualification testing at unit level).
 
USO mechanical/electrical characteristics
-----------------------------------------
The DWE USOs are designed to withstand the Cassini/Huygens launch and cruise
phase (10 years in the event of a 1999 backup launch), as well as the Huygens
atmospheric entry and descent on Titan. The TUSO on Huygens is exposed to
higher mechanical loads than the RUSO on Cassini. The most critical factor for
the TUSO, a major driver in the selection of an ultrastable oscillator based
on rubidium technology, is the peak deceleration of up to 16.1 g during the
Huygens entry phase. It could not be guaranteed that the required frequency
stability of delta f0/f0 < 2 x 10^-10 (f0 = nominal output frequency) could be
met after the Probe entry into Titan's atmosphere with a state-of-the-art
quartz oscillator. The high mechanical load during entry might cause a
deformation of the internal quartz fastening system in combination with an
unpredictable frequency offset and an unknown frequency relaxation time. A
similar problem with continuously varying mechanical stresses on the quartz
box was foreseen in the subsequent pressure variation from 0 bar to 1.5 bar
during descent. These adverse effects can be averted with a rubidium
oscillator, for which the frequency source is also a quartz, because the
nominal output frequency is locked to the very stable frequency of the
rubidium ground-state hyperfine transition.
The basic principle of a rubidium oscillator is to employ the two
ground-state hyperfine levels A and B and a much higher optical level C of
rubidium atoms to produce an error signal for the control circuit of a
voltage-controlled quartz oscillator VCXO. IR light from a rubidium lamp is
filtered and passes through the heated rubidium resonance cell with a
frequency nu_CA = nu_C - nu_A, exciting transitions to state C of the rubidium
gas. Atoms in level C drop back after a very short time either to state A or,
with less probability, to state B. As atoms in state A are continuously
re-excited to C, the population of level B steadily increases ('optical
pumping'). When state A is depopulated, a maximum photocurrent is produced in
the photocell as the light is no longer attenuated by excitation processes
from level A to C. The HF-signal of the synthesiser, which is upconverted from
the quartz output signal, also irradiates the rubidium resonance cell. The
synthesiser is calibrated to generate the exact resonance frequency nu_BA =
nu_B - nu_A ~ 6.835 GHz if the quartz has its nominal output frequency. At
this frequency, atoms in level B de-excite to state A, thereby inducing a
minimum photocurrent, because the rubidium vapour is no longer transparent to
the frequency nu_CA. Deviations from the minimum current condition are
produced by deviations in the nominal VCXO output frequency. The current dip,
however, is very small (0.1% of the total photocurrent) and not suitable for a
DC detection. To circumvent this shortcoming, the synthesiser frequency is
modulated at an audio frequency nu_m = 127 Hz. The similarly modulated
photocurrent can now be AC-detected by synchronous current demodulation. There
is a positive correlation between the sign of the current error signal
(positive or negative) and the offset from the nominal quartz output
frequency. This error signal is used to lock the nominal quartz signal to the
rubidium resonance frequency by varying the quartz control voltage.
The USO consists of the Physics Package (rubidium resonance cell and lamp) and
several printed circuit boards, which contain discrete electronic elements as
well as integrated circuits. The USO electronics and the Physics Package are
integrated into an aluminium box, which is constructed as a Faraday cage to
avoid electromagnetic contamination of the USO environment. The USO box is
attached to the experiment platform via four mounting studs, thereby providing
a thin air buffer for better insulation from the mounting platform. This
reduces the USO conductive heat loss, saving power that would otherwise be
needed for heating.
The box surface is plated with nickel and coated with Chemglaze Z 306. The
total mass of the USO is ~1.9 kg. The electronics and Physics Package is
surrounded by mu-metal shielding to minimise the effects of changes in the
external magnetic fields that range from >10^4 nT on Earth to essentially zero
at Titan. Variations in the ambient magnetic field induce a change in the Rb
hyperfine resonance frequency and thus a frequency shift in the USO output
signal. Radiation-sensitive USO components such as transistors and analogue
ICs are radiation-hardened up to 10 krad. While the maximum radiation dose for
the Probe TUSO is ~ 5 krad, the RUSO on the Orbiter will be exposed to about
18 krad in the event of a 1999 launch. In order to provide additional
radiation protection for the RUSO, the critical components of both USO units
are shielded with tantalum caps (thickness ~1 mm). Radiation shielding
contributes about 10% to the total USO mass budget.
The USO external supply voltage of 28 V (TUSO) or 30 V (RUSO), is transformed
down to 5 V and 17 V by the DC/DC converter. The converter control signal is
provided by the synthesiser, synchronised to the quartz output signal. The
VCXO quartz, located on the Oscillator Board, provides the 10 MHz output
through a buffer amplifier. The same signal is upconverted by the synthesiser
to the rubidium resonance frequency. The photocurrent of the Physics Package
is routed to the Servo Board, which generates the error signal for the voltage
control of the VCXO. The heater control of the rubidium lamp within the
Physics Package is located on a separate Lamp Board. Three analogue sensors
monitor the temperatures of the rubidium lamp, rubidium cell and VCXO,
respectively. A bi-level lock indicator flips from '0' to '1' whenever the
quartz output signal is in lock with the rubidium resonance frequency. The
temperatures and lock indicator signal are part of the Huygens HK data. Table
3 summarises the USO mechanical and electrical characteristics.
 
Table 3. USO mechanical and electrical characteristics.
-----------------------------------------------------------------------------
Mass                                           1.90 +- 0.15 kg
Dimensions (length x width x hieght)           180 x 149 x 118 mm
Warm-up Power                                  P_wu = 18.2 W (<= 30 min)
Steady State Power at baseplate temp. T        P_ss = 10.375 - 0.0625 T (W)
Output Frequency                               10 MHz +- 0.1 Hz
Output Signal Level                            0 +- dBm into 50 Ohms
Warm-up Time to delta f0/f0= 2x10^-10          <= 30 min
Supply Voltage (TUSO)                          28 (+0.35,-0.63) V
Supply Voltage (RUSO)                          30 (+1.5,-3.38) V
-----------------------------------------------------------------------------
 
USO frequency characteristics
-----------------------------
The USO long-term frequency stability requirement of delta f0/f0 <= 2x10^-10
is critical for a successful Doppler Wind Experiment. By 'long-term', it is
meant that the uncertainty in the frequency must be constrained within these
limits for the maximum expected duration of the atmospheric descent (2.5 h),
i.e. the total frequency shift of the PRL signal is <0.4 Hz over the entire
Huygens mission. Assuming a typical DWC angle of 65 deg, an unwanted frequency
shift of this magnitude would be indistinguishable from a zonal wind with
velocity of ~0.15 m/s. This USO frequency stability is thus mandatory for
achieving the primary DWE goal, a determination of Titan's zonal wind height
profile with an accuracy well below the +- 1 m/s level. This must be
maintained throughout the entire Huygens mission, in spite of many rather
severe changes in the environmental conditions (temperature T, pressure P,
acceleration A and magnetic field B). Generally, this requirement can be
expressed by:
 |delta f0/f0| = 1/f0 [(delta f0/delta T Delta T)^2 +
                       (delta f0/delta P Delta P)^2 +
                       (delta f0/delta A Delta A)^2 +
                       (delta f0/delta B Delta B)^2 +
                       (delta f0/delta X Delta X)^2]^0.5   <= 2x10^-10    (23)
where 'X' collectively labels other factors, e.g. the variation of the USO
supply voltage. Typical values for the expected fractional change in the USO
output frequency are listed in Table 4.
Although not as critical as the long-term frequency stability, the short-term
frequency stability is another criterion for the frequency quality of the USO.
The short-term frequency stability is characterised by the mean fractional
frequency deviation
 sigma = Delta f0 / f0                                                    (24)
This quantity, sometimes called the 'Allan deviation', depends on the
integration time tau (see also equation 26). The specified USO short-term
frequency stabilities are shown in Table 5. These values are sufficient to
detect PRL frequency modulations owing to atmospheric turbulence as well as
the Probe's pendulum and rotational motion. Table 6 lists the specifications
on the phase noise of the output signal spectrum for various displacements
from the centre peak.
 
Table 4. Fractional change of USO output frequency.
-----------------------------------------------------------------------------
Environmental           fractional frequency   worst case: Huygens descent
   factor               change delta f0/f0         TUSO         RUSO
-----------------------------------------------------------------------------
Temperature (per deg C)    3 x 10^-12    Delta T ~ 15 deg C     ~ 5 deg C
Pressure P (per bar)       1 x 10^-12    Delta P ~ 1.6 bar      ~ 0 bar
Acceleration A (per g)     4 x 10^-12    Delta A ~ +- 1.0 g     ~ +- 0.1 g
Magnetic field B (per G)   2 x 10^-12    Delta B ~ 1 mG         ~ 0.1 mG
-----------------------------------------------------------------------------
 
 
Table 5. USO short-term frequency stability.
-----------------------------------------------------------------------------
Integration time tau (s)                  Delta f0/f0
-----------------------------------------------------------------------------
        0.1                                 6 x 10^-11
        1                                   1 x 10^-11
       10                                   5 x 10^-12
      100                                   1 x 10^-12
-----------------------------------------------------------------------------
 
 
Table 6. USO phase noise.
-----------------------------------------------------------------------------
Displacement (Hz)                       Phase noise (dBc)
-----------------------------------------------------------------------------
        1                                     -90
       10                                    -120
      100                                    -140
     1000                                    -150
-----------------------------------------------------------------------------
 
 
USO test programme
------------------
At this writing, only results from the EM test programme are available.
A USO test assembly, developed at the University of
Bochum, is used at the unit level to determine USO frequency characteristics.
Of particular interest is the frequency stability of the USO on all time
scales. It is also necessary to characterise the repeatability of the
long-term drift of the USO in order to correct for this effect under the
conditions of the Huygens descent.
The frequency measurement procedure is based on a comparison of the test
frequency f (DWE-USO) with a reference signal f0 (rubidium reference
oscillator), the frequency stability of which is better than or equal to that
of the test signal. Using a synthesiser, the reference frequency is offset
from the nominal frequency of the test object f0 by a known amount f_offset.
The frequency difference of the two signals is generated with the help of a
mixer and then measured by a frequency counter. Following a fully automated
procedure, both the long-term and short-term stabilities of the test object
are determined by recording the frequency difference for an appropriately long
interval (nominal test run: 3 h). The reference and offset frequencies, as
well as the integration and sample times can be adjusted as necessary with
respect to their default values for each individual run.
The number of single measurements is defined by the ratio of the adjusted
total measurement time to the mean duration of the single measurement cycle. A
single measurement cycle consists of the adjusted fixed integration time and
the counter register read-out time. The read-out phase requires about 20 ms.
The mean duration of one measurement cycle is thus about 1.02 s for an
integration time of tau = 1 s, and 10.02 s for tau = 10 s, respectively. The
absolute frequency f(t) and the Allan variance sigma^2 are then derived as
follows:
 f(t) = Delta f + f0 - f_offset                                           (25)
 sigma^2(tau) = (1/N) SUM[k=1..N] { (ybar_k+1 - ybar_k)^2 / 2}            (26)
where ybar_k = Delta f_k / f0, Delta f_k = m_k/tau, and m_k is the kth cycle
count over the integration time tau.
Running measurements of sigma, defined by (26) are made for integration times
tau = 1 s & 10 s. The mean values of the Allan deviation in this case were
< sigma(1 s) > = 1.8 x 10^-11 and < sigma(10 s) > = 5.5 x 10^-12,
respectively.
After reaching its asymptotic value, the output frequency of both models stays
within a band delta f/f < +- 2x10^-10. The model without magnetic compensation
was found to require too much time to warm up and also exhibited undesireable
variations in asymptotic output frequency with temperature. Significant
improvement was achieved by implementation of a magnetic control loop, which
exploits the sensitivity of the rubidium hyperfine transition to the strength
of the magnetic field in the rubidium cell. The strength of the magnetic field
applied to compensate for the thermal drift is determined via a feedback loop
using the thermal sensor in the crystal oscillator. Preliminary results from
recent thermal vacuum tests (FM Test Program) over an ambient temperature
range from -30 deg C to +60 deg C indicate that: (a) the USO warm-up time is
always <30 min, and (b) the variation in mean asymptotic frequency is
<2x10^-9.

        