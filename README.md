# Toggle Theme

This script aims to make it very easy to change the theme of applications.

During the day when my room is bright I prefer to use light themes, while I prefer during later hours a dark theme. To make the switch between the themes easy I wrote this simple script, `toggle-theme`.

With `toggle-theme` you can switch between our favourite light and dark theme. For me it is [catpuccin mocha and catpuccin latte :black_cat:](https://catppuccin.com/).

`toggle-theme` is as simple as it can get. You write bash functions `MyProgram-dark`, `MyProgram-light` and optionally `MyProgram-apply`. These functions define how to setup the theme if needed setup or reset your program to pick up the new theme.

## Installation

Simply copy the `toggle-theme` to you path. For example into `~/.local/bin`. From there on you need to adapt the script to your needs.

## Usage

```
$ toggle-theme <theme>
```

You can pass to the `<theme>` argument in `toggle-theme` either `dark`, `light` or `switch`. Anything else results into an error. Accordingly `toggle-theme` will run the configured scripts.

# License

[MIT](./LICENSE)
