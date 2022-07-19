# tabbed - generic tabbed interface

tabbed is a simple tabbed X window container.

![image](https://user-images.githubusercontent.com/71596800/179753219-c8dbf556-555f-4568-a1cc-0d74f852fee0.png)

## Requirements

In order to build tabbed you need the Xlib header files.

## Installation

```bash
git clone https://github.com/basilioss/tabbed
sudo make install
```

## Usage

- Open st with tabbed: `tabbed -c -r 2 st -w ""`.
- Open surf with tabbed: `tabbed -c surf -e`.
- Tabs will appear if more than one window is opened.
- Open new tab with `ctrl + shift + enter`.
- Check `config.def.h for more keybindings.

## Credits

- Thanks [6gk](https://github.com/6gk/tabbed) for centered title patch
