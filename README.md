
#  CS-GO-config

*Last Updated 21/06/24*
## How to install

Put `\userdata` files in  C:\Program Files (x86)\Steam\userdata\#######\730\local\cfg

Put `\configs` files in  C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\core\cfg

## Launch options
`+exec execauto.cfg` `-allow_third_party_software`

## How to use
### Default keybinds
|Key|Function   |
| ------------ | ------------ |
| MOUSE4 | jump throw bind |
| MOUSE5 | player ping |
| SPACE | jump crouch |
| MWHEELDOWN | jump |
| c | smoke grenade |
| t | molotov |
| z | he grenade |
| MWHEELUP | flashbang |
| HOME | toggle volume |
| n | clutch mode toggle |
| o | mute chat and voice toggle |
| x | radar zoom toggle |
| DEL | iterate through crosshair colour |
| F5 | iterate through preset crosshairs |
| CAPS | old nade crosshair toggle |
| ALT | show team equipment |


Return config to match-ready default config by typing `unload` or `exec unload.cfg` in console.

------------

### pracc.cfg -> configured for servers with **[CS2-Practice-Plugin](https://github.com/CHR15cs/CS2-Practice-Plugin)**  by @CHR15cs installed

Launch by opening console and typing `pracc` or `exec pracc.cfg`.

#### Keybinds

|Key|Function   |
| ------------ | ------------ |
|  INS | say ".bot" (adds bot at location) |
| HOME  | say ".boost" (adds bot to boost player) |
| DEL | say ".nobot" (deletes bot that you are looking at) |
| END| say ".crouchboost" (adds crouching bot to boost player)  |
| PGDN | say ".noflash" (removes flashes) |
| o| say ".bestspawn" (moves player to best spawn from current location) |
| n | say ".throw" (throws last nade) |
| / | say ".clear" (clears active molotovs and smokes) |
| ALT | `noclip` (toggle noclip) |
------------
### demoview.cfg

Launch by opening console and typing `demoview` or `exec demoview`.

#### Keybinds

|Key|Function   |
| ------------ | ------------ |
| PGDN | Slowmo (Hold to play demo at 50% speed) |
| PGUP | Fastforward (Hold to play demo at 500% speed) |
| END | Super Fastforward (Hold to play demo at 1500% speed) |
| HOME | Toggle demo pause (Press to pause & play demo) |
| INS | Toggle xray (press to toggle xray) // *Note: MUST TOGGLE OFF CASTER XRAY CONTROL* |
| UPARROW | Foward 5 seconds (on 128 tick demo) |
| DOWNARROW | Back 5 seconds (on 128 tick demo) |
------------
### solopracc.cfg

Launch by opening console whilst in locally hosted server and typing `exec prac`

#### Keybinds
`DEL` key bind currently broken

|Key|Function   |
| ------------ | ------------ |
| DEL | Kills active grenades |
| ALT | `noclip` (toggle noclip) |
| n | `sv_rethrow_last_grenade` (throws last thrown grenade) |
