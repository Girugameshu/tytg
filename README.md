# TyTg: Thank You Telegram!

Create a telegram bot for any purpose, or remotely control your pc with one. TyTg is written in Python3 and should work on any linux distribution.

TyTg allows users to navigate in a folder in a hosting pc. Directories are shown as Telegram buttons, allowing the creation of custom bots. Also, *.txt files are sent as messages, *.png &co are sent as images. You can also create *.tgfile containing a Telegram ID to send files. This allows to create bots by simply managing directories. 

You can also sort directories by putting {number} in their names. The {number} won't be showed in the button, but it'll be used to sort directories. If directory names ends with numbers, they'll be automatically sorted too.

TyTg will soon add support to change the directories and files remotely using the bot. It will allow to edit text, upload images, files, and so on. You'll also be able to run bash commands. TyTg also support inserting python scripts in the folders that allows making even more complex bots by adding features such as searching files by writing their names.

Finally, TyTg supports adding modules/ that get called on certain commands by admins. A built-in example is announce.py, that allows annuncing a message to every user by replying to that message with /announce. Finally, TyTg saves what every user downloads, how many downloads he did, how many total downloads has a certain file, and so on.

## Example:

Just look into the "main" folder:

    [<3] tree main
    main
    ├── Author {0}
    │   ├── logo.jpg
    │   ├── message.txt
    │   └── nylo_spam.txt
    ├── How to use {1}
    │   └── message.txt
    └── message.txt

This will become:

![](https://raw.githubusercontent.com/veggero/tytg/master/gh-files/example.png) 

Not a single line of code is needed.
