# Network hotspot switcher for i3wm and `nmcli`

My internet at home is unreliable; I switch between my hotspot and my home network constantly.
This script detects which network is connected and issues the appropriate commands to `nmcli` to switch between them.

`nmcli`-based script for i3wm to switch between a hotspot and another network.

## usage

`python3 ./wifi-switcher.py`

## TODO

 - `argparse` to specify preferred and hotspot for configuration within i3 config file