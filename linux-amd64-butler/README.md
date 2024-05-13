itch.io tool for uploading game files.

https://itch.io/docs/butler/pushing.html

butler push directory user/game:channel

Where:

    directory is what you want to upload. It can also be a .zip file.
    user/game is the project you're uploading
        for example: finji/overland for https://finji.itch.io/overland — all lower-case
    channel is which slot you're uploading it to
        for example: windows-beta, osx-bonus, linux-universal, or soundtrack

Channel names will determine the initial set of tags of a slot, but you can always fix them later.

Tagging a channel as 'HTML5 / Playable in browser' needs to be done from the itch.io Edit game page, once the first build is pushed.

The page also needs to be set to 'HTML' rather than the default 'Downloadable'.

butler push mygame user/mygame:win32-final --userversion 1.1.0

