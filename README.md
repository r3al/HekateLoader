# HekateLoader
🚀 Reboot to Hekate Homebrew + Title Takeover 

## Usage
HekateLoader is a piece of software that allows you to reboot to the Hekate payload (Nyx GUI) using a piece of homebrew instead of injecting the payload from another device. This allows for easy switching of payloads without ever turning your switch off or removing the SD card. The first part, `RebootToHekate` is the piece of homebrew (nro) that is placed inside the Switch folder which, when opened, injects the hekate payload named payload.bin on your SD Card root. The second part, `HekateLoader` is the nx-hbloader fork which will launch said nro (should be named hekate.nro in your switch folder) when holding R and pressing your User Icon on the home menu.

## How To Change The Title Override
- Go into the HekateLoader source
- Open hbl.json and change `title_id`, `title_id_range_min` and `title_id_range_max` to the titleid you wish to take over
- Open a cmd in the folder and write 'Make'
- Put the hbl.nsp in your `atmosphere/titles/titleid/` folder 
- Rename hbl.nsp to exefs.nsp

## Credits
- SwitchBrew - https://github.com/switchbrew/nx-hbloader 
- CTCaer - https://github.com/CTCaer/hekate/releases 
- Team ReSwitched - https://github.com/Atmosphere-NX/Atmosphere

