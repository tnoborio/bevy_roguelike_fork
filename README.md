# Bevy Roguelike — modernized fork

This is a community-maintained fork of [sarkahn/bevy_roguelike](https://github.com/sarkahn/bevy_roguelike).
The goal is to learn Bevy while modernizing the codebase to current toolchain and libraries.

> **Status:** actively updating to **Bevy 0.16** and latest ecosystem crates.

![](images/demo.gif)

## Why this fork?

- Keep the project building against **current Bevy** and friends.
- Document the migration steps (notes inline and in PRs).
- Serve as a lean reference for ASCII-style roguelikes on Bevy.

### Upstream & credits

- Original game: **sarkahn/bevy_roguelike** (MIT). Rendering uses **bevy_ascii_terminal**.  
  See the upstream repo and license for details.  
- This fork is unaffiliated with upstream; all credit to the original author(s).

## Tech stack (targets & versions)

- **Engine:** Bevy **0.16** (latest stable as of Aug 2025). Bevy’s MSRV policy generally tracks the **latest stable Rust**. :contentReference[oaicite:0]{index=0}
- **Terminal rendering:** `bevy_ascii_terminal` **0.17.\*** — compatible with Bevy **0.16** (per the crate’s version table). :contentReference[oaicite:1]{index=1}
- **Rust edition:** **2024** (stable since Rust 1.85). :contentReference[oaicite:2]{index=2}

## Getting started

### Prereqs

- **Rust (stable)** — recommended: `rustup update stable`. Bevy relies on recent compiler features, so MSRV ≈ “latest stable”. :contentReference[oaicite:3]{index=3}

### Clone & run (native)

```bash
git clone https://github.com/tnoborio/bevy_roguelike_fork
cd bevy_roguelike_fork
cargo run
