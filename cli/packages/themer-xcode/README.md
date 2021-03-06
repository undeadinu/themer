# themer-xcode

An Xcode theme generator for [themer](https://github.com/mjswensen/themer).

## Installation & usage

Install this module wherever you have `themer` installed:

    npm install themer-xcode

Then pass `themer-xcode` as a `-t` (`--template`) arg to `themer`:

    themer -c my-colors.js -t themer-xcode -o gen

## Output

`themer-xcode` will generate a `Themer Dark.dvtcolortheme` / `Themer Light.dvtcolortheme` (or both) in your output directory.

Copy (or symlink) your theme(s) to `~/Library/Developer/Xcode/UserData/FontAndColorThemes/` (you can create this directory if it does not already exist), then restart Xcode. Your theme will then be available in Preferences > Fonts and Colors.
