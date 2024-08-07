# ThePython10110

I am a programmer/musician.

## Music

Find my music (mostly video game transcriptions) on [MuseScore.com](https://musescore.com/thepython10110)
    and [GitHub](https://github.com/thepython10110/musescore). On GitHub, I have
    a script that automatically converts them into various file formats (including
    MP3, MIDI, PDF, and MusicXML). It will even automatically flip the MIDI files
    using [my version](https://github.com/thepython10110/midiflip) of [midiflip](https://github.com/1j01/midiflip)

## [Software on my computer](software-on-my-computer)

A list of software on my computer (back in January 2023, before I switched to Linux).

<details><summary><h2 id="minetest-mods">Minetest mods</h2></summary>

### Better Randomizer

[GitHub](https://github.com/thepython10110/_better_randomizer), [ContentDB](https://content.minetest.net/packages/ThePython/_better_randomizer/)

A Minetest mod that randomizes node drops, entity drops, and crafting recipes.
    Random drops/recipes are saved and recalled, and can be re-randomized with commands,
    although re-randomizing node drops requires a restart.

### Better Commands

[GitHub](https://github.com/thepython10110/better_commands)

A mod that adds commands and syntax from a certain other voxel game. I have had to
    make some changes due to the differences between Minetest and ACOVG, but it's
    mostly the same (though incomplete). You can do things like this:

```mcfunction
execute as @r[type=sheep] run say I am a random sheep.
```

For compatible command blocks, use Better Command Blocks.

### Better Command Blocks

[GitHub](https://github.com/thepython10110/better_commands)

A mod that adds command blocks from a certain other voxel game. They are designed
    to work with Better Commands.

### BigNum

[GitHub](https://github.com/thepython10110/bignum), [ContentDB](https://content.minetest.net/packages/ThePython/bignum/)
A library mod that adds a data type for arbitrary precision integers. It's copied
    from [a Roblox library](https://rostrap.github.io/Libraries/Math/BigNum).

### ExchangeClone

[GitHub](https://github.com/thepython10110/exchangeclone), [Wiki](https://github.com/thepython10110/exchangeclone/wiki),
    [ContentDB](https://content.minetest.net/packages/ThePython/exchangeclone/)

A fork of [Element Exchange](https://github.com/enchant97/minetest_element_exchange)
    (based on Equivalent Exchange/ProjectE) with bugfixes, better energy values,
    MineClone2/Mineclonia support, and tons of new features such as Dark Matter,
    Red Matter, and tools that can be made with them. Most of the code is mine at
    this point. Basically, it adds an energy value for most items (including items
    from "Why?"), and the ability to convert things into energy and energy into
    other things. For instance, 8 iron/steel ingots (256 energy) can be converted
    into 1 gold ingot (2048 energy), which can be converted into 2048 cobblestone
    (1 energy). It also adds a lot of other things. It's been a while since I've
    updated it... but I may eventually go back to it.

### Portability

[GitHub](https://github.com/thepython10110/portability), [ContentDB](https://content.minetest.net/packages/ThePython/portability/)

Adds a portable crafting table, portable ender chest (although it requires a minor
    change to MineClone's code), and portable enchanting table to MineClone.

### SpawnCraft

[GitHub](https://github.com/thepython10110/spawncraft), [ContentDB](https://content.minetest.net/packages/ThePython/spawncraft/)

A mod for [MineClone](https://content.minetest.net/packages/Wuzzy/mineclone2) that
    adds crafting recipes for spawners and spawn eggs. My first Minetest mod, which
    is why it's literally just a whole bunch of recipes.

### Too Many Aliases

[GitHub](https://github.com/thepython10110/too_many_aliases), [ContentDB](https://content.minetest.net/packages/ThePython/too_many_aliases/)

A MineClone2 mod that adds tons of aliases that make itemstrings match MineCraft
    as much as possible. This is definitely outdated.

### Why?

[GitHub](https://github.com/thepython10110/why), [ContentDB](https://content.minetest.net/packages/ThePython/why/)

A modpack that adds a whole bunch of completely random things to MineClone/Minetest
    Game. Some are useful, others are solely for annoying people, and some are
    _completely_ useless. Not all features are available in Minetest Game.

</details>

<details><summary><h2 id="random-programming-projects">Random programming projects</h1></summary>

### Countdown

[GitHub](https://github.com/thepython10110/countdown)

A Python/Tkinter program that counts down the time until user-specified events,
    with the ability to make custom themes. It requires Python 3 on a Windows
    computer (although using it on other OS's shouldn't take much modification),
    and several Python modules that _should_ automatically be installed. It
    saves either to a JSON file or to a [Home Assistant](https://home-assistant.io)
    server via the REST API. It uses my Python script (`hass.py`) which has several
    functions that make the Home Assistant REST API relatively easy to use.

### GitHub Pages

[GitHub](https://github.com/thepython10110/thepython10110.github.io)

The "code" for this site (if you can really call HTML/Markdown code).

### Midiflip

[GitHub](https://github.com/thepython10110/midiflip), [Demo](midiflip)

A program to flip MIDI files (high notes become low notes, low notes become high
    notes). This is a fork of [1j01's original version](https://github.com/1j01/midiflip),
    and all it adds is the ability to remap pitches to the closest octave to
    their original range. I use it to automatically flip all of my [MuseScore scores](https://github.com/thepython10110/Musescore).

### Tengwar Transcriber

[GitHub](https://github.com/thepython10110/tengwar-transcriber), [Demo](Tengwar-Transcriber)

A program that I barely started that was originally going to convert English into
    Lord of the Rings Elvish Tengwar. I'm unlikely to finish it, especially since
    [Tecendil](https://tecendil.com) already exists.

### UserStyles

[GitHub](https://github.com/ThePython10110/UserStyles), [UserStyles.world](https://userstyles.world/user/ThePython10110)

Themes for a couple of websites.

</details>
