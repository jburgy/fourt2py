# fourt2py
Demonstrate how mesonpy can build a python extension written in legacy fortran

mesonbuild/meson#9598 introduced numpy as a meson dependency but failed to
mention a key ingredient to make it work: numpy must be enumerated as a
build system requirement in `pyproject.toml`.  Obvious when you say it out
loud but took quite a while per this
[discord thread](https://discord.com/channels/1039017663004942429/1383834595908124793). 
