# EchoWave_cmd
CMD interface to connect to all EchoWave II instances opened. To properly detected them, they can’t be minimaze, also if you trigger the device but EchoWave is reduced it won’t work. 

Here are a list of commands that you can use to control EchoWave II from other program like Spike. 

The commands are:

- “Save + filename” —> it will save the TVD file with the filename you chose, if don’t give the entire path + the filename, it will automatically save it in the default folder EchoImages

- “Tap” —> it will freeze or unfreeze depending on EchoWave status

- “Freeze” —> It will just freeze 

- “Run” —> it will just Run

- “Play (+ filename) ” —> it will play the selected filename or the one that is opened 

- “Close” —> it will close the EchoWave instances

Example in Spike:

ProgRun(“Path/To/EchoWave_CMD.exe Save file/path/name”);
ProgRun("Path/To/EchoWave_CMD.exe Tap")
ProgRun("Path/To/EchoWave_CMD.exe Freeze")
ProgRun("Path/To/EchoWave_CMD.exe Run")


It's useful in case you don't or you can't create a sequencer file and you don't want to run manually echowave everytime
