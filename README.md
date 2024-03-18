# ES Applauncher
This is a small tool that mimics an emulator on android in order to allow apps to be listed inside [ES-DE]([https://pages.github.com/](https://gitlab.com/es-de/emulationstation-de)https://gitlab.com/es-de/emulationstation-de).

## Instructions
- Add the `.xml` files to `ES-DE/custom_systems/` (or integrate the content if already existing) to allow the custom system to show up
- Create `applauncher_apps` directory in `ROMs` directory (or let ES-DE create them)
- Optionally create `applauncher_games` directory in ROMs directory (or let ES-DE create them)
- Install the `es_launcher.apk`
- Run the `es_launcher.apk`, it should show a list of all your apps.
- Tap apps to disable / enable them (they wont show up in ES when greyed out)
- Long press apps to change their name (in case you have multiple with the same name, like Citra and Citra MMJ)
- Press the `save` icon in the top right and find the `applauncher_apps` directory, give permission and confirm
- It should have create a file per app you have installed in `applauncher_apps`
- Kill the `es_launcher` and `ES-DE`
- Restart `ES-DE`
- A new system should exist that has a list of your apps
- Select one, it should open the es_launcher which then will run your app, so it should only shortly pop up
- Optionally move all games from `applauncher_apps` to `applauncher_games`
