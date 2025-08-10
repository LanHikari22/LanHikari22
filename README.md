## Hi!

I'm Mohammed. I also go by Lan in this digital space we share.

I'm a computer engineer. I create open source tools, reverse engineer games, and create proofs of concepts. 

## On Visibility

I care about increasing visibility into the creative process of software development and scientific investigations.

Towards this goal, I have decided to make many of my notes for open source development public. These are journals I write as I research, develop and investigate. 

- For concept exploration, see [delta-trace](<https://github.com/delta-domain-rnd/delta-trace>).
- For tooling, system setups, and diagnostics, see [lan-setup-notes](<https://github.com/LanHikari22/lan-setup-notes>).
- For reverse engineering work, see [dism-exe-notes](<https://github.com/dism-exe/dism-exe-notes/tree/main/lan>), [goldensun-notes](<https://github.com/FutureFractal/goldensun-notes/tree/main/lan>).

all these note repositories use [obsidian](<https://obsidian.md/>). They can also largely be viewed in github. Switch to `webview` branch for higher browser viewing compatibility.

## Upcoming works

### [dbmint](<https://github.com/LanHikari22/dbmint>)

This project builds on top of the [dbml](<https://dbml.dbdiagram.io/home/>) file format for creating database schemas and generating sqlite3 databases from them. 

Currently working on generating a rust project that integrates schema information into the rust type system and leverages compile-time guarantees for writing queries.

## Projects

### [bn6f](<https://github.com/dism-exe/bn6f>)

Reverse engineering Mega Man Battle Network 6. This reproduces the original game data from source code. It also has many derivative projects for tooling and analysis

Those include:
- [Related IDA Analysis](<https://github.com/LanHikari22/GBA-IDA-Pseudo-Terminal>) 
- [Automated generation of struct layouts using lua](<https://github.com/LanHikari22/GBA_Memory-Access-Scanner>)
- [Automated dumping of internal textscript within the game](<https://github.com/LanHikari22/bn_textscript_dumper>),

Upcoming:
- [high level editing of bn6f repository, sync with ghidra, and exporting type info for gdb](<https://github.com/LanHikari22/bn_repo_editor>)

### Reproduction projects

[rs_repro](<https://github.com/LanHikari22/rs_repro>) catalogs all minimal reproducible rust examples. This allows me to reference specific repro IDs that can be setup by anyone easily. 

For example, to get started quickly reading/writing [Rusty Object Notation](<https://github.com/ron-rs/ron>) files in rust, check out [repro003](<https://github.com/LanHikari22/rs_repro/blob/main/src/repro_tracked/repro003_ron_read_write.rs>): 

```sh
git clone https://github.com/LanHikari22/rs_repro.git && cd rs_repro && cargo run --features "repro003"
```


## Contact

Feel free to contact me at mailto:lanhikarixx@gmail.com. For comments, critiques, issues, or collaboration requests, please add "GITCHAT" to the email title. For business inquiries, please add "GITBUSINESS" to the email title.
