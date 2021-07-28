# ImportStarship
Roll20 imported for starship from the Hephaistos site. Only for Starfinder by Roll20 sheet.

Version 1.00

In order to import your ship:
1. Create a new character. Make sure to mark it as a starship sheet. 

2. Create an attribute on that sheet named starship_data. Paste the JSON as is into the field for this attribute. 

3. Drag a token to the VTT, select it, and run the !importStarship command. 

Fair warnings!

I've only tested this for ships built with the CRB. So other things may cause crashes. Look at the console in the API page for possible errors as well. 

Expansion bays and systems are lumped into one pane instead of separated. This seems to be a bug in the sheet as I can't shift systems manually either. 

Also, all systems need to be powered off and then back on for the sheet to recognize the correct system; shields, armor, computer, and what-not.
