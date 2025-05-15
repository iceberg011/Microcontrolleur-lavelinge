A smart washing machine controller built in Proteus ISIS with a PIC16F877 microcontroller!
 🧼💧 Programmed in Micro C, this system uses an LM016L LCD to display real-time temperature (via LM35) and water level (via POT-HG),
 ensuring cycles start only when conditions like ≥30°C and ≥50% water level are met. Featuring BUTTONs (RB0, RA4, RB4-RB7) for mode 
 selection (Express, Drying, Washing, Spinning), a MOTOR driven by a 2N6660 MOSFET, and LED-BLUE/GREEN/YELLOW plus BUZZER for feedback,
 it leverages ADC and EEPROM for threshold storage. LOGICPROBE/LOGICSTATE simulate door states, with challenges overcome in sensor integration 
 and interrupt handling
