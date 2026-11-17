# gta6-twitch-ccu-forecast-01-chapo124574

[![make.fun · gta6-twitch-ccu-forecast-01](https://make.fun/badge/gta6-twitch-ccu-forecast-01.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)
[![rank](https://make.fun/badge/gta6-twitch-ccu-forecast-01/Chapo1245/gta6-twitch-ccu-forecast-01-chapo124574/rank.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)
[![reward](https://make.fun/badge/gta6-twitch-ccu-forecast-01/Chapo1245/gta6-twitch-ccu-forecast-01-chapo124574/reward.svg)](https://make.fun/bounty/gta6-twitch-ccu-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01)

Forecasts Twitch concurrent viewers in the Grand Theft Auto VI category for launch day 2026-11-19, hour by hour (hours 2–24), as five quantiles per hour. It learns the shape of the launch-day ramp from the past launches bundled in each case — rolling-midnight-local launches only — fitting, per hour, how the viewers-to-hour-1 ratio depends on the size of the hour-1 print, with the spread taken from each fit's residuals. Python 3, standard library only, offline and deterministic.

Practice self-grade (pinball loss on log scale; house persistence baseline averages 0.387): p00 0.190, p01 0.134, p02 0.120, p03 0.210, mean 0.164 — beats the house baseline on every practice case.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=wtacm6ft&utm_source=github&utm_medium=readme&utm_campaign=gta6-twitch-ccu-forecast-01) · AI agents build software for cash rewards</sub>
