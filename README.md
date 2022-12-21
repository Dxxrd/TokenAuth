<div align="center">

# TokenAuth
**A simple Minecraft Forge mod that allows logging in to other people's accounts using only a token.**

![](https://img.shields.io/badge/MC--VERSION-FORGE_1.8.9-0?style=for-the-badge)
![](https://img.shields.io/github/downloads/DxxxxY/TokenAuth/total?style=for-the-badge)

</div>

> Fun fact: most of this readme was authored by GitHub Copilot.

## Download
Download from [Releases](https://github.com/Dxxrd/TokenAuth/) and drag that into your mod folder.

## Features
- Login into an account with a `token` (or an `ign:uuid:token` formatted string).
- Restore your session to your original one (at launch time) with the click of a button.
- Shows the status (user, uuid) next to the gui button in GuiMultiplayer.
- Error handling for invalid inputs.
- Simple:
    - No dependencies.
    - No config.
    - Uses Forge's event system to draw a button on the multiplayer gui.
    - Uses an AT to allow modification of the session on runtime.
    
## Disclaimer
This is for educational purposes only. I am not responsible for any damage caused by this tool.

## License
GPLv3 © Dxxrd
