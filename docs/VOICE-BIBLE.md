# StarHaven: one-page voice bible (DRAFT, for Josh to approve)

**Tone:** pulp space adventure told in second person. Short, physical sentences (recycled air, crimson emergency light, cold metal). Choices have a cost in Health, Credits or alignment, and the text should say what the cost felt like.

**Names:** the player-facing names were LLM defaults (Orin Kael x6, Kael x22, Kira Voss x2). Replaced by a seeded draw from `docs/voice.json` (station-trade surnames: Draw, Tenner, Ballast, Sluice, Rivet...). New names come from `namegen.py --voice docs/voice.json`, never from a model.
- Jedi Master Orin Kael is now **Havel Draw**; the default player name Kira Voss is now **Nik Tenner**. Display text only: no saves depend on names (endings are stored by id).

**Rules for new characters:** a want that is not "save the galaxy", a limit, something they will not discuss, a reason their tone changes. One family, one surname.

**For Josh to decide (not mine to decide):** the game uses third-party Star Wars proper nouns (Jedi, Hutt, Inquisitor, stormtroopers, ISB, Huttese). For a public repo you may want original substitutes. I left them as they are.
