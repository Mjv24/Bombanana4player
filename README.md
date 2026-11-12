#  BOMBANANA! — Web Edition


A free, browser-based 3D co-op bomb-defusal party game for **3 or 4 players**.
Every monkey has a handicap, nobody has the full picture, and the only way to survive is to talk, wave, point and panic together.


 Fan-made web game inspired by BOMBANANA! by Lefto Studio. Not affiliated with or endorsed by the original developers.
---


##  Play


1. Open the game link on your phone, tablet or computer.
2. Enter your monkey name and tap **Create room**.
3. Share the invite link ( **Copy** / **Share**) with your friends.
4. Everyone picks a seat, allows the microphone, and the host taps **Start bomb**.


No install, no account, no server. Rooms connect directly between browsers.


---


##  The Monkeys


| Monkey | Can | Can't |
|---|---|---|
|  **Blind** | Touch and operate the bomb | See colors, lights or screens (sees white outlines only) |
|  **Deaf** | See the bomb and his teammates' gestures, and talk | Hear anything |
|  **Mute** | Read the bomb manual, hear teammates, gesture | Speak |
|  **Bookworm** (4th player, optional) | Read the **other half** of the torn manual, hear Deaf & Blind, whisper to the Mute | See the bomb or anyone, touch, gesture or slap |


### Who hears whom


| Mode | Talking routes |
|---|---|
| **3 players** | Deaf → Blind & Mute · Blind → Mute · Mute speaks to nobody |
| **4 players** | Same as above, plus Bookworm → Mute only (Bookworm hears Deaf & Blind) |


Voice and text chat follow these rules automatically. In the lobby, everyone hears everyone for a quick voice check.


---


##  4-Player Mode: The Torn Manual


When a 4th player sits in the **Bookworm** seat, the manual is **torn in half**:


 The **Mute** keeps one half (blue, torn on the right).
 The **Bookworm** gets the other half (green, torn on the left).
Every page splits differently: table columns, rows, or whole tables. The split is **reshuffled every bomb**.
Neither half can solve a module alone. The Bookworm whispers his half, the Mute combines it with his own and gestures the answer to the Deaf, who tells the Blind.
With 3 players the Mute gets the whole book back and the game plays as normal.


---


##  Features


**3D scenes:** a cartoon minivan, plane, jungle train and banana truck, each with its own hazard
**13 puzzle modules:** Cables, Switches, Directions, Sliders, Symbols, Calculator, Sound Panel, Morse Code, Talking Monkey, Maze, Piano, plus chaos modules Pressure Valve and Alarm
**A new manual for every bomb**, so nothing can be memorised
**Secret rule twists** that only the Mute knows about (Mirror Madness, Upside-Down Day, Strike Shift)
**Hazards:** power outage, obstructions, loud interruptions, turbulence, tunnels, potholes
**3D gestures:** thumbs, pointing, finger counts 0–10, holding up objects
**3D slaps:** with handprints and dizzy stars
**Modes:** 30-level Campaign, Endless waves, Custom bombs
**Seat rotation** every round, so everyone plays every role
**Live teammate camera windows**
**Voice chat**
**Color-blind modes:** red-green and blue-yellow
**Mobile-friendly:** portrait and landscape, fullscreen, reconnect after switching apps
**Solo practice:** switch between all roles yourself, including 4-player mode
** Voice & sound check panel** for troubleshooting
**Old-version detection:** warns players running a cached old copy
---


##  Host It Yourself (GitHub Pages)


1. Create a new public repository.
2. Upload bombanana-v10.html (or rename it to index.html).
3. Go to **Settings → Pages**, set the source to the main branch and the / (root) folder, then save.
4. After about a minute your game is live at
   https://<your-username>.github.io/<repo-name>/bombanana-v10.html


  Voice chat needs an **https://** link. GitHub Pages provides one automatically.
  When you upload a new version, use a **new file name** (e.g. bombanana-v11.html) so phones don't load an old cached copy.
Netlify Drop (drag and drop the file) also works.


---


##  Tech


Single self-contained HTML file
[Three.js](https://threejs.org/) for 3D rendering
[PeerJS](https://peerjs.com/) for peer-to-peer rooms and voice relay
Web Audio API for sound effects and voice
No backend, no build step
---


##  Troubleshooting


| Problem | Fix |
|---|---|
| No voice | Use the https link, allow the microphone, tap the screen once to enable sound |
| "Out of date" banner | Tap **Update now**, or open the fresh invite link |
| Can't join the room | Make sure the host's tab is still open; rejoin with the same name to get your seat back |
| Anything else | Tap **** and share what the panel says |


---


##  License & Credits


Fan project for personal, non-commercial play.
BOMBANANA! and its concept belong to their respective owners.
