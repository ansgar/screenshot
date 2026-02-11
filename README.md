# screenshot-scripts
There are two scripts in this repository to select a section of the screen and copy the image or its text to the clipboard.

The scripts can be assigned the key combinations Shift + Meta aka Windows + S or Shift + Meta aka Windows + T to replicate the Windows behavior of Snipping Tool or Power Toys Text Extractor.

That would look like 

```ini
[Shift%2BMeta%2BS.??]
Comment=Screenshot in die Zwischenablage
Enabled=true
Exec={your Path to}/screenshot2clipboard

[Shift%2BMeta%2BT.??]
Comment=Text eines Screenshots in die Zwischenablage
Enabled=true
Exec={your Path to}/screenshot2clipboardviaocr
```
in `~/.config/lxqt/globalkeyshortcuts.conf`

if LXQt is your preferrred desktop environment.
