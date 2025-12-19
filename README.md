/* 
  This is example code of Mutable Instruments Plaits 1.2 and Clouds Parasites firmware reverb
  running on Raspberry Pi Pico RP2350 with I2S DAC.

  Program cycles through clean Plaits engines -> Clouds reverb -> Oliverb fx
  An additional DX7 SysEx bank has been added for the OP6 engine, making a total of 25 engines available.
  
  Set:
  
  CPU 276mhz Overclock
  Optimize Even More -O3
  
  Select TinyUSB stack in ArduinoIDE tools for easier adjusments test

  Copyright (c) 2025 Vadims Maksimovs <ledlaux@gmail.com>
  MIT licence

  This code is part of the porting project of Mutable Instruments eurorack modules to Arduino by Mark Washeim
  Main repository: https://github.com/poetaster/arduinoMI

  Original Mutable Instruments Code
  Copyright (c) 2020 Emilie O. Gillet 
  stmlib, Plaits, Clouds libraries
  MIT licence

  Clouds Parasites Firmware
  Authored by Matthias Puech
  https://mqtthiqs.github.io/
  MIT licence
*/
