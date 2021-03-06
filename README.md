# blockup

Scaffold and serve html, specifically focused on [bl.ocks](https://bl.ocks.org/). Go from idea to block from the comfort of your own text editor.

![demo](https://cloud.githubusercontent.com/assets/370976/19009608/acde643a-8743-11e6-9656-d49e4448c2b1.gif)

## why?

[bl.ocks](https://bl.ocks.org/) is a great tool! But using the [Gist site](https://gist.github.com/) as a text editor is no fun. This little tool helps you make blocks just a tiny bit faster:
- one command, `blockup`, scaffolds and serves a new block
- write ES6 and it gets compiled down to ES5
- write [Stylus](http://stylus-lang.com/) and it gets compiled to CSS (because you have a [finite number](http://keysleft.com/) of keystrokes)
- browser reloads on file change
- errors during compilation pop up in notification bar

That's it for now. It probably won't grow beyond this. But if you have an idea, [I'd like to hear it](https://github.com/gabrielflorit/blockup/issues)!

## usage

```sh
Usage: blockup <command>

Commands:
  new    scaffold and serve a new block (default if directory is empty)
  serve  serve current block (default if directory is not empty)

Options:
  -h, --help  Show help                                                [boolean]
  --version   Show version number                                      [boolean]
```

## great! but is there a way to upload to gist from the command line?

Yes! See [gistup](https://github.com/mbostock/gistup).

## install

` npm install -g blockup`

## related

- https://github.com/1wheel/gist-snap: snapshot thumbnails for [bl.ocks.org](http://bl.ocks.org/)
- https://github.com/mbostock/gistup: create a gist from the command line
