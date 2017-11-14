You can find the description for the Icarus Clock Widget [here](clock.md)

# Icarus Launcher

Icarus Launcher is a custom launcher for Android phones built solely for the LARP Icarus by Terre Spezzate. It won't be useful for anyone outside the game. It replaces the launcher (= home screen) of your Android phone and offers functionality you might find useful during the game. It also alters the look and feel of your device to allow for a maximum of immersion.

It offers the following features:
* clock running on the 14h station time cycle
* personal log where you can type notes, record audio clips, or save pictures
* a customizable set of station regulations for easy lookup during the game
* access to all apps on your phone through a list stripped of the icons. No need to find a sci-fi icon for your calculator
* possibility to hide apps you don't want to use
* all of the above locked with a password, so you can easily use your character password, but can disable the lockscreen of your device entirely
* fully customizable colour scheme
* can be locked to all orientations of your device, in case you want to carry it in some crazy configuration

I built this thing in a very short time, so it is possible there are bugs and it might not run on your device.

## Instruction
Install the app and start it by pressing the home button. You should set it as the default launcher once your device asks you to.

On the first launch, the app will show you the configuration screen. This will only be shown once, so do not miss it. If you need to see it another time, you need to clear the app data.

If you are running Android 6 or later: if you want to use the audio recording features, please go to the app settings from here and click on permissions in the following screen. Enable the record audio permission, and go back to the configuration screen with the back button. The storage permission is required to read regulations and blocked apps from your download folder (see the sections for more information).

Once you are done on the configuration screen, leave it via the back button. You will see the Launcher home screen.

## Clock
The clock automatically runs on the scheduled time for the Icarus International run. It offers a few of customization options. You can access the clock settings by tapping on the top bar in any screen where it is shown.

Clock colours will be used by the rest of the launcher as well, to maintain a coherent UI, so feel free to customise this.

The clock allows you to select your shift. It will then remind you, when it is time for you to sleep.

You can enter a time offset (positive or negative) in case the game starts early or late.

## Security

The Launcher automatically locks itself once the screen is turned off. You can lock it manually by pressing the lock icon on the home screen or long-pressing the back/lock icon on the other screens.

When the launcher is locked, you need to unlock it before you can start using it again. To do that, press the UNLOCK button below the clock. You will then be directed to the password screen, where you can enter your password. Entering the password for the first time will set it for the game, so make sure to enter your character password from your character description.

## Personal log

The core of the launcher is a personal log for the events you encounter during the game. I didn't just want to create a notebook, so I added a few twists to this part, that might enable a bit of nice play, if a character password is breached.

Log entries can not be edited once they are saved. This is partly because it saved me the time to build that functionality, but mostly so you can't easily delete incriminating information. You can delete log entries. However, nothing is truly lost in a world of advanced tech, so I decided to at least show that a log entry was originally there. It is play to lose after all, and having a bunch of deleted log entries from a suspicious time, is a great way to get us into trouble. And who knows, maybe there are even some ways to restore them. I explain this in game by every device being connected to a huge network, where it might takr days to purge an entry from all running nodes and backups.

You can create log entries by typing them (or using the very funny speech-to-text function), by recording audio, or by taking a picture with your device camera. All methods for creating a log entry are available from the launcher or from the journal listing the log entries.

To start an audio recording, simply tap the microphone button. A red indicator will be shown when the recorder is running. Tapping the button again will stop and save the recording. Recording audio even works when the screen is off or the launcher is locked, so you can easily record in secret. Recording prevents your device from going to sleep, so it can be a drain on the battery.

## Regulations

On Icarus, there are a lot of regulations and you might not have learned every detail of it. That's why you can look them up in the regulations section. After installation, the app does not have any regulations to show, but you might want to put at least the company bylaw there. To create a regulation that will be shown in the app, follow this procedure:

* create a folder "regulations" within your Android download folder. This is the folder where Android will store downloaded files by default.
* put a txt file in the folder for each section of the regulations you want to use.

The first line of the file marks the category the regulation belongs to. This will be used for sorting them. The second line is the title or caption. All following lines are the content that will be displayed.

To give you an example, here is the file for a company bylaw section.

Since I am in the mining team, I already created custom steps for the miners. If you are a miner, please just use those. I posted them in the mining Facebook group. If you are not on Facebook, contact me (below) and I'll send them to you personally. I don't want to put them on display for anyone to see without the permission of the Icarus team.

## Apps

Of course you might want to use your device in any way I can't really forsee during the game, so the launcher of course also allows you to access your apps as usual. Apps will be shown in a simple list, without Icons. That is because most of them don't look very sci-fi.

Hiding apps. Since it is not very canon to have the Google Play Store available on a device, you can create a list of blocked apps, that will not be shown by the launcher. To do so

* create a file apps.txt in your devices download folder. This is the folder where Android usually stores files you download from the internet.
* enter the names of every app you wish to hide in an individual line.

My file looks like this, for example.

## Contact

If you want to thank me, I will be playing J. Kowalski (#5) in the international run. I'll be happy to hear from you how you liked the app.

Contact me [on facebook](https://www.facebook.com/Thrakbad) or [via mail](mailto:thorsten.schillo@googlemail.com), or [create an issue on github](https://github.com/Thrakbad/Thrakbad.github.io/issues).
