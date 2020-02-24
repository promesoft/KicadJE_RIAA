# KicadJE_RIAA
RIAA apllifier test

# Status - RIAA installed in stereo setup
## Initial 
| Stage  | Detail | Status |
| ------------- | ------------- | ------------- |
| create material  | sch/pcb | OK  |
| | gerber | OK |
| production  |   | OK |
|  | produced | OK |
|  | delivered | OK |
## Preliminary validation
| Test  | Detail | Status |
| ------------- | ------------- | ------------- |
| Initial Inspection | | Chose different RCA |
| Initial Technical Test |  | Different RCA does not match pins |
| Initial Product Test |  | Working - no hum |

## Secondary validation
| Test  | Detail | Status |
| ------------- | ------------- |------------- |
| Product Test |  | |
| Product Test |  |  |
| Quality | | |
| Quality | | |
| Long Term Product Test |  |  |
| Power Draw |  | 

## Errata
### Errata -
1 - RCA footprint wrong (flip gnd and right)

2 - V-GND 2 does not have resistor balance - only LED indicator as input

3 - C107, C109, C111, C112 should either not be mounted or significantly smaller (10nF ?)

4 - U302B needs an 18k to GND on pin 5

## Issues and Notes
### 

# Pictures


# Inspiration

http://audio.engineeringvista.com/AudioKits/Phono-1/Design/Part6.htm

![](KicadJE_RIAA_RevA/RIAA.gif)

http://sound.whsites.net/project25.htm
