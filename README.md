# HogwartsLegacyOptimizer
Optimizations for Hogwarts Legacy on the Steam Deck, based on the Ascendio mod. These tweaks work in many Unreal Engine 4 games and make them significantly smoother.

Update on 3/8/2023: These .ini tweaks seem to still benefit the performance of the game even on the latest patch.

**Automatic Method (only for Steam Deck):**

Download the HogwartsDeckOptimizer-V02.sh file, right click on it > properties > permissions > check the box for "is executable."
Then just click and run it.

**Manual Method (works on Windows too):**

Place this Engine.ini file in:
/home/deck/.local/share/Steam/steamapps/compatdata/990080/pfx/drive_c/users/steamuser/AppData/Local/Hogwarts Legacy/Saved/Config/WindowsNoEditor/Engine.ini

If you're on Windows, place it in %LOCALAPPDATA/Hogwarts Legacy/Saved/Config/WindowsNoEditor/

You need to run the game at least once to generate this directory.

**Completely Removing This:**

To remove these tweaks, delete your Engine.ini file and the game will regenerate a fresh, default one.
