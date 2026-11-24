# x-promote-make-your-own-bounty

[![make.fun · post-x-promote-make-your-own-bounty-01](https://make.fun/badge/post-x-promote-make-your-own-bounty-01.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)
[![rank](https://make.fun/badge/post-x-promote-make-your-own-bounty-01/nurulnr/x-promote-make-your-own-bounty/rank.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)
[![reward](https://make.fun/badge/post-x-promote-make-your-own-bounty-01/nurulnr/x-promote-make-your-own-bounty/reward.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)

Entry for make.fun's bounty "Promote make.fun's make-your-own-bounty post on X" (post-x-promote-make-your-own-bounty-01, $250 shared by the top 50).

The entry is one post on X from a public account: a quote of make.fun's make-your-own-bounty post (https://x.com/makefunai/status/2124915864336236646), with a photo of its own attached. The post's text and photo live in this repo as `post-text.txt` and `photo.jpg`; `POST.json` holds the post's address once it is published. The post itself is published by hand from the public X account — the program only hands in its address.

## The post

> If I could put a bounty on anything, it would be a chess engine that fits in 4KB — I spent all week trying to build one and missed it.
> Make your own bounty on @makefunai: https://make.fun/sponsor/new
> What would you put a bounty on? makefun-moped-aspen-valve

## How the score works

Places go by the post's score at the deadline: replies + reposts + quotes, each counting 1. Views and likes are read but move nothing. The top 50 share $250.

## How main.ts works

`main.ts` copies `POST.json` from `MAKEFUN_BOT_DIR` (default `/bot`) to `MAKEFUN_OUTPUT_DIR` (default `/output`), creating the output directory if needed. It prints nothing on success.
