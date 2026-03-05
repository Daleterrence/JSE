### Note

This is **not** my addon, this was originally made by a user by the name of Nalfey on the FFXIAH forums, who then later removed all of their addons due to some unpleasantness that is not worth getting into here. I'm providing this addon as an archive of their work, as it was beloved by those who used it, and there is a strong desire for it to be available *somewhere*. I probably won't be making any changes to it unless there's a significant bug or something that needs fixing. 

# JSE
JSE (Job Specific Equipment) is an addon for FFXI that tracks the AF, Relic, and Empyrean gear you have and the next available upgrades. 
It looks for the NQ, +1, +2, +3, +4 versions that you have for a specific job and tells you which upgrade materials you already have / need to augment the JSE to the next stage.

## Commands

**`//jse [ af | relic | empy ] <JOB>`**
- Check equipment and available upgrades for a specific job, displays upgrade materials you already have or need to upgrade that job's equipment.

**`//jsetrack [ af | relic | empy ] <JOB>`** 
- Same as the basic //jse command but also displays in an extra, draggable window.

**`//jsetrack [ hide | show ] `**
- Hides/shows the //jsetrack window.  

**`//jseall af <JOB>`** 
- Specifically for AF Cards, this will check for gear on the currently logged-in character and also checks for cards on all charcters/mules that have an existing data file. (The addon must have been loaded once on that character for data to be available)

**`//jsecurrency`**
- Displays tracked currencies for upgrades and their values (Rem's Chapters, Gallimauffry, Apollyon and Temenos units)

**`//jsehelp`**
- Displays the available commands

### v1.10
* Added a new command //jsetrack that displays the results in a dragable window. 
* Merged the //jse and //jsemats into a single command.
* Typo fix for SCH gear names and Maliya. Coral Orb.

### v1.01
* Minor display updates and syntax fix for DRG gear.

### v1.00
* First release.
