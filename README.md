## Design-and-simulation-of-Shunt-Hybrid-Active-Power-Filter-to-reduce-harmonics-on-AC-side

**Pre-Requisites:**(specifically the student who wnats use this project as your academic major project should have these)

  1.A good knowlwdge on POWER SYSTEMS subject.
  
  2.Control systems where you should know about P,PI,PID controllers.
  
  3.Proper knowledge on Converters, Inverters and particularly about Voltage Source Invertsters and their types.
  
  4.Basic usage of MATLAB/Simulink.
  
  5.Having good knowledge on POWER FILTERS will be an added advantage.
  
**Project Overview**
  
  This project involves the **design and simulation of a Shunt Hybrid Active Power Filter (SHAPF)** to reduce harmonics on the AC side caused by **non-linear loads**. The system aims to improve power quality by combining passive filtering with active compensation techniques.
  Although active power filter implemented with three-phase four-leg voltage-source inverters (4L-VSI) have already been presented with the techical literature , the primary contrubution of this paper is a predictive control algorithm designed and implemented specifically for this application. Treditionally , active power filters have been controlling using pre-tuned controllers , sunch as PI-type or adaptive, for the current as well as for dc-voltage loops.
    PI controllers must be designed based on the equivalent linear model, while predictive model obtained using predictive controllers improves the performance of the active power filter, especially during transient operting conditions, because it can quickly follow the current-refernsce signal while maintaining a constant dc-voltage.
    This paper presents the methematical model of the 4L-VSI and the principles of operation of the proposed predictive control scheme, including the design provedure. The complete description of each component can be found within this page.

**Objectives**
  
  a.The objectives and functions of active power filters have expanded from reactive power compentation, voltage regulation, etc. to harmonic isolation between utilities and consumers,and harmonic damping throughtout the distribution as harmonics propagate through the system.
  
  b.Active power filters are either installed at the individual consumer premisis or at substation and/or on distribution feeders.
  
  c.Depending on the compansation objectives , various types of active power filter topologies have evolved. 
  
**Simulation Software:**   MATLAB/Simulink (2009a version required)

**Modeling Techniques:** 

  - Instantaneous reactive power theory (p-q theory)
  - PWM-based control strategies
