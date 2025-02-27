
 
            The majority of the text below was extracted from the Cassini Mission Plan
            (JPL Document D-5564, David Seal, 2002). For more information on the NASA Deep
            Space Network, see Asmar and Renzetti (1993).

             
              Instrument Host Overview
              =========================
             
            For most Cassini Orbiter experiments, data were collected by instruments on
            the spacecraft then relayed via the orbiter telemetry system to stations of
            the NASA Deep Space Network (DSN).  Radio Science required the DSN for its
            data acquisition on the ground.  The following sections provide an
            overview, first of the orbiter, then the science instruments, and
            finally the DSN ground system.
             
             
              Instrument Host Overview - Spacecraft
              =======================================
             
            Cassini was successfully launched on 15 October 1997 from Cape Canaveral,
            Florida, using a Titan IV/Centaur launch vehicle with Solid Rocket Motor
            Upgrade (SRMU) strap-ons and a Centaur upper stage.  The spacecraft flew a
            6.7-year Venus-Venus-Earth-Jupiter Gravity Assist (VVEJGA) trajectory to
            Saturn, during which cruise operations included checkout, characterization,
            calibration, and maintenance of the instruments and limited science
            observations.
             
            Until they separated after Saturn orbit insertion, Cassini was a combined
            Saturn orbiter and Titan atmospheric probe.  It was a three-axis stabilized
            spacecraft equipped for 27 diverse science investigations with 12 orbiter
            and 6 Huygens probe instruments, one high gain (HGA) and two low gain
            antennas (LGAs), three Radioisotope Thermoelectric Generators (RTGs), main
            engines, attitude thrusters, and reaction wheels.  This description covers
            the orbiter portion of Cassini, which will frequently be called "the
            spacecraft".
             
             
               Orbiter Description
               ===================
             
            The Cassini orbiter was a three-axis-stabilized spacecraft.  The origin of
            the spacecraft coordinate system was located at the center of the plane at
            the bus/upper shell structure interface (i.e., base of the electronic bays
            on the upper equipment module).  The remote sensing pallet was mounted on
            the +X side of the spacecraft, the magnetometer boom extended in the +Y
            direction, and the +Z axis completed the orthogonal body axes in the
            direction of the main engine.  The primary remote sensing boresights viewed
            in the -Y direction, the probe was ejected in the -X direction, the HGA
            boresight was in the -Z direction, the main engine exhaust was in the +Z
            direction, and the main engine thrust was in the -Z direction.  The
            coordinates and some of the larger elements of the spacecraft are shown in
            the figure below.
             
                                                        /\
                                         ----------------------------------
                                         \                                /
                                          \                              /    HGA
                                           \                            /
                           MAG Boom          --------------------------
                        ... =================|                        |
                                             |           h            |
                                              \          ^           /
                                               |         |          |
                                               |         |          |
                                    Ysc -------|   v <---o          |
                                               |           b, Xsc   |
                                               |                    |
                                               |                    |
                                               |                    |
                                               |                    |
                                               |                    |
                                               ----------------------
                                                      /      \
                                                     /        \  Main Rocket Engine
                                                     ----------
                                                         |
                                                         |
                                                         |
                                                         V
             
                                                        Zsc
             
             
                       where b and Xsc   point out of the screen or page.
             
             
            The main body of the spacecraft was formed by a stack consisting of the
            lower equipment module, the propulsion module, the upper equipment module,
            and the HGA.  Attached to this stack were the remote sensing pallet, the
            fields and particles pallet, and the Huygens Probe system.  The Huygens
            Probe was built by the European Space Agency and was deployed into the
            atmosphere of Titan by the Orbiter.  Some instruments such as RADAR and some
            instrument components such as those of RPWS were attached to the upper
            equipment module.  The two equipment modules were also used for external
            mounting of the magnetometer boom and the three radioisotope thermoelectric
            generators (RTGs) which supplied the spacecraft power.  The spacecraft
            electronics bus was part of the upper equipment module and carried the
            electronics to support the spacecraft data handling, including the command
            and data subsystem and the radio frequency subsystem.  Other electronics to
            support instruments and other spacecraft functions were also carried in the
            bus.  During the inner cruise, the HGA and two Low Gain Antennas (LGAs)
            were used to transmit data and receive commands.  One of the two LGAs was
            selected when operational constraints prevented pointing the HGA towards
            the Earth.
             
            The spacecraft stood 6.8 meters (22.3 ft) high.  Its maximum diameter, the
            diameter of the HGA, was 4 meters (13.1 ft).  Therefore, the HGA could
            fully shield the rest of the spacecraft (except the deployed MAG boom and
            RPWS antennas) from sunlight when the HGA was pointed within 2.5 degrees of
            the Sun.  The dry mass of the spacecraft was 2523 kg, including the Huygens
            Probe system and the science instruments.  The best estimate of the actual
            spacecraft mass at separation from the Centaur was 5573.8 kg.  Future
            estimates of spacecraft mass were maintained by the Spacecraft Operations
            team (SCO).
             
             
            SPACECRAFT SUBSYSTEMS
            ---------------------
             
            The spacecraft comprised several subsystems, which are described briefly
            below. For more detailed information, see JPL Document D-5564.
             
            Structure Subsystem
            -------------------
             
            The Structure Subsystem (STRU) provided mechanical support and alignment
            for all flight equipment including the Huygens Probe. It also served as a
            local thermal reservoir and provided an equipotential container, an
            electrical grounding reference, RFI shielding, and protection from
            radiation and meteoroids.  The STRU consisted of the Upper Equipment Module
            (UEM) which contained the 12-bay electronics bus assembly, the instrument
            pallets, and the MAG boom, and the Lower Equipment Module (LEM), plus all
            the brackets and structure for integrating the Huygens Probe, the HGA,
            LGAs, RTGs, reaction wheels, the main rocket engines, the four RCS thruster
            clusters, and other equipment.  The STRU also included an adapter which
            supported the spacecraft on the Centaur during launch.
             
             
            Radio Frequency Subsystem
            -------------------------
             
            The Radio Frequency Subsystem (RFS) provided the telecommunications
            facilities for the spacecraft and was used as part of the radio science
            instrument.  For telecommunications, it produced an X-band carrier at 8.4
            GHz, modulated it with data received from the CDS, amplified the X-band
            carrier power to produce 20 W from the Traveling Wave Tube Amplifiers
            (TWTA), and delivered it to the Antenna Subsystem (ANT).  From ANT, RFS
            accepted X-band ground command/data signals at 7.2 GHz, demodulated them,
            and delivered the commands/data to CDS for storage and/or execution.
             
            The Ultra Stable Oscillator (USO), the Deep Space Transponder (DST), the X-
            band Traveling Wave Tube Amplifier (TWTA), and the X-band Diplexer were
            elements of the RFS which were used as part of the radio science
            instrument.  The DST could phase-lock to an X-band uplink and generate a
            coherent downlink carrier with a frequency translation adequate for
            transmission at X-, S-, or Ka-band.  The DST had the capability of
            detecting ranging modulation and of modulating the X-band downlink carrier
            with the detected ranging modulation.  Differenced one-way ranging (DOR)
            tones could also be modulated onto the downlink.  The DST could also accept
            the reference signal from the USO and generate a non-coherent downlink
            carrier.
             
             
            Propulsion Module Subsystem
            ---------------------------
             
            The Propulsion Module Subsystem (PMS) provided thrust and torque to the
            spacecraft. Under command from AACS, the thrust and torque established the
            spacecraft attitude, pointing, and the amount of velocity vector change.
             
            For attitude control, the PMS had a Reaction Control Subsystem (RCS)
            consisting of four thruster clusters mounted off the PMS core structure
            adjacent to the LEM at the base of the spacecraft. Each of the clusters
            contained 4 hydrazine thrusters. The thrusters were oriented to provide
            thrust along the spacecraft +/-Y and -Z axes. RCS thrusters also provide DV
            for small maneuvers.
             
            For larger DVs, the PMS had a primary and redundant pressure-regulated main
            rocket engine.  Each engine was capable of a thrust of approximately 445 N
            when regulated. The bipropellant main engines burned nitrogen tetroxide
            (N2O4) and monomethylhydrazine (N2H3CH3) producing an expected specific
            impulse of up to 308s. These engines were gimbaled so when under AACS
            control during burns the thrust vector could be maintained through the
            shifting center of mass of the spacecraft. AACS-provided valve drivers for
            all the engines/thrusters operated in response to commands received from
            AACS via the CDS data bus.
             
             
            Power and Pyrotechnics Subsystem
            --------------------------------
             
             
             The Power and Pyrotechnics Subsystem (PPS) provided regulated electrical
             power from three RTGs on command from CDS to spacecraft users at 30 Volts
             DC, distributed over a power bus.  In addition, PPS provided power to the
             various pyrotechnic devices on command from CDS.  PPS disposed of excess
             power by heat radiation to space via a resistance shunt radiator.
             Measurements of the output of the radioisotope thermoelectric generators
             indicated a beginning-of- life power of 876 +/- 6 Watts, 740 Watts at SOI,
             and 692 Watts at end of mission.  These estimates were at least 30 Watts
             above pre-launch predictions.
             
             
            Command and Data Subsystem
            --------------------------
             
            The Command and Data Subsystem (CDS) received the uplink command stream via
            the RFS and decoded it.  The stream included timing (immediate or
            sequence), routing, action, and parameter information.  The CDS then
            distributed commands designated for other subsystems or instruments,
            executed those commands which were decoded as CDS commands, and stored
            sequence commands for later execution.
             
            The Cassini spacecraft included two identical Solid State Recorders (SSRs).
            Each CDS (A and B) was attached to the two SSRs such that each CDS could
            communicate (read, write) with only one SSR at any one time. The Mission
            and Science Operations Office had the capability to control how the SSR
            attachments were configured via immediate command or a stored sequence.
            Under fault response conditions flight software (FSW) could switch an SSR
            attachment from CDS A to CDS B.
             
            The CDS received data from other on-board subsystems via the data bus, then
            processed and formatted them for telemetry and delivered them to RFS for
            transmission to Earth.  Each subsystem interfaced with the data bus through
            a standard Bus Interface Unit (BIU) or a Remote Engineering Unit (REU).
            Data were collected in 8800 bit frames, and Reed-Solomon Encoded on
            downlink.  A 32 framesync marker along with the encoding increased these
            frames to 10,112 bits.
             
            CDS software contained algorithms that provided protection for the
            spacecraft and the mission in the event of a fault.  Fault protection
            software ensured that, in the case of a serious fault, the spacecraft would
            be placed into a safe, stable, commandable state (without ground
            intervention) for a period of at least two weeks to give the mission
            operations team time to solve the problem and send the spacecraft a new
            command sequence.  It was also capable of autonomously responding to a
            predefined set of faults needing immediate action.
             
             
            Attitude and Articulation Control Subsystem
            -------------------------------------------
             
            The Attitude and Articulation Control Subsystem (AACS) provided dynamic
            control of the spacecraft in rotation and translation. It provided fixed-
            target staring for HGA and remote sensing pointing and performed target
            relative pointing using inertial vector propagation as well as repetitive
            subroutines such as scans and mosaics. AACS also controlled actuators for
            the main rocket engine gimbals. Rotational motion during the Saturn tour
            that required high pointing stability was normally controlled by the three
            main Reaction Wheel Assemblies (RWAs), although modes requiring faster
            rates or accelerations may have used thrusters. The additional fourth
            reaction wheel could articulate to replace any single failed wheel.
             
            AACS contained a suite of sensors that included redundant Sun Sensor
            Assemblies (SSA), redundant Stellar Reference Units (SRU, also called star
            trackers), a Z-axis accelerometer, and two 3-axis gyro Inertial Reference
            Units (IRU).  Each IRU consisted of four gyros, three orthogonal to each
            other and the fourth skewed equidistant to the other three.
             
             
            Temperature Control Subsystem
            -----------------------------
             
            The TEMPerature control subsystem (TEMP) allowed operations over the
            expected solar ranges (0.61 to 10.1 AU) with some operational constraints.
            Temperatures of the various parts of the spacecraft were kept within
            allowable limits by a large number of local TEMP thermal control
            techniques, many of which were passive.  The 12-bay electronics bus had
            automatically positioned reflective louvers.  Radio Isotope Heater Units
            (RHU) were used where constant heat input rates were needed and where
            radiation was not a problem.  Multilayer insulation blankets covered much
            of the spacecraft and its equipment.
             
            Electric heaters were used in different locations and operated by CDS and
            instruments.  Temperature sensors were located at many sites on the
            spacecraft, and their measurements were used by CDS to command the TEMP
            heaters.  Shading was executed by pointing the HGA (-Z axis) towards the
            sun; the HGA was large enough to provide shade for the entire spacecraft
            body including the Huygens Probe.
             
             
            Mechanical Devices Subsystem
            ----------------------------
             
            The mechanical devices subsystem provided a pyrotechnic separation device
            used to separate the spacecraft from the launch vehicle adapter.  Springs
            provided the impulse to separate the spacecraft from the adapter.  The
            mechanical devices subsystem also provided a self-deploying 10.5 meter
            coiled longeron mast stored in a canister for the two magnetometers,
            electrostatic discharge covers over inflight separation connectors, an
            articulation system for the backup reaction wheel assembly, a "pinpuller"
            for the RPWS Langmuir Probe, and louvers and variable RHUs for temperature
            control.
             
             
            Electronic Packaging Subsystem
            ------------------------------
             
            The Electronic Packaging Subsystem (EPS) consisted of the electronics
            packaging for most of the spacecraft in the form of the 12-bay electronics
            bus.  The bus was made up of bays containing standardized, dual-shear plate
            electronics modules.
             
             
            Solid State Recorder Subsystem
            ------------------------------
             
            The two Solid State Recorders (SSRs) were the primary memory storage
            and retrieval devices used on the orbiter.  Each SSR contained 128
            submodules, of which 8 were used for flight software and 120 were used for
            telemetry.  Each submodule could hold 16,777,200 bits for data, so the
            total data storage for telemetry on each SSR was 2.013 Gbits.  Expressed in
            terms of 8800-bit telemetry frames, this was 228,780 frames per SSR.
             
            Spacecraft telemetry and AACS, CDS, and instrument memory loads were stored
            in separate files called partitions.  All data recorded to and played back
            from the SSR was handled by the CDS. There were three different SSR
            functional modes: Read-Write to End, Circular FIFO, and Ring Buffer.  There
            was also a record pointer and a playback pointer, which marked the memory
            addresses at which the SSR could write or read.  In Read-Write to End,
            there was a logical beginning and end to the SSR.  Recording began at this
            logical beginning and continued until either the SSR was reset (the record
            and playback pointers were returned to the logical beginning) or until the
            record pointer reached the end.  If the record pointer did not reach the
            end, recording was halted until the SSR was reset.  In Circular FIFO, there
            was no logical end to the SSR.  The data was continuously recorded until
            the record pointer reached the playback pointer.  The Ring Buffer mode
            behavior was similar to the Circular FIFO except that recording did not
            stop if the record pointer reached the playback pointer.
             
             
            Antenna Subsystem
            -----------------
             
            The ANTenna subsystem (ANT) provided a directional high gain antenna (HGA)
            with X-, Ka-, S and Ku-band for transmitting and receiving on all four
            bands.  Because of its narrow halfpower beam width of 0.14 deg for Ka-band,
            it had to be accurately pointed.  The HGA, and the low gain antenna 1
            (LGA1) located on the HGA feed structure, were provided by the Italian
            Space Agency.  Another LGA (LGA2) was located below the Probe pointing in
            the -X direction.  During the inner solar system cruise, the HGA was Sun-
            pointed to provide shade for the spacecraft.  ANT provided two LGAs which
            allowed one or the other to receive/transmit X-band from/to the Earth when
            the spacecraft was Sun-pointed.  The LGAs also provided an emergency
            uplink/downlink capability while Cassini was at Saturn.  The HGA downlink
            gain at X-band was 47dBi and the LGA1 peak downlink gain was 8.9 dBi.  The
            X-band TWTA power was 20 watts.
             
             
            ORBITER SCIENCE INSTRUMENTS
            ---------------------------
             
             There were 12 science instrument subsystems on the Cassini spacecraft,
             listed immediately below with their acronyms, then described in more
             detail in the following paragraphs.  Three of the instruments (CAPS, CDA,
             and MIMI/LEMMS) were capable of commanded articulation relative to the
             spacecraft.
             
             
                      Cassini Plasma Spectrometer               CAPS
                      Cosmic Dust Analyzer                      CDA
                      Composite Infrared Spectrometer           CIRS
                      Ion and Neutral Mass Spectrometer         INMS
                      Imaging Science Subsystem                 ISS
                      Magnetometer                              MAG
                      Magnetospheric Imaging Instrument         MIMI
                      Cassini RADAR                             RADAR
                      Radio and Plasma Wave Science             RPWS
                      Radio Science Subsystem                   RSS
                      Ultraviolet Imaging Spectrograph          UVIS
                      Visible and Infrared Mapping Spectrometer VIMS
             
             
            Cassini Plasma Spectrometer (CAPS): The CAPS instrument was designed to
            perform an in-situ study of plasma within and near the magnetosphere of
            Saturn.  Specific science and measurement objectives were:
             
            1) Orbital Tour Observing Objectives:
               a)   Near continuous survey.
               b)   MAPS Campaigns.
               c)   SOI, targeted Titan and icy satellite observations.
               d)   CAPS Magnetospheric Survey.

            2) Solar Wind/Aurora Campaign Objectives:
               a)   Measure solar wind while ORS observed aurora.
               b)   Unambiguous measurements of unperturbed solar wind, correlation
                    with Earth based and RPW auroral data.

            3) Study microphysical and rapidly varying processes near the bow shock and
               magnetopause.

            4) Observe particle acceleration, particle injection, and dynamical events
               (e.g.  substorms) in the magnetotail.

            5) Measure vertical (field aligned) structure of plasma in the inner
               magnetosphere.

            6) Observe the dynamics and microphysics of the auroral and Saturn
               Kilometric Radiation (SKR) source regions.

            7) Study the Titan plasma torus and distant signatures of the
               interaction of Titan with the magnetosphere.

            8) Study the distant signatures of satellites and ring interactions with
               the magnetosphere.
             
             
            Cosmic Dust Analyzer (CDA): The CDA instrument was designed to perform an
            in- situ study of dust grains in the Saturn system.  Specific science and
            measurement objectives were:
             
            1) Study interplanetary and interstellar dust at Saturn.

            2) Saturn Rings Objectives:
                a)    Map size distribution.
                b)    Search for particles in the so-called  clear zone (F/G ring).
                c)    Determine orbits of particles to identify their possible parents.
                d)    Study the interaction between the E ring and magnetosphere of Saturn
                e)    Distinguish temporal and spatial effects.
                f)    Analyze eccentricity and inclination of dust orbits
                      independently.

            3) Icy Satellites Objectives:
                a)    Interaction with the ring system.
                b)    Role of satellites as a source and sink for ring particles.
                c)    Chemical composition of satellites (dust atmospheres).
             
             
            Composite Infrared Spectrometer (CIRS): The CIRS instrument was designed to
            perform spectral mapping to study temperature and composition of surfaces,
            atmospheres, and rings within the Saturn system.  Specific science and
            measurement objectives were:
             
            1) Thermal Structure Objectives:
               a)   Vertical profiles of atmospheric temperature.
               b)   Maps of atmospheric and surface temperatures.
               c)   Aerosol opacities.
               d)   Thermal inertia of surfaces.
               e)   Subsurface regolith structure.
               f)   Ring particle sizes.
               g)   Ring thermal structure.

            2) Composition Objectives:
               a)   Spatial distribution of atmospheric gases.
               b)   Surfaces.
               c)   Ring material.

            3) Atmosphere Objectives:
               a)   Circulation:  Zonal jets, Meridional motion, vortices, wave,
                    convection.
               b)   Composition:  Dis-equilibrium species, elemental and isotope
                    abundances and distribution, ortho/para ratio, condensable
                    gases, external sources (e.g., rings).
               c)   Clouds/Aerosols:  Composition, microphysical properties, spatial
                    and temporal distribution.
               d)   Atmospheric.  Structure:  Temperature, pressure, density, vertical
                    distribution of major constituents.
               e)   Internal Structure:  He abundance, internal heat, gravity.
               f)   Aurora, lighting, airglow:  Spatial and temporal distribution,
                    special properties.
               g)   Titan:  Aerosols and clouds, Titan winds.

            4) Rings Objectives:
               a)   Vertical structure and thermal gradient.
               b)   Vertical Dynamics.
               c)   Particle Surface Properties.
               d)   Particle Composition.
               e)   Radial Structure.

            5) Non-Targeted Icy Satellites Objectives:
               a)   Determine surface composition.
               b)   Determine vertical thermal structure (Greenhouse).
               c)   Determine thermophysical properties (Thermal Inertia).
               d)   Search for active thermal sources (space and time).
             
             
            Ion and Neutral Mass Spectrometer (INMS): The INMS instrument was designed
            to perform an in-situ study of the compositions of neutral and charged
            particles within the Saturn magnetosphere.  Specific science and
            measurement objectives were:
             
            1) Outer Magnetosphere: Science Objectives:
               a)   Neutral and ion composition of the magnetosphere.
               b)   Composition of the Titan plasma torus.
               c)   Additional low energy ion distribution function information to
                    complement CAPS.

            2) Inner Magnetosphere: Science Objectives:
               a)   Studies of solar system formation.  Plasma sources derived from
                    the rings and icy satellites - composition and isotopic ratio.
               b)   Studies of plasma transport.  Determination of plasma transport
                    velocities and determination of momentum transfer from charge
                    exchange chemistry - water products.
             
             
            Imaging Science Subsystem (ISS): The ISS instrument was designed to perform
            multispectral imaging of Saturn, Titan, rings, and icy satellites to
            observe their properties.  Specific science and measurement objectives
            were:
             
            1) Motions and Dynamics:
               a)   Basic flow regime (Titan).
               b)   Poleward flux of momentum.
               c)   Poleward flux of heat (with CIRS).
               d)   Life cycles and small-scale dynamics of eddies.
               e)   Radiative heating for dynamical studies.

            2) Clouds and Aerosols:
               a)   Could and haze stratigraphy (strongly couples with wind studies).
               b)   Particle optical properties.
               c)   Particle physical properties.
               d)   Auroral processes and particle formation.
               e)   Haze microphysical models.

            3) Lightning (related to water clouds on Saturn; we do not know what to 
               expect for Titan).

            4) Auroras (H and H2 emissions on Saturn, N and N2 emissions on Titan).

            5) ISS High Priority Rings Goals:
               a)   Ring Architecture/Evolution:  Azimuthal, radial, temporal
                    variations across tour.
               b)   New satellites: orbits, masses/densities, effects on rings;
                    complete inventory of inner moons of Saturn.
               c)   Search and characterize material potentially hazardous to Cassini:
                    diffuse rings, arcs, Hill sphere material, etc.
               d)   Orbit refinement of known satellites; temporal variations;
                    resonant effects.
               e)   Particle/Disk properties: vertical disk structure; particle
                    physical properties and size distribution; variations across disk.
               f)   Spokes: Formation timescales/process; periodic variations.
               g)   Diffuse Rings (E, G): Structure, characterize particle properties.
             
             
            Magnetometer (MAG): The MAG instrument was designed to study the magnetic
            field of Saturn and its interactions with the solar wind.  Specific science
            and measurement objectives were:
             
            1) Intrinsic magnetic fields of Saturn and its moons:
               a)   Determine the multiple moments of dynamo-driven
                    magnetic field of Saturn
               b)   Determine weather Titan has an internal field due to dynamo action,
                    electromagnetic induction or even remnant magnetization in a 
                    so-called  dirty ice  crust.
               c)   Search for possible evidence of ancient dynamos and crustal
                    remnants in the icy satellites.

            2) Derive a 3-D global model of the magnetospheric magnetic field.

            3) Establish the relative contributions to electromagnetic and mechanical
               stress balance.

            4) Identify the energy source for dynamical processes (rotationally driven,
               solar wind driven, or other).

            5) Characterize the phenomena of the distant dayside/flank planetary
               environment.

            6) Survey satellite/dust/ring/torus electromagnetic interactions.

            7) Determine tail structure and dynamic processes therein.

            8) Establish nature and source of all ULF wave sources.

            9) Magnetosphere/ionosphere coupling.

            10) Titan:
                a)   Determine the internal magnetic field sources of Titan as well as
                     the sources external to I I - thereby determining the interaction
                     type.
                b)   Determine all Titan-plasma flow interactions (magnetosphere,
                     magnetosheath, solar wind).
                c)   Determine the variation of the Titan-magnetosphere interaction
                     with respect to Titan orbital phase.
                d)   Determine the nature of the low frequency wave (ion
                     cyclotron/hydromagnetic) spectrum of the near-Titan plasma
                     environment.

            11) Icy Satellites:
                a)   Search for possible evidence of ancient dynamos and crustal
                     remanence in the icy satellites
                b)   Investigate icy satellite plasma environments.
             
             
            Magnetospheric Imaging Instrument (MIMI): MIMI was designed for global
            magnetospheric imaging and in-situ measurements of the  magnetosphere
            of Saturn and solar wind interactions.  Specific science and measurement
            objectives were:
             
            1) MIMI Survey:
               a)   What is the source of energetic particles in the magnetosphere
                    of Saturn and how are they energized?
               b)   To what extent does the solar wind and rotation regulate the size,
                    shape and dynamics of the magnetosphere of Saturn; are there 
                    Earth-like storms and substorms?
               c)   How does the interaction between the magnetospheric particle
                    population and Saturn cause the aurora, and affect magnetospheric
                    and upper atmospheric processes?
               d)   How does the distribution of satellites affect global
                    magnetospheric morphology and processes?

            2) MIMI Campaigns:
               a)   How do satellites and their exospheres affect local magnetospheric
                    plasma flow and contribute to energetic particle populations?
               b)   What particles (species, energy) cause Saturnian aurora; what
                    processes accelerate them and what is the exospheric response?
               c)   What unique role do the rings of Saturn play in controlling the
                    structure, composition, and transport of the inner magnetosphere?
             
             
            Cassini RADAR (RADAR): The RADAR instrument was designed for synthetic
            aperture RADAR (SAR) imaging, altimetry, and radiometry of the surface
            of Titan. Specific science objectives for the Cassini mission were as 
            follows.
             
            1) Rings:
               a)   Determine scattering properties of rings.
               b)   Determine ring global properties.
               c)   Determine additional thermal and compositional properties of rings.
               d)   Extended ring global properties: low-elevation measurements.
               e)   Radial scans through optically thin rings (E, F and G).
               f)   Identify thermal component.

            2) Catalog of base radar/radiometric properties each satellite and their
               degree of global variation.
             
             
            Radio and Plasma Wave Science (RPWS): The RPWS instrument was designed to
            study plasma waves, radio emissions, and dust in the Saturn system.
            Specific science and measurement objectives were:
             
            1) Aurora and SKR: Obtain radio and plasma wave data which provide
               information on the SKR source and plasma waves on auroral field lines.

            2) Satellite and ring interactions: Measure dust flux, look for effects of
               selective absorption of electrons and ions near rings (thermal
               anisotropy), multi-ion wave particle interactions, satellite torii.

            3) Inner Magnetosphere: Wave particle interactions via ULF waves; Stability
               of trapped electrons and relation to whistler-mode emissions;
               ECH (N+ 1/2)fce waves trapped near the equatorial region and heating of
               cool electrons.

            4) Titan Interactions: Multi-ion species wave-particle interactions;
               Evidence of Titan plumes/detached plasma blobs.

            5) Magnetospheric Boundaries: Nature of the Saturnian Bow shock: Look for
               the signatures of waves accelerating electrons.

            6) What is the nature of the magnetotail of Saturn?  Are there substorms or
               other dynamical processes there?

            7) Observe lightning via SED and whistlers from the atmosphere of Saturn
               (and possibly Titan).

            8) Determine the equatorial dust flux and scale height as a function of
               radial distance.

            9) Provides for mapping and synoptic measurements required for the RPWS
               portion of the magnetospheric survey.

            10) Search for electromagnetic phenomena which may be triggers of ring
                spokes.
             
             
            Radio Science Subsystem (RSS): The RSS was designed to study atmospheres
            and ionospheres of Saturn, Titan, rings, and gravity fields of Saturn and
            its satellites (also, search for gravitational waves during cruise).
            Specific science and measurement objectives were:
             
            1) Ring Occultations:
               a)   To profile radial ring structure with resolution less than or equal
                    to 100m; characterize structure variability with azimuth, wavelength,
                    ring-opening-angle, and time.
               b)   To determine the physical particle properties (size distribution,
                    bulk density, surface density, thickness, viscosity).
               c)   To study ring kinematics and dynamics (morphology, interaction with
                    embedded and exterior satellites), and to investigate ring origin
                    and evolution.

            2) Atmospheric Occultations:
               a)   To determine the global fields of temperature, pressure, and zonal
                    winds in the stratosphere and troposphere of Saturn.
               b)   To determine the small scale structure due to eddies and waves.
               c)   To determine the latitudinal variations of NH3 abundance in
                    the atmosphere of Saturn.
               d)   To improve the knowledge of H2/He ratio in the troposphere
                    of Saturn (RSS+CIRS).

            3) Ionospheric Occultations:
               a)   To determine the vertical profiles of the electron density in
                    the terminator ionosphere of Saturn, and its variability with 
                    latitude.
               b)   To investigate interaction of the ionosphere with the
                    magnetosphere and rings of Saturn.

            4) Gravity Field of Saturn:
               a)   To determine the mass of Saturn and zonal harmonic coefficients of
                    its gravity field to at least degree 6 (J2, J4, J6).
               b)   To constrain models of the interior of Saturn based on the results

            5) Gravity Field and Occultation of Untargeted Satellites:
               a)   To determine the masses of Mimas, Tethys, Dione, Hyperion, and
                    Phoebe.
               b)   To search for a possible tenuous ionosphere around any occulted
                    satellites (a la Europa and Callisto).
             
             
            Ultraviolet Imaging Spectrograph (UVIS): The UVIS instrument was designed
            to produce spatial UV maps, map ring radial structure, and to determine
            hydrogen/deuterium ratios.  Specific science and measurement objectives
            were:
             
            1) Saturn System Scans:
               a)   EUV and FUV low resolution spectra of magnetosphere neutral and ion
                    emissions.
               b)   System scans at every apoapsis.

            2) Satellites:
               a)   Latitude, longitude and phase coverage coordinated through SSWG.
               b)   Distant stellar occultations to determine satellite orbits and
                    Saturn reference frame.

            3) Atmosphere:
               a)   Vertical profiles of H, H2, hydrocarbons, temp in exo,
                    thermosphere.
               b)   Long integrations map of hydrocarbons, airglow.
               c)   Map emissions with highest resolution at the limb.
               d)   Auroral Map:  H and H2 emissions over several rotations.

            4) Ring Stellar Occultation Objectives:
               a)   Highest Radial resolution (20m) structure of rings
               b)   Discovery and precise characterization of dynamical features
                    generated by ring-satellite interactions.
                         - Density waves and bending waves.
                         - Edge waves and ring shepherding.
                         - Embedded moonlets and discovery of new moons from
                           dynamical response in rings.
               c)   Discovery and precise characterization of azimuthal structure in
                    rings.
                         - Eccentric rings.
                         - Density waves and edge waves.
                         - Small-scale self-gravitational clumping in rings.
               d)   Measure temporal variability in ring structure.
               e)   Simultaneously measure UV reflectance spectrum of rings.
                         - Determine microstructure on particle surfaces.
                         - Compositional information on ring particles.
               f)   Measure size distribution of large particles through occultation
                    statistics.
               g)   Measure dust abundance in diffraction aureole.
               h)   Simultaneously search for flashes from 0.1 m - 1.0 m meteoroid
                    impacts.
             
             
            Visible and Infrared Mapping Spectrometer (VIMS): The VIMS instrument was
            designed to produce spectral maps to study the composition and structure of
            surfaces, atmospheres, and rings.  Specific science and measurement
            objectives were:
             
            1) Ring Observation:
               a)   Determine ring composition and its spatial variations.
               b)   Determine light scattering behavior of rings as a function of I, e,
                    and alpha.
               c)   Constrain sizes and surface textures of ring particles.
               d)   Establish optical depth profile of rings as a function of
                    wavelength, incidence angle, and longitude.
               e)   Characterize variable features such as non-circular ringlets,
                    F ring, spokes, etc., and their evolution.
               f)   Ring moon compositions.

            2) Icy Satellite Observation:
               a)   Measure UV and NIR spectra to:
                           - Identify and map surface materials at the highest spatial
                             resolution.
                           - Determine microphysical surface properties.
                           - Provide data on energy balance.
             
             
              Instrument Host Overview - DSN
              ================================

            Radio Science investigations utilized instrumentation with
            elements both on the spacecraft and at the NASA Deep Space Network
            (DSN).  Much of this was shared equipment, being used for routine
            telecommunications as well as for Radio Science.
             
            The Deep Space Network was a telecommunications facility managed by
            the Jet Propulsion Laboratory of the California Institute of
            Technology for the U.S.  National Aeronautics and Space
            Administration.
             
            The primary function of the DSN was to provide two-way communications
            between the Earth and spacecraft exploring the solar system.  To carry
            out this function the DSN was equipped with high-power transmitters,
            low-noise amplifiers and receivers, and appropriate monitoring and
            control systems.
             
            The DSN consisted of three complexes situated at approximately equally
            spaced longitudinal intervals around the globe at Goldstone (near
            Barstow, California), Robledo (near Madrid, Spain), and Tidbinbilla
            (near Canberra, Australia).  Two of the complexes were located in the
            northern hemisphere while the third was in the southern hemisphere.
             
            The network comprised four subnets, each of which included one antenna
            at each complex.  The four subnets were defined according to the
            properties of their respective antennas: 70-m diameter, standard 34-m
            diameter, high-efficiency 34-m diameter, and 26-m diameter.
             
            These DSN complexes, in conjunction with telecommunications subsystems
            onboard planetary spacecraft, constituted the major elements of
            instrumentation for radio science investigations.
             
        