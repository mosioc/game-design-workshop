# GAME DESIGN FUNDAMENTALS: A Critical Workshop for Practitioners

## Core Definitions

### Key Roles

- **Game Designer**: A document-driven problem-solver who authors the game's "soul" through written specifications (not a lone visionary). They write design documents, balance spreadsheets, and iteration logs that define every mechanic before it's built.
- **Game Developer**: The broader term for anyone who creates games, including programmers, artists, and designers working together.
- **Game Director**: The final arbiter who approves or rejects changes to the game's vision and design documents.

### Specialized Designer Roles (Modern AAA)

- **Gameplay Designers**: Handle second-to-second interactions (combat feel, movement)
- **Systems Designers**: Create overarching mechanics (progression, economy, balance)
- **Level Designers**: Design environments and encounter placement
- **Quest Designers**: Write narrative missions and branching paths
- **Technical Designers**: Bridge between design intent and code implementation
- **UX Designers**: Focus on interface, accessibility, and player communication

### Core Concepts

- **GDD (Game Design Document)**: The "living bible" containing the game's vision, core loop, mechanics, systems, progression, and levels. The game literally doesn't exist until this document does.
- **Genre**: Categories of games defined by their core mechanics and player expectations (horror, action, RPG, etc.). However, genres are descriptive labels, not prescriptive rules.
- **Framework**: A structured analytical tool for understanding how games work (like MDA)

---

## PART 1: The Game Designer's Role

### Key Documents That Create Games

**Game Design Document (GDD)**

- Purpose: The master document containing vision, mechanics, systems, progression
- Owner: Lead/Systems Designers
- Example: God of War Ragnarök's GDD specified combo finishers, Pre-Fall attacks, and two distinct shield types,each requiring separate designers

**Pitch Deck**

- Purpose: 10-30 slides selling the emotional contract to directors and publishers
- Owner: Game Director + Lead Designer
- Flow: Greenlight → vertical slice → full production

**Balance Spreadsheets**

- Purpose: Economy, progression curves, damage values, spawn rates
- Owner: Systems Designers
- Example: Updated after every playtest; drives iteration

**Asset Lists & Flowcharts**

- Purpose: Exact specifications for animations, UI screens, dialogue, encounters
- Owner: Level/Quest/Technical Designers
- Use: Artists and programmers work directly from these

**Playtest Reports & Iteration Logs**

- Purpose: Document what broke, what felt wrong, what needs changing
- Critical Rule: Only changes approved by Designer + Director enter the game

### Real Example: Red Dead Redemption 2

- **Development**: 7 years, massive team specialization
- **Designer Specialization**: Some designers worked exclusively on horse systems (bonding mechanics, saddle stats, breed behaviors)
- **Scale**: Most design happens in "gray box" (untextured geometry) before art is added
- **Critical Question**: "When a GDD becomes 800 pages and 200 people touch it, who truly owns the vision?"

---

## PART 2: The MDA Framework

### Definition

**MDA Framework**: Mechanics → Dynamics → Aesthetics

- **Mechanics**: Rules, systems, and stats that exist in code (what designers directly control)
- **Dynamics**: How players actually behave in response to mechanics
- **Aesthetics**: Emotional responses players feel

**Critical Insight**: Designers can only directly edit mechanics. The rest is prediction → playtest → revise.

### Examples

**Alien: Isolation (Horror Evolution)**

_Original System:_

- Mechanic: Automatic checkpoints (borrowed from Call of Duty)
- Dynamic: Players walked carelessly knowing death = minor setback
- Aesthetic: No fear (WRONG for horror)

_Final System:_

- Mechanic: Manual save stations taking 6 seconds to operate
- Dynamic: Players hide, panic, listen for the alien while saving
- Aesthetic: Terror and isolation (CORRECT for horror)

**Lesson**: Context destroys universality. What works in action games kills horror games.

**Zelda: Breath of the Wild (Breaking Weapons)**

- Mechanic: All weapons degrade and break
- Dynamics: Players hoard less, experiment more, engage with resource systems
- Aesthetics: Resourcefulness, exploration, impermanence (not power fantasy)

**Baldur's Gate 3 (2023)**

- Mechanic: D\&D 5e dice rolls for dialogue/actions
- Dynamic: Players save-scum before important conversations, experiment with builds
- Aesthetic: Player expression prioritized over challenge
- GDD explicitly states: "Dice rolls must never block plot artifacts" (forces save-scumming, but accepted because vision is "player expression")

**Red Dead Redemption 2 (Honor System)**

| Mechanic | Dynamic | Aesthetic |
|----------|---------|-----------|
| Honor scale from -8 to +8 affecting NPC reactions, store discounts (10–50%), and loot quality | Players greet everyone repeatedly to “farm” honor; donate $20 multiple times instead of $100 once | Moral dissonance: game forces robbery/killing in story missions, yet punishes the same behavior in free roam |


**Design Problem**: Mechanical contradiction,required story missions demand criminal behavior while free roam mechanics punish it.

---

## PART 3: Vision-Driven Design

### Definition

**Vision**: The emotional contract with the player,the specific feeling you promise (not vague "fun"). Written on page 1 of the GDD.

### Vision Statements That Shipped

| Game        | Vision                                 | Supporting Mechanics |
|-------------|-----------------------------------------|-----------------------|
| Doom (2016) | "Push-forward combat , you are the predator" | Glory kills restore health, no reloading, enemies flee from you, rapid movement |
| Subnautica  | "Thrill of the unknown"                | Deep ocean becomes darker and more dangerous |
| Hades       | "Failure is progress"                  | Death advances narrative; every run provides story content |
| Flower      | "Calm, meditative joy"                 | Removed levels, spells, resource management, time limits, failure states |


### Flower's Radical Subtractions

**Original Features** (removed): Level-ups, spells, resource management, time limits,"expected features of other video games"

**Designer Quote**: "We've played so many games growing up, these bad habits form. A lot of the time we like to make things very fun, but fun doesn't always help the emotion you want to deliver." ,Jenova Chen

**The Radical Act**: Having courage to remove what "every game has" when it contradicts your vision.

### When Vision Aligns: Doom 2016

**Vision**: "Push forward combat"

**Supporting Elements**:

- Rapid movement speed
- Glory kills require closing distance, restore health
- Demons flee from player
- No reloading (constant aggression)
- Heavy metal soundtrack
- Violent, empowering animations

**Quote**: "All the elements have to sing the same notes to make the impact strong" ,Jenova Chen

### Mechanical Contradiction: Callisto Protocol

- Mechanic 1: Limited ammo → creates fear, vulnerability
- Mechanic 2: One-button instant stealth kills → creates power, confidence
- Result: **Contradictory emotions** (which feeling wins?)

### Red Dead Redemption 2: Camp System Failure

**Vision**: "Feel part of a living family; contributions matter"

**Mechanics**:

- Donation box accepts money, valuables, pelts
- Camp upgrades (Dutch's tent, Arthur's lodging with fast travel, supply wagons)
- Camp chores (carrying hay, chopping wood) for honor boosts

**The Failure**: "The game does a poor job of letting the player feel the influence of their actions on the camp. Regardless of whether the player buys all camp upgrades... the Van der Linde camp will still be there... as if nothing happened."

**Why This Matters**: False choice,the game continues identically whether you engage or ignore the system. Documents promised an emotional contract the code couldn't keep.

---

## PART 4: Borrowing Mechanics

### Definition

**Borrowing**: Using mechanics from other games as reference. Not theft,it's mandatory because no mechanic is truly original. Games exist in "intertextual space."

**The Process**:

1. What is the original MDA?
2. Does that aesthetic serve MY vision?
3. How must I change the mechanic to fit?

### The Right Way: Elden Ring (2022)

FromSoftware has been "working on the same formula since Demon's Souls in 2009," continuously "refining and experimenting with each successive outing."

**Result**: Elden Ring represents "the peak of a very specific, influential video game formula",not revolutionary, but masterfully refined.

**GDD Title**: Literally "Refinement of the Souls Formula Since 2009"

### The Wrong Way: Early Soulslikes

Treated genre as **checklist**:

- ✓ Bonfires for checkpoints
- ✓ Estus flasks for healing
- ✓ Souls as currency
- ✓ Stamina-based combat

**Problem**: Copied surface features without understanding the philosophy behind them.

**Quote**: If you consider a genre "a long list of must-have mechanics," you'll "end up making the same thing over and over again."

### Mechanical Contradictions from Borrowing

**Alien: Isolation's Checkpoint Crisis**

- Borrowed: Automatic checkpoints (convenient in CoD)
- Result: Players rushed to next checkpoint, got killed, respawned safely
- Problem: "Convenient" mechanic undermined "scary" mechanic
- Solution: Manual save stations that involve risk

**Red Dead Redemption 2's Mask System**

**Borrowed Mechanic**: Disguise system from heist games

- Player Expectation: Wear mask → no honor loss, no witness recognition

**Actual Implementation**: "Wearing a bandana does not grant the player amnesty from changes in honor: it only prevents eyewitnesses from immediately recognizing the player."

**Reason**: Honor represents Arthur's self-reflection, not reputation

**Problem**: Game never explains this difference → player confusion and betrayal

**Lesson**: When you borrow a mechanic, players bring expectations from the original context. If your implementation differs, communicate clearly.

### Far Cry 2 vs Far Cry 4 (Same Franchise, Different Vision)

**Far Cry 2**:

- Weapons jam, malaria attacks, jeeps break down
- Rare saves, far apart
- Result: Harrowing survival struggle

**Far Cry 4**:

- Abundant ammo, reliable weapons
- Easy enemy tracking
- Permanent progress
- Result: Power fantasy action movie

**Critical Insight**: Your game's "feel" comes from mechanical choices, not narrative window-dressing.

---

## PART 5: Design for Humans, Not Theory

### Definition

**Playtesting**: The moment when design documents meet reality with actual players.

**Core Problem**: "Your brain is a truly bad video game simulator",everything seems fun in your mind's eye. You can only spot problems when the game is real.

**Fundamental Truth**: A game idea is "worthless until you've proven its value through a prototype."

### What Playtesting Reveals

**Baldur's Gate 3 Example**:

- Used early access period extensively
- Found: Game-breaking bugs, balance issues, player feedback
- Result: "Intelligent enemy AI responds to your actions so even repeated combat encounters against the same enemies feel distinct"

**Players Find**:

- Exploits you never imagined
- Ways to sequence-break
- Misunderstandings of "obvious" mechanics
- Degenerate strategies

### Degenerate Strategy: RDR2's Dead Eye

**The Mechanic**:

- Slow-motion targeting system
- Levels 1-5 with increasing power
- Can be used with Dead Eye tonics (easily farmable)

**Player Behavior**:

- Clear entire enemy camps without risk
- Win duels instantly
- Trivialize legendary animal hunts

**Design Problem**: The game gives a powerful tool but doesn't balance encounters around it. Combat becomes either trivially easy (with Dead Eye) or tediously difficult (without).

**What Playtesting Should Reveal**: "Players will always optimize the fun out of a game if given the chance."

### Target Audience Matters

**Spider-Man (2018)**

_Critic Perspective_: Web-swinging too simple, no challenge, impossible to fail

_Actual Target Audience_: Casual PS4 gamers wanted "incredible sensation of being Spider-Man"

_GDD Statement_: "Accessible power fantasy for casual audience",simple swinging is a **feature**, not a bug.

**Your Job as Critic**: Recognize when a game isn't made for you vs. when it failed its actual audience.

### Accessibility and Vision

**Celeste's Assist Mode**:

- Explains how game is "supposed to be played"
- Offers difficulty reduction if needed (new players, disabilities, story interest)
- Communicates the intended experience while offering options

**The Last of Us Part II**:

- 60+ accessibility features
- Three presets (vision, hearing, motor)
- Full control customization
- Warning: "Combat accessibility settings can significantly alter the gameplay experience"

**Critical Insight**: Options don't threaten vision if you communicate the intended experience.

**Quote**: "Non-disabled players are using these features to adjust the game to their preferences and eliminate frustration. Accessible design is good universal design."

### RDR2's Travel System

**Design Challenge**: 29 square miles, slow travel, long distances

**Player Options**:

- Fast travel from camp (requires $300+ in upgrades)
- Cinematic camera auto-pilot on roads
- Trains/stagecoaches between towns

**Design Philosophy**: "We want you to experience the journey, not skip it" (but we'll give you an out)

**Playtest Insight**: Some players love slow contemplative travel (supports immersion), others find it tedious (conflicts with pacing).

**Rockstar's Solution**: Provide multiple options, but make fast travel deliberately inconvenient.

---

## PART 6: Getting Into Game Design

### What Hiring Managers Want

**Portfolio Contents**:

1. Clean, well-structured GDD (even 5-10 pages)
2. Balance spreadsheets with revision history
3. Before/after playtest notes showing iteration
4. Prototype + devlog proving the document became reality

**Quote**: "Portfolio over credentials",make stuff, show ability to design.

### Tools for Game Design Work

**Document Creation**:

- Google Docs (GDDs, pitch decks)
- Excel/Google Sheets (balance spreadsheets)
- Miro/Figma (flowcharts, asset lists)

**Prototyping Tools**:

- Unity (industry-standard game engine)
- Unreal Engine (AAA-quality visuals)
- Dreams (accessible creation tool)
- Tabletop Simulator (board game prototypes)

**Level Editors**: Mod existing games to show design understanding

**Game Jam Platforms**: itch.io, Ludum Dare, GMTK Game Jam

### Career Paths

**Traditional Route**:

1. Game jams (48-hour prototypes)
2. Mods (using existing game editors)
3. QA/Testing (learn how games break)
4. Junior Designer
5. Indie or AAA studios

**QA Route**:

- "Not uncommon for QA testers to impress their bosses and get moved into design roles"
- **Important**: "QA is a vitally important role in of itself and shouldn't be seen as just a stepping stone"

**Alternative Path**:

- Start at smaller studios (mobile games, kids games)
- Build experience and portfolio
- Move to AAA

### University: Worth It?

**Warning**: "The college diploma itself isn't the important bit... it's about making the most of the opportunities and connections"

**What Universities Provide**:

- Time to build portfolio
- Industry connections
- Access to internships/work experience
- Collaborative environment

**Not Required**: Many positions don't require a game design degree

### Interview Process

**Design Thinking Tests**:

- "What would happen if you remove one of the options in rock paper scissors?"
- Dismantling your portfolio to see how you react to criticism

**Personality Tests**:

- Team player assessment
- Adaptability to someone else's vision
- Communication effectiveness
- Resilience to feedback

**Design Tests** (often on-site):

- Add a new mechanic to existing game
- Design a level/encounter for the studio's game
- Time-pressured execution

**Example RDR2 Interview Questions**:

- "How would you redesign RDR2's honor system to better align with the story's mandatory criminal actions?"
- "Design a camp interaction system that makes player donations feel more impactful"

### Industry Challenges

**The Dark Side**:

- **Crunch**: Extreme overtime (RDR2: "100-hour weeks")
- Mass layoffs/studio closures
- Online abuse and threats
- Workplace harassment

**Self-Protection**:

- Research studios on Glassdoor
- Talk to current/former employees
- Look for toxic culture warning signs

**Geographic Limitations**:

- Few developers in India, South America, parts of Asia
- May need to relocate
- Remote work expanding options

### The Indie Alternative

**Examples**: Solo designers of Axiom Verge, Stardew Valley, Gunpoint had "way more creative control than the dude working on Red Dead Redemption's horses"

**Reality Check**:

- Not easier
- No guaranteed income
- Extremely competitive market
- Thousands released yearly

---

## Key Takeaways (All 15)

1. **The game is the documents**,everything else is implementation
2. **Vision lives on page 1 of the GDD**,every mechanic must justify its existence
3. **Mechanics create experience, not narrative** (Far Cry 2 vs 4 prove this)
4. **"It depends"**,design choices must serve your specific vision
5. **Borrowing mechanics is essential** (Elden Ring, BG3 succeeded through decades of refinement)
6. **Test if borrowed mechanics fit YOUR vision** (Alien: Isolation's checkpoints)
7. **Mechanics can fight each other** (Callisto Protocol, RDR2 honor system)
8. **Sometimes remove "standard" features** (Flower's subtractions)
9. **Your brain is a terrible game simulator**,prototype everything
10. **Design for your target audience** (Spider-Man for casual gamers, not critics)
11. **Playtesting reveals everything**,players will surprise you
12. **Borrowing without MDA documentation = mechanical contradiction**
13. **Great critics already reverse-engineer GDDs**,you're 60% designer already
14. **Analysis ≠ Design, but critical thinking is 50% of the job**
15. **Keep questioning**,"any lesson you've learned needs to be constantly re-evaluated"

### Designer's Mantra

**From Yacht Club Games**: "It depends on the game you are trying to create, the emotions you're trying to evoke, and the experience you want your players to have."

**Final Designer + Director Mantra**: "Does this change make the player feel what page 1 promised? If not, cut it,no matter how cool."

---

## The Red Dead Redemption 2 Design Autopsy

### The Good

- MDA in action across all systems
- Vision-driven world building
- Exceptional attention to detail

### The Bad

- **Mechanical contradictions**: Story demands crime, honor punishes crime
- **False choices**: Camp donations don't impact world
- **Borrowed mechanics without adaptation**: Mask system confuses players

### The Ugly

- **Development cost**: 7 years, 100-hour weeks, massive specialization
- **Question**: When does perfectionism become diminishing returns?

### The Lesson

Even masterpieces have design flaws. Your job as critic-turned-designer:

1. Identify these contradictions
2. Understand why they happened
3. Learn how to avoid them in your own work

---

## Final Thought

**As Critics**: You already ask "why does this work?"

**As Designers**: You'll ask "how can I make this work?"

**The Transition Requires**:

- Humility (your first designs will be bad)
- Collaboration (you can't do it alone)
- Iteration (nothing works on the first try)
- Resilience (most ideas will fail)

**Your Advantage**: Your critical eye,your ability to see WHY games succeed or fail,is the foundation everything else builds on.
