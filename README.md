# Introduction to instrument design based on Arduino microcontroller with Kacper Ziemianin


![analog digital  in_bb](https://github.com/user-attachments/assets/6ff1ee2b-087c-4288-9467-9f03e33a57cb)


# Materials
- Arduino Uno Kit
- Photoresistor sensor </br>
- Optional
  - audio jack component or a small speaker with leads


# Arduino Examples Used 
Can be found in the Arduino IDE under File -> Examples
- Basics -> Blink,
  - to test connectivity
- Digital -> DigitalInputPullup
  - to test the button
- Arduino Serial -> SerialCallResponse
  - to test the serial communication of the potentiometer
- Mozzi -> Sensors -> Know_LightLevel_FMSynth
  - FM Synth with a potentiometer and a photoresistor oscillator

## Resources
- [Demo of Kacper's Project](https://www.youtube.com/watch?v=cHuIpSeTTjM)
- [Circuit Bending: Build Your Own Alien Instruments (Archive)](https://archive.org/details/CircuitBendingBuildYourOwnAlienInstruments)
- [Introduction to Arduino Book (PDF)](https://www.introtoarduino.com/downloads/IntroArduinoBook.pdf)
- [Arduino Tutorials](https://www.arduino.cc/en/Tutorial/HomePage)
- [6 Awesome Free Arduino eBooks](https://www.electronicsforu.com/resources/6-awesome-free-arduino-ebooks)
- [Fritzing Breadboard for demo](https://fritzing.org/tags/breadboard)
- [DigiKey's 4 Band Resistor Color Code Calculator](https://www.digikey.com/en/resources/conversion-calculators/conversion-calculator-resistor-color-code)

# Workshop Learning Moments
 - My left USB was not being recognized by the Arduino IDE. I switched to my right side USB and it worked.
 - I tried replacing a photoresistor with a potentiometer, but it did not work. The code examples relies on a photoresistor component
 - The resistor for the photoresistor was too low, I tried a 10 or above and the sensitivity increased which lead to more synth modulation.
