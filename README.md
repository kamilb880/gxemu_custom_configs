# GXemu Custom Configs

Custom PS2 emulator configuration files for use with **GXemu** on PlayStation 3 (CECHC/E models).

Each file is named after the game's PS2 serial ID (e.g. `SLUS_213.76`) and contains tuned emulation parameters to improve compatibility and performance.

All configs in this repository have been **tested and verified**. For compatibility details, refer to wiki's table:  
[PS2 GXemu Emulator Compatibility List](https://www.psdevwiki.com/ps3/PS2_GXemu_Emulator_Compatibility_List)

**Keep in mind to use Evilnat's CFW 4.92.2 or higher for external configs to be loaded!**  
If configs are still not loaded on emu start, check XAI Plugin in XMB: Network -> Custom Firmware Tools -> Updates -> PS2 EMUs MOD.

## How to use

1. Copy config files to your PS3's hard drive under:
   ```
   /dev_hdd0/vm/gx/
   ```
2. Launch selected PS2 game — modified GXemu will automatically apply matching config file.

## Game List

| Game Title | Region | Config File ID | Custom config description |
|---|---|---|---|
| Backyard Wrestling 2 - There Goes the Neighborhood | NTSC-U | `SLUS_210.43` | Config fixes textures flickering and screen shaking almost complately, but sound distortion is still present. |
| Bard's Tale | PAL | `SLES_531.54` | Config fixes flickering textures. |
| Bard's Tale, The | NTSC-U | `SLUS_208.03` | Config fixes flickering textures. |
| The Battleship | NTSC-J | `SLPM_624.97` | Config fixes SPS issues (Tamsoft engine game). |
| Black | NTSC-U | `SLUS_213.76` | Config fixes character teleporting and camera spinning at end of fourth level. |
| Blockbuster Hyper | NTSC-J | `SLPM_621.71` | Config fixes SPS issues (Tamsoft engine game). |
| Bloodrayne 2 | NTSC-U | `SLUS_208.62` | Config fixes white diagonal on-screen line and pixelated texture glitches. |
| Buffy the Vampire Slayer - Chaos Bleeds | NTSC-U | `SLUS_205.66` | Config fixes VIF1 issues (missing textures, overall slowdown). |
| Buffy the Vampire Slayer - Chaos Bleeds | PAL | `SLES_518.90` | Config fixes flickering graphics and frame drops (VIF1 issue). |
| Burnout 2 - Point of Impact | NTSC-U | `SLUS_204.97` | Config fixes graphical bugs. |
| Burnout 2 - Point of Impact | PAL | `SLES_510.44` | Config fixes graphical bugs. |
| Burnout 3 - Takedown | NTSC-U | `SLUS_210.50` | Config fixes Virtual Memory Card issues. |
| Bust-A-Bloc | NTSC-J | `SLKA_150.30` | Config fixes SPS issues (Tamsoft engine game). |
| Car Racing Challenge | PAL | `SLES_534.85` | Config fixes SPS issues (Tamsoft engine game). |
| Crash Bandicoot Twinsanity | NTSC-U | `SLUS_209.09` | Config fixes loading saved game freeze and random ingame freezes. Use game v2.00, as in v1.00 there is possible freeze after Dingodile boss fight - this is a fault of the unpatched game itself, not an emulation issue. |
| Crash Tag Team Racing | NTSC-U | `SLUS_211.91` | Config fixes coin FPS issue. |
| Crash Twinsanity | PAL | `SLES_525.68` | Config fixes loading saved game freeze and random ingame freezes. Use game v2.00, as in v1.00 there is possible freeze after Dingodile boss fight - this is a fault of the unpatched game itself, not an emulation issue. |
| Crazy Taxi | NTSC-U | `SLUS_202.02` | Config for NTSC-U version works properly with 'Greatest Hits' version of the game, but it also requires fixed gxemu. |
| The Daibijin | NTSC-J | `SLPM_624.84` | Config fixes SPS issues (Tamsoft engine game). |
| The Daikiju | NTSC-J | `SLPM_624.93` | Config fixes SPS issues (Tamsoft engine game). |
| David Douillet Judo | PAL | `SLES_543.66` | Config fixes missing portraits and stats while competitors selecting. |
| Dawn of Mana | NTSC-U | `SLUS_215.74` | Config fixes missing geometry and looped sound effects. |
| Demolition Girl | PAL | `SLES_534.03` | Config fixes SPS issues (Tamsoft engine game). |
| Disney's Golf | NTSC-U | `SLUS_205.32` | Config fixes all freezes (VIF1 related). Screen turns black on crossfades and while using shot meter. Shot meter is still visible. Framerate wise the game is fine and can be played through. |
| Evil Twin - Cyprien's Chronicles | PAL | `SLES_502.01` | Config fixes PS3 shutdown when creating save file. |
| Evolution Snowboarding | NTSC-U | `SLUS_205.46` | Config, fixes blackscreen after Konami logo. |
| Evolution Snowboarding | PAL | `SLES_513.92` | Config fixes black screen after Konami logo. |
| Evolution Snowboarding | NTSC-J | `SLKA_250.14` | Config fixes black screen after Konami logo. |
| Fighting Angels | PAL | `SLES_534.08` | Config fixes SPS issues (Tamsoft engine game). |
| The Gassen Sekigahara | NTSC-J | `SLPM_624.77` | Config fixes SPS issues (Tamsoft engine game). |
| Gran Turismo 3 - A-Spec | NTSC-U | `SCUS_971.02` | Config fixes the FMV stuttering, image shaking on car selection screen |
| Growlanser Generations [Disc 1] | NTSC-U | `SLUS_207.58` | Config fixes freeze on save game attempt. |
| Growlanser Generations [Disc 2] | NTSC-U | `SLUS_207.59` | Config fixes freeze on save game attempt. |
| International Cue Club | PAL | `SLES_509.14` | Config fixes flickering graphics. |
| Jak 3 | PAL | `SLES_536.17` | Config fixes texture flickering caused by mipmapping |
| Jak and Daxter - The Precursor Legacy | PAL | `SCES_503.61` | Config fixes short term freezes when picking up specific precursor orbs. Frame rate drops often but does not affect game speed. |
| Jak and Daxter - The Precursor Legacy | NTSC-U | `SCUS_971.24` | Config fixes short term freezes when picking up specific precursor orbs. Frame rate drops often but does not affect game speed. |
| Jaws Unleashed | NTSC-U | `SLUS_210.62` | Config fixes random freezing issue |
| Jaws Unleashed | PAL | `SLES_541.70` | Config fixes random freezing issue. |
| Klonoa 2 - Lunatea's Veil | NTSC-U | `SLUS_201.51` | Config fixes missing sounds. |
| Kourin! Zokusha Goddo! | NTSC-J | `SLPS_204.52` | Config fixes SPS issues (Tamsoft engine game). Flashing graphics and some slowdown. |
| Kuon | NTSC-U | `SLUS_210.07` | Config fixes the bugged Sugoroku minigame. |
| Kyousou! Tansha King | NTSC-J | `SLPM_623.99` | Config fixes SPS issues (Tamsoft engine game). |
| Makai Tensei | NTSC-J | `SLPM_653.29` | Config fixes SPS issues (Tamsoft engine game). |
| Makai Tensei | NTSC-J | `SLPM_658.72` | Config fixes SPS issues (Tamsoft engine game). |
| Maxxed Out Racing-Nitro | PAL | `SLES_545.45` | Config fixes SPS issues (Tamsoft engine game). |
| McDonald's Original Happy Disc | NTSC-J | `SCPM_851.01` | Config fixes crash after intro of Piposaru 2001 demo. PaRappa the Rapper 2 demo is playable. |
| Metal Gear Solid 3 - Subsistence | NTSC-U | `SLUS_212.43` | Config fixes SPS appearence when gun is raised, also enables Online play. |
| Mike Tyson - Heavyweight Boxing | NTSC-U | `SLUS_203.45` | Config fixes SPS and major graphical glitches on characters and initial splash screen freeze. |
| Motorbike King | PAL | `SLES_525.18` | Config fixes SPS issues (Tamsoft engine game). |
| Musashi Samurai Legend | NTSC-U | `SLUS_209.83` | Config fixes graphical glitches and wrong NPC calculations. |
| Myst III - Exile | PAL | `SLES_507.26` | Config fixes texture glitches and stuttering. |
| Oanechan Go Go Go! | NTSC-J | `SLPS_204.89` | Config fixes SPS issues (Tamsoft engine game). |
| Orphen - Scion of Sorcery | NTSC-U | `SLUS_200.11` | Config fixes freezing FMV sequences. Character voices in cutscenes are still doubled. |
| Party Girls | PAL | `SLES_534.06` | Config fixes massive SPS (Tamsoft engine game). |
| Party Girls | NTSC-J | `SLKA_150.42` | Config fixes SPS issues (Tamsoft engine game). |
| Pipo Saru [Ape Escape] 2001 | NTSC-J | `SCPS_110.14` | Config fixes black screen after intro. |
| R Racing Evolution | NTSC-U | `SLUS_207.21` | Config fixes minor SPS issues at the beginning of some races and while passing other cars. A slowdown appears on race start and overall speed is lowered, other than that game runs fine. |
| Rally Fusion - Race of Champions | NTSC-U | `SLUS_203.61` | Config (required for both PAL and NTSC versions) fixes freezing upon entering a race and opening start menu bug/freeze. |
| Rally Fusion - Race of Champions | PAL | `SLES_509.97` | Config (required for both PAL and NTSC versions) fixes freezing upon entering a race, opening start menu bug/freeze, and significantly improves frame rate. |
| Resident Evil Gun Survivor 2 - Code Veronica | PAL | `SLES_506.50` | Config from netemu increases FPS a bit, but there are still FPS slowdowns. The game is playable though. |
| The Runaway - Toumei Highway | NTSC-J | `SLPM_625.64` | Config fixes SPS issues (Tamsoft engine game). |
| Secret Agent Clank | NTSC-U | `SCUS_976.23` | Config fixes walk/run calculations and Fort Sprocket softlock caused by robot falling through floor. |
| Shadow of Zorro, The | PAL | `SLES_506.62` | Config fixes PS3 shutdown when creating save file. |
| Shin Megami Tensei - Persona 4 | NTSC-U | `SLUS_217.82` | Config restores missing HUD elements. |
| Shogun's Blade | PAL | `SLES_534.00` | Config fixes SPS issues (Tamsoft engine game). |
| Silent Hill 2 | NTSC-U | `SLUS_202.28` | Config fixes James disappearing leg issue. |
| Silent Hill 2 - Director's Cut | PAL | `SLES_511.56` | Config fixes James disappearing leg issue. |
| Silent Hill 3 | NTSC-U | `SLUS_206.22` | Config fixes camera inaccuracies. |
| The Silent Hill Collection [Disc1of3] | PAL | `SLES_503.82` | Config fixes James disappearing leg issue. |
| SNK vs Capcom Chaos | NTSC-J | `SLPS_253.16` | Config fixes slowdown and flickering graphics. |
| SSX | NTSC-U | `SLUS_200.95` | Config fixes freezes |
| Star Wars - Clone Wars | NTSC-U | `SLUS_205.10` | Config fixes freeze in 1st mission |
| Star Wars - The Clone Wars - Republic Heroes | NTSC-U | `SLUS_219.13` | Config fixes empty subtitles, lack of UI elements (icons, text, etc.) |
| Star Wars - The Force Unleashed | PAL | `SLES_546.58` | Config fixes graphical glitches, subtitles, and QTE buttons. |
| Star Wars - The Force Unleashed | NTSC-U | `SLUS_216.14` | Config fixes graphical issues: in-game, UI, hidden subtitles |
| Street Racing Syndicate | NTSC-U | `SLUS_205.82` | Config fixes freeze at splash screen on version 1.03. Disc version 2.00 works fine without custom config. |
| Summoner 2 | NTSC-U | `SLUS_204.48` | Config fixes black screen during the opening FMV sequence. |
| Tales of the Abyss | NTSC-J | `SLPS_255.86` | Config fixes freeze at Choral Castle. |
| Tales of the Abyss | NTSC-U | `SLUS_213.86` | Config fixes freeze at Choral Castle. |
| The Toubou Prisoner | NTSC-J | `SLPS_204.80` | Config fixes SPS issues (Tamsoft engine game). |
| True Crime - New York City | NTSC-J | `SLPM_664.73` | Config fixes freeze on opening menu screen and major controls/animation issues (VU0 delay slot issue). Updated config additionally fixes freezes near Grand Central Station and possibly others. |
| True Crime - New York City | PAL | `SLES_536.16` | Config fixes freeze on opening menu screen and major controls/animation issues (VU0 delay slot issue). Updated config additionally fixes freezes near Grand Central Station and possibly others. |
| True Crime - New York City | PAL | `SLES_536.18` | Config fixes freeze on opening menu screen and major controls/animation issues (VU0 delay slot issue). Updated config additionally fixes freezes near Grand Central Station and possibly others. |
| True Crime - New York City | NTSC-U | `SLUS_211.06` | Config fixes freeze on opening menu screen, major controls/animation issues and freezes near Grand Central Station (and possibly others). |
| Wallace & Gromit in Project Zoo | NTSC-U | `SLUS_206.47` | Config fixes black screen |
| Women's Swim Meet | NTSC-J | `SLPM_625.34` | Config fixes SPS issues (Tamsoft engine game). |
| Xenosaga - Episode I - Der Wille zur Macht | NTSC-U | `SLUS_204.69` | Config fixes immovable character at AGWS shop. |
| Yakuza | NTSC-U | `SLUS_213.48` | Config fixes game crashes in Ch.7 when loading "Mysterious Organization" and Ch.13 when loading "MBI.", Ch.3 after the funeral and a fight scene in Ch. 5. and in Ch.10 in mid-battle. |
| | Backyard Wrestling - Don't Try This At Home | NTSC-U | `SLUS_206.38` | Config fixes graphical glitches (VIF1 timing issue), but game still suffers huge frame drops and sound distortion. |

## Region Codes

| Code | Region |
|---|---|
| PAL | Europe (SCES, SLES, SCED, SLED) |
| NTSC-U | USA / Canada (SCUS, SLUS) |
| NTSC-J | Japan / Korea / Asia / Hong Kong (SCPM, SCPS, SLKA, SLPM, SLPS, SCAJ, SLAJ) |
| NTSC-C | China Mainland (SCCS) |

## Notes

- Config files are identified by PS2 serial ID, not game title. Keep the files named exactly as stored in this repo.
- Game titles follow the PS2 Games Masterlist from [psdevwiki.com](https://www.psdevwiki.com/ps3/PS2_Emulation/PS2_Games_Masterlist).
- Multiple config files for the same title cover different regional disc pressings.
- Two-disc games (e.g. Growlanser Generations) have separate configs per disc.
