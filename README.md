# sakana cli

```
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡠⠖⠉⠀⣀⠀⠈⠑⢦⢠⠚⠉⢀⣀⠈⢳⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⡴⠋⢀⣤⣶⣿⣍⣉⣿⠆⢸⡇⠠⣾⠋⢹⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢸⠁⢠⡟⢰⡏⠀⠈⠉⠁⠀⠚⠛⠀⣿⠀⣼⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⠓⣿⠀⠀⠀⠀⠀⢀⡴⢶⡄⣻⠄⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⣿⠀⠀⠀⠀⢰⣿⡵⠟⠁⢹⡃⢾⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⢀⡆⠀⣿⠀⣷⠀⠀⠀⠀⠀⠉⠀⠀⠀⢸⣇⢸⠀⠀⠀⠀⠀⠀⠰⢤⡀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⣰⠋⢀⣤⡿⠀⣿⣀⣀⣠⣤⣤⡴⠖⡦⠀⢸⡇⢸⣤⠶⠶⠶⠶⠶⣄⠀⠙⡄⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⣇⠀⠿⠷⢶⠆⣴⠦⠤⢤⠾⠛⡇⢰⡇⠀⢸⡧⢈⡴⠞⠛⠛⠳⣄⠙⣷⠀⠃⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠘⠢⠄⠀⣸⠀⣿⠀⠀⠀⠀⠀⡇⢸⡇⠀⢸⡇⢸⠀⠀⠀⠀⢀⡗⢰⡏⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣹⡄⢹⡀⠀⠀⠀⠀⣷⢸⡇⠀⢸⡇⢻⠀⠀⠀⠀⢈⡷⢈⡇⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⣻⡁⠀⠀⠀⢀⡇⢈⣷⠀⢸⠆⢸⠂⠀⠀⠀⢸⡇⠘⡇⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⡄⠀⠷⠞⠛⠀⠀⠀⢀⣘⣷⣛⠁⠀⠻⠶⠛⠀⠀⠀⠀⠘⠷⠞⠃⢀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠈⠂⡄⠀⣠⣴⣾⣿⣿⣿⣿⣿⣿⣿⣷⣾⣶⣶⣶⣯⠇⠀⢤⡀⠒⠉⡀⠀⢀⡀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠘⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⣽⣭⣿⣿⣿⣿⣷⣤⡀⠉⠒⠊⠁⣀⡀⢱⡀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⣄⠈⠙⠿⢯⣽⣿⡻⣿⣿⣿⠿⣿⣿⣙⠋⠈⠉⠛⣿⣷⣤⣶⣿⠟⠁⢸⠁
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⠢⠤⣀⡀⠉⢻⢿⣟⣋⣼⠽⡫⠧⢤⣄⡠⠴⠯⣻⣿⣿⠁⢀⡔⠃⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⠟⠀⡎⢶⡭⢨⣿⠀⡇⠰⠖⣸⠇⠀⡄⠈⢿⣿⠀⢸⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⡠⠔⠋⢀⣠⡔⢶⣄⢷⠠⢸⢀⡧⣶⣆⣿⠀⠸⡜⡄⠈⠿⠀⢨⠀⠀⠀
⠀⠀⠀⠀⠀⠀⣀⡠⠤⠒⠉⢀⣠⣴⣶⢟⠙⠛⠶⠏⣤⠖⢹⣿⠟⠟⢸⣿⣷⡀⠘⣌⠒⠒⠒⠋⠀⠀⠀
⠀⠀⣀⠤⠖⠊⠁⣀⣠⣴⣶⣿⣿⠛⣣⠘⠛⢀⣠⣴⣿⣶⣿⡏⣴⣇⣿⣿⣿⢿⡄⠘⣆⠀⠀⠀⠀⠀⠀
⠀⡞⠁⣠⣴⠞⠏⠉⠻⢿⣍⠀⠛⠂⢀⣠⣴⡿⠿⠛⠛⣯⣠⡆⣻⢁⡻⣭⣿⣮⢿⡄⠸⡄⠀⠀⠀⠀⠀
⢸⠁⢸⡻⠊⠉⠓⠒⠒⠾⠗⠒⠚⢭⣽⡿⠋⢀⡠⠤⣄⠈⢁⣷⣯⣸⠓⢦⣹⣿⣯⣧⠀⠹⡄⠀⠀⠀⠀
⠈⢇⠀⠙⠢⠤⠤⣀⣀⣀⠤⠤⠔⠛⠉⢀⡴⠋⠀⠀⠈⠀⢸⣏⢋⠿⢷⣤⣀⣉⣿⣿⣷⡀⠹⡄⠀⠀⠀
⠀⠀⠑⠒⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠊⠁⠀⠀⠀⠀⠀⠀⢸⣾⣦⣄⣀⠀⠀⠉⢩⣻⣿⣷⠀⡇⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡄⠈⢯⠈⠁⠉⠉⠉⠉⠉⠉⣵⣿⠀⡄⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠑⣄⠈⠛⠤⣀⣀⠀⢀⣀⣸⠿⠃⢠⠇⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠑⠦⣄⡀⠀⠁⠈⠀⠀⠀⠴⠃⠀⠀⠀⠀
```

A Lua script that will output a random ascii art that is fish, fish-containing or a fish-like creature.

Careful: some fih may contain unicode characters

# help

```
Usage: sakana [OPTIONS]

Using without options will include all ascii arts (big and small)

Options:
    --big
      outputs only the big fihes
    --nobig
      output only small fihes

Options that do not produce fihes:
    --help
      prints this text
    --count
      counts how many sakanas are in the pond
```

# installation
There is only a [sbpm](https://github.com/RambilE/sbpm) way of installing this right now (or just manually copy the file to ~/.loca/bin)
```
sbpm get rambile/sakana
```

When i will "rewrite" sbpm in lua this will be the new way of installing this
