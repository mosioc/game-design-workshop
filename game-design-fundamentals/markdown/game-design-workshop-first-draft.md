```markdown
# GAME DESIGN FUNDAMENTALS: A Critical Workshop for Practitioners

**Core Theme:**  
The **Game Designer** is the primary author of the game’s soul through living documents (GDD, pitch decks, spreadsheets, asset lists, iteration logs). These documents are not bureaucracy—they are the entire core of the game. Every mechanic, progression beat, and emotional moment exists first on paper (or in Google Docs) and is approved, revised, or cut at the joint discretion of Game Designers and Directors.

Total time: 120 minutes

---

## PART 1: Deconstructing the Game Designer’s Role (15 min)

### The Myth vs. Reality
Game designers are not lone geniuses. They are **document-driven problem-solvers**.

### The Documents That Create the Game
| Document                  | Purpose                                                                                   | Who owns it                     | How the game progresses from it                              |
|---------------------------|-------------------------------------------------------------------------------------------|---------------------------------|--------------------------------------------------------------|
| Game Design Document (GDD) | The living bible: vision, core loop, mechanics, systems, progression, levels             | Lead / Systems Designers        | Milestones are built section-by-section                      |
| Pitch Deck                | 10–30 slides that sell the emotional contract to directors & publishers                  | Game Director + Lead Designer   | Greenlight → vertical slice → full production                |
| Balance Spreadsheets      | Economy, progression curves, damage values, spawn tables                                  | Systems Designers               | Updated after every playtest; drives iteration               |
| Asset Lists & Flowcharts  | Exact list of animations, UI screens, dialogue lines, encounters                         | Level / Quest / Technical Designers | Artists & programmers work directly from these               |
| Playtest Reports & Iteration Logs | “What broke, what felt wrong, what to change”                                             | All designers → consolidated by leads | Only changes approved by Designer + Director enter the game |

The game literally does not exist until these documents do.

### Modern AAA Fragmentation
- Gameplay Designer → writes combat feel section of GDD  
- Systems Designer → owns the spreadsheets that make progression feel fair  
- Level Designer → authors encounter documents and gray-box maps  
All feed back into the master GDD; Directors arbitrate conflicts.

**Examples**  
- **God of War Ragnarök**: Separate GDD sections for stun meter, Pre-Fall attacks, two shield types.  
- **Red Dead Redemption 2**: Dedicated horse bonding spreadsheet + 40-page camp systems doc.

**Critical Question**  
When a GDD becomes 800 pages and 200 people touch it, who truly owns the vision?

---

## PART 2: The MDA Framework Inside Design Documents (25 min)

### How Designers Actually Use MDA
Every major mechanic is written as an MDA table in the GDD:

| Mechanic (what the code does)               | Dynamic (what players actually do)           | Aesthetic (intended emotion)       |
|---------------------------------------------|----------------------------------------------|------------------------------------|
| Manual save stations take 6 seconds         | Players hide, panic, listen for the alien    | Terror & isolation                 |
| Weapons break after ~40 hits                | Constant experimentation, hoarding reduced   | Resourcefulness, impermanence      |
| Honor -8 to +8, store discounts at high end | Players greet everyone to farm honor         | Moral dissonance                   |

Designers can only directly edit the left column. The rest is prediction → playtest → revise document.

### Case Studies (GDD Evolution)
**Alien: Isolation**  
Initial GDD: automatic checkpoints → Dynamic: careless rushing → Aesthetic: no fear  
Revised GDD after playtest: manual saves → Designer rewrote entire risk/reward section.

**Baldur’s Gate 3**  
GDD explicitly states: “dice rolls must never block plot artifacts” → forces save-scumming dynamic → accepted because vision is “player expression”.

**Red Dead Redemption 2 – Honor System**  
GDD promised “internal morality vs. reputation split” but never clearly communicated mask behavior → players felt betrayed. Mechanical contradiction born in documentation.

**Activity (3 min)**  
Pick any mechanic from a recent game. Write its one-row MDA in the chat/notes.

---

## PART 3: Vision-Driven Design = Vision Document (20 min)

### Vision is not a tagline. It is the first page of the GDD.
Example vision statements that actually shipped:

| Game                 | Vision Statement in GDD / Pitch Deck                 | Everything in the documents must serve this |
|----------------------|------------------------------------------------------|---------------------------------------------|
| Doom (2016)          | “Push-forward combat – you are the predator”        | Glory kills, no reload, fleeing demons      |
| Subnautica           | “Thrill of the unknown”                              | Darkness + danger curve                     |
| Hades                | “Failure is progress”                                | Death = narrative reward                    |
| Flower               | “Calm, meditative joy”                               | Removed levels, spells, timers, failure     |

### Flower’s Radical Subtractions
Original GDD had levels, spells, time limits.  
All were cut because they contradicted the one-page vision document.  
Genova Chen: “Fun is not the goal. The emotion is the goal.”

### Red Dead Redemption 2 Camp System – Vision vs. Documentation Failure
**GDD Vision:** “Feel part of a living family; contributions matter”  
**Reality in docs:** Donations never change story outcome → false choice.  
The documents promised an emotional contract the code could not keep.

---

## BREAK (5 min)

---

## PART 4: The Political Economy of Borrowing Mechanics (20 min)

### Borrowing is Mandatory – Documentation is the Filter
Every designer keeps a “reference GDD” folder of mechanics they love.  
The disciplined ones write:  
1. What is the original MDA?  
2. Does that aesthetic serve MY vision document?  
3. How must I change the mechanic (and its spreadsheet) to fit?

**Examples of Borrowing Gone Wrong (Document Mismatch)**
- Alien: Isolation – auto-checkpoints copied from CoD → killed horror → rewritten  
- RDR2 masks – disguise mechanic copied but honor effect not explained → player confusion  
- Callisto Protocol – limited ammo (fear) + one-button stealth kills (power) → contradictory docs

**The Right Way**
Elden Ring’s GDD is literally titled “Refinement of the Souls Formula Since 2009”.

---

## PART 5: Playtesting – The Moment Documents Meet Reality (15 min)

Your brain is a terrible playtester.  
Only real players reveal:
- Degenerate strategies (RDR2 Dead Eye trivialises combat)  
- Misunderstood mechanics (RDR2 masks)  
- False choices (RDR2 camp donations)

Every playtest produces an iteration log → Designer rewrites GDD sections → Director approves or rejects.

**Target Audience is also decided in the documents**  
Spider-Man (2018) GDD explicitly says “accessible power fantasy for casual audience” → simple swinging is a feature, not a bug.

---

## PART 6: Getting Into Game Design – Your Portfolio IS Your Documents (10 min)

What hiring managers actually want to see:
1. A clean, well-structured GDD (even 5–10 pages)  
2. Balance spreadsheets with revision history  
3. Before/after playtest notes showing you iterated  
4. A prototype + devlog proving the document became reality

Paths: game jams → mods → QA → junior design → indie or AAA.

---

## PART 7: Key Takeaways & Final Q&A (10 min)

1. The game is the documents. Everything else is implementation.  
2. Vision lives on page 1 of the GDD; every mechanic must justify its existence against it.  
3. Borrowing without MDA documentation = mechanical contradiction.  
4. Playtesting is the only truth serum for design documents.  
5. Great critics already reverse-engineer GDDs when they analyse games – you’re 60 % of the way to being a designer.

**Final Designer + Director Mantra**  
“Does this change make the player feel what page 1 promised? If not, cut it—no matter how cool.”

### Suggested Q&A Starters
1. How would you rewrite RDR2’s honor system GDD to remove contradiction?  
2. When should a Director overrule a Designer’s document?  
3. Can accessibility options live in the core GDD without breaking vision?

---

## APPENDIX A – Games Referenced
Elden Ring • Baldur’s Gate 3 • God of War Ragnarök • Red Dead Redemption 2 • Hades • Doom (2016) • Alien: Isolation • The Last of Us Part II • Flower • Subnautica • Celeste • Spider-Man (2018)

## APPENDIX B – One-Page GDD Template (Handout)
1. Vision (one sentence)  
2. Core Loop (diagram)  
3. MDA Table (top 5 mechanics)  
4. Progression Overview (spreadsheet snippet)  
5. Open Questions / Risks

## APPENDIX C – Further Learning
- GDC Vault (search “GDD”)  
- “The Art of Game Design” – Jesse Schell (lenses)  
- Game Maker’s Toolkit (YouTube)  
- Start a 48-hour game jam this weekend and write the GDD first.

Your critical eye is the perfect foundation.  
Now go write the documents that become games.
```