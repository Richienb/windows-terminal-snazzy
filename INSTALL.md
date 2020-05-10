### [Windows Terminal](https://github.com/microsoft/terminal)

#### Install

Start Windows Terminal and click on the down arrow symbol `˅` from menu bar. This will open a drop down menu from which select Settings option. Alternatively use `Ctrl + ,` to open Settings directly.

In the `profile.json` settings file for Windows Terminal, find the `schemes` section and paste the content of `snazzy.json`.

Example:

```json
"schemes": [
    {
        "name" : "Snazzy",
        ...
    }
]
```

#### Activate

Once the color scheme has been defined, it's time to enable it. Find the `profiles` section and add a `colorScheme` value to the profile you want to apply the theme to.

Example:

```json
"profiles": [
	{
        "guid": "{c5e01457-d08a-47fd-aa60-b128820d7352}",
        "name": "cmd",
        "commandline": "cmd.exe",
		"hidden": false,
		"colorScheme" : "Snazzy"
    }
]
```
