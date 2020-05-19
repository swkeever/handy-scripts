# Handy Scripts

Here is a collection of the scripts that I find handy.

More to come! Pull requests are welcome.

## Usage

After cloning this repo, follow [these instructions](https://gist.github.com/nex3/c395b2f8fd4b02068be37c961301caa7) to set up your `PATH` so that you can run any of the scripts by typing `<script_name>` in your terminal.

## List of scripts

*Note: If Usage is omitted, it means the script is supposed to be used by simply calling the script name.*

- `close_windows`: closes all currently opened windows.
  - Dependencies: `wmctrl`
  - [Source](https://askubuntu.com/a/166686)
- `pbcopy`: copies the text from stdin into clipboard buffer.
  - Dependencies: `xclip`
  - Usage: `echo "Welcome To OSTechNix!" | pbcopy`
  - [Source](https://www.ostechnix.com/how-to-use-pbcopy-and-pbpaste-commands-on-linux/)
- `pbpaste`: pastes copied content
  - Dependencies: `xclip`
  - Usage: `` echo `pbpaste` ``
  - [Source](https://www.ostechnix.com/how-to-use-pbcopy-and-pbpaste-commands-on-linux/)
