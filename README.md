# Launcher
This is the GUI application that is used to launch separate apps, such as School View (originally CanvasView), RePiskel, etc.

## App Outline
The app opens and displays the icons for each app, just like a desktop. (On tiling window managers, this will be specifically made floating.)
There are settings that can be changed, such as making the theme consistent, notification settings, etc.
When an app is opened, the window will tell the app's window to be the same size as it, and when the app opens on top of it, the launcher will close.
That app will then resize to a normal size.

When the app is closed, it will shrink its window size down to the launcher's size, then reopen the launcher.

## Other Stuff
Trying to launch an app manually with integration with this Launcher will fail if the app is already opened or the Launcher is open.
Trying to open the Launcher will fail if the Launcher is already open, or if another app with Launcher integration is open.
