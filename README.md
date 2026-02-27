# Writing-Projects

The place where I store and work on all of my writing projects.

## About

This is the parent repository for all of my personal writing work. It doesn't contain much on its own — the content lives in the submodules below. Think of it as the container that holds everything together in one place, with Obsidian configured at the root so the whole collection can be opened as a single vault.

## Submodules

This repository references four submodules. Two are public and two are private.

### [WP-Author-Study](https://github.com/Broomfields/WP-Author-Study) — Public

Study notes on the techniques and practices of different authors, collected to better inform my own writing. Organised by author, with each directory covering their style, craft choices, and anything worth taking away.

### [WP-Skills-Study](https://github.com/Broomfields/WP-Skills-Study) — Public

A focused study of specific writing skills and techniques, independent of any particular author. Currently split into character writing and prose techniques. The goal is to build a reference I can return to as my understanding develops.

### WP-World-Of-Essentia — Private

The main writing project. A personal fantasy world built around a universal magic system rooted in essence — elemental energy shaped by environment and channelled through meridian pathways developed by living beings. The project is split between world building (fundamentals, subsystems, geography, society, bestiary) and stories set within it. The first short story in progress is *All She Gave the Flame*. This repository is private and not publicly accessible.

### WP-Miscellaneous-World-Building — Private

A scratch space for random world building ideas as they come to me — new races, magic systems, cultures, character premises, story concepts. Anything that doesn't yet belong to a specific project lands here. This repository is private and not publicly accessible.

## Cloning

If you clone this repository, the public submodules will initialise without issue. The two private submodules (`WP-World-Of-Essentia` and `WP-Miscellaneous-World-Building`) will fail to pull unless you have been granted access — you'll get an authentication error rather than anything breaking permanently.

```bash
git clone --recurse-submodules https://github.com/Broomfields/Writing-Projects
```

If you only want the public submodules, you can initialise them selectively:

```bash
git submodule update --init WP-Author-Study
git submodule update --init WP-Skills-Study
```

## Tooling

- **Obsidian** is the writing and note-taking environment, configured at the repository root so all submodules are accessible within a single vault.
- **Git** for version control across all projects.
