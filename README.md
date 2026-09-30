# NoJumpDelay

> [!IMPORTANT]
> **This repository is archived and no longer maintained.**
>
> NoJumpDelay has been rebuilt as a new mod. Development continues at
> [urntt/nojumpdelay](https://github.com/urntt/nojumpdelay).
>
> The last release from this repository is v3.0.0 for Minecraft 26.2. Older releases remain available on this
> repository's Releases page.

A simple Fabric client-side mod that removes the player's jump cooldown and add air jump.

## Features

* Removes jump delay so player will jump immediately after landing when holding the jump key
* Adds air jump so player can jump midair when holding the configured air jump key (default R)

## Requirements

* Minecraft 26.2+
* Fabric Loader 0.19.3+
* Fabric API 0.154.0+

## Installation

1. Download the latest `.jar` from Releases
2. Put it into your `.minecraft/mods` folder
3. Launch the game

## Development

Build the mod:

```bash
./gradlew build
```

The jar will be in:

```path
build/libs/
```

## License

MIT License
