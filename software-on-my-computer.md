# Software On My Computer
A complete (?) list of all the software (apps/VST plugins, etc.) I have on my computer (Windows 10).
Everything is free (besides the games), and a lot is open-source. None of the links are direct download links (or at least they weren't when I made this list).
An asterisk (\*) means that it's open-source.



Slightly unrelatedly, [Chris Titus Tech](https://christitus.com) has created a [utility](https://github.com/christitustech/winutil) that (among other things) makes it incredibly easy to install or update apps on a Windows computer. I use it every time I reinstall Windows (annoyingly, I've had to do it at least 3 times in the past year). The easiest way to access it is to open PowerShell and run
```
irm https://christitus.com/winutil | iex
```
This will download the script, then run it. This means you don't have to open Edge... ever, if you don't want to, since you can just download Chrome (or another browser) using that utility. Of course, you could also use WinGet with the same result, but the UI makes it easier to select more than one thing.


<details><summary><h1>Apps</h1></summary>

### Built-in Windows 10 stuff
Obvsiously.

### [7-Zip](https://7-zip.org)\*
An open-source utility for creating and opening archives.

`winget install 7zip.7zip`

`scoop install 7zip`

### [Audacity](https://www.audacityteam.org)\*
An open-source program for recording audio. I rarely use it, since I have alternatives with more features, but it's nice to have for some things.

`winget install Audacity.Audacity`

`scoop install audacity`

### [AutoHotkey (v2)](https://autohotkey.com)\*
An open-source utility for creating custom hotkeys, macros, and various other things. I don't use it much, but I have an AHK autoclicker that's useful in some situations.

`winget install AutoHotkey.AutoHotkey` (v2.x)

`winget install Lexicos.Autohotkey` (v1.x)
`scoop install autohotkey` (v2.x)

### [BespokeSynth](https://www.bespokesynth.com)\*
An open-source modular DAW. It can host 64-bit VST2, VST3, LV2, and CLAP plugins, and it has several dozen built-in modules. Bespoke is absolutely incredible, and EVERYTHING can be modulated. Unfortunately, the last official release (1.1.0) was released in November 2021, but it's still being frequently updated, so nightly builds are really the only way to get all the features.

`winget install BespokeSynth.BespokeSynth` (this installs 1.1.0, if you want the latest version, go to the [GitHub release page](https://github.com/BespokeSynth/BespokeSynth/releases) and download the nightly release)

### [Bulk Rename Utility](https://www.bulkrenameutility.co.uk)
A free (for personal use) utility for renaming multiple files at once.

`winget install TGRMNSoftware.BulkRenameUtility`

`scoop install bulk-rename-utility`

### [Cakewalk by Bandlab](https://www.bandlab.com/products/cakewalk)
This used to be my main DAW, before I discovered Bespoke, and later Waveform. I never actually record anything useful, I just mess around. The main reason I still have it on my computer is that it can host 32-bit plugins (of which I have a few). It hosts 32 and 64-bit VST2, VST3, and DirectX plugins. Its biggest disadvantage, in my opinion, is how annoying it is to get MIDI mapping and automation working. With Waveform, it's literally as simple as clicking MIDI Learn, changing a parameter, then moving a knob. That's how Cakewalk is *supposed* to work, but there's a whole bunch of steps you have to do first, and even after having done those, I still couldn't get it to work.

### [Carla](https://github.com/falkTX/Carla)\*
"Carla is a fully-featured modular audio plugin host, with support for many audio drivers and plugin formats." It's also open-source and runs as a VST2, VST3, CLAP, and LV2 plugin, as well as a standalone app. Although Carla and Bespoke are very similar, I prefer Bespoke for various reasons.

### [Chocolatey](https://chocolatey.org/install)\*
A package manager that I basically never use (I mostly use Winget instead). But it has a very useful `choco refreshenv` command, which refreshes the environment variables.

### [ClickPaste](https://github.com/Collective-Software/ClickPaste)\*
A tool that makes pasting into certain places easier. Basically, you click the icon in the notification area, then click where you want it to "paste." Then, instead of actually pasting, it quickly types out the contents of your clipboard. Very useful for VNC.

### [Clink](https://mridgers.github.io/clink)\*
Some command prompt utility I literally never use... although looking at the website, maybe I should. I installed it because [`autojump`](https://github.com/wting/autojump)\* depended on it, but then I couldn't get `autojump` working.

`winget install chrisant996.Clink`

`scoop install clink`

### [Discord](https://discord.com)
A chat/communication/messaging software.

`winget install Discord.Discord`

`scoop install discord`

### [DISTRHO Cardinal](https://github.com/DISTRHO/Cardinal)\*
An open-source VST2/VST3/LV2/CLAP/standalone version of VCV Rack v2.

### [Everything](https://www.voidtools.com)
An amazing tool that can quickly search every single file on a Windows computer. 

`winget install voidtools.Everything`

`scoop install everything`

### [EverythingToolbar](https://github.com/stnkl/EverythingToolbar)\*
An easy way to add Everything to the taskbar, made to look like normal Windows Search.

`winget install stnkl.EverythingToolbar`

### [Flow Launcher](https://github.com/Flow-Launcher/Flow.Launcher)\*
An open-source search utility with plenty of add-ons. I've looked at a lot of these, including [PowerToys](https://learn.microsoft.com/en-us/windows/powertoys) Run\*, [Keypirinha](https://keypirinha.com/), [ueli](https://ueli.app)\*, and [Wox](https://wox.one)\*.

`winget install Flow-Launcher.Flow-Launcher`

`scoop install flow-launcher`
 
### [Git](https://git-scm.com/)\*
Version control software... I'm assuming if you're reading this list, you know what it is.

`winget install Git.Git`

`scoop install git`

### [GitHub CLI](https://cli.github.com)\*
A command line application for Git/GitHub.

`winget install GitHub.cli`

### [GitHub Desktop](https://desktop.github.com)\*
A UI application for Git/GitHub.

`winget install GitHub.GitHubDesktop`

### [Google Chrome](https://google.com/chrome)
Google's web browser. I know it may not necessarily be the fastest or the most secure, but it's the one I use.

`winget install Google.Chrome`

`scoop install googlechrome`
 
### [Helios](https://github.com/nickzman/helios)
A nice screensaver
 
### [`midiflip`](https://github.com/1j01/midiflip)\*
A command line utility that can flip MIDI files. It supports wildcards, so you could do something like `midiflip -i "midis/**/*.mid" -o "transformed/"` It requires [NodeJS](https://nodejs.org/en)\*.
`npm install midiflip`

### [Micro](https://micro-editor.github.io/)\*
Basically an open-source, cross-platform version of `nano`, with more features.

`winget install zyedidia.Micro`

`scoop install micro`

### [Muse Hub](https://www.musehub.com)
An app used to download things like MuseScore 4, Muse Sounds, Audacity, and a couple of other things. But I'm literally going to uninstall this as soon as I finish this list... I hate this app for several reasons. Firstly, I just hate app installers that are also apps that need installation. It just seems ridiculous. Secondly (and most importantly), it installs a service that automatically runs in the background and makes it really annoying to get rid of. Uninstalling Muse Hub doesn't get rid of it, the folder it's in has... weird permissions, and you can't set the service to "manual" because you don't have permissions to do that, and you don't have permission to change the permission. While it could just be the torrent client it claims to be, there's no way to know, since it's not open-source. Basically, if it *is* a virus or something (I doubt it is, but still), it's a very well-designed one. 
 
### [MuseScore](https://musescore.org)\*
An open-source app for creating sheet msuic. I have both MuseScore 3 and MuseScore 4. I rarely use 4 because (in my opinion) it came out of beta *way* too early. It's got tons of bugs and WAY too much built-in unremovable reverb. But the features it adds (mostly the VST3 instrument/effect support) are huge improvements.
For MuseScore 4:

`winget install Musescore.Musescore`

`scoop install musescore`
For MuseScore 3 (untested):

`winget install MuseScore.Musescore -v 3.6.2.548021803`

`scoop install musescore@3.6.2.548021803`

### [Node.js](https://nodejs.org/en)\*
Not entirely sure what exactly this is (a "JavaScript Runtime Environment"), but I know that there a bunch of things that are installed with `npm` (which I assume is the Node Package Manager). I installed this for [`midiflip`](https://github.com/1j01/midiflip)\*.

`winget install OpenJS.NodeJS`

`scoop install nodejs`

### [Notepad++](https://notepad-plus-plus.org/downloads)\*
A text/code editor.

`winget install Notepad++.Notepad++`

`scoop install notepadplusplus`
 
### [O&O RegEditor](https://www.oo-software.com/en/ooregeditor)
A better registry editor. It's portable.
`scoop install regeditor`
 
### [Plane9](https://www.plane9.com)
A nice-looking screensaver.
 
### [Plogue Sforzando](https://www.plogue.com/products/sforzando.html)
An SFZ soundfont player, also available as VST2/VST3.

`winget install plogue.sforzando`
 
### [PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3)\*
I installed it one day, wondering what the difference was between Windows PowerShell and PowerShell 7... then discovered it had autocomplete and never used Windows PowerShell again. I've never really gone through any PowerShell tutorials, so I don't know how to actually use it on its own for scripting or anything, but it's nice to have autocomplete.

`winget install Microsoft.PowerShell`
 
### [PowerToys](https://learn.microsoft.com/en-us/windows/powertoys)
Several Windows utilities. I mostly just use Always On Top, but occasionally find uses for a couple of the others.

`winget install Microsoft.PowerToys`

`scoop install powertoys`
 
### [PuTTY](https://www.putty.org)\*
An SSH/Telnet client. I use it to connect to my Raspberry Pi.

`winget install PuTTY.PuTTY`

`scoop install putty`

### [Python](https://python.org)\*
A programming language you've probably heard of.

`winget install Python.Python.3.11` (or `Python.Python.2` or `Python.Python.3.[something]`)
`scoop install python`

### [QuickLook](https://github.com/QL-Win/QuickLook)\*
Exactly what it sounds like: Mac's Quick Look for Windows. When a file is selected, pressing space shows information about it.

`winget install QL-Win.QuickLook`

`scoop install quicklook`

### [SciTE4AutoHotkey](https://www.autohotkey.com/scite4ahk)\*
A code editor specifically for AutoHotkey.
 
### [Scoop](https://scoop.sh)\*
A package manager for Windows (but I usually just use Winget).

### [Shell](https://nilesoft.org)
A way to modify the default Windows context menu. Support for alternate file managers, such as Tablacus, is somewhat incomplete, and there are some features that don't exist yet, but the developer seems to be pretty quick at fixing bugs.

`winget install Nilesoft.Shell`

`scoop install nilesoft-shell`

### [Slack](https://slack.com)
A chat/communication/messaging software, but more business-oriented that Discord.

`winget install SlackTechnologies.Slack`

`scoop install slack`

### [SoundSwitch](https://soundswitch.aaflalo.me/)\*
Switches the audio input/output device with a hotkey. Due to the fact that I use an old audio interface, I occasionally have issues. Sometimes, one of the virtual USB audio ports (from the computer to the audio interface) will just randomly stop working for a few minutes, so I have to switch to another one. This app cuts that process from ten seconds to one.

`winget install AntoineAflalo.SoundSwitch`

`scoop install soundswitch`

### [Spitfire Audio App](https://www.spitfireaudio.com/library-manager)
Another installer app.... D: but this one I actually use sometimes, so I'm keeping it. You need it to install several sample libraries, such as LABS and "BBC Orchestra Symphony Discover."

### [Steam](https://store.steampowered.com/about)
A gaming app that you've probably heard of.

`winget install Valve.Steam`

### [SuperF4](https://stefansundin.github.io/superf4)\*
A much faster way to force quit an app than going to Task Manager.

`winget install StefanSundin.Superf4`

`scoop install superf4`
 
### [Surge XT](https://surge-synthesizer.github.io)\*
A VST2/VST3/CLAP/standalone synth. It can do quite a bit.

`winget install SurgeSynthTeam.SurgeXT`
 
### [Sysinternals](https://learn.microsoft.com/en-us/sysinternals)
Way too many Windows utilities, most of which I will *never* use.
A few individual utilities can be installed with Winget, use 
`winget search Sysinternals` to find them.
`scoop install sysinternals`

### [Tablacus Explorer](https://tablacus.github.io/explorer_en.html)\*
I don't have a built-in tabbed file manager, so I use this instead. It may not look as nice and... *Mac-like* (yes, I said it) as that of Windows 11, but it's portable, open-source, works great and is incredibly customizeable, though it does require a bit of learning. I've tried several alternatives, such as [Files](https://files.community), [OneCommander](https://onecommmander.com), and multiple versions of QTTabBar (no link because I don't want to spend ten minutes trying to figure out which one is actually the newest), but Tablacus was just the one I liked more.
 
### [TX16wX](https://www.tx16wx.com)
A software sampler that can load various soundfonts and other things like that.

### [Unity/Unity Hub](https://unity.com)
A game development environment, which I mostly use to make levels for Human Fall Flat (Unity Hub is the installer)
Unity Hub:

`winget install Unity.UnityHub`

`scoop install unity-hub-np`
Unity:

`winget install Unity.Unity.2020` (or 2021, 2022...)

### [VCV Rack](https://vcvrack.com/Rack)\*
A virtual modular synth, which is only somewhat open-source. The free community version is open-source, while the VST plugin Pro version is not.

`winget install VCVRack.VCVRack`

### [Visual Studio](https://visualstudio.microsoft.com)
"It’s how you make software." "What do you want to [code, build, debug, deploy, collaborate on, analyze, learn] today? Visual Studio can do that."

`winget install Microsoft.VisualStudio.2022.Community` (and probably other years/versions as well)

### [Visual Studio Code](https://code.visualstudio.com)\*
An open-source code editor with (quick Google) over 30,000 extensions.

`winget install Microsoft.VisualStudioCode`

### [Vital Synth](https://vital.audio/)\*
A VST2/VST3/standalone synth. The only source code that has been made publicly available hasn't been updated since April 2022, but it's still source code. I sort of prefer this to Surge XT. They both do similar things, but Vital is much more intuitive, although slightly more CPU-hungry.
 
### [VLC Media Player](https://www.videolan.org/vlc/)\*
An open-source media player with a lot of features.

`winget install VideoLAN.VLC`

`scoop install vlc`
 
### [VSTHost](https://www.hermannseib.com/english/vsthost.htm)\*
This is... a host... for VST plugins. About as simple as it gets. While this program *was* open-source (hence the asterisk), all versions since v1.16r are not. Anyway, several years ago, I found this on an old 32-bit Windows XP laptop, and had absolutely NO idea what it was, since at that point I'd never even heard of a VST plugin. A couple years later, I was looking for a way to get around what I thought was a problem with Cakewalk (turns out I just hadn't figured out how to do it) when I came across this. I downloaded it, then suddenly realized that I'd seen it before. I'll probably never use it again, since I've found other tools that do the job much better.
 
### [Waveform Free](https://www.tracktion.com/products/waveform-free)
Waveform Free is the only DAW I've ever found that has a free version that actually has all the features of the full version. The only difference is that the free version lacks a few built-in plugins (such as the arpeggiator and various effects). But there are free alternatives to all or most of them, so it really is just a DAW. It doesn't even have the usual "free version" things like nag screens, constant reminders that you don't have the full version, and track limits. It also has a really cool plugin rack feature.

### [WingetUI](https://github.com/marticliment/WingetUI)\*
An open-source UI for Winget and Scoop. Very useful, especially its update blacklisting feature.

`winget install SomePythonThings.WingetUIStore`

`scoop install wingetui`
 
### [WizTree](https://diskanalyzer.com/)
Basically [WinDirStat](https://windirstat.net/)\* but much faster and not open-source. It looks through all the files and shows a visual representation of their size. I don't really need this app with a 4TB spinning disk, but it would have been nice to have when I had a 256GB SSD.

`winget install AntibodySoftware.WizTree`

`scoop install wiztree`
 
### [Zoom](https://zoom.us)
A video converencing app that everyone who lived through COVID probably knows about.

`winget install Zoom.Zoom`

`scoop install zoom`

</details>

<details><summary><h1>Games</h1></summary>

These are all the games I *own*, although I don't currently have all of them installed.

### [Baba is You](https://store.steampowered.com/app/736260/Baba_Is_You)
A 2D tile-pushing puzzle game where the rules keep changing. I don't honestly know how best to explain this game, but basically, there are words that you can push around to control the way the world works. There's also a level editor and sharing system.

### [Biped](https://store.steampowered.com/app/1071870/Biped)
Honestly, very similar to Human Fall Flat, only it's 1-2 players controlling robots, and you control your feet instead of your hands. 

### [Human: Fall Flat](https://store.steampowered.com/app/477160/Human_Fall_Flat)
Blobby humanoids with gecko hands flop around trying to reach the end of the level. That's about it. You can also create levels with Unity, which is pretty cool.
 
### [FEZ](https://store.steampowered.com/app/224760/FEZ)
A perspective-based puzzle platformer, involving a 2-dimensional character, Gomez, discovering the power of rotation around the vertical axis using a magical fez. Although it doesn't have much of a story, it is an amazing game (even though I had to look up the answers to several puzzles). The music is also great. The weirdest thing about FEZ is the fact that there's one puzzle that nobody has really "solved." People have brute-forced it and posted the solution online, but even though the game's been around since 2012, nobody's figured out *why*.

### [ibb & obb](https://store.steampowered.com/app/95400/ibb__obb)
A 2-player co-op 2D platformer game with gravity reversal. That's about all I have to say.
 
### [Minetest](https://minetest.net)\*
Minetest is a free, open-source, cross-platform, portable voxel game engine and client (?), with which several games have been made, including Minetest Game, which is just kind of a basic built-in game. There's also MineClone 2, a game that is trying to recreate MineCraft. Minetest has easy multiplayer, and anyone can host a server. Also, all Minetest mods and games are written in Lua, meaning that they're also open-source and relatively easy to make, assuming you know how to code.

### [Portal](https://store.steampowered.com/app/400/Portal)
You probably know what this is. Set in the same universe as Half Life (which I've actually never played), a test subject wakes up in Aperture Laboratories. An AI named GLaDOS leads/forces her through several tests, most of which require a portal gun. Then a bunch of other things happen, that may or may not include baking and cake. It's a great game with phrases like "Fifteen Hundred Megawatt Aperture Science Heavy Duty Super-Colliding Super Button."

### [Portal 2](https://store.steampowered.com/app/620/Portal_2)
The sequel to Portal. 9 9 9 9 9 after the first game, Chell is awakened by a personality core named Wheatley, then has to do a bunch more testing, then several more things happen, which really establish the backstory of the game and prove that it's in the same universe as Half Life, as well as explaining why/how GLaDOS is the way she is. Did I mention there was also an entire 2-player cooperative sequel story included with it, as well as a built-in level editor and online (or split-screen) co-op? The worst thing about this game is the distinct absence of cake. How could you not play a game with quotes like, "When life gives you lemons, don't make lemonade. Make life take the lemons back! ... Demand to see life's manager! ... Do you know who I am? I'm the man who's going to burn your house down! With the lemons! I'm going to get my engineers to make a combustible lemon that BURNS YOUR HOUSE DOWN!"

### [Portal Stories: Mel](https://store.steampowered.com/app/317400/Portal_Stories_Mel)
A fan-made Portal 2 mod set between Portal and Portal 2. Plenty of *really* hard tests and also a reasonable story (although it's not nearly as entertaining as the original games). Also, the music is great.

### [Quantum Conundrum](https://store.steampowered.com/app/200010/Quantum_Conundrum)
A game where you can switch between dimensions (not like X, Y, Z, more like Fluffy, Heavy, etc) to complete levels.

### [StarCraft/Brood War/StarCraft Remastered](https://starcraft.com)
An RTS game involving 3 species (Terran/human, Zerg, and Protoss) fighting each other for various reasons. There's a story, as well as online multiplayer with AI.

### [StarCraft II](https://starcraft2.com)
The highly superiour sequel to StarCraft. With better graphics, better sound, better gameplay, and a level editor with WAY more features than I'm ever going to use.

### [Tachyon: The Fringe](https://store.steampowered.com/app/32760/Tachyon_The_Fringe)
A space game that's older than I am, about the "Galactic Spanning Corporation" (GalSpan) trying to take over very profitable sectors from Bora colonists. You get to choose which side you play on, meaning you really need to play through twice. There are definitely some compatibility issues with Windows 10, but I managed to get it to run (after about five hours of trying). To make sure I wouldn't have to go through all that again, I just compressed the folder and uploaded it somewhere so that even if I have to/choose to reset/replace my computer, I can still easily get a working version. (I don't know how well this method would work with the Steam version, but that seems to work mostly fine anyway).

### [There Is No Game: Wrong Dimension](https://store.steampowered.com/app/1240210/There_Is_No_Game_Wrong_Dimension)
A point and click puzzle game that does not want to be played... and also has a girlfriend.

</details>


<details><summary><h1>VST plugins</h1></summary>

### [Airwindows](https://airwindows.com)\*
A set of over **300** open-source VST effects with simple UI's. 
 
### [AGML II](http://www.amplesound.net/en/pro-pd.asp?id=7)
The best free virtual acoustic guitar I've been able to find (even though I play guitar, so I rarely use it). It has AU, VST2, VST3, AAX, RTAS, and standalone versions.
 
### [BlueArp](https://omg-instruments.com/wp/?page_id=63)
A MIDI arpeggiator VST2/AU plugin. Personally, I prefer Cream.

### [Cakewalk by Bandlab stuff](https://www.bandlab.com/products/cakewalk)
Cakewalk by Bandlab comes with several plugins. The DirectX plugins are not supported by many current DAWS, and BREVERB and TH3 *will not run* anywhere besides Cakewalk. But several other plugins (BOOST11, Channel Tools, SI-Bass Guitar, SI-Drum Kit, SI-Electric Piano, and SI-String Section) work anywhere that supports VST2.

### [Carla](https://github.com/falkTX/Carla)\*
"Carla is a fully-featured modular audio plugin host, with support for many audio drivers and plugin formats." It's also open-source and runs as a LADSPA, DSSI, VST2, VST3, AU, and LV2 plugin, as well as a standalone app. Although Carla and Bespoke are very similar, I prefer Bespoke for various reasons.

### [Cream](https://www.kirnuarp.com)
An excellent arpeggiator plugin. The "demo" version (what I have) is literally just the full version but with no presets.
 
### [Several Chowdhury DSP plugins](https://chowdsp.com/products.html)\*
These are interesting plugins. I'd have to say that the most unique is Chow Matrix, which is something for creating custom delay chains. One of the plugins says it "supports the following desktop plugin formats: VST3, AU, CLAP, AAX, Standalone, and LV2, as well as Standalone and AUv3 on iOS devices." The other plugin descriptions say nothing about what formats they're available in.

### [Drum Pro](https://www.studiolinked.com/drum-pro/)
Not the best drum plugin. It doesn't comply with the standard MIDI drum layout and although it has synthy drum sounds, it's just a rompler. 
 
### [DISTRHO Cardinal](https://github.com/DISTRHO/Cardinal)\*
An open-source VST2/VST3/LV2/CLAP/standalone version of VCV Rack v2.

### [Funimator](https://musictop69.wixsite.com/orchestools/media)\*
Sort of a filter/gain sequencer. It's open source, and available as a VST3.

### [Krush](https://www.tritik.com/product/krush)
A great bitcrusher/downsampler, basically essential for Fez-like music...

### [Magical 8bit Plug](https://ymck.net/app/magical-8bit-plug-en)\*
An 8-bit synth, meant to sound like that of old video games. It's open-source.

### [Melda Audio plugins](https://www.meldaproduction.com/downloads)
Around 40 free VST2/VST3/AU/AAX plugins, mostly effects, and several more paid ones. I particularly like Monastery Grand, a piano instrument for MSoundFactory.

### [MIDImonitor](https://web.archive.org/web/20180329184952/http://www.thepiz.org/plugins/?p=midiMonitor)\*
Apparently, the official website doesn't exist anymore. As far as I can tell, this plugin (and all the other plugins) are open-source and located [here](https://code.google.com/archive/p/pizmidi/downloads), but I'm not going to actually download things looking for the source code.

### [MT-PowerDrumKit](https://www.powerdrumkit.com)
A great sounding sampled drum kit VST/AU/AAX plugin. It has a rather annoying nag screen every time you load it, and it doesn't produce sound until you skip it. You can get rid of it by donating. You can route each drum individually, to up to 8 different stereo outputs. It also has a *grooves* feature, letting you easily find drumm patterns and drag them into your DAW.

### [Muse FX](https://www.musehub.com)
A few effects (Chorus, Compressor, De-esser, Delay, Master, Noise Gate, Pitch Fix, Reverb, Rotary, and two EQ effects). Unfortunately, they must be downloaded through Muse Hub.

### [Orchestools P1ano S](https://musictop69.wixsite.com/orchestools)\*
An open-source piano plugin. In my opinion, it doesn't sound that great. It's available as a VST3, "Linux plugin," and Windows standalone app.

### [Orchestools Sections](https://musictop69.wixsite.com/orchestools/orchestools-two)\*
Four great (and open-source) orchestral plugins: Strings, Brass, Winds, and Percussion, available as VST3 and... "Linux plugin," which I'm not going to download right now.

### [Ribs](https://hvoyaaudio.itch.io/ribs)
A VST/AU granular plugin.
 
### [PAPU](https://socalabs.com/synths/papu)\*
An open-source VST2, VST3, "Mac," and "Linux" plugin. I won't download those to figure out what the other formats are. It's a Nintendo Gameboy synth emulator.

### [Plogue Sforzando](https://www.plogue.com/products/sforzando.html)
An SFZ soundfont player, also available as VST2/VST3.

`winget install plogue.sforzando`
 
### [Spitfire BBC Symphony Orchestra Discover](https://www.spitfireaudio.com/bbc-symphony-orchestra-discover)
A good-quality orchestral VST2/VST3/AU/AAX plugin from Spitfire.

### [Spitfire LABS](https://labs.spitfireaudio.com)
A plugin and over 50 libraries for it. This is mentioned on basically every list of free instrument plugins, usually right at the top.

### [Steven Slate Drums 5.5 Free](https://stevenslatedrums.com/ssd5/#:~:text=GarageBand%20Big%20Sur-,SSD%205.5%20FREE,-Get%20the%20fully)
A great drum plugin with no nag screen like MT-PowerDrumKit has.
 
### [SUB Analog Drums](https://plugins4free.com/plugin/3133)
Not including a link to the official website because it just says, "unlock free download with a social share." It's a drum synth, available as VST and AU plugins.
 
### [Surge XT](https://surge-synthesizer.github.io)\*
A VST2/VST3/CLAP/standalone synth. It can do quite a bit.

`winget install SurgeSynthTeam.SurgeXT`

### [Tape Cassette 2](https://www.caelumaudio.com/CaelumAudio/?Page=TapeCassette2)
A tape simulator/emulator thing.
 
### [TX16wX](https://www.tx16wx.com)
A software sampler that can load various soundfonts and other things like that.
 
### [Valhalla free plugins](https://valhalladsp.com)
Several great reverb/delay plugins, available as VST2/VST3/AAX/AU plugins.
 
### [Vital Synth](https://vital.audio/)\*
A VST2/VST3/AU/LV2standalone synth. The only source code that has been made publicly available hasn't been updated since April 2022, but it's still source code. I sort of prefer this to Surge XT. They both do similar things, but Vital is much more intuitive, although slightly more CPU-hungry.

### WaveForm Free built-in stuff
Waveform Free comes with several plugins, but as far as I can tell, they probably aren't useful anywhere else. But it does have a reasonable synth, several effects, a rompler, and a couple of other things.

### [XOXOS plugins](https://xoxos.net/vst/)
A ton of (unfortunately 32-bit) VST plugins, including instruments and effects.
 
</details>

<details><summary><h1>Drivers/device-specific software</h1></summary>
 
 - The driver for an M-Audio Fast Track Ultra (kind of buggy on Windows 10, making me even more hesitant to try Windows 11). The driver is no longer available on the M-Audio website, so I'm not going to put a link here.
 - The [driver](https://m-audio.com/support/download/drivers/usb-midi-series-5.0.1) for an M-Audio KeyRig 25 (or O2 25, since they're literally the exact same device)
 - [A few things](https://www.usa.canon.com/support/p/canoscan-lide-100) for my CanoScan LiDE 100
 - [Software](https://support.brother.com/g/b/downloadlist.aspx?c=us&lang=en&prod=mfc7840w_all&os=10013) for a Brother MFC-7840W
 - [Logitech Unifying software](https://support.logi.com/hc/en-us/articles/360025297913). I somehow ended up with three Logitech Unifying mice and one keyboard, all of which are connected to the same receiver.
 
 </details>