# AudysseyOne v1.1

Optimize your home theatre system in under 5 minutes with just 1-click!
A platform and installation free script that works right in your web browser,
and with just a few clicks, redefines what's possible with Audyssey unlocking the full potential of your home cinema audio system.
First ever utilization of the Room EQ Wizard's API and full automation of state of the art Audyssey calibration optimization.





@ocaudiophile
  • 46 seconds ago
Audyssey One has been updated to version 1.2 today with the following improvements and revisions:

* Subwoofer volume alignment frequency range has been modified from 22.3Hz – 178.2Hz to 28.3Hz – 226.3Hz. This change may result in a slight increase in bass response for certain audio systems. However, if desired, the previous frequency range can be reverted by modifying line 625 of the script.
* The calculation of crossover frequencies has been optimized for faster performance and reduced memory usage. As a result, there is no longer a need to increase REW's memory settings. Additionally, the calculated crossover frequencies are FINALLY completely accurate to five decimal places for every possible system configuration.
* To minimize driver loads and increase clarity, any calculated crossover frequency below 80Hz will be automatically raised to 80Hz.
* The logging functionality has been enhanced, providing some additional enthusiast information.
* A timer has been implemented to report the total execution time at the end of the optimization process.

To do:

* Implementing an exhaustive subwoofer alignment process with iterative targeting of minimum total phase delays at the crossover frequencies. Assistance from experienced coders is needed, as my hopeless attempts today have resulted in multiple REW crashes.
* Enabling manual optimal relative alignment of multiple subwoofers by taking Audyssey measurements in 'directional mode' and then switching to 'standard mode.' However, it is uncertain whether Audyssey will accept running the calibration in directional mode on older receiver models, even if the mode can be activated through the app."
