This repo contains some personal changes I made to some icons and the OpenSUSE logo for my status bar.

Install with `./install.sh --alternative`.

My version:

<img width="963" height="117" alt="image" src="https://github.com/user-attachments/assets/061ab5e6-abd2-4478-a709-81b7ea666cf2" />

<img width="964" height="118" alt="image" src="https://github.com/user-attachments/assets/17a5e7c0-4dcb-4383-b69d-91635f76ae7c" />

<img width="964" height="118" alt="image" src="https://github.com/user-attachments/assets/3adbf4d1-8fa3-4fe7-872f-826f2f89ef39" />

Original:

<img width="964" height="118" alt="image" src="https://github.com/user-attachments/assets/a442cfdd-6cdb-4f9e-92de-a27c731e2d71" />


<img src="logo.png" alt="Logo" align="right" /> WhiteSur Icon Theme
======

MacOS Big Sur like icon theme for linux desktops

### Donate

If you like my project, you can buy me a coffee:

<span class="paypal"><a href="https://www.paypal.me/vinceliuice" title="Donate to this project using Paypal"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal donate button" /></a></span>

## Install tips

Usage:  `./install.sh`  **[OPTIONS...]**

|  OPTIONS:           | |
|:--------------------|:-------------|
|-d, --dest           | Specify theme destination directory (Default: $HOME/.local/share/icons)|
|-n, --name           | Specify theme name (Default: WhiteSur)|
|-t, --theme          | Specify theme color variant(s) [default/purple/pink/red/orange/yellow/green/grey/all] (Default: blue)|
|-a, --alternative    | Install alternative icons (redesigned MacOS default icons)|
|-b, --bold           | Install bold panel icons version|
|-r,--remove,-u,--uninstall | Uninstall (remove) icon themes|
|-h, --help           | Show this help|

> **Note for snaps:** To use these icons with snaps, the best way is to make a copy of the application's .desktop located in `/var/lib/snapd/desktop/applications/name-of-the-snap-application.desktop` into `$HOME/.local/share/applications/`. Then use any text editor and change the "Icon=" to "Icon=name-of-the-icon.svg"

> For more information, run: `./install.sh --help`

![alt](alt-version.png?raw=true)

![bold](bold-size.png?raw=true)

> Bold version suggested use in `High resolution display` like 4k display with 200% scale!

## Requirement
You can use this with:

### GTK theme

WhiteSur-gtk-theme: https://github.com/vinceliuice/WhiteSur-gtk-theme

### KDE theme

WhiteSur-kde: https://github.com/vinceliuice/WhiteSur-kde

## Preview
![1](preview.png)
![2](preview01.png)
