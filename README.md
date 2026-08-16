# Slot Design & Math — Companion Repo

Companion material for *Slot Design & Math: A Practical Guide to Build and
Launch Your Casino Game*.

## exercises/

Folders are named for the chapter they belong to. Open `exercise.xlsx`, work
it yourself, then check `solution.xlsx`.

| Folder | Game | What it teaches |
|---|---|---|
| `ch06-01-core-concepts` | Coin flips, two dice | EV, variance, standard deviation, RTP = EV/bet |
| `ch06-02-basic-line-game` | 50 lines, wild on reels 2-5 | Line hits with no wild on reel 1, feature odds, free games |
| `ch07-01-wilds-on-all-reels` | 20 lines, wild everywhere | Wilds on reel 1, tiered scatter awards, separate free game strips |
| `ch07-02-weighted-stepper` | 3-reel stepper, progressive | Weighted reels, per-row distributions, any-BAR pays, progressive math |
| `ch07-03-ways-game` | 1024 ways | Ways math, separate base and free game reel sets |
| `ch08-01-markov-chains` | 5 coins, 5 rounds | Markov chains, weighted starting state |
| `ch08-02-skill-based-bonus` | Single-zero roulette | Optimal-strategy RTP, optimal stopping |

Note: `ch06-01` ships solved. It's a worked example, not a problem set.

## simulation/

Runnable simulators for the Chapter 6 and 7 game models. The book shows
pseudocode; the real implementations live here.

## prompts/

Prompts for building the prototyping engine described in Section 4.
