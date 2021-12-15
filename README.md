# The Key

## What is this?

Stack Overflow made an [April Fool joke](https://stackoverflow.blog/2021/03/31/the-key-copy-paste/) about a 3-key keypad just for copy/paste. And then [built one](https://drop.com/buy/stack-overflow-the-key-macropad#overview). So I had to have one.

Oh, I Tweeted about it.

https://twitter.com/andypiper/status/1471189409332670464?s=21

![The Key](img/IMG_4629.jpeg)

## Links

- [Original joke](https://stackoverflow.blog/2021/03/31/the-key-copy-paste/)
- [The Key](https://drop.com/buy/stack-overflow-the-key-macropad#overview) on Drop
- [Configuring The Key](https://drop.com/talk/93641/how-to-configure-stack-overflow-the-key-macropad) on Drop

The configuration steps documented above work fine (NB my Key came configured as Ctrl-C-V, but I predominently - not exclusively - use a Mac, and prefer Cmd-C-V). However, the site suggested (Keyboard Firmware Builder) is end-of-life, so ideally there would be better QMK support / integration with the up-to-date tooling.

## Resources

- 📁 `firmwares` - contains `.hex` files to upload using [QMK Toolbox](https://github.com/qmk/qmk_toolbox) or CLI
- 📁 `kbfirmware` - `.json` configuration for the (deprecated) [Keyboard Firmware Builder](https://kbfirmware.com/) site
- 📁 `keyboard-layout-editor` - files from the [Keyboard Layout Editor](http://keyboard-layout-editor.com) site. The `.json` layout can be imported into the KFB site. Also in a [Gist](https://gist.github.com/andypiper/1b3f5e690d8311475f31bd90f3b29d3c) that can be [loaded directly](http://www.keyboard-layout-editor.com/#/gists/1b3f5e690d8311475f31bd90f3b29d3c).

![Layout](keyboard-layout-editor/stack-overflow-the-key.jpg)

### TODO

- Create proper firmware for [qmk_firmware](https://github.com/qmk/qmk_firmware/) tooling and Configurator, since the `.json` files here are not compatible.

### What else?

Find [me](https://stackoverflow.com/users/262478/andy-piper) on Stack Overflow!

Send me PRs with alternative configurations? I'm still using mine as Cmd-C-V layout, single layer. More layers! Macros! Lighting!
