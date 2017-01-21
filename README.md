# shelper
shell scripts i worte over time, that i think are usefull for other shell scripts

## central part
2 scripts
- singleparam (a simple "include" `. singleparam` thar just executes a script onece per paramete)
- shelper (not completly done yet, but with the same principale, just that it also parsed optiona parameters and provides them as variables)

## genal scriots
these are rather shortcuts for usecases that ocure a lot, but that are complex to type or where the simple solution is bash specific or simply unsecure
startswith
h2n, n2h (humsn readanbe number `-h` are converted into numbers, and via versa)
squote (take the input and convert it to a string that can be used in |sh or exec)
...

## usecase specific
zsh + X: shell functins that will put a good title on the terminal emulator
mounting of devices when the device lable is the same as the /media/* folder name
...
