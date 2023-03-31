# Project – "Mackerel Deck"

## An HMI Mockup and Corresponding PLC Program Written in Ladder Logic for the Allen-Bradley / Rockwell Automation Platform

## HMI

![HMI](https://github.com/NH3R717/Mackerel_Deck/blob/7465bdef17d5803bb689ffb2c7ee5f94d6336661/Assets/Mackerel%20HMI.png?raw=true)

## RSLogix LAD 2

![PLC](https://github.com/NH3R717/Mackerel_Deck/blob/d67ed124dcaba8a883d179c7d2b1ddb29db7c5c6/Assets/Mackerel_Deck_LAD_2.png?raw=true)

### This software is intended to control a fan coil unit (FCU) providing air condition to a occupied space used for food processing.

## Problem

### Liquid sub-cooled (-40˚F) refrigerant is supplied to the FCU evaporator via a pump at 45psi. This limits the total evaporator pressure to about 40psi via a back pressure regulator with a corresponding temperature of 25˚F and causes rapid FCU ice-up. No defrost functionality is installed.

## Solution

### Add ability to the FCU's PLC program that allows the refrigerant supply solenoid valve to cycle open/close at settable intervals (while the FCU's fans continue to run) only permitting refrigerant flow for sort durations – preventing ice build-up. Anticipated effective cycle time – approx. 3 minutes on / 12 minutes off.

## Mockup Link

[Mackerel Deck](https://www.plcfiddle.com/fiddles/f9a0e3f8-c6e4-46c7-9072-eb28f5b64c19)
