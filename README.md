# pop-launcher-bitwarden

Bitwarden plugin for Pop_OS! pop-launcher - your Bitwarden vault is always at your hand.
Puts the password into the clipboard.

## Requirements

- rbw (https://github.com/doy/rbw) `cargo install rbw`
- xclip `sudo apt install xclip`
- CopyQ `sudo apt install copyq`
- notify-send `sudo apt install notify-osd`

### Installation

Just clone the repo and run `make install`

### Usage
First of all, configure `rbw`` with `rbw config`
In the pop launcher press bw <search query> to search for your password.
Searches in Name, Username and Path.
Press enter to put the password into the clipboard.
