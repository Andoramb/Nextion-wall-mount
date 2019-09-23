# Nextion wall mount

Hi there!

In this project I tried to create a simple(?) wall mount with quick and easy access to Home Assistant.
The purpose is to have a remote controller, that's mounted on the wall and gives a quick info of the day ... or basically whatever you need from Home Assistant.

Demo video [HERE](https://www.youtube.com/watch?v=TL8wZNnS4jI)

## Features:
Basically everything is connected to Home Assistant through Esphome:

**1. Overview - General info:**
   - Indoor / Outdoor temperature / Rain Forecast + Weather Symbol
   - Display Date and Time
   - My Facebook Birthay Calendar / Facebook Events / Google Calendar
   - Byebye - Automation (music and lights off, etc)
   - Play/Pause Media player - Kodi in my case
    
**2. Lights- The important ones:**
   - Kitchen, Livingoom and Bedroom Lights toggle (Slider not implemented yet)
        
**3. Media - Radio and quick controls:**
   - 6 stations
   - Vol +/-
   - Play/Pause button   
    
**4. Vacuum Cleaner - Map:**
    - Apartment layout with zones
    - Vacuum Controls: play/pause, "TrashSpot", Go home, Set speed
    - Stream music on the vacuum
        
**5. Automations - Switches:**
    - Kitchen plug - for the coffee maker
    - Morning routine automation (lights on, music on at for ex. 6:45)
    - Wifi status
    - Secret menu - but of course
      - Change display brightness
      - Reboot the display
      
**6. Screensaver**     
      
# Other features:
  - Screen turns off after 1h standby time
  - Screen brightness is set based on *sun elevation* and devices connected to Wifi (*group.all_devices*)
  - Auto refresh every page and relevant variables initialize with correct state data (ex. if the lights are on, switch will turn to on)
    
      
## HW used:
1. Home Assistant
2. Wemos D1 mini - with Esphome
3. Nextion Display - NX4832T035_011
    - Mine is actually TJC4832T035_011 but both are the same(?) HW
    - 3.5inch with a resolution of 480x320
    - Resistive touch
4. A passive buzzer, that gives audio feedback on touch
5. 3D printed case for the wall mount


## Resources and SW:
You can find the used resources in the repo.
Basically none the SW and HW is actually *my* work:
- Icons were exported from [Material Design Icons](https://materialdesignicons.com) - Thanks!
- The weather pictures were taken from [Yr Weather Symbols repo](https://github.com/YR/weather-symbols) - Thanks!
- For [Esphome](https://esphome.io): The basic descriptions from the site is **really** helpful.
  - A lot of code from various github repos served as a base, tailored to my setup.

## Something very important:
**This display board is _not Nextion_**!

This is actually TJC. And the HMI file will not open in Nextion Editor -> only USART HMI editor. I'm not sure if the project can be ported either way, but essentially the 2 editors are the same (chinese vs english...)


I barely started this project, just for fun. As I'm no programmer, I still need to work on the coding, but the community comes in handy!
I will probably start uploading some code later, when I'm satisfied with it :)
Until that, you can find some STL-s for the wall mount.
