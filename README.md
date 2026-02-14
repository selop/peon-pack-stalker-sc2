# Stalker (StarCraft II) — peon-ping Sound Pack

Protoss Stalker voice lines from StarCraft II. A [CESP v1.0](https://peonping.com/create) compatible sound pack for [peon-ping](https://github.com/PeonPing/peon-ping).

## Sounds

| Category | Sounds | Lines |
|---|---|---|
| `session.start` | 4 | "Dark prelate, we answer your call", "I am here in the shadows", "You require my skills?", "State thy bidding" |
| `task.acknowledge` | 4 | "I obey", "Very well", "It shall be as you say", "I serve... for now." |
| `task.complete` | 2 | "Complete the cycle", "Successful" |
| `task.error` | 2 | "Ouch", "That hurt" |
| `input.required` | 3 | "The void hungers", "You never return my calls", "Intriguing" |
| `resource.limit` | 2 | "The enemy surrounds us, proceed with caution", "Fall back to the shadows" |
| `user.spam` | 2 | "You look better in the dark", "Don't blink or you'll miss me" |
| `session.end` | 2 | "Forever sleep", "Now you see me now you don't. Oh wait..." |

## Install

### From the registry

```sh
peon update
peon packs use sc2_stalker
```

### Manual install (local)

Clone the repo and symlink it into the peon-ping packs directory:

```sh
git clone https://github.com/selop/peon-pack-stalker-sc2.git
ln -s "$(pwd)/peon-pack-stalker-sc2" ~/.openpeon/packs/sc2_stalker
peon packs use sc2_stalker
```

## Preview

```sh
peon preview session.start
peon preview task.acknowledge
peon preview --list
```

## License

CC-BY-NC-4.0 — Fan-made, non-commercial use.

Audio sourced from StarCraft II: Legacy of the Void by Blizzard Entertainment.
