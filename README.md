# PART 1 - How to create your own module

[ THIS README IS A WORK IN PROGRESS ]


You can use these scripts to start your project:

https://github.com/azerothcore/azerothcore-boilerplates

-------------------------------------------------------

# PART 2 - EXAMPLE OF A README.md

# MY NEW MODULE (title)


## Description

This module allows to do this and this.


## How to use ingame

Do this and that.

![my new module screenshot](/screenshots/my_module.png?raw=true "my new module screenshot")


## Requirements

My new module requires:

- AzerothCore v1.0.1+


## Installation

```
1) Simply place the module under the `modules` directory of your AzerothCore source. 
2) Import the SQL manually to the right Database (auth, world or characters) or with the `db_assembler.sh` (if `include.sh` provided).
3) Re-run cmake and launch a clean build of AzerothCore.
```

## Edit module configuration (optional)

If you need to change the module configuration, go to your server configuration folder (where your `worldserver` or `worldserver.exe` is), copy `my_module.conf.dist` to `my_module.conf` and edit that new file.


## Credits

@Me (author of the module): Check out my soundcloud - Join my discord

@BarbzYHOOL: best guy

@Talamortis: almost best guy

AzerothCore: [repository](https://github.com/azerothcore) - [website](http://azerothcore.org/) - [discord chat community](https://discord.gg/PaqQRkd)
