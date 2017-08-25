# HomeAudioSystem

A combination of hardware and software to provide universal sharing of audio streams across the apartment. 

# 1. Features

## 1.1. Common
* Multiple inputs, multiple outputs 
* Arbitrary connection of inputs to outputs (n to m)
* Broadcasting
* Outputs are built using Raspbery Pi, Audio HAT and speakers

## 1.2. Input types
* PCs
* Media server
* Android devices via Bluetooth
* Microphone
* Automatic notifications

## 1.3. Configuration
* Each input has default output; this is the speaker in the room the input located in
* When output is not producing sound it should shut down the speaker; relay can be used for this
* If the user is moving from one room to another, the output should switch automatically
* Headphones should not be connected to the system
