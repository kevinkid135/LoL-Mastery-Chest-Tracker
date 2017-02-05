#### Domains:
* https://lolcc.000webhostapp.com/
* https://www.lolcc.me

If you are checking this website without any League of Legends background, feel free to search for the name "Kirox3" without quotations. This is my personal game handle.

# About
This application allows the user to search up a summoner name and see all chest availability for each champion. All data will be obtained from the riot API.

## Current Features
* Display champion portraits and graphically show if the chest is unlocked or not
* Sorted by:
	* champions with chests
	* alphabetically
	
* FWOTD Calculator
	* Determines whether FWOTD is up. If not, it will tell you how much time is left.
	
* Search by champion name

## TODO List
* Make the portrait glows reflect the tier they're currently in:
	* Tier 4: Gold - #2da7a8
	* Tier 5: Red - #2da7a8
	* Tier 6: Purple - #ae26b4
	* Tier 7: Emerald/Teal - #2da7a8
	* [Master Emote Reference Images](http://1.bp.blogspot.com/-4D5ZQjXvLzo/VQDK1opIjJI/AAAAAAAAlqQ/DHXkZFedzs4/s1600/44.jpg)


## Features (planning stage)
These will be features that I've thought of, but have not mapped out its implementation.

* Sort by (client side):
	* Highest mastery rank
	* Alphabetical
	* Champions with chests (then alphabetical)
	* Champions without chests (then alphabetical)
* Hide/show certain champions based on:
	* Chest availability
	* champion owned	
* Create an offline JSON file of static champion information.
	* This can be a script ran every time the version has changed since the last run.
	* The JSON file will 2 identical arrays for faster access:
		* champID => array(name, key, portraitURL)
		* champKey => array(name, ID, portraitURL)

* Progress bar to show how many chests you've unlocked in the season
	* The progress bar will indicate the total amount of chests you can unlock in a year, and how much you've unlocked so far

### Personal Goals with this project:
* Create a usable and functional website
* Apply constant code refractoring to maintain clean and readbale code that is easily maintained in later stages
* Learn to work with an API (riot API)
* Have a high quality assurance
	* Avoid code smells
* Create test cases
* Learn to use GitHub
	* Creating a proper README
	* Comitting
	* Documenting changes
