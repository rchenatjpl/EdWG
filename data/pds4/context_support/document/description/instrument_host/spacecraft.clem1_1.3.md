
              Online Reference: http://wundow.wustl.edu/clem/frontpage.html

 
    Instrument Host Overview
    ========================
      For most Clementine experiments, data were collected by
      instruments on the spacecraft.  Those data were then relayed
      via the telemetry system to stations of the NASA Deep Space
      Network (DSN) on the ground.  Radio Science experiments (such
      as radio tracking of the spacecraft and bistatic radio
      scattering experiments) required that DSN hardware also
      participate in data acquisition.  The following sections
      provide an overview first of the spacecraft and then of the
      DSN ground system as both supported Clementine science
      activities.  The Naval Research Laboratory (NRL) also
      operated a tracking station at Pomonkey, Maryland.  Air Force
      Satellite Control Network (AFSCN) Remote Tracking Stations
      (RTS); a station of the Centre Nationales d'Etudes Spatiales
      (CNES) near Pretoria, South Africa; stations of the Navy Space
      Surveillance Network (NAVSPASUR); and a NASA site in Chile also
      participated in radio commanding and/or tracking.  But these
      were incidental to acquisition of science data and are not
      described further.
 
 
    Instrument Host Overview - Spacecraft
    =====================================
      The Clementine spacecraft was built at the US Naval Research
      Laboratory in Washington, DC.  It carried sensors, attitude
      control systems and software designed and built by the
      Lawrence Livermore National Laboratory (LLNL). The United
      States Air Force (USAF) supplied advanced lightweight
      composite structures and the launch vehicle, a Titan IIG
      refurbished ICBM.  Low spacecraft mass was achieved by
      incorporating many lightweight technologies developed
      through the research and development activities of the
      Strategic Defense Initiative (SDI).  NASA provided
      communications support through the Jet Propulsion
      Laboratory's (JPL) Deep Space Network; orbit determination
      and operations support were provided from both the NASA
      Goddard Space Flight Center and JPL.  Supporting these
      laboratories were scores of industrial contractors.
 
      The spacecraft consisted of an octagonal prism about 2
      meters high.  The all-aluminum frame was of conventional
      construction; the mid-deck was an aluminum honeycomb.
      Spacecraft dry mass was about 230 kg; an approximately
      equal mass of liquid fuel was added.  Total mass in the
      launch configuration was 1690 kg, with most of the weight
      in the solid  rocket motor (SRM) required for translunar
      insertion.
 
      The main instrumentation on Clementine consisted of four
      cameras, one with a laser-ranging system.  The cameras
      included an ultraviolet-visible (UVVIS) camera, a long-
      wavelength infrared (LWIR) camera, the laser-ranger (LIDAR)
      high-resolution (HIRES) camera, and a near-infrared (NIR)
      camera.  In addition the spacecraft had two star tracker
      cameras (A-STAR, B-STAR), used mainly for attitude
      determination; these also served as wide-field cameras for
      various scientific and operational purposes.  The sensor
      package had a mass of 8 kg.  The sensors were all located on
      one side of the spacecraft body, 90 degrees from the solar
      panels.  The spacecraft also carried a charged particle
      telescope to characterize the spacecraft environment.
      Radio tracking data from the spacecraft S-band transponder
      provided information on the lunar gravity field.  A small
      set of bistatic radar experiments was conducted using the
      radio transmitter to determine the scattering properties of
      the lunar surface.
 
 
      Propulsion Subsystem
      --------------------
        The Propulsion Subsystem provided three functions: (1) firing
        the SRM for translunar injection, (2) providing three-axis
        and spin-stabilized attitude control, and (3) providing
        trajectory changes and trims after separation of the SRM.
 
        The STAR 37FM SRM provided 3115 m/sec delta-V capability
        for translunar injection.  Its thrust specification was
        47260 N (nominal) and 54799 N (maximum).  The SRM mass was
        1152 kg.  For the SRM burn, the spacecraft was spun up to
        60 rpm using 4.4 N thrusters, then despun using opposing
        4.4 N thrusters following the burn.  The SRM was separated
        from the remainder of the spacecraft after translunar
        injection.
 
        A single 489 N bi-propellant thruster mounted on one end
        of the prism provided 1744 m/sec delta-V capability after
        the SRM separation.  It was used to adjust the phasing orbit,
        for lunar orbit insertion (550 m/sec), for lunar orbit
        trims (including the change in periselene latitude), and
        for departure from lunar orbit (540 m/sec).  It was fueled
        by nitrogen tetraoxide and monomethyl hydrazine (N2O4/MMH);
        195 kg of fuel was stored in four tanks; pressurization
        was provided by 1 kg of helium stored in two tanks.
 
        Ten fine (4.4 N) and two coarse (22.2 N) monopropellant
        thrusters provided attitude control for slewing during
        lunar mapping, for spin-up and spin-down, for momentum
        dumping, and for active nutation control.  These thrusters
        were fueled by 55.5 kg of hydrazine in a single tank.
 
 
      Attitude Control Subsystem
      --------------------------
        The Attitude Control Subsystem provided both three-axis
        and spin-stabilized control.  It included two Inertial
        Measurement Units (IMUs), two Star Tracker Cameras (STCs),
        four reaction wheels, and the twelve monopropellant
        thrusters described above.  The system was designed for
        attitude control of better than 0.05 degrees and knowledge
        of better than 0.03 degrees.
 
        The Star Tracker Cameras were mounted on opposite sides
        of the spacecraft, allowing at least one to obtain star
        field coverage at all times without interference from the
        Sun.  Each could provide three-axis attitude determination
        from a single image provided the Sun, Moon, and Earth were
        not in the field of view.
 
        The four reaction wheels (2 Nms) provided attitude control
        for fine pointing and for low acceleration slews.  The
        Attitude Control subsystem normally used three orthogonal
        reaction wheels for control, keeping the fourth (mounted
        at equal angular displacements from each of the other
        three) in reserve.
 
 
      Electric Power Subsystem
      ------------------------
        The Electric Power Subsystem included a pair of
        independently gimbaled, single axis, GaAs/Ge solar
        arrays providing a total spacecraft power of up to 360
        watts at 30 Vdc, with a specific power of 240 w/kg.  The
        two arrays protruded from opposite sides of the prism; by
        rolling the spacecraft and rotating the panels, full
        solar illumination of the panels could be achieved.
        The solar arrays were used to charge a 15 A-h, 22-cell,
        47-w hr/kg, Nihau common pressure vessel battery.  Power
        control distribution electronics distributed, conditioned,
        and monitored use of electrical power.  A Sensor Power
        Distribution System performed power distribution and
        conditioning for imaging sensors.
 
 
      Thermal Control Subsystem
      -------------------------
        The Thermal Control Subsystem maintained internal
        spacecraft temperatures within design limits.  External
        spacecraft surfaces were used under heat-generating
        units to radiate excess thermal energy.  Multi-layered
        insulation blankets covered all non-radiating external
        surfaces.
 
        A 4.1 kg beryllium block served as a thermal capacitor,
        storing excess heat when radiating surfaces were unable
        to dissipate it quickly enough.  Diode heat pipes carried
        heat from the block to radiating surfaces and protected
        against reverse flow.
 
        Sixty thermostats and heaters provided active protection
        against cold to various boxes, tanks, and propellant lines
        throughout the spacecraft.
 
 
      Command, Telemetry, and Data Handling Subsystem
      -----------------------------------------------
        Spacecraft data processing was performed by 3 computing
        systems.  A MIL-STD-1750A computer with a capacity of 1.7
        million instructions per second was used for safe mode,
        attitude control system, and housekeeping operations.  A
        reduced instruction set computer (RISC) 32-bit processor,
        capability of 18 million instructions per second, was used for
        image processing and autonomous operations.  The Clementine
        mission represents the first long duration flight of a 32-bit
        RISC processor.  Also incorporated was a state-of-the-art
        image compression system provided by the French Centre
        Nationale d'Etudes Spatiale (CNES).  A data handling unit
        with its own microcontroller sequenced the cameras,
        operated the image compression system, and directed the
        data flow.
 
        During imaging operations, the data were stored in a 3 kg,
        2 Gbit dynamic solid state data recorder.  They were later
        transferred to the ground stations using a 128 kb/s S-band
        downlink.  The spacecraft was commanded from the ground
        using a 1 kb/s S-band uplink from either the NASA Deep Space
        Network or from a DoD station.
 
        Demonstration of autonomous navigation, including autonomous
        orbit determination, was a major goal of the Clementine
        mission.  Autonomous operations were conducted in lunar
        orbit.
 
 
      Spacecraft Coordinate System
      ----------------------------
        The spacecraft +Z axis vector was in the nominal
        direction of the instrument sensor panel.  The +X axis
        vector was parallel to the nominal direction of the main
        thruster nozzle, and the -X axis vector was parallel to
        the spacecraft high-gain antenna (HGA) boresight.  The
        +Y axis vector formed a right-handed coordinate system
        and was in the nominal direction of the solar panel
        rotation axis.  The low-gain 'omni-directional'
        antennas were mounted on the +Z and -Z sides of the
        spacecraft body.  The spacecraft velocity vector was in
        approximately the -X direction when the spacecraft was
        oriented for nadir viewing.  In the figure below the
        viewer is facing the sensor panel; the viewer is looking
        in the -Z direction.
 
 
                               +X Axis
                                   ^
                                   |
                                   |
 
                              Main Thruster
                                \-----/
          ---------------        \   /         --------------
         |       |       |   -------------   |       |       |
         |       |       |  |             |  |       |       |
         |       |       |  |             |  |       |       |
  +Y     |       |       |  |   Sensor    |  |       |       |
    <--- | Solar | Panel |--|             |--| Solar | Panel |
 Axis    |       |       |  |    Panel    |  |       |       |
         |       |       |  |             |  |       |       |
         |       |       |  |             |  |       |       |
         |       |       |   -------------   |       |       |
          ---------------    / High-Gain \    ---------------
                            /   Antenna   \
                            ---------------
                                   |
                                   |
                                   V
                               -X Axis
 
 
      For more information see [REGEONETAL1994].
 
 
    Instrument Host Overview - DSN
    ==============================
      The Clementine Radio Science investigations utilized
      instrumentation with elements both on the spacecraft and at
      the NASA Deep Space Network (DSN).  Much of this is shared
      equipment, being used for routine telecommunications as
      well as for Radio Science.
 
      The Deep Space Network is a telecommunications facility managed
      by the Jet Propulsion Laboratory of the California Institute of
      Technology for the U.S. National Aeronautics and Space
      Administration.
 
      The primary function of the DSN is to provide two-way
      communications between the Earth and spacecraft exploring the
      solar system.  To carry out this function the DSN is equipped
      with high-power transmitters, low-noise amplifiers and
      receivers, and appropriate monitoring and control systems.
 
      The DSN consists of three complexes situated at approximately
      equally spaced longitudinal intervals around the globe at
      Goldstone (near Barstow, California), Robledo (near Madrid,
      Spain), and Tidbinbilla (near Canberra, Australia).  Two of the
      complexes are located in the northern hemisphere while the third
      is in the southern hemisphere.
 
      The network comprises four subnets, each of which includes one
      antenna at each complex.  The four subnets are defined according
      to the properties of their respective antennas: 70-m diameter,
      standard 34-m diameter, high-efficiency 34-m diameter, and 26-m
      diameter.
 
      These DSN complexes, in conjunction with telecommunications
      subsystems onboard planetary spacecraft, constitute the major
      elements of instrumentation for radio science investigations.
 
      For more information see [ASMAR&RENZETTI1993].

        