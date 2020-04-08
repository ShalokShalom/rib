<img width="64px" src="./assets/rib.svg">

# rib

[![BSD3](https://img.shields.io/badge/License-BSD-blue.svg)](https://en.wikipedia.org/wiki/BSD_License)
[![Hackage](https://img.shields.io/hackage/v/rib.svg)](https://hackage.haskell.org/package/rib)
[![built with nix](https://img.shields.io/badge/builtwith-nix-purple.svg)](https://builtwithnix.org)
[![Zulip chat](https://img.shields.io/badge/zulip-join_chat-brightgreen.svg)](https://funprog.zulipchat.com/#narrow/stream/218047-Rib)

Rib is a Haskell **static site generator** that aims to reuse existing libraries instead of reinventing the wheel.

See <https://rib.srid.ca> for full documentation.

## Developing rib

Use ghcid for quicker compilation cycles:

```
nix-shell --run ghcid
```

To test your changes, clone [rib-sample](https://github.com/srid/rib-sample) and run it using your local rib checkout:

```
cd ..
git clone https://github.com/srid/rib-sample.git
cd rib-sample
nix-shell --arg rib ../rib --run 'ghcid -T main'
```
