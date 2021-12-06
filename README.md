# audio-bio-semi
Resettable audio trigger for use with biosemi

The trigger has two indicator LED's, a red and a green, either one is lid. 

- When audio is received and all inputs of the paralel port (bits 0-7/pins 1-8) ar set 0, the red LED will turn on, and the BioSemi will detect bit 128 set to 1.
- When no audio is received and a trigger of bit 7 (bit 128) is given, the green LED is turned on and the BioSemi will detect bit 128 set to 0.

In case both a parallel trigger and a audio pulse are received simultaniously by the device the output is undetermined.

