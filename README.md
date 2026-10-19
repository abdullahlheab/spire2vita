# Spire Vita

An unofficial, fan-made Slay the Spire 2 clone for the PS Vita, written from scratch in C++20.
This repository is the place to **request access, report bugs and give feedback**. It holds no
code, game files or builds.

Spire Vita is not affiliated with or endorsed by Mega Crit. Slay the Spire is a trademark of
Mega Crit. If you enjoy it, buy the original.

## What it is

- A native PS Vita homebrew that plays Slay the Spire 2: all five characters (Ironclad, Silent,
  Defect, Regent, Necrobinder), three acts, events, Ancients, shops, rest sites, relics, potions,
  enchantments, afflictions, custom and daily modes, run history and the compendium.
- Runs at 960x544 with button, stick and touch controls.
- Saves at each room. Save & Quit returns you to the start of the fight, or to the room's entry for
  events.
- A Test Run mode for trying any card, relic, potion, encounter or event.

## You need your own copy of the game

Spire Vita uses Slay the Spire 2's own art, text and audio, so it's only for people who own the
game on Steam. Nothing here is sold, and it's shared privately between friends who own the game.

## How to get it

1. Open an issue with the **Access request** template and include your Steam profile link.
2. Add me as a friend on Steam.
3. Play a run with me, so I can see you own the game.

After that, I'll send you a private download link for the `.vpk`. Install it with VitaShell like
any other homebrew.

The link and the file are for you only. Don't re-share them, post them or upload them anywhere.

## Reporting a bug

Open an issue (the bug report template asks for this) and include:

1. **What happened**, and what you expected. If it plays differently from the original, say how.
2. **How to reproduce it:** character, act, encounter or event, and the cards or relics involved.
3. **Which version** of the VPK you were on.
4. **Attachments:**
   - Screenshots or a short video.
   - For a **crash** on the Vita (error C2-12828-1 or similar), the crash dump
     `ux0:data/psp2core-*.psp2dmp`.
   - For **slowdowns**, `ux0:data/spirevita/perf.txt`, a timing log the game writes every 5 seconds.

Never attach game files or a `.vpk` to an issue.

## Status

Playable start to finish. Known areas still in progress:

- Creature animations and visual effects (sprites are currently static).
- Multiplayer is not supported.
