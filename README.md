# CoCo Jam 2020 (48-Hour Game Jam)

<img src="https://omaralfarajat.github.io/images/honey-home/drunk.png"  height = "135" width="240" /> <img src="https://omaralfarajat.github.io/images/honey-home/inpain.png" height = "135" width="240" /> <img src="https://omaralfarajat.github.io/images/honey-home/failed.png" height = "135" width="240" />

**Download and Play (Windows, Linux, Mac):** <a href="https://gotl.itch.io/honey-im-home">gotl.itch.io/honey-im-home</a>  

**Play in Browser:** <a href="https://simmer.io/@OhmZ/honey-i-m-home">simmer.io/@OhmZ/honey-i-m-home</a>

**Ranked Top 5:** <a href="https://itch.io/jam/coco-jam/results ">itch.io/jam/coco-jam/results</a>

**Attributions:**
- Unity Letterboxing package obtained from <a href="https://github.com/seleb/Better-Minimal-WebGL-Template">github.com/seleb/Better-Minimal-WebGL-Template</a>
- Halfway jingle sound effect obtained from <a href="https://www.zapsplat.com/music/musical-game-tone-mystery-complete-end/">zapsplat.com/music/musical-game-tone-mystery-complete-end</a>

## Introduction
Developed by our team "GoreNest" and submitted for the 48-hour <a href="https://itch.io/jam/coco-jam/entries">CoCo Jam</a> held by Concordia Game Dev and ETS Conjure. The theme of the game jam was "No Pain, No Gain". 

## Description
* Pain is indicated by the red overlay.
* Drunkenness is indicated by the blur and wobbling effects.
* Walking into garbage increases the pain, but sobers you up.
* Walking into the green beers gets you drunker, but lowers the pain.
* It's much more difficult to move around when you're drunk.
* Either too much pain or being too drunk will make you collapse. Make sure to balance walking into garbage and drinking road beers. 

## Controls
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax"><span style="font-weight:bold">Input</span></th>
    <th class="tg-0lax"><span style="font-weight:bold">Action</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">W</td>
    <td class="tg-0lax">Move forward</td>
  </tr>
  <tr>
    <td class="tg-0lax">A</td>
    <td class="tg-0lax">Move left</td>
  </tr>
  <tr>
    <td class="tg-0lax">D</td>
    <td class="tg-0lax">Move right</td>
  </tr>
  <tr>
    <td class="tg-0lax">Esc</td>
    <td class="tg-0lax">Exit the game at any point</td>
  </tr>
</tbody>
</table>

## Credits
Programmers: <a href="https://github.com/OmarAlFarajat">Omar Al-Farajat</a> and <a href="https://github.com/lyonelz96">Lyonel Zamora</a>.

Artists: <a href="https://github.com/Tjsreel">Tj'sReel</a> and <a href="https://github.com/GOTLTL">John Tran</a>.

Animator: <a href="https://github.com/Tjsreel">Tj'sReel</a>.

Sound and Music: <a href="https://github.com/GOTLTL">John Tran</a>.

### Contributions 
<a href="https://github.com/OmarAlFarajat">Omar Al-Farajat</a>
* A "treadmill" effect to make the road and environment move under the player sprite to give the impression of moving forward in 3D space. 
* Scaling and translating the house from under a sprite mask on the horizon of the road to give the impression of approaching it from a distance. 
* An obstacle spawner that uses a fixed vector fan and relative sprite scaling to give the impression that obstacles are placed on the road in 3D. 
* A simple audio manager for music and sound effects.
* General code for tying scenes together and triggering game state events. 

[Lyonel Zamora](https://github.com/lyonelz96)
 * Drunk movement; The character gets more difficult to control the drunker he is, and easier to control the more in pain he is.
 * Implemented the Drunk VFX using Unity's Post-Processing. They get more intense the drunker the character is.
 * Worked on some basic scenes like the Menu and the Intertitles scenes.
 * Implemented the Pain overlay that appears as the character gets hit with objects on the street.
