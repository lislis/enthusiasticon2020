3 min: Introducing DIY controllers and the altctrl (alternative controls) game scene. This will be about showcasing inspirational examples that exist out there and some of my own work.
5 min 30 seconds: Crash course in electronics and communication protocols, aka how to build a controller and make it send data to a game engine.
30 seconds: have fun and learn about things!

---

Video games as art

---

Human-Computer-Interaction

---

Interaction between the physical and the digital!

---

Probably what got people excited about VR?!

---

Not just playing a game but playing with the idea of a game

---

altctrl

@GDC 2019

https://www.cnet.com/pictures/alt-ctrl-gdc-where-a-toilet-plunger-becomes-your-game-controller/15/

@GDC 2017

https://www.rockpapershotgun.com/2017/03/08/alt-ctrl-gdc-2017/

Alt Ctrl Game Jam 2015 - 2017

https://altctrlgamejam.com/
https://twitter.com/rasmus_dyhr/status/780736850990362625

https://twitter.com/Cosmografik/status/780674356385050624


Swaj - Midi Keyboard

Pigarus - microcontrollers, motors and a fan

Fishing for Compliments - microcontroller + sensor

Pisu kawaii - microcontroller + sensor


---

How to get started?

Assuming you have a game idea

---

Some hardware that talks to your computer/ game engine / creative coding environment.

---

Hardware

Inputs!

- can be mouse and keyboard in unusual ways
- Midi controllers! Lots of software to interface with
- Microcontrollers + everything*

*Everything

That give you a Voltage or resistance
So the microcontroller can measure the differences!

Outputs!

Motors, displays

---

Talking

Midi

Microcontrollers that register as keyboards
Makey Makey, Arduino Leonardo / Micro

->


Serial Protocols

What is serial communication

USB -> Universal Serial Bus

Libraries in most languages and game engines

UART, I2C, SPI

Pros/ Cons of each?

I2C pretty common

https://www.deviceplus.com/arduino/arduino-communication-protocols-tutorial/



---

Make a game!
Make a controller!
Have fun and learn!


      # Lots to chose from!

      - SWAJ

      - Fishing for compliments

      - Pigarus



      ## UART

      - Universal Asynchronous Receiver/Transmitter no clock - baud
      - rate!  two devices -> otherwise bus contention Its own piece
      - of circuitry on your board can be emulated with software (eg
      - when you don't have enough)

      ---

      ## SPI

      - Serial Peripheral Interface synchronous (synced clocks!)  lots
      - of wires, one (master) to many (slaves) Used with sensors and
      - modules that talk to your microcontroller

      ---

      ### I2C

      - Inter-integrated circuit synchronous (synced clocks!)
      - communication on short distance (on one board) fixes
      - short-commings of UART and SPI multiple masters and slaves, 2
      - wires
