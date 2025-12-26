> Edited for use in IDX on 07/09/12

# Welcome to my Cosmos Exploration app 👋

This is a project where the beauty of space meets the creativity of modern generation.

Cosmospin potrays nasa's APOD (Astronomy Pictures of the Day) in the form of pinterest view.

## Get started

#### How to install the app

`git clone  https://github.com/itscliffordonyango/cosmospin-main.git`

`cd cosmospin-main`

#### Android

Android previews are defined as a `workspace.onStart` hook and started as a vscode task when the workspace is opened/started.

Note, if you can't find the task, either:

- Rebuild the environment (using command palette: `IDX: Rebuild Environment`), or you can run this command

   `npm run android -- --tunnel`

  This command  will manually run android and see the output in your terminal. The device should pick up this new command and switch to start displaying the output from it.

In the output of this command/task, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You'll also find options to open the app's developer menu, reload the app, and more.

#### Web

Web previews will be started and managred automatically. Use the toolbar to manually refresh.

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.
