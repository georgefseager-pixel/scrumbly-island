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
| Esc (or controller Start) | Pause menu: keep exploring, save, load, new game |
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
- A party of up to five scrumblies down the left; the first slot is your PARTNER. Each one you catch gets a random name for keeps, shown as "[Name] the [Species]" (from a list of ~400: normal, silly, cute, random words, and nods to Ouran High School Host Club, Ace Attorney, My Chemical Romance, Red Rising, Black Butler, Mistborn, Attack on Titan, The Summer Hikaru Died, The Witcher, Red Dead Redemption 2, Professor Layton and gothic literature)
- Rare sizes: about 1 in 20 scrumblies is Big and 1 in 20 is Small. They look it, their hit and bounce zones scale to match, a scan points it out, and a catch is named "[Name] the Big Bobo" / "[Name] the Small Bobo"
- The Speshul, a little green monkey with big googly eyes: clings near the tops of palm trees and leaps to another tree as soon as you start climbing after it. Knock it down with a thrown rock (the aim arc turns pink when you're on target) and it tumbles to the sand, sees stars, then runs around in a panic, which is your chance to net it. After about 7 seconds it scampers back up a tree
- The Pengin, a very shy little green penguin: waddles about the sand near the rock nooks dotted around the beach. If it sees you within about 8 m it panics and runs flat out to its nearest nook and hides inside, only coming out once you've gone. Set a cage trap in front of a nook's doorway, then show yourself so it runs straight in
- Cage traps: set one down and any scrumbly that walks over it is shut inside (Mermigglies stay in the water, so never). Collect it with E or your net before it rattles the cage and breaks out after about 24 seconds. Empty traps can be picked up and reused
- Professor Loveopolis's Ranch, just along the beach from the start: a thatched hut and a fenced pen with an open gate. The Professor, a big bearded frog-man in a lab coat, stands in the gateway. Talk to him to open the Box (48 slots) and swap scrumblies between it and your party. With a full party you can't catch any more: leave some with the Professor first. Up to five boxed scrumblies live in the pen (water-lovers in its pond) and crowd round with hearts and happy coos when you visit. You must always keep at least one scrumbly in your party, so your Partner slot is never empty
- Your Partner follows you around: it hops after you when you wander off, waits at the foot of trees you climb, floats in the shallows, and settles nearby to watch you. Look at it and press E to pet it for hearts, sparkles and a happy squint. Every few minutes it lets you know how it feels with a little note (about 70 different ones)
- Saving: the game autosaves as you play (party, Box, Scrumblydex, where you're standing, rocks and traps, placed traps, music). The title screen offers Continue, New game and Load game. The pause menu has three save slots, plus Download save file and Load from a save file for backups or moving between computers. Saves live in this browser; the save file works anywhere
- The Mermiggly, half frog and half mermaid: splashes, spins and leaps about in the shallows and may stop to wave at you, but bolts and dives within about 9 m. Hit one with a rock and it gets cross and leaves for a while. There's no way to catch one yet
- The Scrumblydex: a red handheld scanner. Point it at a scrumbly and click to scan it, which pops up its entry with a cute fact and a catching tip. Tab opens the full list of 60 entries (4 real, the rest placeholders): unseen ones are blacked-out silhouettes, scanned ones show their info, and caught ones get a badge
- Procedural calypso music and ocean sounds, made with Web Audio
