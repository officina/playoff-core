# Requires

Python 3+

# Install

```Python3
pip install playoff-core
```

# Using

In order to use this toolbox, you need:

- Playoff game;
- subscription plan that allows to make API calls;
- a configured client;
- create a `.env` file containing `Client_ID`, `Client_secret` and `hostname` 
of the corresponding game.

**Example**:

```
ORIGINAL_CLIENT_ID=Bf7dhMnM73EQtMjRjOGYyN2VmODhh
ORIGINAL_CLIENT_SECRET=MGMxYzQ0YzdCmD937tYjUyOWM1NWI3YjlhNTdiODY2MTAtOGE0MS0xS
ORIGINAL_HOSTNAME="playoff.cc"
```

# Settings

Settings available are:

- **Version**: game version;
- **Player_id**: a player id needed to certain API calls;
- **Cycle**: time lapse to obtain leaderboard, can have following values:
    - *daily*;
    - *weekly*;
    - *monthly*;
    - *yearly*;
    - *alltime*.
- **Level**: log message level, can have following values:
    - *debug*;
    - *info*;
    - *warning*. 