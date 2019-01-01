# Model for Active Redundant System with PRISM 4.4: InsulinLoopComponents 

## safety critical system: 
### - Blood Glucose Level Sensor (two parallel connected components)
### - Controllable Insulin Pump
### - Smartphone

## Active redundancy

## Parallel system: R(t) = S(t)
### parallel fail-silent components
## ■ for the parallel components the system reliability is equal to the system
safety since the system may potentially cause a hazard if it does not
function correctly
![PFSActiveRedundant](PFSActiveRedundant.png)
## TMR system: R(t) < S(t)
### voting, triple modular redundancy (TMR)
## ■ for TMR systems the reliability is not equal to the safety since the system
can be in a safe state although it is not functioning correctly, e.g. all three
components disagree (if system reacts accordingly)
