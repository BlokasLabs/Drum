# Drum

Drum is the Blokas Edition of the [Bleep Drum](http://bleeplabs.com/store/bleep-drum-midi/). It features a built-in speaker, so the beats won't stop flowing even when there's no headphones or external speaker at hand's reach!

## Building The Source Code

The firmware has dependencies on Bounce2 and MIDI libraries. They can easily be setup from within the Arduino IDE:

1. Go to Sketch -> Include Library -> Manage Libaries...
2. Install the following libraries:
    * [Bounce2](https://github.com/thomasfredericks/Bounce2) by Thomas Ouellet Fredericks with contributions from: Eric Lowry, Jim Schimpf and Tom Harkaway.
    * [MIDI Library](https://github.com/FortySevenEffects/arduino_midi_library) by Forty Seven Effects.

After dependencies are set up, just open DRUM/DRUM.ino in [Arduino IDE](https://www.arduino.cc/en/Main/Software) and it should build successfully.
