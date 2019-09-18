# Nextion wall mount

Hi there!

In this project I tried to create a simple(?) wall mount with quick and easy access to Home Assistant.
The purpose is to have a remote controller, that's mounted on the wall and gives a quick info of the day ... or basically whatever you need from Home Assistant.

## Features:
Basically everything is connected to Home Assistant through Esphome:

1. Overview - General info:
    - Indoor / Outdoor temperature / Rain Forecast + Weather Symbol
    - Display Date and Time
    - My Facebook Birthay Calendar / Facebook Events / Google Calendar
    - Byebye - Automation (music and lights off, etc)
    - Play/Pause Media player - Kodi in my case
    
2. Lights- The important ones:
    - Kitchen, Livingoom and Bedroom Lights
        
3. Media - Radio and quick controls:
    - 6 stations
    - Vol +/-
    - Play/Pause button   
    
4. Vacuum Cleaner - Map:
    - Apartment layout with zones
    - Vacuum Controls: play/pause, "TrashSpot", Go home, Set speed
    - Stream music on the vacuum
        
5. Automations - Switches:
    - Kitchen plug - for the coffee maker
    - Morning routine automation (lights on, music on at for ex. 6:45)
    - Wifi status
    - Secret menu - but of course
      - Change display brightness
      - Reboot the display
      
      
## HW used:
1. Home Assistant
2. Wemos D1 mini - with Esphome
3. Nextion Display - NX4832T035_011
    - Mine is actually TJC4832T035_011 but both are the same(?) HW
4. A passive buzzer, that gives audio feedback on touch
5. 3D printed case for the wall mount




I barely started this project, just for fun. As I'm no programmer, I still need to work on the coding, but the community comes in handy!
I will probably start uploading some code later, when I'm satisfied with it :)
Until that, you can find some STL-s for the wall mount.
