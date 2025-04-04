# frc-arch-pkgs

`frc-arch-pkgs` is a collection of Arch Linux `PKGBUILD` packages designed to simplify the installation and management of common tools used by FIRST Robotics Competition (FRC) teams.

## Packages

This repository includes `PKGBUILD` scripts for the following tools:

- **frc-elastic-dashboard-bin**: A prebuilt package for the [Elastic Dashboard](https://github.com/Gold872/elastic-dashboard).
- **frc-advantagescope-bin**: A prebuilt package for the [Advantage Scope](https://docs.advantagescope.org/) data visualization tool.
- **frc-pathplanner-bin**: A prebuilt package for the [PathPlanner](https://pathplanner.dev/home.html) path planning tool.

## Installation

To install a package from this repository:

1. Clone the repository:

```bash
git clone https://github.com/TheBotlyNoob/frc-arch-pkgs.git
cd frc-arch-pkgs
```

2. Build the package using `makepkg`:

```bash
cd <package-name>
makepkg -si
```
