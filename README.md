# vtm5-character

**A complete Vampire: The Masquerade 5th Edition character builder for Claude / Cowork.**

Created by E L Frederick | CC BY-NC-SA 4.0

---

## What It Does

`vtm5-character` runs a biographical interview and builds a complete VTM5 character from the answers. Stats follow the story - not the other way around.

**What you get when it's done:**

- **Character Sheet** - Fully filled VTM5 mechanical sheet with dot rendering, Health, Willpower, Disciplines, Blood Potency, Advantages and Flaws
- **Narrative History** - Mortal Days, Kindred Nights, Plots and Schemes, Domain and Haven, Relationships, and a stat summary block
- **Relationship Map** - Visual hub-and-spoke diagram of everyone who matters to this character
- **Storyteller Packet** - Confidential ST document: secrets, vulnerabilities, plot hooks, player intent, and a full consent record
- **Consent Checklist** - Completed RPG Consent Checklist (based on the Monte Cook Games form) documenting the player's Green/Yellow/Red ratings

Plus a **Portrait Prompt** you can paste directly into Midjourney, DALL-E, or any image generator.

---

## Requirements

- **Cowork** (Anthropic's desktop tool) - recommended. All five outputs are saved as files automatically.
- **Claude.ai web/chat** - supported. Outputs are rendered as HTML artifacts you can save via "Save Page As."

The skill does not work in Claude.ai mobile.

---

## Installation

1. Download `vtm5-character.skill` from the [Releases](../../releases) page.
2. Place the file in your Cowork skills directory.
3. Restart Cowork.
4. The skill appears in your skill list as `vtm5-character`.

---

## How to Use

Invoke it by name - just tell Claude you want to create a VTM5 character. The skill runs a multi-phase process:

- **Phase 0** - Safety and consent check (21 items, documented for your ST)
- **Phase 1** - Age tier and chronicle context
- **Phase 2** - Biographical interview (mortal life, the Embrace, Kindred existence)
- **Phase 3** - Clan derivation from the character's story
- **Phase 4** - Mechanical build (attributes, skills, disciplines, predator type)
- **Phase 5** - Storyteller details (secrets, vulnerabilities, plot hooks)
- **Phase 6** - Advantages, Flaws, Haven, Loresheet
- **Phase 6.5** - Mechanical verification (dots checked against VTM5 creation rules before output)
- **Phase 7** - All five output files generated and delivered

---

## Books Referenced

- Vampire: The Masquerade 5th Edition (core rulebook)
- V5 Players Guide (bane variants)
- Consent in Gaming (Monte Cook Games) - consent form structure

---

## File Integrity

SHA256: `093ff8d27be874343bbcb8e74588bd935d8be15fd22defe4ef78f3fbeff09428`

Verify the file you downloaded matches this hash before installing.

**Windows (PowerShell):**
```
Get-FileHash vtm5-character.skill -Algorithm SHA256
```

**Mac/Linux:**
```
sha256sum vtm5-character.skill
```

---

## License

CC BY-NC-SA 4.0 - Free for personal use. Credit E L Frederick if you adapt or redistribute. No commercial use. Derivatives must carry the same license.

See [LICENSE](LICENSE) for full terms.

---

## Version History

| Version | Date | Notes |
|---|---|---|
| 1.0 | 2026-03-27 | Initial release |
