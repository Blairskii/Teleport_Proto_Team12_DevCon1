**Digital Prototype Development - GAME-10016** Group 12 - Jake, Blair
and Sergio

**“Tele-Frag” - Design Documentation**

**Overview:**

Tele-Frag is a sci-fi first-person shooter that seeks to push the
concept of the “Tele-Frag” to the limit, putting the player through
fast-paced arena FPS-style combat while allowing the player to instantly
teleport to and (usually) destroy any enemy they face. The ISS Virtue is
being invaded, and it’s on the player to use their skills to fend off
the forces of The Resonant.

**Objective:**

![telefrag](https://media.githubusercontent.com/media/Blairskii/Teleport_Proto_Team12_DevCon1/refs/heads/master/Assets/gZdRF.png)

We seek to create an FPS prototype that investigates how “Tele-Fragging”
can be used as a central mechanic for navigation, combat and
problem-solving, and to explore the possibilities for this mechanic’s
broader application as a central part of gameplay. What we want to know
is: how engaging is this as a central combat mechanic, and what
constraints does it place on level design?

This mechanic allows for interesting combat scenarios, and enables us to
create FPS combat encounters that exist as more of a “puzzle” than
traditional FPS encounters. This is also a fairly unexplored mechanic in
games, and while teleporting is in all sorts of games, tele-fragging is
actually fairly rare. Even rarer is a game that utilizes this as a main
mechanic that will be used to solve combat puzzles, navigate levels, and
otherwise just to defeat enemies.

**Design Rationale**

The idea for Tele-Frag originated from a desire to see a well-known
mechanic used in other games used on its own as a main, central
mechanic. Tele-Fragging is an interesting and engaging mechanic, and the
limitation of it only being usable on enemies adds challenge, forcing
the player to consider how they can leverage enemy positions and firing
lines to navigate a level. The player being able to teleport anywhere
would eliminate the challenge present here as they’d just be able to
teleport straight to where they need to go, whether it’s the exit
itself, or a path that leads there, and so adding that limitation forces
the player to think more carefully about how they can apply it,
potentially in creative ways. This mechanic will strongly influence
level design, to the point where the challenge of this game will come
less from combat with enemies but more from navigating the levels
*while* doing combat with enemies.

![tf2telefrag](https://media.githubusercontent.com/media/Blairskii/Teleport_Proto_Team12_DevCon1/refs/heads/master/Assets/300px-Telefrag.png)

Considering that enemies are the means by which you teleport, enemy
placement will become incredibly important. It is key that we ensure
that enemies are both dynamic enough that the whole game isn’t *just*
telefragging, and static enough that players will be able to
consistently line up the shots and tele-frags they need to hit once
they’ve figured out how to beat the level. These considerations around
level design and enemy placement are why we are focusing on evaluating
the constraints this mechanic places on level design, as with a game
like this, just like Superhot or Neon White, the level itself is the
challenge, while the enemies are mostly there to provide some resistance
as the player works out how to reach the exit.

**Team & Roles:** 

- Jake - Design, Documentation
  
- Blair - Programming, Design
  
- Sergio - Assets, Level Design

**Core Gameplay:**

The real “meat and potatoes” of the game is using your weapons and
ability in creative ways to defeat enemies and navigate a level. In each
level, there will be a number of enemies. Some of these enemies will be
placed in strategically important spots while others won’t, and the
player will have to decide what enemies to kill with their guns and what
enemies to kill with a tele-frag. The player only has so many uses of
this tele-frag ability, however, and so choosing the correct target to
use it on is important. The goal of each level is to reach an exit, but
killing enemies will award additional points, which contributes to a
score displayed at the end of a level. Each level will be timed, and the
more quickly you beat a stage, the higher your score will be. A restart
level/respawn button will be available on the pause menu, which will be
useful for speedrunners or those just looking to optimize their score in
a particular level.  

**Core Mechanics:**

- **Moving and Shooting**

  - The ability to move and shoot is the most basic and central part of
    any FPS, and it is no different here. The player must be able to
    move around the level quickly, and fire and aim smoothly and
    precisely. This game will play something like an arena shooter of
    the past, and so players need to be able to move in order to avoid
    projectiles, stay away from enemies that fight in close range, and
    to navigate the level itself. Similarly, the shooting must also be
    precise and snappy, as Tele-Frag’s combat will be fast-paced, and
    players will not be able to afford missing a large number of their
    shots due to “bloom”, random spread patterns, or poor mouse controls
    that don’t offer raw input.

- **Jumping and Dashing**

  - While moving and shooting is essential, no less essential is the
    ability to jump. Players must be able to jump, or possibly even
    double jump so that they can maneuver around the levels, navigate
    platforming challenges, dodge attacks that travel along the floor,
    and otherwise not feel like their feet are nailed to the floor.
    Dashing is significantly less essential, but works in conjuction
    with jumping to greatly enhance player mobility, and provide new
    avenues for fast-paced action combat.

- **The Bio-Kinetic Resonator**

![resonator](Assets\TF2_TimeGauntlet_Concept.png)

- This is an advanced prototype of a device that allows the user to
  synchronize their energetic waveform with that of others’, which via
  quantum tunnelling, teleports the user to a location within the mass
  of the target. Upon arriving at the target, the energy transfer of the
  teleportation, combined with the sudden appearance of a human where
  some unfortunate alien’s innards previously were, typically causes a
  violent and gory explosion of viscera. More straightforwardly, this
  ability will allow a player to aim at an enemy, use the teleport
  ability, and instantly appear where the enemy was, with the enemy
  being killed the moment they teleport. The device has a limited number
  of charges that will be replenished between combat encounters, or
  could be replenished via another mechanic during an encounter (such as
  with an execution/finisher move that will kill the enemy and restore a
  charge).

**Graphics and Aesthetics:**

Tele-Frag is a sci-fi game, and so much of the game will be steeped in a
range of different sci-fi aesthetics, such as the more gritty and
industrial parts of the ship in the lower levels, the clean and pristine
looking halls and rooms of the upper levels, and the functional and
utilitarian look of the middle decks. Graphically, the game will take on
a gritty, retro FPS aesthetic, similar to that of the original Quake,
Duke Nukem 3D or Half-Life. While games like Duke Nukem 3D use sprites
for their weapons, enemies, pickups and more, Tele-Frag would use simple
or low-poly 3D models to represent these things, similar to what
Half-Life does for them.

![halflife](Assets/33e23e70-857f-11ee-bbc6-eb8368f39728.png)

**Interface, HUD and UI**

The UI and Interface in Tele-Frag will be fairly utilitarian, showing
mostly what is necessary, and eschewing most non-essential elements.
From the menu, beneath the game’s logo, the player will have the
following options: *Start* or *Continue* (depending on whether or not
they already have an in-progress playthrough), *Load Save*, *Settings*,
*Exit*, and a small *Credits* button in the corner. The menu will be
styled as the green-tinted and slightly blurry screen of one of the
numerous consoles or terminals throughout the ship. The buttons
described previously will be styled as part of the UI of the old PC, as
will the logo of the game itself. The HUD of Tele-Frag will also be
fairly utilitarian. In the bottom right corner will be: Ammo remaining
in your magazine, Ammo in reserve, and the name or an image of the
weapon you are currently using. In the top left will be a medium-sized
circular minimap that will display the player’s location, any pickups or
ammo available, and the location of objective critical items, as well as
all of the other rooms they have visited. Unvisited rooms will remain
obscured on the map, and neither the room shape nor any contents within
will be visible on the map until the player has traveled close enough.

**Narrative Hook:**

It is the year 2153. Within a century of first landing on the moon,
humanity had crossed yet another great hurdle. Interstellar Space. With
the development of the Vernier-Baxter Electrothermal Engine in 2060,
humanity’s dream of conquering the stars was finally within reach. While
the rocket engines of the past were too weak and inefficient to carry
passengers or cargo across vast interstellar distances, the
Vernier-Baxter Engine shattered the limitations we once faced, and
finally allowed us to travel across the galaxy quickly.

What followed was the largest economic and industrial boom in human
history; thousands and thousands of new companies emerged, each of them
setting out to claim a little piece of the galaxy for themselves. A new
frontier was ripe for the picking, and none would let this opportunity
go to waste. With the advent of Interstellar Transportation came new
industries springing up: Interstellar Shipping companies, Private
Security companies, Asteroid Mining companies, Dyson Sphere-producing
energy companies and far more would all crop up, all of them fitting
into a new niche carved out for them in the frontier. 

For the next thirty years, all would see the benefits and prosperity
attained from humanity’s conquest of the stars, and with how quickly
we’d spread across the galaxy, it seemed apparent to all that we were
merely at the foot of a vast and prosperous future for humanity. 

Key words: Seemed apparent. 

Unfortunately, it was not to be. In early 2096, a bug began appearing on
computers all across Earth, which was now the seat of humanity’s
galaxy-spanning empire. This bug, which came to be known as the Silicon
Plague, slowly began to corrupt any and all devices it encountered,
network connected or otherwise, eventually reducing all of the data on
said devices into useless junk data. While it could, in theory, have
been contained on Earth, we were slow to respond, and by the scale of
the problem was uncovered, it had already been spread throughout the
galaxy via the FTL Communications System. It took three months for this
bug to be fully discovered, and in that time, it had already consumed
approximately 18% of the data available on the now-shattered remains of
the galactic internet. 18% of the entire internet just deleted. Gone.
That’s not even including the rest of the data on devices that aren’t
connected to the internet. Once the scale of the damage was realized,
authorities immediately leapt into action, desperate to save as much of
the data as possible.

Over the next two years, nearly every cybersecurity and cyberwarfare
expert across the galaxy worked tirelessly to undo the damage and
restrain if not subdue the virus. The virus was too widespread to be
effectively contained at this point, but not all was lost. While this
virus was able to withstand everything humanity had thrown at it so far,
there was one fatal weakness it had that hadn’t been taken advantage of
yet. Its own self-improvement algorithms. Unlike many other viruses, the
infamous virus that caused the Silicon Plague was designed to constantly
improve itself based on the conditions it faces. “Recursive
self-improvement” was what they called it. This was why it had been so
hard to remove. Any time you’d think you were about to destroy it, it’d
develop some new kind of defense and evade destruction once again. After
months of cyberwarfare against this virus, humanity’s best and brightest
finally unveiled their secret weapon: Longinus, a one-of-a-kind
cyberwarfare program developed under the utmost secrecy, designed to
pierce the defenses of quite literally any program put against it.
Longinus was immensely successful against the Silicon Plague, and
managed to abuse the self-improvement algorithm of the virus to get it
to destroy itself, like a snake eating its own tail. 

When all was said and done, the Silicon Plague had utterly ravaged
humanity. Even putting aside the immense economic destruction, the blood
that had been shed from all of the chaos that erupted, and the draconian
governments that emerged in the wake of the Silicon Plague, one of the
most tragic losses to the Silicon Plague was the sense of connection
that had emerged in the galaxy. It was a prosperous time, and humanity
was on the up and up. There was this notion that, despite the fact that
we may exist on opposite ends of the galaxy, we’re still in this
together. We’re all riding the same wave.

After the Silicon Plague, that notion no longer existed. With most of
the systems humanity used to unite across the stars having been trashed,
many worlds quickly devolved into revolts, civil wars, societal
collapses, and just wild, uncontrolled violence. With the brief Golden
Age of humanity decisively coming to a close by the early 2110s, a new
era of suspicion, strife, and cynicism would emerge, and with it, a new
coat of paint on the same old power structures.

It is now 2153, forty years after the end of the Golden Age. With the
passing of the Silicon Plague came the fall of the old Grand
Conglomerate, and the rise of the new human empire, The Sovereign.
Seeking to appease the older demographics still nostalgic for the
interstellar expeditions of old, and to establish some new conquests of
their own, The Sovereign have since tasked the Interstellar Expedition
Committee with launching a new wave of expeditions. 

You are Sgt. Weyland, a recent hire aboard the ISS Virtue, the IEC’s
brand new flagship. You’ve been serving aboard the ship for the last two
months as a security officer, since it first departed Earth. One day,
while the ship was collecting thermal energy from a nearby star, during
your regular patrol on the stasis decks, where all of the non-essential
passengers and crew remain in stasis, awaiting arrival at their
destination, you notice a strange sound. “THUNK”. “THUNK”. “THUNK”. You
hear a few more of these noises coming from outside the ship’s hull
before you realize what they are. “Oh fuck…BREACHING CHARGES!”. “BOOM!”.
In an instant, the entire room lights up. You are hit by a powerful
shockwave one second, and in the next, your consciousness dims. The
entire room is instantly depressurized, and you are pulled out into
space along with the smoke, fire, and the rest of the objects in the
room. Luckily, before you are pulled out, your suit’s systems pick up on
what is happening and react, immediately sealing and pressurizing your
suit. 

After taking a moment to reorient yourself after coming back to your
senses, you realize that you’re no longer inside the ship, and are
slowly drifting further away from the ship. With no thrusters. This is
bad. Even with air, if you can’t get back to the ship, you’ll just be
stuck out here until your air runs out. Spotting a lone maintenance
drone drifting around not far off from where you are headed, you hatch
up a plan. As it stands, you’re not going to be able to reach the drone,
but if you can throw your rifle and pack far enough away, it should push
you enough that you can drift within reach. Not ideal, but what good is
any of it if you die out in space?  “Okay, gotta hit this or else I
suffocate in the void of space. Let’s do this.” 

You begin focusing. Your eyes narrow and a bead of sweat begins to form
on your forehead. “Easy does it now.” You carefully unhook your backpack
from your suit and bring it around in front of you. Your eyes focus in
on the drone, and you spend a tense minute working out where you need to
throw the pack to get the right angle. “Okay . . . I got it. Just gotta
throw it this way…”

You shift into position, coiled like a snake ready to strike. Just a few
moments now, and you’ll be right where you need to be. More sweat forms
on your forehead. Your nose itches. Your belt is bothering you. Might
have tied your shoes too tight. In those few painfully tense moments,
it’s like everything that could possibly distract or annoy you unites as
one to screw with you. But you persist. “IT’S GO TIME!” You throw the
pack and rifle together as hard as you physically can. It doesn’t move
you much, but it’s enough to move you into the trajectory of the drone.
“YES!” you cry out triumphantly within your pressurized helmet. A few
moments later, you swing your arm out and just manage to get a firm grab
on the side of the maintenance drone. The drone starts freaking out, but
a few moments later, its emergency rescue protocols kick in, and it
starts hauling you back to the repair bay where it emerged from. 

A wave of relief washes over you, and you finally exhale the breath that
you feel like you’ve been holding for a million years. Now that you’re
not in any immediate danger, you can finally think about what the hell
happened back there. Were those breaching charges? Who the hell was
breaching us? Why didn’t we detect them on the sensors? With all of
these new questions still forming in your mind, you finally arrive in
the repair bay on Deck 11. Shortly after arriving, you hear a broadcast
on a radio in the room. Something about an invasion? Attackers? What the
hell is going on? Well, you’re security, so this is on you. 

This is where *Tele-Frag* starts. From here on, you’d explore the ship,
and learn about what happened as you fight the alien invaders, the
ship’s systems that have gone haywire, and more, a la System Shock or
Marathon.

**Sources & Citations:**

Raycasting:
https://dev.epicgames.com/documentation/en-us/unreal-engine/using-a-single-line-trace-raycast-by-channel-in-unreal-engine

Fixing Collision Issues: https://youtu.be/arlKkPSHYXU?feature=shared

Unreal FPS Tutorial: https://youtu.be/h3vBLjwQH2w?si=-p4REyYitU2U0hAK

Importing 3D models to Unreal:
https://youtu.be/axF0m6lOjG8?feature=shared

**Image Sources:**

Titanfall 2 Time Gauntlet:
https://titanfall.fandom.com/wiki/Time_gauntlet?file=TF2_TimeGauntlet_Concept.jpg

Team Fortress 2 Telefrag:
https://wiki.teamfortress.com/wiki/Telefrag#/media/File:Telefrag.png

Telefrag Icon:
https://gaming.stackexchange.com/questions/5829/in-team-fortress-2-what-is-telefragging-and-how-is-it-done

Half-Life Screenshot:
https://www.engadget.com/half-lifes-big-25th-anniversary-update-includes-four-new-multiplayer-maps-and-much-more-193932590.html?guccounter=1
