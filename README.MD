# consolidate
Console based ASCII date sim


![icon](res/icon.png)

Made for [GameOff](https://itch.io/jam/game-off-2017) gamedev contest.

# system requirements
I haven't figure out specific system requirements for the game but I assume that having a Windows or Linux OS on your machine should be enough to run the build. 

# customization
You are free to alter the assets. You can change the entire dialog to your self written and replace all scenes. Navigate to `res/` folder and see. All scenes are just `.txt` files with ASCII arts. To change the dialog you should be able to deal with `JSON` format. Dialog is located under `res/dialog/`.

# deploy/build
1. Install requirements using pip. You probably want to use [virtualenv](https://virtualenv.pypa.io/en/stable/).

`pip install -r requirements.txt`

2. There is a build scripts to make an executable. `build.sh` for Unix based systems and `build.bat` for Windows. Windows executable requires `res` folder to be in the same directory. Linux build is fully standalone.


# todo

1. Refactoring!
2. Ability to set player name.
3. Ability to choose the story from several available.
4. Change dialog resource format from JSON to ?
