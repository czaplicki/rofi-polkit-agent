# rofi-polkit-agent
Simple polkit agent for window managers, using rofi as prompt.

## Usage
```
Usage : rofi-polkit-agent [-h|--help] [ROFI_OPTIONS]...
```

Start the polkit agent with default options :
```sh
rofi-polkit-agent
```

Start the polkit agent with any additional argument passed directly to rofi :
```sh
rofi-polkit-agent -theme PATH -monitor NUM
```

## Installation
### Arch AUR
This script is available on the AUR as `rofi-polkit-agent`


### Manual Installation
- Install dependencies
- Clone this repository
- Make this script executeable (chmod +x path/to/script)
- Place script somewhere in your path

## Dependencies
| package          | source                                                |
|------------------|-------------------------------------------------------|
| sh               | a posix complient shell, preinstalled on most systems |
| coreutils        | a coreutils suit, preinstalled on most systems        |
| jq               | https://stedolan.github.io/jq/                        |
| rofi             | https://github.com/davatorium/rofi                    |
| cmd-polkit-agent | https://github.com/OmarCastro/cmd-polkit              |


## Contribute
If you know anyway to make the script safer,
please leave a issue and/or make a pull request.
All help is appreciated!

## WARNING/DISCLAMIER
This script does not take any real measures to 'securely' take in the password.
As stated in the rofi man pages about the -password flag
   "Hide the input text. This should not be considered secure!".
All the script does is enabling that flag and the disable history flag.
No other measures are taken so use at your own discretion.

## Credits
Without these programmers, this one would never had been made.
- https://github.com/OmarCastro the creator of cmd-polkit
- https://github.com/davatorium the creator of rofi
- https://github.com/stedolan   the creator of jq


