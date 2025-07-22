# Audio Amplifier Project

This project involves the design and simulation of a multi-stage audio amplifier using LTSpice. The amplifier is intended to strengthen low-power audio signals (like those from a microphone) and drive a 10Ω speaker within a power budget of 0.5W.

## Project Structure

The amplifier consists of the following four stages:

1. **Pre-Amplifier Stage**  
   - Differential amplifier configuration.
   - Boosts weak microphone signals and reduces noise.

2. **Gain Stage**  
   - Common emitter amplifier.
   - Provides voltage amplification.

3. **Active Bandpass Filter**  
   - Filters signals within 20 Hz to 20 kHz.
   - Removes out-of-range noise components.

4. **Power Amplifier Stage**  
   - Class AB emitter follower.
   - Amplifies current to drive the speaker.

## Tools Used
- **LTSpice** for circuit simulation.
- **Hand calculations** for design verification. &
- **Hardware**

## Contents
- **Filter/** — Bandpass filter LTSpice design files.
- **Gain/** — Voltage gain stage circuit files.
- **PowerAmp/** — Power amplifier design.
- **PreAmp/** — Pre-amplifier circuits.
- **totaL/** — Final integrated amplifier files.
- **Project Report.pdf** — Detailed documentation of the amplifier design and performance.

---

> This project was developed as part of the Semester 4 EW-II course.
