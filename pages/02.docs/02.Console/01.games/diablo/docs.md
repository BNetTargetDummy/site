---
title: Diablo
---

## Diablo 3

```
$ td request d3 <resource>
```

### Commands

#### data

  - `--key, -k` String - the key of the data resource
    - choices: `artisan`, `follower`, `item`
  - `--id, -i` String - the ID of the data resource
    - artisan: `blacksmith`, `jeweler`, `mystic`
    - follower: `templar`, `scoundrel`, `enchantress`
    - item: the item ID

#### era

  - `--id, -i` Number - the era ID
  - `--leaderboard, -b` String - the leaderboard ID
  - `--token, -t` String - an authenticated user access token

#### profile

  - `--battletag, -b` String - the battletag of the user profile
  - `--hero, -i` Number - the hero ID

#### season

  - `--id, -i` Number - the era ID
  - `--leaderboard, -b` String - the leaderboard ID
  - `--token, -t` String - an authenticated user access token