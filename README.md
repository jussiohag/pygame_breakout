# pygame_breakout

Jussi Hagstrom

## testing pygame & git configuration
read the GIT_INSTRUCTIONS.txt for Github instructions

## pygame_menu installation 
(from https://www.omgubuntu.co.uk/2023/04/pip-install-error-externally-managed-environment-fix)

Since our Kubuntu 23.04 development environment doesn't include an apt package for pygame_menu we'll install it manually. 

Pip doesn't work globally in Ubuntu ("managed environment" error, see link above, so we have to create virtual environment for pip to install pygame_menu: 

[code]
$ cd pygame_breakout
$ python3 -m venv .venv/pygame_menu_virtual_env
$ .venv/pygame_menu_virtual_env/bin/pip3 install pygame-menu
[/code]

Run the code 

[code]
$ python3 PaddleSmash.py
[/code]


todo: 
- change the name to breakout 
- ... 
