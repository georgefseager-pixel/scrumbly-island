# Scrumbly Island

A light, playful 3D monster-catcher set on a tropical island. Explore, then find clever ways to lure and catch silly creatures called scrumblies.

## Play

Open `index.html` in a browser. You need an internet connection because Three.js and the fonts load from CDNs.

| Key | Action |
| --- | --- |
| WASD / arrows | Walk |
| Shift | Run |
| Space | Jump |
| Mouse | Look (click to capture the mouse) |
| Esc (or controller Start) | Pause menu: keep exploring, save, load, new game, settings, controls |
| Click | Use the item in hand (swing the net, throw a rock) |
| 1–5 / scroll wheel / Q | Swap item |
| E | Pick up a rock you're looking at |
| Click (Scrumblydex out) | Scan the scrumbly in your sights |
| Tab (Scrumblydex out) | Open / close the Scrumblydex list (arrows browse, Esc closes) |
| (rocks out) | A dotted arc shows the throw and a ring marks where it lands; both turn pink with a bracket when you'd hit a scrumbly |
| E (near Professor Loveopolis) | Open the Box: click a scrumbly, then click a slot to move or swap it (arrows + Enter, or d-pad + A, also work) |
| E (looking at your partner) | Pet your partner |
| Click (cage trap out) | Set a trap on the sand in front of you (a green ghost shows where; red means you can't) |
| E (looking at a trap) | Collect what's inside, or pick an empty trap back up |
| Hold click (teleporter out) | Hold the red button for three seconds to zap back to the ranch (10-minute recharge) |
| Walk or jump into a palm | Grab on; W/S climb, A/D shimmy round, Space leap off |
| M | Music on/off |

## So far

- A New Game tutorial with Professor Loveopolis: he gives you the net and asks for your first catch; is amazed (he's never caught one) and gives you the Scrumblydex; asks you to scan three kinds of scrumbly; gives you a cage trap and asks you to catch five; then shows you the Box and sends you off to explore and help the other islanders. An objective tracker and a "!" over the Professor show what to do next. Saves from before the tutorial skip it
- Pinksand Shore: a ring of pink-sand beach with shells, starfish, rocks, driftwood and palm trees
- Shallow water you can wade into, up to about 1 m deep
- A placeholder jungle in the middle, closed for now
- Palm trunks are solid and climbable
- A big catching net in first person: swing it to slam it into the sand (or splash the shallows)
- Gamepad support: left stick move, right stick look, A jump, RT/X use item, LB/RB or d-pad swap item, B pick up rock, Y Scrumblydex list, Back music
- The first scrumbly, the Bobo: a shy dumpling that pops a "!" and burrows into the sand when you get within about 6 m, then resurfaces once you're 12 m away or up a palm tree. Stun it by jumping off a palm onto its head or by hitting it with a thrown rock, then net it within 5 seconds. Or ambush it: leap off a palm next to one and swing your net straight away (within about half a second of landing) to catch it before it can dive New ones turn up elsewhere later
- Inventory hotbar along the bottom: the net, a stack of up to 10 rocks, the Scrumblydex and 3 cage traps
- A party of up to five scrumblies down the left; the first slot is your PARTNER. Each one you catch gets a random name for keeps, shown as "[Name] the [Species]" (from a list of ~500: normal, silly, cute, random words, and nods to Ouran High School Host Club, Ace Attorney, My Chemical Romance, Red Rising, Black Butler, Mistborn, Attack on Titan, The Summer Hikaru Died, The Witcher, Red Dead Redemption 2, Professor Layton, gothic literature, Danganronpa and The Lord of the Rings)
- Rare sizes: about 1 in 12 scrumblies is Big and 1 in 12 is Small. They look it, their hit and bounce zones scale to match, a scan points it out, and a catch is named "[Name] the Big Bobo" / "[Name] the Small Bobo"
- The Speshul, a little green monkey with big googly eyes: clings near the tops of palm trees and leaps to another tree as soon as you start climbing after it. Knock it down with a thrown rock (the aim arc turns pink when you're on target) and it tumbles to the sand, sees stars, then runs around in a panic, which is your chance to net it. After about 7 seconds it scampers back up a tree
- The Pengin, a very shy little green penguin: waddles about the sand near the rock nooks dotted around the beach. If it sees you within about 8 m it panics and runs flat out to its nearest nook and hides inside, only coming out once you've gone. Set a cage trap in front of a nook's doorway, then show yourself so it runs straight in
- The Duckshark, a shark that thinks it's a duck: floats, paddles, dabbles (tail up) and quacks out in the deeper shallows. Wade into the water near one and it charges and bites. Stun it with a rock from dry land, then wade in and net it while it's seeing stars
- Health: you have one heart (bottom left). A bite knocks you out and you wake up at the ranch, where Professor Loveopolis patches you up with one of several different pep talks. Visiting the ranch always restores you to full health
- The Weevil, a little brown sausage dog: races round the same looping circuit over and over, leaving a trail of paw prints in the sand. Far too quick to net, and a rock only makes it cross (it even speeds up). Follow the paw prints and set a cage trap right on its track
- The Beeappy, a big round happy bumblebee: drifts about overhead, bobbing between net height and well above the palm trees, and never lands, so traps can't catch it. Net it when it dips low, or leap at it from a palm. Hit it with a rock and it turns red and chases you to sting you, unless you net it first
- Scenery: an enormous Duckshark (45 times normal size) paddles in a slow circle far out to sea off the beach near the start, bobbing, swishing its tail, dabbling now and then and letting out a deep far-off quack
- The Beeangy: net a Beeappy while it's red and chasing you and you catch a Beeangy instead, a separate red, furrow-browed, permanently cross bee with its own Scrumblydex entry
- Bink, one of a kind: a small fluffy pink alien on a tiny flying saucer that putters round the whole beach in one long loop, never stopping or slowing. One rock just wobbles the saucer; after three hits it sinks to the sand and Bink is dizzy for a few seconds, long enough to net. There is only one Bink, so it is never Big, Small or Shiny, it is just called "Bink", and once caught it never appears in the wild again
- Cage traps: set one down and any scrumbly that walks over it is shut inside (Mermigglies stay in the water, so never). Collect it with E or your net before it rattles the cage and breaks out after about 24 seconds. Empty traps can be picked up and reused
- Professor Loveopolis's Ranch, just along the beach from the start: a thatched hut and a fenced pen with an open gate. The Professor, a big bearded frog-man in a lab coat, stands in the gateway. Talk to him to open the Box (48 slots) and swap scrumblies between it and your party. With a full party you can't catch any more: leave some with the Professor first. Up to five boxed scrumblies live in the pen (water-lovers in its pond) and crowd round with hearts and happy coos when you visit. You must always keep at least one scrumbly in your party, so your Partner slot is never empty
- Scrimple Scrumple, the first islander, appears once the tutorial is done: a lanky purple hippy frog-man in round orange shades and a tie-dye poncho, camped by an orange tent and campfire along the beach. He is horrified that you catch scrumblies (and that you are in league with his old rival Professor Loveopolis), so he buys them to set them free. His shop shows all your scrumblies with gold prices: trickier species are worth more, Big and Small ones 1.5x, Shinies 6x. Your partner and one-of-a-kind scrumblies like Bink can't be sold. Gold shows next to your health
- Scrimple's notice board unlocks after your first sale. It always has three requests for endangered scrumblies you've scanned: usually 3 to 5 of one species, sometimes one Big or Small one, and rarely (never more than one at a time) a Shiny. Pick a request you can fill, choose which scrumblies to release (the cheapest are picked for you), and get a much better reward than selling them one by one. A "!" over the board means you can fill a request. The next time you see Professor Loveopolis after meeting Scrimple, he has a grumble about that head-in-the-clouds hippy
- Dr. Tealbottom, the second islander, appears after the tutorial: a teal frog-woman scientist in a lab coat, with goggles pushed up and a curly bun, by a satellite beacon that sweeps the sky and blinks. She's a colleague of Professor Loveopolis and runs three experiments. First, catch a Bobo without a rock (ambush it from a palm tree); she rewards you with a second cage trap. Second, prove the Beeangy exists by bringing one in your party; she works out it's just a Beeappy holding a grudge and gives you a health injection (a second heart). Third, prove the UFO is real by bringing Bink; she gives you the teleporter, a remote with a big red button that zaps you back to the ranch after a three-second hold (recharges in ten minutes, shown on its hotbar slot). Then she heads off to tell Loveopolis, and from then on stands beside the ranch with plenty to say. A "!" over her means she has something for you
- Shiny variants: about 1 in 40 scrumblies has special colours (a golden Bobo, a purple Speshul, a pink Pengin, a blue Beeappy...). Wild Shinies sparkle, and a catch is named "[Name] the Shiny [Species]" (or "the Shiny Big Bobo"), with a rainbow Shiny tag in the party and Box
- Your Partner follows you around: it hops after you when you wander off, waits at the foot of trees you climb, floats in the shallows, and settles nearby to watch you. Look at it and press E to pet it for hearts, sparkles and a happy squint. Every few minutes it lets you know how it feels with a little note (about 70 different ones)
- Settings (from the pause menu): interface size, screen edge margin (for TVs that crop the edges), look sensitivity, invert look up/down, music and sound volume, and shadows on/off. Kept in this browser. A Controls page lists every key and controller button
- Performance: decoration and palms are culled in slices, scrumblies and the ranch are merged into few draw calls, far-off creatures aren't drawn, and the render resolution adapts to keep the frame rate smooth
- Saving: the game autosaves as you play (party, Box, Scrumblydex, where you're standing, rocks and traps, placed traps, music). The title screen offers Continue, New game and Load game. The pause menu has three save slots, plus Download save file and Load from a save file for backups or moving between computers. Saves live in this browser; the save file works anywhere
- The Mermiggly, half frog and half mermaid: splashes, spins and leaps about in the shallows and may stop to wave at you, but bolts and dives within about 9 m. Hit one with a rock and it gets cross and leaves for a while. There's no way to catch one yet
- The Scrumblydex: a red handheld scanner. Point it at a scrumbly and click to scan it, which pops up its entry with a cute fact and a catching tip. Tab opens the full list of 60 entries (8 real, the rest placeholders): unseen ones are blacked-out silhouettes, scanned ones show their info, and caught ones get a badge
- Procedural calypso music and ocean sounds, made with Web Audio
