# Scrumbly Island

A light, playful 3D monster-catcher set on a tropical island. Explore, then find clever ways to lure and catch silly creatures called scrumblies.

## Play

Open `index.html` in a browser. You need an internet connection because Three.js and the fonts load from CDNs.

| Key | Action |
| --- | --- |
| WASD / arrows | Walk |
| Shift | Run |
| Space | Jump |
| Mouse | Look (click to capture the mouse, Esc to pause) |
| Click | Use the item in hand (swing the net, throw a rock) |
| 1–5 / scroll wheel / Q | Swap item |
| E | Pick up a rock you're looking at |
| Click (Scrumblydex out) | Scan the scrumbly in your sights |
| Tab (Scrumblydex out) | Open / close the Scrumblydex list (arrows browse, Esc closes) |
| (rocks out) | A dotted arc shows the throw and a ring marks where it lands; both turn pink with a bracket when you'd hit a scrumbly |
| Walk or jump into a palm | Grab on; W/S climb, A/D shimmy round, Space leap off |
| M | Music on/off |

## So far

- Pinksand Shore: a ring of pink-sand beach with shells, starfish, rocks, driftwood and palm trees
- Shallow water you can wade into, up to about 1 m deep
- A placeholder jungle in the middle, closed for now
- Palm trunks are solid and climbable
- A big catching net in first person: swing it to slam it into the sand (or splash the shallows)
- Gamepad support: left stick move, right stick look, A jump, RT/X use item, LB/RB or d-pad swap item, B pick up rock, Y Scrumblydex list, Back music
- The first scrumbly, the Bobo: a shy dumpling that pops a "!" and burrows into the sand when you get within about 6 m, then resurfaces once you're 12 m away or up a palm tree. Stun it by jumping off a palm onto its head or by hitting it with a thrown rock, then net it within 5 seconds. New ones turn up elsewhere later
- Inventory hotbar along the bottom: the net, a stack of up to 10 rocks and the Scrumblydex
- A party of up to five scrumblies down the left; the first slot is your PARTNER. Each one you catch gets a random name for keeps, shown as "[Name] the [Species]" (from a list of ~350: normal, silly, cute, random words, and nods to Ouran High School Host Club, Ace Attorney, My Chemical Romance, Red Rising, Black Butler, Mistborn, Attack on Titan, The Summer Hikaru Died, The Witcher, Red Dead Redemption 2 and Professor Layton)
- Rare sizes: about 1 in 20 scrumblies is Big and 1 in 20 is Small. They look it, their hit and bounce zones scale to match, a scan points it out, and a catch is named "[Name] the Big Bobo" / "[Name] the Small Bobo"
- Your party and Scrumblydex progress are saved in the browser, so they're still there next time you open the game
- The Mermiggly, half frog and half mermaid: splashes, spins and leaps about in the shallows and may stop to wave at you, but bolts and dives within about 9 m. Hit one with a rock and it gets cross and leaves for a while. There's no way to catch one yet
- The Scrumblydex: a red handheld scanner. Point it at a scrumbly and click to scan it, which pops up its entry with a cute fact and a catching tip. Tab opens the full list of 60 entries (2 real, the rest placeholders): unseen ones are blacked-out silhouettes, scanned ones show their info, and caught ones get a badge
- Procedural calypso music and ocean sounds, made with Web Audio
