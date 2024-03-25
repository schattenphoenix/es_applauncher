# ES Applauncher
This is a small tool that mimics an emulator on android in order to allow apps to be listed inside [ES-DE]([https://pages.github.com/](https://gitlab.com/es-de/emulationstation-de)https://gitlab.com/es-de/emulationstation-de).

## Major changes in v2!
- Now needs to be pointed to ROMs
- Will create needed directories
- Will also create icons for you to move
- Can mark games with the checkbox

## Instructions
- Add the `.xml` files to `ES-DE/custom_systems/` (or integrate the content if already existing) to allow the custom system to show up
- Install the `es_launcher.apk`
- Run the `es_launcher.apk`, it should show a list of all your apps.
- Tap apps to disable / enable them (they wont show up in ES when greyed out)
- Tap checkboxes to mark them as games
- Long press apps to change their name (in case you have multiple with the same name, like Citra and Citra MMJ)
- Press the `save` icon in the top right and find the `ROMs` directory, give permission and confirm
- It should have create the needed folders and a file per app you have installed in `applauncher_apps` or `applauncher_games`
- Kill the `es_launcher` and `ES-DE`
- Restart `ES-DE`
- The new systems should show up
- Select one, it should open the es_launcher which then will run your app, so it should only shortly pop up
- Optionally move all icons from `applauncher_apps` or `applauncher_games` to `ES-DE/downloaded_media/android[apps|games]/covers`

## This is complicated for updates when I just installed a new app!
To update the applist, just launch ES Launcher from the app selection and select and deselect what you want and save again.
It should remove all deselected apps and put everything in the right folder, no need to follow all steps again.

## But xyz doesn't work!
Create an issue, I might look into it when I have time.

## Can I buy you a coffee?
If you happen to come to Berlin (Germany), sure, hit me up.
Otherwise I suggest you support ES-DE instead.
Leon is a great dev and invested a lot of work, I just created a small dirty app to help with one small shortcoming that will be fixed later down the line.
He should have all the coffee he can!
