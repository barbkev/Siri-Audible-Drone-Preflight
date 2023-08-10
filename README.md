# Siri-Audible-Drone-Preflight
Siri Shortcut for an Audible, hands-free Preflight Checklist for Drone Pilots

# Setup
1. Create a list in the Reminders app called "Preflight Checklist"
2. Open both "UAS Preflight Checklist.shortcut" and "Preflight Weather Briefing.shortcut"
3. Answer the setup questions - not all of the defaults may work for your setup.
4. Run UAS Preflight Checklist, allow permissions as requested for reading/editing lists, requesting location, and writing files.

# Use
Preflight Checklist will read from your "Preflight Checklist" Reminder list and listen for you to say "Check" (This is customizable during setup - you can give it any word such as "Yes" or "Affirmative"). If you say anything else, such as "Skip", the item will not be checked and you will later have the option to come back and run through the missed items.
After running the checklist, each item is recorded into the "Preflight Log.txt" file, which should be saved in your "Shortcuts" folder (or the folder you selected during setup). A timestamp marks when it was run and each time the checklist is run the file is appended so that you have a record of running the checklist.
