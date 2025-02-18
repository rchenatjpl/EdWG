                        
                                   
      Instrument Overview                      
      ===================                      
      The Alpha Particle X-Ray Spectrometer (APXS) is an instrument 
      that will provide information on the elemental composition of 
      the comet surface. The instrument is based on the interaction 
      of alpha particles and x-rays with matter. It operates in two 
      modes: the alpha mode (Rutherford backscattering) and the 
      x-ray mode for alpha-particle and x-ray induced x-ray 
      spectroscopy. The APXS combines these methods in one single 
      instrument while being low in mass and power consumption.
      Historically, there was also a proton mode that has been 
      omitted in the new design in favor of an advanced x-ray mode.
      The acronym APXS stands for the old and new design. Using 
      the x-ray mode, the Rosetta APXS is able to determine in-situ 
      concentrations of elements from sodium to strontium at levels 
      down to several hundred ppm. Light elements such as carbon, 
      nitrogen and oxygen can be detected using the alpha mode, 
      usually with sensitivity of 1 atom %. In addition, most of the
      elements are determined by both modes, albeit with different 
      efficiency and accuracy. Hydrogen(and helium) cannot be 
      measured at all by nature of the methods, although, water can
      still be inferred from any excess of oxygen (which APXS 
      determines accurately) over what is required from the overall
      stoichiometry (assuming no other light elements in the 
      sample). The Rosetta APXS consists of a sensor head, a 
      deployment device and electronics. The sensor head contains 
      Curium-244 alpha sources (with an activity of about 40 mCi at 
      integration time and with a half-life of 18.11 years) that 
      bombard the sample with alpha particles of an energy of about
      5.5MeV and x-rays of about 14 to 21 keV (emitted by the 
      Plutonium-240 daughter). The back-scattered alpha particles 
      are measured by six alpha detectors and the x-ray radiation by
      one high-resolution x-ray detector (energy resolution, 
      measured as full width at half maximum (FWHM), is 180 eV at 
      6.4 keV at temperatures below -40degC).          
                                     
                                     
      Scientific Objectives                      
      =====================                      
      The goal of the Rosetta APXS experiment is to determine the 
      chemical composition of the cometary surface at the landing 
      site and its potential alteration with time due to increase 
      activity when the comet approaches the Sun. The data obtained 
      will be used to characterize the surface of the comet, to 
      obtain the gas/dust ratio, determine the chemical composition 
      of the dust component, and to compare the dust with the 
      composition of known meteorite types. These results will be 
      brought into context with other measurements made on the 
      lander and the orbiter to fully obtain a more complete picture
      of the present state of the comet, and to get insight into its
      evolution and origin.               
                                     
                                     
      Calibration                          
      ===========                          
      In the laboratory, the instrument was calibrated in vacuum 
      measuring a geological sample, called SSK-1 (already used for 
      the MPF (Mars Pathfinder Rover Sojourner) and MER (Mars 
      Exploration Rover) APXS) with known composition in a standard 
      geometry (distance between sample surface and detector). The 
      data from this sample are used to compare the performance and
      sensitivity of the Rosetta APXS with MPF APXS and MER APXS. 
      This cross calibration mainly determines the energy scale, the
      detector efficiency and the quality of the alpha and the x-ray 
      spectra ( endpoint sharpness in the alpha mode and FWHM of the 
      x-ray lines in the x-ray mode). Using these instrument 
      specific properties, the calibration of the Rosetta APXS can 
      be achieved using the extensive MER calibration and future new
      calibration measurements tailored to cometary samples.  
                                     
                                     
      Operational Considerations                   
      ========================== 
      The APXS can store the current XRAM content if it is 
      continuously powered with 5V on the KAL line. When it is 
      powered OFF, the content gets lost and is restored with the 
      PROM default values after the next power ON.
      Please note that after power ON, those values have to be 
      uploaded if values different from the default ones need to be
      used. That is necessary for example in the case of changing 
      the threshold in order to obtain response for low energies and
      in the case of the safe LG parameter to operate the deployment 
      of the deployment device.
      Due to problems observed in previous payload checkouts and for 
      security, the command for downloading the relevant spectra 
      will be sent twice. In that way we assure that even in the 
      case we may have some error with the download of the spectra, 
      the probability of losing important science will be 
      substantially reduced
  
                                     
      Detectors                            
      =========                            
      Silicon drift detector for x-ray detection.
      6 alpha solid state silicon detectors.
                                     
                                     
      Electronics                          
      ===========                          
      Details on the electronics of the instrument are described in 
      the APXS ADP.                         
  
                                     
      Location                             
      ========                             
      The sensor head is located on the outside of the lander, 
      mounted in an opening of the balcony's floor. To bring the 
      APXS in contact with the comet surface, it is moved by the
      deployment device that can lower and raise the sensor head by 
      a command.                       
      
                                   
      Operational Modes                        
      =================                        
      Normal mode - used to obtain energy spectra and during data 
      transmission.
      Deployment mode - used to operate the deployment device.
          
                             
      Subsystems                           
      ==========                           
      Not applicable
                                     
                                     
      Measured Parameters                      
      ===================                      
      Counts vs. energy spectra. 512 channels (1 to 14.5 KeV) for 
      the X-ray mode and 256 channels (0.6 to 6 MeV) for the Alpha
      mode.