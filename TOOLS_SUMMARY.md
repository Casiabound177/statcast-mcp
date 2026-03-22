# Statcast MCP — tools summary

**One-liner for social posts**

> **Statcast MCP** — 24 tools for MLB data in ChatGPT / Cursor / Claude: Statcast pitch search, batter & pitcher pitch logs, FanGraphs season stats, **team roster batting & pitching** (full lineup + staff), xStats & exit velo leaderboards, **batch expected stats** for whole lineups, sprint speed, standings, Statcast percentiles, OAA + outfield directional OAA, and Baseball Reference date-range hot/cold splits. Natural language → real Savant / FG / BRef data.

**Shorter (280 chars target — tweak as needed)**

> Statcast MCP: 24 @MLB data tools for AI clients — pitch-level Statcast, season & **team** stats (lineup + rotation + pen), expected stats (incl. batch for full lineups), exit velo, arsenals, sprint speed, standings, percentiles, OAA, BRef streaks. pybaseball + MCP. ⚾📊

**Hashtags (optional)**

`#MLB` `#Sabermetrics` `#Statcast` `#MCP` `#OpenSource` `#Python`

**Tool count by area**

| Area | Tools |
|------|--------|
| Identity | `player_lookup` |
| Pitch-level Statcast | `statcast_search`, `statcast_batter`, `statcast_pitcher` |
| Season (league) | `season_batting_stats`, `season_pitching_stats` |
| Season (**team roster**) | `team_season_batting_stats`, `team_season_pitching_stats` |
| Expected / barrels / arsenals | `statcast_batter_expected_stats`, `statcast_pitcher_expected_stats`, `expected_stats_batch`, `statcast_batter_pitch_arsenal`, `statcast_batter_exitvelo_barrels`, `statcast_pitcher_exitvelo_barrels`, `statcast_pitcher_pitch_arsenal`, `statcast_pitcher_arsenal_stats` |
| Running / standings | `sprint_speed_leaderboard`, `team_standings` |
| Statcast percentiles | `batter_percentile_ranks`, `pitcher_percentile_ranks` |
| Defense | `outs_above_average`, `outfield_directional_oaa` |
| BRef date ranges | `batting_stats_date_range`, `pitching_stats_date_range` |

**Verify locally**

```bash
PYTHONPATH=src python scripts/verify_tools.py
```

Last run: all **24** tools completed without errors (uses 2024 fixtures + network).
