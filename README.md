## Auto-cast buffs script (Jakadak edit)

Do you want to use habitica party-buff, but have free API slots at all times?
Here is something for you <3

[Original script](https://github.com/bumbleshoot/auto-cast-buffs)

This version runs every 5 mins and leave space for your other API scripts (like auto-accept script).
As usual script checks the player's class to determine which skill to cast, and checks the player's mana to determine how many times to cast that skill.

## Setup Instructions
It is highly recommended that you use a desktop computer for this, as some of the steps don't work well on mobile. Make sure you read the [Before Installing](#before-installing) section above, and follow the instructions there if applicable!
1. Click [here](https://script.google.com/d/1aaIM1sQwQcHHNBCiUZWveD_dsAUX8pM8wqM4uZc4h5U52z5adBjZaVc1/edit?usp=sharing) to go to the Auto Cast Buffs script (Jakadak edition). If you're not already signed into your Google account, you will be asked to sign in.
2. In the main menu on the left, click on "Overview" (looks like a lowercase letter i inside a circle).
3. Click the "Make a copy" button (looks like two pages of paper).
4. At the top of your screen, click on "Copy of Auto Cast Buffs (Jakadak edit)". Rename it "Auto Cast Buffs" and click the "Rename" button.
5. Click [here](https://habitica.com/user/settings/api) to open your API Settings. Highlight and copy your User ID (it looks something like this: `35c3fb6f-fb98-4bc3-b57a-ac01137d0847`). In the Auto Cast Buffs script, paste your User ID between the quotations where it says `const USER_ID = "";`. It should now look something like this: `const USER_ID = "35c3fb6f-fb98-4bc3-b57a-ac01137d0847";`
6. On the same page where you copied your User ID, click the "Show API Token" button, and copy your API Token. In the Auto Cast Buffs script, paste your API Token between the quotations where it says `const API_TOKEN = "";`. It should now look something like this: `const API_TOKEN = "35c3fb6f-fb98-4bc3-b57a-ac01137d0847";`
7. Update `RESERVE_MANA` to the amount of mana you want left over after the script casts your buffs for you. Only edit the number in between the `=` and the `;`.
ADVENCED: If you are familiar with the code, you can adjuct CAST_PER_MINUTE or PROCESS_TIME (check below).
8. Click the "Save project" button near the top of the page (looks like a floppy disk).
9. Click the drop-down menu to the right of the "Debug" button, near the top of the page. Select "install" from the drop-down.
10. Click the "Run" button to the left of the "Debug" button. Wait for it to say "Execution completed".

**PS: What is PROCESS_TIME?**  
This script is using "wait" funciotn, that is set up, to cast 1 spell every 3s. But casting the spell also take some time (aproximatly 1s). So I use PROCESS_TIME as a way to include *costing spell time* in total *wait time*.
If you are courious about average cast/script time, you can chack [this](https://github.com/jakadak/auto-cast-buffs/wiki/Average-run-cast-time) graphs in wiki.


You're all done! If you need to change the settings or uninstall the script at some point, follow the steps below.  
[Errors? Chack: Before Installing](https://github.com/jakadak/auto-cast-buffs/wiki/Before-Installing)  
[Changing the Settings](https://github.com/jakadak/auto-cast-buffs/wiki/Changing-the-Settings)  
[Uninstalling the Script](https://github.com/jakadak/auto-cast-buffs/wiki/Uninstalling-the-Script)  
[Updating the Script](https://github.com/jakadak/auto-cast-buffs/wiki/Updating-the-Script)  

original script & tutorial by [@bumbleshoot](https://github.com/bumbleshoot/auto-cast-buffs#setup-instructions)
