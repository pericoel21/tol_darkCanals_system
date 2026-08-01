# Dark Canals

## What is this?
You're looking at a GitHub _repository_ for an _Obsidian Vault,_ which contains the rules for _Dark Canals,_ a Roleplaying Game System still in development by Matthew J. Ratcliffe (aka Tomb of Lime).

If you're new to words like _repository, Obsidian, Vault, Git_ or _GitHub_, don't worry! Everything will be made clear in this page!

### Obsidian
**[Obsidian](https://obsidian.md) is a notes management app** which works with local files; the **notes are in your computer,** in a folder that Obsidian calls _Vault._ 

 Obsidian uses **text notes in a format called Markdown,** and **shows them as a wiki,** with links, a graph view, and everything cross-referenced.

### Git & GitHub
**Git is a software that tracks changes in files.** This allows us to have notes that change over several versions, but we can keep track of the changes.

**GitHub** is a place where we can **upload and share projects managed with Git.** Anyone can pull a full copy of the vault from GitHub, get every update automatically, and browse it with all links and structure intact — much nicer than reading raw Markdown files one by one.

## What's in here
This is the structure of the Vault:
- `dark_canals/mechanics/` — core rules and skill system
- `dark_canals/philosophy/` — design principles and tone guidelines for running the game
- `dark_canals/devlog/` — development notes and design decisions as the system evolves
- `utility/templates/` — reusable Obsidian templates for content creation

## How to use this vault

### Setting up locally

1. **Install Git**, if you don't already have it.
    - Check first: open a terminal and run `git --version`. If it prints a version number, skip to step 2.
    - Windows: [git-scm.com](https://git-scm.com/download/win)
    - macOS: `brew install git` (or it may already be installed)
    - Linux: `sudo apt install git` (Debian/Ubuntu/Mint) or your distro's equivalent

2. **Clone this repo:**
    
    ```bash
    git clone https://github.com/pericoel21/tol_darkCanals_system.git
    ```
    
    This downloads the full vault into a new `tol_darkCanals_system` folder.
    
3. **Install Obsidian** — free, available for Windows, macOS, and Linux at [obsidian.md](https://obsidian.md).
    
4. **Open the vault:**
    
    - Launch Obsidian
    - Click **Open folder as vault**
    - Select the `tol_darkCanals_system` folder you just cloned
    - Obsidian will load it with the theme, plugins, and layout already configured

### Staying up to date

Since this vault is actively developed, pull the latest changes whenever you want to catch up:

```bash
cd tol_darkCanals_system
git pull
```

Reopen or refresh the vault in Obsidian afterward to see the changes.
