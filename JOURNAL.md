## 9/23
### Starting Research
Today I started the initial research process. Planning out parts and finding out how I'm going to tackle partials and dynamics.
I found this [anemometer](https://moderndevice.com/products/wind-sensor) that could be perfect for what I need. I think I will also be using the rotary encoder to control the partial. something simillar to [this EVI](https://berglundinstruments.com/nuevi-trumpet-horn-tuba-fingering-instrument/) that I found
I also created the kicad document and this repo
*Time Spent:* 2hr

## 9/27
### Schematic Time
Today I worked on finalizing the schematic. I posted it in the slack channel to get feedback before I move on to the making of the PCB.\

<img width="720" height="341" alt="image_720" src="https://github.com/user-attachments/assets/2701ca05-c274-4f45-8e1f-a2893895d355" />

I have all of my compenents as well as breakouts in case after I build it, I want to add other functionality.
I have a macro button that can be used as a trigger for some instruments, and as an effect button for others.
Also, I added the slide potentiometer for tuning and pitch bend, as well as a rotary encoder that will handle partials.
The Anemometer will measure how fast I am blowing air and I can translate that to the velocity that gets transmitted over MIDI.
*Time Spent:* 3.5hr

## 9/28
### Acting on feedback

After some feedback I learned that I need an external ADC so I am using [this one](https://www.adafruit.com/product/856?srsltid=AfmBOoqUDW9lRRgYDhqV9-GxvOzXFku9BKXl2naoguj5eppcnvzZRftK) because it has all the channels I need. I also cleaned up my spi wiring and I added a second macro button.
I learned that I was doing my spi wrong so I had to go back and fix that. I also added the breakouts for the rest of the GPIO on the Pi Pico

<img width="719" height="497" alt="image_720" src="https://github.com/user-attachments/assets/f0096611-a472-4240-b529-b03618de0f42" />

*Time Spent:* 4hr
