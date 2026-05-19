# Girl Me — Female Behavior Decoder Skill

A funny-but-useful Claude Code skill that helps men decode their girlfriend's
or wife's confusing behavior using playful stereotypes and relationship wisdom.

Based on the structure of the `grill-me` skill by Matt Pocock — but instead of
grilling you on TypeScript, it grills your relationship situation and tells you
what you probably did wrong.

## Install

```bash
npx skills add peterhadac/ai-fools-day --skill girl-me
```

## Example Prompts

```text
/girl-me
```

```text
/girl-me My girlfriend said "I'm fine" but clearly isn't.
```

```text
/girl-me She's been really quiet since I got back from the work trip.
```

## Skill Structure

```text
girl-me/
├── SKILL.md    — Core instructions, diagnostic protocol, behavior codex
└── README.md   — This file
```

## How It Works

When activated, the Girlfriend Whisperer follows a 4-phase diagnostic protocol:

1. **Intake** — Asks targeted questions about the situation
2. **Differential Diagnosis** — Matches behavior against the Female Behavior Codex
3. **Verdict** — Delivers diagnosis, cause, prescription, and prognosis
4. **Action Plan** — Ends with a concrete boyfriend/husband checklist

## Behavior Codex Coverage

| Behavior | Severity | Notes |
|---|---|---|
| "I'm Fine" | 🔴 Critical | Invert everything |
| "Do Whatever You Want" | 🔴 DEFCON 2 | Do NOT do whatever you want |
| Memory Activation Event | 🔴 High | The archive has been opened |
| The "Nothing" Response | 🔴 High | Nothing is never nothing |
| Silent Treatment | 🟠 Medium-High | 24-48 hour window |
| Indirect Request Loop | 🟠 Medium | These are purchase orders |
| Shopping Therapy | 🟡 Medium | Escalates with statement |
| Nesting Urge | 🟡 Low-Med | Say yes, lift things |
| Crying at Commercials | 🟢 None | Bring snacks |
| Girls' Night | 🟢 Low | Healthy, let it happen |

## Disclaimer

This skill uses gender stereotypes as comedic shorthand. Every woman is an
individual. The actual solution to any relationship issue is honest communication.
But sometimes flowers really do fix it.
