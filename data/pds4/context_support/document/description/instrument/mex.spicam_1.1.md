
 
  MARS EXPRESS SPICAM Description
  ===============================
 
    Revisions
    ----------
 
    2004 09 14    V001 initial Dimarellis
 
    Purpose
 
         This document describes the SPICAM (SPectroscopy for the
         Investigation of Characteristics of the Atmosphere of Mars)
         instrument on Mars express mission.
 
 
  Introduction
  =============
    In this document all technical details concerning the Spicam
    instrument are given. The mechanical and electrical
    characteristics are listed. The optical interfaces with
    spacecraft and the fields of view are explicit.
 
    This document is organized as:
        Introduction
        Instrument summary
        Design Description
        Physical configuration
        Subsystems
 
 
  Instrument summary:
  ===================
    SPICAM Light is a collaboration of
    -Service d'Aeronomie, Verrieres le Buisson, France;
    -IASB, Bruxelles, Belgique and
    -IKI, Moscow, Russia.
 
    The Spicam Light instrument is made of 2 boxes. The first box
    called DPU acts as the main electronic interface with the
    Spacecraft. The other is the sensor box or unit. This sensor unit
    has one channel in the ultraviolet wavelength range - 118-320 nm -
    (named SUV), and another one (named SIR) in the near infrared
    wavelength range - 1.1-1.7 micrometers.
 
    SPICAM Light  Main characteristics summary Table:
 
    Spectral bands
                            118 - 320 nm (UV)
                            1.1 - 1.7 microns (IR)
    Spectral sampling
                            UV: 0.55 nm/pix
                            IR: 0.8 nm/pix at 1.5 micron
    Mass
                            DPU          0.71 kg
                            SU           4.14 kg
                            Total        4.85 kg
    Power
                            DPU+SU  17 W to 26 W
    Volume
                            DPU:     1.65 x 1.14 x 0.65 dm3
                            SU:          4 x 2.4 x 1.15 dm3
    Data rate
                            9 and 34 kbit/s
                            (averaged over several seconds)
    Data Volume
                            100 - 300 Mbits / day
    Observations
                            One Board Time TC, One Spicam TC
                            Duration: 5 to 30 mn
    Pointing (orientation)
                            Inertial Star
                            Inertial Sun
                            Nadir
 
 
  Design Description:
  ===================
    The Sensor Unit is made of:
        the servitudes channel
        the UV channel
        the IR channel
    The Sensor Unit has two openings for Nadir viewing, one for UV
    channel, the other for IR channel located on the Nadir face of S/C.
    In addition, there is an opening for Solar viewing. This Solar
    aperture is NOT on the S/C Nadir face.
 
    The Sensor Unit has two mechanisms, one which move On and Off a slit
    in the UV channel, the other which moves a shutter on the Solar
    aperture. Spicam mechanisms are fully autonomous and no separate
    commands are needed for mechanism operations. Each mechanism has two
    statuses, ON and OFF for slit, OPEN and CLOSED for shutter.
 
    The UV channel is a spectrometer with an optical baffle, an off
    axis parabolic mirror, a slit with two positions, a grating and a
    detector which an intensified CCD. On the CCD, the rows which are
    parallel to the unit baseplate, are the spectral dimension.
 
    The IR channel is made of an entrance lens, an AOTF and two single
    pixels detectors (for each polarisation). As the AOTF acts as a
    filter, the IR spectrum is obtained by electrically scanning the
    AOTF frequency. All the channels have their own digital
    electronics which performs all operations at detector level and
    digitizes the data, then waiting for transmission to the DPU
    through a RS422 link at 937 kbits/s.
 
    The DPU main functions are:
        electrical interfaces with S/C
        send commands and get data from the subunits
        formatting data before transmission to S/C
 
    The DPU has the general control of the instrument. It sends commands
    to the sub units and retrieves data. Then it formats and produces
    telemetry packets. Servitudes refers to non-detector elements of
    Sensor Unit.
    The polling of the sub units is done by the DPU, at a rate defined
    in the Telecommand.
    Depending on the operating mode, The IR channel is switched ON or
    not.
 
 
  Physical configuration:
  =======================
    The Sensor Unit has two main directions of sight, one is Nadir ( s/c
    +Z), the other is 'behind' Solar panel, -Y side.
 
    The Sensor Unit has two openings for Nadir viewing, one for UV
    channel, the other for IR channel located on the Nadir face of S/C.
    The instrument optical axis is parallel to the baseplate and
    perpendicular to the Nadir face of the spacecraft.
 
    The Sensor Unit has three apertures:
     - Main UV aperture on Nadir face.
     - IR aperture on Nadir face.
     - Secondary UV and IR aperture for Sun viewing
            internal mirrors and fibre bent the Solar light in the
            instrument main optical axis
 
    In addition, there is an opening for Solar viewing. This Solar
    aperture is not on the S/C Nadir face. The Solar viewing opening
    opening is built in the base plate of the Sensor Unit. This opening
    will have to be oriented towards the Sun prior to each solar
    occultation observation. This opening can be closed by a mechanical
    shutter.
 
    Apertures definition:
      apertures Nadir face ( perpendicular to Zb)   UV    42 x 45 mm2
                                                    IR    diameter 32 mm
      aperture in (-Yb,-Xb) at 60 deg from -Yb        diameter 2 mm
               (UV and IR Sun occultation)
 
    The Sensor Unit  is located in the payload compartment of the S/C,
    near the -Y wall. A hole in the instrument mounting wall and in the
    -Y wall will be used for Solar occultation.
 
    Axis reference are in respect with Spacecraft Reference Frame
    (Spacecraft MICD, mechanical frame).
 
    Summary of operations:
 
    nI  Operational Mode    Target  Subsystem   Aperture
    --  ----------------    ------  ---------   --------
    1   Test Mode           NA      NA
    2   Sun Mode            Sun     UV+IR       Secondary UV+IR aperture
    3   Star Mode           Star    UV          aperture  on Nadir face
    4   Nadir Mode          Nadir   UV+IR       apertures on Nadir face
    5   Limb Mode           Limb    UV          aperture  on Nadir face
 
    Pointing, general assumptions:
 
    Assume pointing is done by Spacecraft
    Assume rotation of 90 deg, duration is around 11 mn (0.14 deg/s
    TBC). It seems that Spicam is quite demanding concerning S/C
    manoeuvers and resources availability. We examine resources needed
    by Spicam: - Manoeuver duration: is dependent on orbit parameters,
    actual Spacecraft attitude and desired inertial direction
    (selected objective) and will computed. It may be that total
    manoeuver duration during one orbit may be in conflict with Earth
    attitude needed for data transmission. However we note that there
    are 2 orbits (of 3) per day without transmission to earth. - Other
    resources as wheel usage and power: Wheel usage is a resource to
    be shared between instruments. Nadir pointing is more wheel
    consuming than fixed inertial attitude. Power is not a concern for
    Sun occultation (it drops to 0 anyway). For Star occultation, the
    angle around +Z axis is a free parameter and therefore can be
    adjusted for maximum power collection if necessary.
 
    In the Inertial mode, pointing direction is any inertial (relative
    to stars) direction. This direction must be kept fixed during
    observation duration of 2 to 8 mn. It is defined as any star
    direction which may be occulted by Mars in dark side of Planet.
    (see operational modes for details) In nadir mode, nominal nadir
    pointing (as other instruments) in bright side of Planet.
 
    The following table gives the Experiment viewing requirements for
    each objective.
 
   Objective    FOV (*)        FOV avoidance   Pointing        Duration
                                               Direction       (typical)
   ---------    -----------    -------------   ---------       ---------
 
   Star         1 deg x 3 deg  15 deg x 15 deg Inertial STAR   2 to 8 mn
     (UV)                      (Sun)
   Sun          slit           NA              Inertial SUN    2 to 8 mn
     (UV+IR)
   Nadir        slit           NA              Marsocentric    30 mn
     (UV+IR)                                   (Nadir)
   Limb         slit           15 deg x 15 deg Inertial        2 to 8 mn
     (UV)                      (Sun)
 
    There is no illumination constraints for OFF mode of Spicam for
    sensor point of view (energy is spread by grating).
    For information, following present orbit, 30 mn at Nadir around
    pericenter is the duration on orbit where S/C altitude is < 800km.
 
    (*) Spicam fields of view:
        UV channel
            Full CCD                    4 deg x 3 deg
            STAR mode       no slit     1 deg x 3 deg, no vignetting
            Nadir, Limb     slit        1.3 arc min x 3 deg
            Sun             pinhole     2 arc min
        IR channel
            Nadir                       1 deg circular
            Sun                         pinhole 2 arc min
 
 
  Subsystems:
  ===========
    List of elements of Sensor Unit:
        UV channel  parabolic off axis mirror, focal length = 120 mm
                slit with two positions
                grating
                intensified CCD with electronics box
        IR AOTF channel
 
    --->Servitudes Unit:
 
    This block is made of two boards:
        power board, which provides individual power for UV and IR
            UV needs +5, +15, -15 V
            IR needs  +5, +/-12, +/-15V
            Peltier cooler (UV and IR) 3.3 V
            The input 28V is coming from DPU where it is filtered.
        microprocessor board, this board controls:
            the two mechanisms,
            the IR switch on,
            the high voltage level (for UV channel)
            and retrieves 8 temperatures.
 
 
    --->UV detector Unit:
 
    The UV detector is made of 3 parts:
        a CCD camera with the head and two electronic boards (follow on
        of Mars96) an intensifier (Hamamatsu) with a 12 mm window which
        is coupled to the CCD by fibre optics
        a programmable high voltage (Hamamatsu) for the intensifier
 
    In the head, the CCD (TH 7863) is mounted on a one stage Peltier
    cooler for a delta T around 15 0C. The two electronic boards of
    the CCD camera are mechanically mounted on the servitudes boards.
    The CCD detector head is mounted in such a way that the columns
    are perpendicular to the baseplate of the Sensor Unit. The rows
    direction is the spectral dimension.
 
    The UV detector records a window of 5 rows allowing to have at the
    same time, in Star mode, the Star spectrum surrounded by the
    background spectra. The rows can be elementary pixels or binned
    pixels (binned columns). The nominal binning is between 4 and 8. The
    position of the rows is programmable.
 
    --->IR Channel Unit:
 
    The IR channel is made of an entrance lens, an AOTF crystal which
    acts as a negative filter, two (Hamamatsu) single pixels detectors
    (two polarisations) with their own Peltier cooler, and an electronic
    board. When the AOTF is powered (at a certain frequency), it selects
    a wavelength which goes up to the detectors. A full spectrum is then
    obtained by scanning the frequencies. The measurement is obtained by
    the difference between the AOTF on and off.
 
    --->DPU and flight software:
 
    The DPU is made of 3 boards:
        the power board which has 28V Interpoint filter modules for the
        whole instrument and provides 5V for the DPU itself (Interpoint
        module), the microprocessor board, based on a 80C32 chip, with
        Ram, Prom, Fifos as buffer for telemetry, and counters for time
        maintenance. the interface board which has an Actel FPGA RH1020
        for telecommand/ telemetry logic and interfaces circuits to S/C
        lignes.
 
    The DPU has two connectors for data lignes (one nominal and one
    redundant), two connectors for power lines, and one connector
    towards the Sensor Unit.
 
    DPU Hardware and software characteristics:
    microprocessor        80C32   30 MHz
    Eprom                 32 Ko
    Ram                   128 Ko for 2 pages
    Fifo TC               32 x 8 Kbits
    Fifo TM               3 x 32 x 8 Kbits (able to store 16 sec of data)
    Software code         26 Ko
    External data         43 Ko
    CPU load              < 50 %
 
 
  Principal Investigator
  ======================
    Jean-Loup Bertaux
    Service d'Aeronomie, IPSL/CNRS, FRANCE

        