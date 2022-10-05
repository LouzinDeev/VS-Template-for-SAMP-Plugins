# SA-MP Plugin VS 2022 Template

## How To compile?
	Use Ctrl + shift + b for build the solution
	OBS:If VS can't open the dependencies, or gives an error when opening the files
	go to Project -> Show all files, then you can repeat to go back to the filters, if you want

## How Install?
	Just execute the installer

## Testing
	i set it to play .dll file in test/plugins folder, use command terminal

	```bash
	cd test
	sampctl p init
	```
	After just add "plugins": ["yourPluginName.dll"] to pawn.json in runtime section.

	DO NOT FORGET TO ADD THE INCLUDE WITH YOUR NATIVES "_"
