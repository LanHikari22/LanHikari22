## Hi!

I'm Mohammed. I also go by Lan in this digital space we share.

I'm a computer engineer. I create open source tools, reverse engineer games, and create proofs of concepts. 

## On Visibility

I care about increasing visibility into the creative process of software development and scientific investigations.

Towards this goal, I have decided to make many of my notes for open source development public. These are journals I write as I research, develop and investigate. 

- For concept exploration, see [delta-trace](https://github.com/deltatraced/delta-trace/tree/webview).
- For tooling, system setups, and diagnostics, see [lan-setup-notes](https://github.com/LanHikari22/lan-setup-notes/tree/webview).
- For reverse engineering work, see [dism-exe-notes](https://github.com/dism-exe/dism-exe-notes/tree/webview/lan), [goldensun-notes](https://github.com/FutureFractal/goldensun-notes/tree/webview/lan).
- For Rust database tooling with dbmint, see [dbmint-notes](https://github.com/dbmint/dbmint-notes/tree/webview).

all these note repositories use [obsidian](https://obsidian.md/). They can also largely be viewed in github via the `webview` branch.

## Overview

- Check out my [monthly overview](https://github.com/deltatraced/delta-trace/blob/webview/lan/overview/monthly/2025/Mn%2009%20September.md)!
- Check out my [projects](https://github.com/deltatraced/delta-trace/blob/webview/lan/portfolio/Projects.md)!

## Contact

Feel free to contact me at mailto:lanhikarixx@gmail.com!

## Upcoming works

### [dbmint](https://github.com/LanHikari22/dbmint)

This project builds on top of the [dbml](https://dbml.dbdiagram.io/home/) file format for creating database schemas and generating sqlite3 databases from them. 

Currently working on generating a rust project that integrates schema information into the rust type system and leverages compile-time guarantees for writing queries.

## Projects

### [bn6f](https://github.com/dism-exe/bn6f)

Reverse engineering Mega Man Battle Network 6. This reproduces the original game data from source code. It also has many derivative projects for tooling and analysis

Those include:
- [Related IDA Analysis](https://github.com/LanHikari22/GBA-IDA-Pseudo-Terminal) 
- [Automated generation of struct layouts using lua](https://github.com/LanHikari22/GBA_Memory-Access-Scanner)
- [Automated dumping of internal textscript within the game](https://github.com/LanHikari22/bn_textscript_dumper),

Upcoming:
- high level editing of bn6f repository, sync with ghidra, and exporting type info for gdb with [bn_repo_editor](https://github.com/LanHikari22/bn_repo_editor)

### Reproduction projects

[rs_repro](https://github.com/LanHikari22/rs_repro) catalogs all minimal reproducible rust examples. This allows me to reference specific repro IDs that can be setup by anyone easily. 

For example, to get started quickly reading/writing [Rusty Object Notation](https://github.com/ron-rs/ron) files in rust, check out [repro003](https://github.com/LanHikari22/rs_repro/blob/main/src/repro_tracked/repro003_ron_read_write.rs): 

```sh
git clone https://github.com/LanHikari22/rs_repro.git && cd rs_repro && cargo run --features "repro003"
```

## Fun Stats

| [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LanHikari22)](https://github.com/LanHikari22) | [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LanHikari22&hide=Assembly,LLVM)](https://github.com/LanHikari22)<br>                                               |
| -------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| With Assembly and LLVM (Reconstruction projects)                                                                           | Without Assembly and LLVM                                                                                                                                                                       |
| [![GitHub Streak](https://streak-stats.demolab.com?user=LanHikari22&border_radius=6)](https://github.com/LanHikari22)      | ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=LanHikari22&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&rank_icon=github) |

![LanHikari22's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=LanHikari22&theme=tokyo-night&hide_border=true)
