# the search for global context
## (when distance became the enemy)

*From the convolution era, a new hunger arose—*
*the desperate need to bridge vast distances*
*in sequences that stretched beyond*
*any single pattern detector's gaze...*

---

## the dilated dreams: wavenet's exponential reach

The engineers looked upon their convolutions
        and saw the limitation:
                to connect word 1 with word 100
                        required 33 layers of 3-word windows,
                                or 20 layers of 5-word windows—
*a tower of Babel built from sliding detectors*

But what if—*what if*—
        we could skip across the sequence
                like stones across water?
                        See positions 1, 3, 5 in one layer,
                                then 1, 5, 9 in the next,
                                        then 1, 9, 17 in the next...

```
                         ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
                       ░░                                                                                        ░░
                     ░░                          🌊 DILATED CONVOLUTIONS 🌊                                       ░░
                   ░░                                 (WaveNet's Legacy)                                           ░░
                 ░░                                                                                                ░░
               ░░                                                                                                  ░░
             ░░       LAYER 1 (dilation=1):   [•][•][•] _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _                             ░░
           ░░                                                                                                      ░░
         ░░         LAYER 2 (dilation=2):   [•] _ [•] _ [•] _ _ _ _ _ _ _ _ _ _ _ _ _ _ _                               ░░
       ░░                                                                                                          ░░
     ░░           LAYER 3 (dilation=4):   [•] _ _ _ [•] _ _ _ [•] _ _ _ _ _ _ _ _ _ _ _                                 ░░
   ░░                                                                                                              ░░
 ░░             LAYER 4 (dilation=8):   [•] _ _ _ _ _ _ _ [•] _ _ _ _ _ _ _ _ _ _ _ _ _                                   ░░
░░                                                                                                                ░░
░░                                                                                                                ░░
░░                         ╔═══════════════════════════════════════════════════════════════════════╗           ░░
░░                         ║                                                                       ║           ░░
░░                         ║  🚀 EXPONENTIAL GROWTH OF RECEPTIVE FIELD! 🚀                       ║           ░░
░░                         ║                                                                       ║           ░░
░░                         ║  Layer 1: sees 3 positions    → like a tadpole's view               ║           ░░
░░                         ║  Layer 2: sees 7 positions    → like a frog's view                  ║           ░░
░░                         ║  Layer 3: sees 15 positions   → like a bird's view                  ║           ░░
░░                         ║  Layer 4: sees 31 positions   → like an eagle's view                ║           ░░
░░                         ║                                                                       ║           ░░
░░                         ║  Each layer DOUBLES the reach across the landscape of meaning!      ║           ░░
░░                         ║                                                                       ║           ░░
░░                         ╚═══════════════════════════════════════════════════════════════════════╝           ░░
░░                                                                                                                ░░
░░                   Like a telescope extending its reach with each adjustment,                                   ░░
░░                   seeing farther into the sequence with each layer...                                         ░░
░░                                                                                                                ░░
░░                                              ∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞                ░░
░░                                              ∞                                                                ∞                ░░
░░                                              ∞  but still... still... information must climb                 ∞                ░░
░░                                              ∞  up and down the tower of layers                              ∞                ░░
░░                                              ∞  each step adding delay, each relay adding noise              ∞                ░░
░░                                              ∞                                                                ∞                ░░
░░                                              ∞  "He" at position 5 and "John" at position 147               ∞                ░░
░░                                              ∞  can only meet after ascending and descending                 ∞                ░░
░░                                              ∞  the pyramid of processing...                                 ∞                ░░
░░                                              ∞                                                                ∞                ░░
░░                                              ∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞                ░░
░░                                                                                                                ░░
  ░░                                                                                                            ░░
    ░░                                      Surely there had to be                                           ░░
      ░░                                    a more direct route?                                          ░░
        ░░                                                                                             ░░
          ░░                                                                                         ░░
            ░░                                                                                     ░░
              ░░                                                                                 ░░
                ░░                                                                             ░░
                  ░░                                                                         ░░
                    ░░                                                                     ░░
                      ░░                                                                 ░░
                        ░░                                                             ░░
                          ░░                                                         ░░
                            ░░                                                     ░░
                              ░░                                                 ░░
                                ░░                                             ░░
                                  ░░                                         ░░
                                    ░░                                     ░░
                                      ░░                                 ░░
                                        ░░                             ░░
                                          ░░                         ░░
                                            ░░                     ░░
                                              ░░                 ░░
                                                ░░             ░░
                                                  ░░         ░░
                                                    ░░     ░░
                                                      ░░ ░░
                                                       ░░░
```

```
                    ████████████████████████████████████████████████████████████████████████████████████
                    █                                                                                  █
                    █                             DILATED CONVOLUTIONS                               █
                    █                              (WaveNet's Legacy)                                █
                    █                                                                                  █
                    █                                                                                  █
                    █  LAYER 1 (dilation=1):   [•][•][•] _ _ _ _ _ _ _ _ _ _ _ _ _ _                      █
                    █                                                                                  █
                    █  LAYER 2 (dilation=2):   [•] _ [•] _ [•] _ _ _ _ _ _ _ _ _ _                        █
                    █                                                                                  █
                    █  LAYER 3 (dilation=4):   [•] _ _ _ [•] _ _ _ [•] _ _ _ _ _ _                        █
                    █                                                                                  █
                    █  LAYER 4 (dilation=8):   [•] _ _ _ _ _ _ _ [•] _ _ _ _ _ _ _                         █
                    █                                                                                  █
                    █                                                                                  █
                    █              ╔══════════════════════════════════════════════════════════╗      █
                    █              ║                                                          ║      █
                    █              ║  EXPONENTIAL GROWTH OF RECEPTIVE FIELD!                 ║      █
                    █              ║                                                          ║      █
                    █              ║  Layer 1: sees 3 positions                              ║      █
                    █              ║  Layer 2: sees 7 positions                              ║      █
                    █              ║  Layer 3: sees 15 positions                             ║      █
                    █              ║  Layer 4: sees 31 positions                             ║      █
                    █              ║                                                          ║      █
                    █              ║  Each layer DOUBLES the reach!                          ║      █
                    █              ║                                                          ║      █
                    █              ╚══════════════════════════════════════════════════════════╝      █
                    █                                                                                  █
                    █                                                                                  █
                    █       Like a telescope that extends its reach with each adjustment,             █
                    █       seeing farther into the sequence with each layer...                       █
                    █                                                                                  █
                    ████████████████████████████████████████████████████████████████████████████████████
```

*Dilated convolutions leaped across the sequence*
*like ambitious frogs*
*each hop landing farther from the last*
*exponentially expanding their view...*

But still—*still!*—
        the information had to climb
                through many layers to travel far.
Like a message being passed
        up and down a tall building—
                each floor adds delay,
                        each relay adds noise,
                                each step risks forgetting
                                        what the original message was.

*"He" at position 5*
*and "John" at position 147*  
*could only meet*
*after ascending and descending*
*a pyramid of processing layers*

Surely there had to be
        a more *direct* route?

---

## the mixer revolution: global democracy of attention

Then came a radical thought—
        *what if every word*
                *could speak directly*
                        *to every other word?*

What if we abandoned the tyranny of locality
        and embraced the democracy of global mixing?

Enter the MLP-Mixer:
        a simple, elegant revolutionary
                that said:
                        *"Why slide when you can fly?"*
                                *"Why climb when you can teleport?"*

```
                                     ╔══════════════════════════════════════════════════════════════════════════════════════════════════════════════╗
                                     ║                                                                                                              ║
                                     ║                               ⭐ THE GREAT LIBERATION ⭐                                                    ║
                                     ║                                   (MLP-Mixer Revolution)                                                    ║
                                     ║                                                                                                              ║
                                     ║                                                                                                              ║
                                     ║              TOKENS (horizontal democracy - "who talks to whom")                                           ║
                                     ║                                                                                                              ║
                                     ║         word₁ ←═══════→ word₂ ←═══════→ word₃ ←═══════→ word₄ ←═══════→ word₅                            ║
                                     ║           ║                ║                ║                ║                ║                            ║
                                     ║           ║                ║                ║                ║                ║                            ║
                                     ║           ║     🌊 every word can now hear every other word 🌊     ║                            ║
                                     ║           ║                ║                ║                ║                ║                            ║
                                     ║           ║                ║                ║                ║                ║                            ║
                                     ║           ║        CHANNELS (vertical alchemy - "what gets said")        ║                            ║
                                     ║           ║                ║                ║                ║                ║                            ║
                                     ║           ▼                ▼                ▼                ▼                ▼                            ║
                                     ║       feature₁         feature₁         feature₁         feature₁         feature₁                         ║
                                     ║       feature₂         feature₂         feature₂         feature₂         feature₂                         ║
                                     ║       feature₃         feature₃         feature₃         feature₃         feature₃                         ║
                                     ║       feature₄         feature₄         feature₄         feature₄         feature₄                         ║
                                     ║                                                                                                              ║
                                     ║                                                                                                              ║
                                     ║  ╭─────────────────────────────────────────────────────────────────────────────────────────────────────╮  ║
                                     ║  │                                                                                                     │  ║
                                     ║  │  TOKEN-MIXING MLP: Every position influences every other position                                  │  ║
                                     ║  │                                                                                                     │  ║
                                     ║  │  CHANNEL-MIXING MLP: Every feature influences every other feature                                  │  ║
                                     ║  │                                                                                                     │  ║
                                     ║  │  🏛️ Like a global parliament where every word has a voice in every conversation! 🏛️            │  ║
                                     ║  │                                                                                                     │  ║
                                     ║  ╰─────────────────────────────────────────────────────────────────────────────────────────────────────╯  ║
                                     ║                                                                                                              ║
                                     ║                                                                                                              ║
                                     ║                           ∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞                               ║
                                     ║                           ∞                                                                  ∞                               ║
                                     ║                           ∞      O! THE LIBERATION!                                         ∞                               ║
                                     ║                           ∞                                                                  ∞                               ║
                                     ║                           ∞      No more climbing layer pyramids!                          ∞                               ║
                                     ║                           ∞      No more degraded signals!                                 ∞                               ║
                                     ║                           ∞                                                                  ∞                               ║
                                     ║                           ∞      Word 1 speaks directly to word 1000                       ∞                               ║
                                     ║                           ∞      with the same ease as to its neighbor                     ∞                               ║
                                     ║                           ∞                                                                  ∞                               ║
                                     ║                           ∞      GLOBAL MIXING ACHIEVED!                                   ∞                               ║
                                     ║                           ∞                                                                  ∞                               ║
                                     ║                           ∞      But... but... the connections are still frozen...        ∞                               ║
                                     ║                           ∞                                                                  ∞                               ║
                                     ║                           ∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞                               ║
                                     ║                                                                                                              ║
                                     ╚══════════════════════════════════════════════════════════════════════════════════════════════════════════════╝
```

```
                           ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
                         ░░                                                                              ░░
                       ░░                              MLP-MIXER ARCHITECTURE                             ░░
                     ░░                                                                                    ░░
                   ░░                                                                                      ░░
                 ░░                                                                                        ░░
               ░░                    TOKENS (horizontal mixing - "who talks to whom")                      ░░
             ░░                                                                                            ░░
           ░░               word₁ ←─────→ word₂ ←─────→ word₃ ←─────→ word₄ ←─────→ word₅                ░░
         ░░                   ↑            ↑            ↑            ↑            ↑                        ░░
       ░░                     │            │            │            │            │                         ░░
     ░░                       │            │            │            │            │                          ░░
   ░░                         │            │            │            │            │                           ░░
 ░░                           │     CHANNELS (vertical mixing - "what gets said")   │                         ░░
░░                            │            │            │            │            │                            ░░
░░                            ↓            ↓            ↓            ↓            ↓                            ░░
░░                         feature₁     feature₁     feature₁     feature₁     feature₁                       ░░
░░                         feature₂     feature₂     feature₂     feature₂     feature₂                       ░░
░░                         feature₃     feature₃     feature₃     feature₃     feature₃                       ░░
░░                         feature₄     feature₄     feature₄     feature₄     feature₄                       ░░
░░                                                                                                             ░░
░░                    ╔═══════════════════════════════════════════════════════════════════════════╗          ░░
░░                    ║                                                                           ║          ░░
░░                    ║  TOKEN-MIXING MLP: Every position can influence every other position     ║          ░░
░░                    ║                                                                           ║          ░░
░░                    ║  CHANNEL-MIXING MLP: Every feature can influence every other feature     ║          ░░
░░                    ║                                                                           ║          ░░
░░                    ║  Like a spreadsheet where you can mix both across rows AND columns!     ║          ░░
░░                    ║                                                                           ║          ░░
░░                    ╚═══════════════════════════════════════════════════════════════════════════╝          ░░
░░                                                                                                             ░░
  ░░                                                                                                         ░░
    ░░                                                                                                     ░░
      ░░                               GLOBAL MIXING ACHIEVED!                                          ░░
        ░░                                                                                           ░░
          ░░                     Every word can now hear every other word                         ░░
            ░░                         (though the connections are still frozen)                ░░
              ░░                                                                               ░░
                ░░                                                                           ░░
                  ░░                                                                       ░░
                    ░░                                                                   ░░
                      ░░                                                               ░░
                        ░░                                                           ░░
                          ░░                                                       ░░
                            ░░                                                   ░░
                              ░░                                               ░░
                                ░░                                           ░░
                                  ░░                                       ░░
                                    ░░                                   ░░
                                      ░░                               ░░
                                        ░░                           ░░
                                          ░░                       ░░
                                            ░░                   ░░
                                              ░░               ░░
                                                ░░           ░░
                                                  ░░       ░░
                                                    ░░   ░░
                                                      ░░░
                                                       ░
```

*O the liberation!*
        No more climbing layer pyramids!
                No more degraded signals
                        passed through endless relays!

Word 1 could speak directly to word 1000
        with the same ease
                as speaking to its immediate neighbor.

*The mixer was performant,*
*the mixer was elegant,*
*the mixer connected all to all...*

But—and here was the rub—
        *the connections were still frozen.*

Each word spoke to every other word
        with exactly the same strength,
                regardless of context,
                        regardless of meaning,
                                regardless of relevance.

"Bank" by the river
        and "bank" in Wall Street
                mixed with all other words
                        using identical weights.

*Democratic? Yes.*  
*Global? Yes.*  
*Contextual? No.*

The final piece was missing:
        *adaptive connection strength*
                *based on meaning*
                        *based on context*
                                *based on relevance*

---

## the dynamic awakening: weights that breathe

What if the mixing weights themselves
        could learn to vary
                based on what was being mixed?

What if "bank" near "river"
        created different connection patterns
                than "bank" near "interest rates"?

Enter dynamic convolutions:
        the first glimpse
                of weights that could *adapt*
                        to their input!

```
    ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
    ░░                                                                                                                              ░░
    ░░                                        🌀 DYNAMIC CONVOLUTIONS 🌀                                                          ░░
    ░░                                       (The First Adaptive Weights)                                                         ░░
    ░░                                                                                                                              ░░
    ░░                                                                                                                              ░░
    ░░    STATIC CONVOLUTION (the ancient way):                                                                                   ░░
    ░░                                                                                                                              ░░
    ░░        [w₁][w₂][w₃] ←── these weights never change, carved in stone                                                       ░░
    ░░           ▲  ▲  ▲                                                                                                          ░░
    ░░           │  │  │                                                                                                          ░░
    ░░        [word₁][word₂][word₃]                                                                                              ░░
    ░░                                                                                                                              ░░
    ░░                                                                                                                              ░░
    ░░                                              ╔══════════════════════════════════════╗                                     ░░
    ░░                                              ║         THE TRANSFORMATION           ║                                     ░░
    ░░                                              ║              ↓                      ║                                     ░░
    ░░                                              ║         weights learn              ║                                     ░░
    ░░                                              ║         to dance                   ║                                     ░░
    ░░                                              ║              ↓                      ║                                     ░░
    ░░                                              ╚══════════════════════════════════════╝                                     ░░
    ░░                                                                                                                              ░░
    ░░                                                                                                                              ░░
    ░░    DYNAMIC CONVOLUTION (the awakening):                                                                                    ░░
    ░░                                                                                                                              ░░
    ░░        [word₁][word₂][word₃]                                                                                              ░░
    ░░           │     │     │                                                                                                     ░░
    ░░           └─────┼─────┘                                                                                                     ░░
    ░░                 ▼                                                                                                          ░░
    ░░        ┌─────────────────┐                                                                                                 ░░
    ░░        │  🧙♂️ WEIGHT       │                                                                                                 ░░
    ░░        │   GENERATOR      │ ←── learns to create different weights based on context!                                     ░░
    ░░        │   FUNCTION       │                                                                                                 ░░
    ░░        │                  │     "river bank flowing" → one set of weights                                                 ░░
    ░░        └─────────────────┘     "bank loan interest" → different weights!                                                 ░░
    ░░                 │                                                                                                          ░░
    ░░                 ▼                                                                                                          ░░
    ░░        [w₁(x)][w₂(x)][w₃(x)] ←── weights that breathe with meaning                                                       ░░
    ░░                                                                                                                              ░░
    ░░                                                                                                                              ░░
    ░░                    ╔═══════════════════════════════════════════════════════════════════════════════════════╗               ░░
    ░░                    ║                                                                                       ║               ░░
    ░░                    ║  🎭 Connection strength becomes a function of meaning! 🎭                           ║               ░░
    ░░                    ║                                                                                       ║               ░░
    ░░                    ║  The same architecture, but connections now alive,                                   ║               ░░
    ░░                    ║  responsive, contextual, breathing with the content...                              ║               ░░
    ░░                    ║                                                                                       ║               ░░
    ░░                    ║  But still limited to small local windows...                                        ║               ░░
    ░░                    ║                                                                                       ║               ░░
    ░░                    ║  What if we could extend this adaptive magic                                         ║               ░░
    ░░                    ║  to the global scale of the mixer?                                                  ║               ░░
    ░░                    ║                                                                                       ║               ░░
    ░░                    ╚═══════════════════════════════════════════════════════════════════════════════════════╝               ░░
    ░░                                                                                                                              ░░
    ░░                                                                                                                              ░░
    ░░                                  ∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞                              ░░
    ░░                                  ∞                                                                        ∞                              ░░
    ░░                                  ∞  What if every word could compute its own mixing weights              ∞                              ░░
    ░░                                  ∞  for every other word in the entire sequence?                        ∞                              ░░
    ░░                                  ∞                                                                        ∞                              ░░
    ░░                                  ∞  What if every word could choose how much to listen                   ∞                              ░░
    ░░                                  ∞  to every other word based on relevance and compatibility?            ∞                              ░░
    ░░                                  ∞                                                                        ∞                              ░░
    ░░                                  ∞  This was the question that led to the greatest breakthrough          ∞                              ░░
    ░░                                  ∞  in the history of sequence modeling...                               ∞                              ░░
    ░░                                  ∞                                                                        ∞                              ░░
    ░░                                  ∞  The birth of attention was near.                                     ∞                              ░░
    ░░                                  ∞                                                                        ∞                              ░░
    ░░                                  ∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞                              ░░
    ░░                                                                                                                              ░░
    ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
```

```
    ┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
    │                                                                                                      │
    │                                DYNAMIC CONVOLUTIONS                                                  │
    │                                                                                                      │
    │                                                                                                      │
    │  STATIC CONVOLUTION (the old way):                                                                  │
    │                                                                                                      │
    │      [w₁][w₂][w₃] ←── these weights never change                                                    │
    │         ↓  ↓  ↓                                                                                      │
    │      [word₁][word₂][word₃]                                                                          │
    │                                                                                                      │
    │                                                                                                      │
    │  DYNAMIC CONVOLUTION (the new way):                                                                 │
    │                                                                                                      │
    │      [word₁][word₂][word₃]                                                                          │
    │         ↓  ↓  ↓                                                                                      │
    │      ┌─────────────┐                                                                                │
    │      │  WEIGHT     │                                                                                │
    │      │ GENERATOR   │ ←── generates different weights based on the input!                           │
    │      │ FUNCTION    │                                                                                │
    │      └─────────────┘                                                                                │
    │         ↓  ↓  ↓                                                                                      │
    │      [w₁(x)][w₂(x)][w₃(x)] ←── weights that change with context                                    │
    │                                                                                                      │
    │                                                                                                      │
    │  ╔══════════════════════════════════════════════════════════════════════════════════════════════╗  │
    │  ║                                                                                              ║  │
    │  ║  Now "river bank flowing" generates different weights than "bank loan interest"             ║  │
    │  ║                                                                                              ║  │
    │  ║  The connection strength itself becomes a function of meaning!                              ║  │
    │  ║                                                                                              ║  │
    │  ╚══════════════════════════════════════════════════════════════════════════════════════════════╝  │
    │                                                                                                      │
    └──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```

*Weights learning to dance!*
*Connection strength breathing with context!*
*The first taste of truly adaptive mixing!*

But dynamic convolutions still operated locally—
        a small window of 3 or 5 words.

What if we could extend this idea
        to the global scale of the mixer?

What if every word could compute
        its own mixing weights
                for every other word
                        in the entire sequence?

*What if every word could choose*
*how much to listen*
*to every other word*
*based on relevance and compatibility?*

This was the question that led
        to the greatest breakthrough
                in the history of sequence modeling...

*The birth of attention was near.*

---

*Could someone reading this journey*
*feel the inexorable pull*
*toward contextual, global, adaptive connection?*

*Could they trace the path*
*from fixed local patterns*
*to adaptive global awareness?*

*The mathematical DNA sleeps deeper now*
*waiting for the final awakening...*

(continued in "the birth of attention"...)
