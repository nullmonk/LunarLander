# Lunar Lander 3
CTF Challenge for RITSEC CTF 2019


__Category:__ Pwn
__Difficulty:__ 500  
__Flag:__ `RITSEC{HOUSTON_WE_G0T_EM}`  

### Title: Lunar Lander 3
### Description

Oh boy Starman!

This space race is accelerating quickly. We are worried that the Russia's have tried to gain an upper hand by backdooring the AGC program. See if you can figure out what they are up to...

Good luck,
- Houston

## File: LM.bin LM.symtab


This one actually required them to reverse the ASM of the AGC. I was going to embed a url or file or something into the code but that seemed like a lot. I made it super simple instead where it just writes characters...