

            The Waves instrument consists of one electric dipole antenna, one magnetic
            search coil, two pre-amplifiers, three receivers, and a digital processing
            unit.  Taken together these components can detect and digitize wave electric
            fields from 50 Hz to 45.25 MHz and wave magnetic fields from 50 Hz to 20
            kHz.  At the highest duty cycle, Waves can record one sweep per second
            across all spectral bands while simultaneously capturing 5 waveforms in
            various bands.
            
            Electric fields are detected via an electric dipole antenna deployed from
            the aft flight deck in a 'V' configuration with a tip-tip length of about 4
            meters.  The signal from the electric antenna is conditioned in the electric
            preamplifier which has three frequency bands and each band has an attenuator
            that can be selected or not, to limit the input to the receivers under 
            strong signal conditions.  When enabled attenuations are 25.3 dB, 25.3 dB, 
            and 19.0 dB for the 50 Hz - 20 kHz, 10 kHz - 150 kHz and 100 kHz - 45 MHz
            bands respectively.  Wave magnetic components, are detected via a magnetic
            search coil which is also mounted to the aft flight deck.  The signals from
            the search coil are conditioned by a magnetic preamplifier located close to
            the sensor, but within the spacecraft thermal environment.
            
            The instrument includes three receivers to detect signals from the sensors.
            The first is a 3-channel low frequency receiver (LFR) that is used to
            analyze plasma waves.  Two channels measure electric fields in the frequency
            ranges of 50 Hz to 20 kHz and 10 to 150 kHz, and one channel measures
            magnetic fields in the range of 50 Hz to 20 kHz.  The electric channels
            include an attenuator that may be toggled either on or off by the automatic
            gain control software in the data processing unit.  When on signals are
            attenuated by 19.8 dB (low-band) and 19.4 dB (high-band) in addition to any
            attenuation by the electric preamp.  All 3 LFR channels are sampled
            simultaneously.  This receiver produces a digitized waveform from each
            channel which is either sent directly to the ground (after compression) in
            burst mode or spectrum analyzed in the Waves digital signal processor to
            produce spectra with ~ 10 logarithmically-spaced channels per decade of
            frequency.
            
            The LFR also has a noise input from the spacecraft power distribution unit
            (PDDU).  By subtracting this noise channel from the channel from either
            antenna, a noise cancellation process can be carried out. Based on in-flight
            experience, there is insufficient spacecraft noise as determined from the
            line from the PDDU to merit this additional processing; this will be
            re-evaluated at Jupiter.
            
            Waves also contains two nearly identical high frequency receivers, HFR-44
            and HFR-45.  (The numeric suffix is just a tracking ID and bares no
            relationship to frequency.)  Each receiver contains three channels.  A
            baseband channel, which handles measurements in the 0.1 to 3 MHz band, a
            down-mixed log response channel for sweep frequency operations in the 3 MHz
            to 41 MHz range, and a paired-mixer channel covering the 3 MHz to 45.25 MHz
            range for acquiring high frequency resolution spectra near the electron
            cyclotron frequency.  To provide additional support for handling large
            amplitude signals, each HFR has a front-end 32 dB step-attenuator that may
            be set to add further attenuation to incoming signals, in 2 dB steps.  The
            operation of the step-attenuators is handled automatically by the Waves
            digital signal processing unit.
            
            The HFR baseband channel operates much as the LFR, though waveforms are
            digitized at the much higher rate of 7 Msps.  Like the LFR, HFR baseband
            samples may be sent out 'as-is' (with compression) in burst mode or sent to
            the digital signal processor for conversion to spectra in survey made.
            
            The HFR down-mixed log response channel operates quite differently.
            Incoming signals are mixed with a locally generated pure sine wave.  The
            result is then low-pass filtered below 500 kHz.  Due to the low pass filter,
            only frequency components within 500 kHz of the of local mixer frequency
            contribute to the output signal power.  This down-mixed signal is directed
            to a log-amplifier which produces an output voltage proportional to the
            logarithm of the energy in the band, which is then digitized at 8-bit
            resolution.  Measurements are taken as in a classic swept frequency
            receiver.  The mixer signal is set to 3.5 MHz and then incremented in 1 MHz
            steps ending at 40.5 MHz, thus producing successive measurements of spectral
            density in 1 MHz bands from 3 MHz to 41 MHz.  This channel is used 
            exclusively for generating survey mode data.
            
            The HFR paired-mixer channel shares components with the log response channel
            but feeds incoming signals to two frequency mixers instead of just one.
            Both mixers are set to the same mixing frequency, but for one mixer, the
            local tone is 90 degrees out of phase with the other.  As with the log
            response channel, the mixer output is low-pass filtered below 500 kHz and 
            the two resulting down-mixed signals are digitized at 1.3125 MHz and
            transmitted to the ground for further processing into high resolution 1 MHz
            bandwidth spectra, details of the processing steps are outlined in Appendix
            C of VOLSIS.HTM.  The purpose for collecting high resolution measurements
            far above the baseband is to examine detailed structure near the electron
            cyclotron frequency, so instead of merely sweeping the receiver across all
            bands in a regular cadence, the mixer tone is either commanded to a
            particular frequency or set to automatically track Fce using measurements
            provided by the MAG instrument on-board.  The mixer frequency can be set
            between 3.5 and 44.75 MHz in 0.25 MHz steps, which allows for 1 MHz spectra
            covering the range of 3 MHz to 45.25 MHz.  In cases where Fce drops below
            3 MHz the HFR baseband channel is used for data collection and the mixers
            are disabled.  
            
            The Waves digital signal processing unit is implemented in a field-
            programmable gate array.  This unit handles all measurement scheduling,
            automatically controls receiver attenuators, provides facilities for
            converting digitized waveforms to spectra, provides loss-less Rice
            compression, and handles communications with the Juno spacecraft command
            and data system.

        