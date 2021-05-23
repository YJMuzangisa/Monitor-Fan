# Monitor temperature in my rooms

## Overview
Monitor temperature in the rooms of my house remotly using a raspberry Pi 4. With a GUI as my interface, I would be able to turn on and off my fan or heater and be given an estismation for how long it wil take for my room to reach temperatur x.
Plus, a series of emails would be sent to my account reminding me to check my interface for updates and to make changes; a reminder to turn on or off my fan (or heater).

## Purpose
The main aim is too help save my electricity consumption. It should be a good idea to have my room warm (or cool) when I come back home. And plus, my electricity bill tells me that this might be a good idea.

## Prerequisites
* IDE to run java project (or javac on your command prompt)
* A Raspberry Pi 4 (Raspberry 3 or 3+ should also work)
* Python3 in your Raspberry Pi 4 (I've set my code to work with python3 rather than python)
* SSH to remotely access your raspberry Pi machine and execute commands.
_(Note: You could choose not to use SSH and run your raspberry with an external monitor)_
* A DHT22 temperature sensor
* Two tp-link smart plugs
* An email account
