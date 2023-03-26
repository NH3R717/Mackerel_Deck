# Notes

[x] add images to readme.md

[x] install RSLogix Emulate – 02/26/23

[x] install RSLinx (Ability for RSLogix to communicate with RSLogix Emulate) – 02/27/23

[X] connect RSLogix Emulate to Mackerel Deck Project

[] ...

# PLC Fid Online

Development Notes For "Mackerel Deck" (Marel Deck) Ladder Logic program upgrade— for elimination of coil ice-up.

Versions

• <V4.0.0 ("unsaved")
• V4.1 (It Works) https://www.plcfiddle.com/fiddles/2920c130-d690-4050-8494-c55ead9d8027
• V4.3 (Cleaned) https://www.plcfiddle.com:/fiddles/7c2508e1-5aa6-4cdf-a3d6-f3a248ba2772
• V4.4 (E-stop move) https://www.plcfiddle.com:/fiddles/7c17ee18-facd-4096-8eb7-ecc89004ad26
• V4.4.1 () https://www.plcfiddle.com:/fiddles/2150b720-3a97-4b56-be98-e63e89906f9c
• V4.4.2 ()
• V4.5.1 (Refactor— New) https://www.plcfiddle.com:/fiddles/725656a8-9d89-47e3-9ef7-af697fd76cb0
• V4.5.2 (Refactor— Add Variables) https://www.plcfiddle.com/fiddles/725656a8-9d89-47e3-9ef7-af697fd76cb0
• V4.5.3 (Refactor— #1 Rung/Space Temp Compare) https://www.plcfiddle.com:/fiddles/191788b8-41ca-40a1-9925-6a28b31229f3
• V4.5.4 (Refactor— #2 Rung/Cooling On Delapy) https://www.plcfiddle.com:/fiddles/2ca159fe-c6fc-4550-8a97-aa49ae807b69
• V4.5.5 (Refactor— #3 Rung/Solenoid(s)) https://www.plcfiddle.com/fiddles/2ca159fe-c6fc-4550-8a97-aa49ae807b69
• V4.5.6 (Refactor— #4 Rung/Off Cooling Latch) https://www.plcfiddle.com:/fiddles/6af74939-a791-41e4-a9db-f4163a84491a
• V4.5.7 (Refactor— #5 Rung/Switch On Cooling [Last Rung]) https://www.plcfiddle.com:/fiddles/106a4b4a-7b02-45d8-989c-38960677e6dd
• V4.5.7 (Refactor— #6 Rung/Update Variables|Test) https://www.plcfiddle.com:/fiddles/c90da33a-7e54-4e82-991d-2c31674770b3
• V5.0 (Push For Production) https://www.plcfiddle.com:/fiddles/c90da33a-7e54-4e82-991d-2c31674770b3
• V5.0.1 (E-stop/Run) https://www.plcfiddle.com:/fiddles/3612dc1f-62ee-4d1c-b05b-ac9082272a66
• V5.1.1 (remove latches) https://www.plcfiddle.com:/fiddles/f9a0e3f8-c6e4-46c7-9072-eb28f5b64c19

I/O & "Tags"

• Run — Bool
• Fans — Bool
• E-stop — Bool

• Solenoids_Liquid_SuctionEPR — Bool
or
• Solenoid_Liguid — Bool
• Solenoid_EPR — Bool

• Temperture_Space — Num
• Temperture_Space_Set_Point — Num

• Mode_Cooling_On — On Delay Timer
• Mode_Cooling_Off — On Delapy Timer
• Mode_Switch — Bool
• Mode_Latch — Bool

• Call_Cooling

Notes:
Bullet Point in Windows "alt 0149"
