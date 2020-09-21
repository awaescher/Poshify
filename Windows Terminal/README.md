# Windows Terminal

## Functions and aliases for PowerShell

See https://github.com/awaescher/Poshify/PowerShell

## Settings

```

// To view the default settings, hold "alt" while clicking on the "Settings" button.
// For documentation on these settings, see: https://aka.ms/terminal-documentation

{
	"$schema": "https://aka.ms/terminal-profiles-schema",

	"defaultProfile": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",

	"profiles": [
		{
			// Make changes here to the powershell.exe profile
			"guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
			"name": "Windows PowerShell",
			"commandline": "powershell.exe",
			"colorScheme": "OneHalfLight-Fixed",
			"background": "#ffffff",
			"fontSize": 9,
			"cursorShape": "filledBox",
			"cursorColor": "#383a42",
			//"acrylicOpacity": 0.55,
			//"useAcrylic": false,
			"hidden": false
		},
		{
			// Make changes here to the cmd.exe profile
			"guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
			"name": "cmd",
			"commandline": "cmd.exe",
			"hidden": false
		},
		{
			"guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
			"hidden": false,
			"name": "Azure Cloud Shell",
			"source": "Windows.Terminal.Azure"
		}
	],

	// Add custom color schemes to this array
	"schemes": [
		{
			"name": "Afterglow",
			"black": "#151515",
			"red": "#ac4142",
			"green": "#7e8e50",
			"yellow": "#e5b567",
			"blue": "#6c99bb",
			"purple": "#9f4e85",
			"cyan": "#7dd6cf",
			"white": "#d0d0d0",
			"brightBlack": "#505050",
			"brightRed": "#ac4142",
			"brightGreen": "#7e8e50",
			"brightYellow": "#e5b567",
			"brightBlue": "#6c99bb",
			"brightPurple": "#9f4e85",
			"brightCyan": "#7dd6cf",
			"brightWhite": "#f5f5f5",
			"background": "#212121",
			"foreground": "#d0d0d0"
		},
		{
			// back FBFBFB
			"name": "ayu_light",
			"black": "#000000",
			"red": "#ff3333",
			"green": "#86b300",
			"yellow": "#f29718",
			"blue": "#41a6d9",
			"purple": "#f07178",
			"cyan": "#4dbf99",
			"white": "#ffffff",
			"brightBlack": "#323232",
			"brightRed": "#ff6565",
			"brightGreen": "#b8e532",
			"brightYellow": "#ffc94a",
			"brightBlue": "#73d8ff",
			"brightPurple": "#ffa3aa",
			"brightCyan": "#7ff1cb",
			"brightWhite": "#ffffff",
			"background": "#fafafa",
			"foreground": "#5c6773"
		},
		{
			"name": "OneHalfDark",
			"black": "#282c34",
			"red": "#e06c75",
			"green": "#98c379",
			"yellow": "#e5c07b",
			"blue": "#61afef",
			"purple": "#c678dd",
			"cyan": "#56b6c2",
			"white": "#dcdfe4",
			"brightBlack": "#282c34",
			"brightRed": "#e06c75",
			"brightGreen": "#98c379",
			"brightYellow": "#e5c07b",
			"brightBlue": "#61afef",
			"brightPurple": "#c678dd",
			"brightCyan": "#56b6c2",
			"brightWhite": "#dcdfe4",
			"background": "#282c34",
			"foreground": "#dcdfe4"
		},
		{
			"name": "OneHalfLight-Fixed",
			"black": "#383a42",
			"red": "#e45649",
			"green": "#50a14f",
			"yellow": "#c18401",
			"blue": "#0184bc",
			"purple": "#a626a4",
			"cyan": "#0997b3",
			"white": "#fafafa",
			"brightBlack": "#4f525e",
			"brightRed": "#e06c75",
			"brightGreen": "#98c379",
			"brightYellow": "#e3ab42",
			"brightBlue": "#61afef",
			"brightPurple": "#c678dd",
			"brightCyan": "#56b6c2",
			"brightWhite": "#cccccc",
			"background": "#fafafa",
			"foreground": "#383a42"
		}
	],

	// Add any keybinding overrides to this array.
	// To unbind a default keybinding, set the command to "unbound"
	"keybindings": []
}

```