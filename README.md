# Ask-perplexity


# Running without building the app
Open the root directory of the project in cmd.
> run "npm install".
> close the cmd(if there are no issues. if there are, just write "npm audit fix --force" in the cmd and press enter.
>

Now, make a shortcut:
> The target: C:\Windows\System32\cmd.exe /c npm start

> Start in: "{the location of the folder with the all the files of this project}"


I found it faster to open it like that, for some reason the exe was taking a bit longer to start. Also, dont forget to change it so that it starts minimized, because then the cmd window will be seen and that just pointless :). You can also change the icon for the shortcut.


# To build this thing:

> run "npm install" in this project's directory.
>
> run "npm install electron-builder --save-dev" in this project's directory.
>
> run "npm run build" in this project's directory.
>
If you did all of this, everything should work fine. If it doesnt, make an issue and provide a video of you doing what i have said and it not working. Good luck!
(If it says "To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details."

do what it says: run "npm audit fix --force")

Also i provided the icon so you can, you know, have an icon for the shortcut.

# And yes, you can log-in with your Google account, and probably with the rest of them too(i tested only the Google account)
