# raspberry_shields
Custom shields for raspberrypi


Documentations : 

- [Page wweb raspberrypi](https://www.raspberrypi.com/documentation/computers/raspberry-pi.html)
- [Datasheet BCM2711 ](https://datasheets.raspberrypi.com/bcm2711/bcm2711-peripherals.pdf?_gl=1*1varbtl*_ga*NDYxMjQyMzI5LjE3MTE0NTk1MDc.*_ga_22FD70LWDS*MTcxMTQ1OTUwNi4xLjEuMTcxMTQ1OTY0MS4wLjAuMA..)
 
Les broches des VL53 sont sur des broches pwm, mais on ne peut utiliser que deux pwm sur les 4 en même temps car il s'agit de deux fois les mêmes ( voir Doc section 5.3 ) 

Les broches I2C sont en PULL UP ( GPIO 2 et 3 ) 
