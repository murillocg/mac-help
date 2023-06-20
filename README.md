# MacBook Help - Tips for using

Guide with tips related to migration from Windows to MacBook

## Setup

### Install basics tools

- Install Chrome
- Install iTerm2 with oh my zsh
- Install TextMate
- Install IntelliJ

### Install Java and Maven

Use the sdkman to manage java, including multiple versions.

Install sdkman:
```sh
curl -s "https://get.sdkman.io" | bash
```

Chose the java version and install
```sh
sdk list java
sdk install 17.0.6-sapmchn
```

Install the maven latest version
```sh
sdk install maven
```

### Install JMeter
```sh
brew install jmeter
```

List JMeter directories
```sh
brew list jmeter
```

## Shortcuts

### General

Shift Cmd 5: Open Screenshot and display the tools

Ctrl Cmd Q: Immediately lock your screen

Cmd Space bar: Show or hide the Spotlight search field

Cmd Comma (,): Open preferences for the front app

Cmd H: Hide the windows of the front app. To view the front app but hide all other apps, press Option-Command-H

### Document shortcuts

Fn Up: Page up

Fn Down: Page down

Ctrl D: Delete the character to the right of the insertion point. Or use Fn-Delete.

Cmd B: Boldface the selected text, or turn boldfacing on or off. 

Cmd I: Italicize the selected text, or turn italics on or off.

Cmd K: Delete the text between the insertion point and the end of the line or paragraph.

Cmd Left-Arrow: Move the insertion point to the beginning of the current line.

Cmd Right-Arrow: Move the insertion point to the end of the current line.

Option Left-Arrow: Move the insertion point to the beginning of the previous word.

Option Right-Arrow: Move the insertion point to the end of the next word.

### IntelliJ Shortcuts

Ctrl Option o: Optimize imports

Cmd [: Navigate to previows location 

Cmd ]: Navigate to next location 

Shift Cmd A: Find action

Esc: Focus on the editor

Cmd E: Recent files

Shift Cmd E: Recent locations

Cmd O: Open classes

Shift Cmd O: Open file

Cmd 1: Project view

Option F7: Find usages

Cmd N: Generate

Option Cmd L: Reformat code

Cmd F9: Build project

Shift Cmd V: Paste from History

Cmd Z: Undo

Shit Cmd Z: Redo

Cmd Delete: Delete line

Cmd D: Duplicate line or Select	lines

Shift Cmd U: Toggle case

### Caret navigation

Ctrl Shift Down: Next method

Ctrl Shift Up: Previous method

Option Shift Left: Move Caret to previous word with selection

Option Shift Right: Move Caret to next word with selection

# References 

https://support.apple.com/en-us/HT201236







