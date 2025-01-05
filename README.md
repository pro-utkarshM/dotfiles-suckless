# dotfiles-suckless

This repository contains my customized configuration files (dotfiles) for Suckless tools, including `dwm`, `dmenu`, and `st`. These configurations are tailored to enhance my workflow and may serve as a reference for others interested in similar setups.

## Repository Structure

- `dwm/`: Custom configuration for the Dynamic Window Manager.
- `dmenu/`: Custom configuration for the dynamic menu.
- `st/`: Custom configuration for the simple terminal.

## Installation

To use these configurations, clone the repository and build each tool as needed:

```bash
git clone https://github.com/pro-utkarshM/dotfiles-suckless.git
cd dotfiles-suckless
```

For each tool (`dwm`, `dmenu`, `st`), navigate to its directory and run:

```bash
cd tool_name
sudo make clean install
```

Replace `tool_name` with the respective directory name.

## Usage

After installation, you can start using the customized Suckless tools as per your workflow. Ensure that the binaries are in your system's `PATH`.

## Acknowledgements

- [Suckless.org](https://suckless.org) for developing minimalist and efficient software.
- The open-source community for continuous contributions and improvements.
