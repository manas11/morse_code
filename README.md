# Morse Code generation using Logisim 

This project contains the files related to the digital-design project of 3rd semester. Morse code is a method used in telecommunication to encode text characters as standardized sequences of two different signal durations, called dots and dashes.

Implementation of digital circuit is done using **Logisim** for this project.

## Running the project
**The .circ file of morse code is included and can be run by the following steps:**
-	Open the file morse_code.circ in Logisim
-	Set the frequency of the clock to 2Hz for better view of blinking.
-	Select your input (options from 1 to 9), set the shift/load to 1 and see the morse code answer in the output blinker.
-	The selection lines send the signal whether the input is 1-9 then it calculates according to the M functions and sends output of 5 bit.
-	The output goes one by one to the shift right register.
-	With delay, the output signal is displayed and we get dots and dashes.
-	This is our final output.
