# GXemu Custom Configs

Custom PS2 emulator configuration files for use with **GXemu** on PlayStation 3 (CECHC/E models).

Each file is named after the game's PS2 serial ID (e.g. SLUS_213.76) and contains tuned emulation parameters to improve compatibility and performance.

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

<table>
<thead><tr><th>Game Title</th><th>Region</th><th>Config File ID</th><th>Config description</th></tr></thead>
<tbody>
<tr><td>Backyard Wrestling - Don't Try This At Home</td><td nowrap>NTSC-U</td><td>SLUS_206.38</td><td>Config fixes graphical glitches (VIF1 timing issue), but game still suffers huge frame drops and sound distortion.</td></tr>
<tr><td>Backyard Wrestling 2 - There Goes the Neighborhood</td><td nowrap>NTSC-U</td><td>SLUS_210.43</td><td>Config fixes textures flickering and screen shaking almost complately, but sound distortion is still present.</td></tr>
<tr><td>Bard's Tale</td><td nowrap>PAL</td><td>SLES_531.54</td><td>Config fixes flickering textures.</td></tr>
<tr><td>Bard's Tale, The</td><td nowrap>NTSC-U</td><td>SLUS_208.03</td><td>Config fixes flickering textures.</td></tr>
<tr><td>Battleship, The </td><td nowrap>NTSC-J</td><td>SLPM_624.97</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Black</td><td nowrap>NTSC-U</td><td>SLUS_213.76</td><td>Config fixes character teleporting and camera spinning at end of fourth level.</td></tr>
<tr><td>Blockbuster Hyper</td><td nowrap>NTSC-J</td><td>SLPM_621.71</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Bloodrayne 2</td><td nowrap>NTSC-U</td><td>SLUS_208.62</td><td>Config fixes white diagonal on-screen line and pixelated texture glitches.</td></tr>
<tr><td>Buffy the Vampire Slayer - Chaos Bleeds</td><td nowrap>NTSC-U</td><td>SLUS_205.66</td><td>Config fixes VIF1 issues (missing textures, overall slowdown).</td></tr>
<tr><td>Buffy the Vampire Slayer - Chaos Bleeds</td><td nowrap>PAL</td><td>SLES_518.90</td><td>Config fixes flickering graphics and frame drops (VIF1 issue).</td></tr>
<tr><td>Burnout 2 - Point of Impact</td><td nowrap>NTSC-U</td><td>SLUS_204.97</td><td>Config fixes graphical bugs.</td></tr>
<tr><td>Burnout 2 - Point of Impact</td><td nowrap>PAL</td><td>SLES_510.44</td><td>Config fixes graphical bugs.</td></tr>
<tr><td>Burnout 3 - Takedown</td><td nowrap>NTSC-U</td><td>SLUS_210.50</td><td>Config fixes Virtual Memory Card issues.</td></tr>
<tr><td>Bust-A-Bloc</td><td nowrap>NTSC-J</td><td>SLKA_150.30</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Car Racing Challenge</td><td nowrap>PAL</td><td>SLES_534.85</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Crash Bandicoot Twinsanity</td><td nowrap>NTSC-U</td><td>SLUS_209.09</td><td>Config fixes loading saved game freeze and random ingame freezes. Use game v2.00, as in v1.00 there is possible freeze after Dingodile boss fight - this is a fault of the unpatched game itself, not an emulation issue.</td></tr>
<tr><td>Crash Tag Team Racing</td><td nowrap>NTSC-U</td><td>SLUS_211.91</td><td>Config fixes coin FPS issue.</td></tr>
<tr><td>Crash Twinsanity</td><td nowrap>PAL</td><td>SLES_525.68</td><td>Config fixes loading saved game freeze and random ingame freezes. Use game v2.00, as in v1.00 there is possible freeze after Dingodile boss fight - this is a fault of the unpatched game itself, not an emulation issue.</td></tr>
<tr><td>Crazy Taxi</td><td nowrap>NTSC-U</td><td>SLUS_202.02</td><td>Config for NTSC-U version works properly with 'Greatest Hits' version of the game, but it also requires fixed gxemu.</td></tr>
<tr><td>Daibijin, The</td><td nowrap>NTSC-J</td><td>SLPM_624.84</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Daikiju, The</td><td nowrap>NTSC-J</td><td>SLPM_624.93</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>David Douillet Judo</td><td nowrap>PAL</td><td>SLES_543.66</td><td>Config fixes missing portraits and stats while competitors selecting.</td></tr>
<tr><td>Dawn of Mana</td><td nowrap>NTSC-U</td><td>SLUS_215.74</td><td>Config fixes missing geometry and looped sound effects.</td></tr>
<tr><td>Demolition Girl</td><td nowrap>PAL</td><td>SLES_534.03</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Disney's Golf</td><td nowrap>NTSC-U</td><td>SLUS_205.32</td><td>Config fixes all freezes (VIF1 related). Screen turns black on crossfades and while using shot meter. Shot meter is still visible. Framerate wise the game is fine and can be played through.</td></tr>
<tr><td>Evil Twin - Cyprien's Chronicles</td><td nowrap>PAL</td><td>SLES_502.01</td><td>Config fixes PS3 shutdown when creating save file.</td></tr>
<tr><td>Evolution Snowboarding</td><td nowrap>NTSC-U</td><td>SLUS_205.46</td><td>Config, fixes blackscreen after Konami logo.</td></tr>
<tr><td>Evolution Snowboarding</td><td nowrap>PAL</td><td>SLES_513.92</td><td>Config fixes black screen after Konami logo.</td></tr>
<tr><td>Evolution Snowboarding</td><td nowrap>NTSC-J</td><td>SLKA_250.14</td><td>Config fixes black screen after Konami logo.</td></tr>
<tr><td>Fighting Angels</td><td nowrap>PAL</td><td>SLES_534.08</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Gassen Sekigahara, The</td><td nowrap>NTSC-J</td><td>SLPM_624.77</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Gran Turismo 3 - A-Spec</td><td nowrap>NTSC-U</td><td>SCUS_971.02</td><td>Config fixes the FMV stuttering, image shaking on car selection screen</td></tr>
<tr><td>Growlanser Generations [Disc 1]</td><td nowrap>NTSC-U</td><td>SLUS_207.58</td><td>Config fixes freeze on save game attempt.</td></tr>
<tr><td>Growlanser Generations [Disc 2]</td><td nowrap>NTSC-U</td><td>SLUS_207.59</td><td>Config fixes freeze on save game attempt.</td></tr>
<tr><td>International Cue Club</td><td nowrap>PAL</td><td>SLES_509.14</td><td>Config fixes flickering graphics.</td></tr>
<tr><td>Jak 3</td><td nowrap>PAL</td><td>SLES_536.17</td><td>Config fixes texture flickering caused by mipmapping</td></tr>
<tr><td>Jak and Daxter - The Precursor Legacy</td><td nowrap>PAL</td><td>SCES_503.61</td><td>Config fixes short term freezes when picking up specific precursor orbs. Frame rate drops often but does not affect game speed.</td></tr>
<tr><td>Jak and Daxter - The Precursor Legacy</td><td nowrap>NTSC-U</td><td>SCUS_971.24</td><td>Config fixes short term freezes when picking up specific precursor orbs. Frame rate drops often but does not affect game speed.</td></tr>
<tr><td>Jaws Unleashed</td><td nowrap>NTSC-U</td><td>SLUS_210.62</td><td>Config fixes random freezing issue</td></tr>
<tr><td>Jaws Unleashed</td><td nowrap>PAL</td><td>SLES_541.70</td><td>Config fixes random freezing issue.</td></tr>
<tr><td>Klonoa 2 - Lunatea's Veil</td><td nowrap>NTSC-U</td><td>SLUS_201.51</td><td>Config fixes missing sounds.</td></tr>
<tr><td>Kourin! Zokusha Goddo!</td><td nowrap>NTSC-J</td><td>SLPS_204.52</td><td>Config fixes SPS issues (Tamsoft engine game). Flashing graphics and some slowdown.</td></tr>
<tr><td>Kuon</td><td nowrap>NTSC-U</td><td>SLUS_210.07</td><td>Config fixes the bugged Sugoroku minigame.</td></tr>
<tr><td>Kyousou! Tansha King</td><td nowrap>NTSC-J</td><td>SLPM_623.99</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Makai Tensei</td><td nowrap>NTSC-J</td><td>SLPM_653.29</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Makai Tensei</td><td nowrap>NTSC-J</td><td>SLPM_658.72</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Maxxed Out Racing-Nitro</td><td nowrap>PAL</td><td>SLES_545.45</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>McDonald's Original Happy Disc</td><td nowrap>NTSC-J</td><td>SCPM_851.01</td><td>Config fixes crash after intro of Piposaru 2001 demo. PaRappa the Rapper 2 demo is playable.</td></tr>
<tr><td>Metal Gear Solid 3 - Subsistence</td><td nowrap>NTSC-U</td><td>SLUS_212.43</td><td>Config fixes SPS appearence when gun is raised, also enables Online play.</td></tr>
<tr><td>Mike Tyson - Heavyweight Boxing</td><td nowrap>NTSC-U</td><td>SLUS_203.45</td><td>Config fixes SPS and major graphical glitches on characters and initial splash screen freeze.</td></tr>
<tr><td>Motorbike King</td><td nowrap>PAL</td><td>SLES_525.18</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Musashi Samurai Legend</td><td nowrap>NTSC-U</td><td>SLUS_209.83</td><td>Config fixes graphical glitches and wrong NPC calculations.</td></tr>
<tr><td>Myst III - Exile</td><td nowrap>PAL</td><td>SLES_507.26</td><td>Config fixes texture glitches and stuttering.</td></tr>
<tr><td>Oanechan Go Go Go!</td><td nowrap>NTSC-J</td><td>SLPS_204.89</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Orphen - Scion of Sorcery</td><td nowrap>NTSC-U</td><td>SLUS_200.11</td><td>Config fixes freezing FMV sequences. Character voices in cutscenes are still doubled.</td></tr>
<tr><td>Party Girls</td><td nowrap>PAL</td><td>SLES_534.06</td><td>Config fixes massive SPS (Tamsoft engine game).</td></tr>
<tr><td>Party Girls</td><td nowrap>NTSC-J</td><td>SLKA_150.42</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Pipo Saru [Ape Escape] 2001</td><td nowrap>NTSC-J</td><td>SCPS_110.14</td><td>Config fixes black screen after intro.</td></tr>
<tr><td>R Racing Evolution</td><td nowrap>NTSC-U</td><td>SLUS_207.21</td><td>Config fixes minor SPS issues at the beginning of some races and while passing other cars. A slowdown appears on race start and overall speed is lowered, other than that game runs fine.</td></tr>
<tr><td>Rally Fusion - Race of Champions</td><td nowrap>NTSC-U</td><td>SLUS_203.61</td><td>Config (required for both PAL and NTSC versions) fixes freezing upon entering a race and opening start menu bug/freeze.</td></tr>
<tr><td>Rally Fusion - Race of Champions</td><td nowrap>PAL</td><td>SLES_509.97</td><td>Config (required for both PAL and NTSC versions) fixes freezing upon entering a race, opening start menu bug/freeze, and significantly improves frame rate.</td></tr>
<tr><td>Resident Evil Gun Survivor 2 - Code Veronica</td><td nowrap>PAL</td><td>SLES_506.50</td><td>Config from netemu increases FPS a bit, but there are still FPS slowdowns. The game is playable though.</td></tr>
<tr><td>Runaway - Toumei Highway, The</td><td nowrap>NTSC-J</td><td>SLPM_625.64</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Secret Agent Clank</td><td nowrap>NTSC-U</td><td>SCUS_976.23</td><td>Config fixes walk/run calculations and Fort Sprocket softlock caused by robot falling through floor.</td></tr>
<tr><td>Shadow of Zorro, The</td><td nowrap>PAL</td><td>SLES_506.62</td><td>Config fixes PS3 shutdown when creating save file.</td></tr>
<tr><td>Shin Megami Tensei - Persona 4</td><td nowrap>NTSC-U</td><td>SLUS_217.82</td><td>Config restores missing HUD elements.</td></tr>
<tr><td>Shogun's Blade</td><td nowrap>PAL</td><td>SLES_534.00</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Silent Hill 2</td><td nowrap>NTSC-U</td><td>SLUS_202.28</td><td>Config fixes James disappearing leg issue.</td></tr>
<tr><td>Silent Hill 2 - Director's Cut</td><td nowrap>PAL</td><td>SLES_511.56</td><td>Config fixes James disappearing leg issue.</td></tr>
<tr><td>Silent Hill 3</td><td nowrap>NTSC-U</td><td>SLUS_206.22</td><td>Config fixes camera inaccuracies.</td></tr>
<tr><td>Silent Hill Collection, The</td><td nowrap>PAL</td><td>SLES_503.82</td><td>Config fixes James disappearing leg issue.</td></tr>
<tr><td>SNK vs Capcom Chaos</td><td nowrap>NTSC-J</td><td>SLPS_253.16</td><td>Config fixes slowdown and flickering graphics.</td></tr>
<tr><td>SSX</td><td nowrap>NTSC-U</td><td>SLUS_200.95</td><td>Config fixes freezes</td></tr>
<tr><td>Star Wars - Clone Wars</td><td nowrap>NTSC-U</td><td>SLUS_205.10</td><td>Config fixes freeze in 1st mission</td></tr>
<tr><td>Star Wars - The Clone Wars - Republic Heroes</td><td nowrap>NTSC-U</td><td>SLUS_219.13</td><td>Config fixes empty subtitles, lack of UI elements (icons, text, etc.)</td></tr>
<tr><td>Star Wars - The Force Unleashed</td><td nowrap>PAL</td><td>SLES_546.58</td><td>Config fixes graphical glitches, subtitles, and QTE buttons.</td></tr>
<tr><td>Star Wars - The Force Unleashed</td><td nowrap>NTSC-U</td><td>SLUS_216.14</td><td>Config fixes graphical issues: in-game, UI, hidden subtitles</td></tr>
<tr><td>Street Racing Syndicate</td><td nowrap>NTSC-U</td><td>SLUS_205.82</td><td>Config fixes freeze at splash screen on version 1.03. Disc version 2.00 works fine without custom config.</td></tr>
<tr><td>Summoner 2</td><td nowrap>NTSC-U</td><td>SLUS_204.48</td><td>Config fixes black screen during the opening FMV sequence.</td></tr>
<tr><td>Tales of the Abyss</td><td nowrap>NTSC-J</td><td>SLPS_255.86</td><td>Config fixes freeze at Choral Castle.</td></tr>
<tr><td>Tales of the Abyss</td><td nowrap>NTSC-U</td><td>SLUS_213.86</td><td>Config fixes freeze at Choral Castle.</td></tr>
<tr><td>Toubou Prisoner, The</td><td nowrap>NTSC-J</td><td>SLPS_204.80</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>True Crime - New York City</td><td nowrap>NTSC-J</td><td>SLPM_664.73</td><td>Config fixes freeze on opening menu screen and major controls/animation issues (VU0 delay slot issue). Updated config additionally fixes freezes near Grand Central Station and possibly others.</td></tr>
<tr><td>True Crime - New York City</td><td nowrap>PAL</td><td>SLES_536.16</td><td>Config fixes freeze on opening menu screen and major controls/animation issues (VU0 delay slot issue). Updated config additionally fixes freezes near Grand Central Station and possibly others.</td></tr>
<tr><td>True Crime - New York City</td><td nowrap>PAL</td><td>SLES_536.18</td><td>Config fixes freeze on opening menu screen and major controls/animation issues (VU0 delay slot issue). Updated config additionally fixes freezes near Grand Central Station and possibly others.</td></tr>
<tr><td>True Crime - New York City</td><td nowrap>NTSC-U</td><td>SLUS_211.06</td><td>Config fixes freeze on opening menu screen, major controls/animation issues and freezes near Grand Central Station (and possibly others).</td></tr>
<tr><td>Wallace & Gromit in Project Zoo</td><td nowrap>NTSC-U</td><td>SLUS_206.47</td><td>Config fixes black screen</td></tr>
<tr><td>Women's Swim Meet</td><td nowrap>NTSC-J</td><td>SLPM_625.34</td><td>Config fixes SPS issues (Tamsoft engine game).</td></tr>
<tr><td>Xenosaga - Episode I - Der Wille zur Macht</td><td nowrap>NTSC-U</td><td>SLUS_204.69</td><td>Config fixes immovable character at AGWS shop.</td></tr>
<tr><td>Yakuza</td><td nowrap>NTSC-U</td><td>SLUS_213.48</td><td>Config fixes game crashes in Ch.7 when loading "Mysterious Organization" and Ch.13 when loading "MBI.", Ch.3 after the funeral and a fight scene in Ch. 5. and in Ch.10 in mid-battle.</td></tr>
</tbody>
</table>

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
