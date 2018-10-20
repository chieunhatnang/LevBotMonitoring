# LevBotMonitoring
Automatically restart any bot at a specific time or periodically

# Download

# Usage
This bot supports 2 working mode. By default, the monitor starts without argument and it will load the saved setting from the previous session (setting.ini file). In this mode, it will also overwrite the setting when it's closed.  If the monitor is started with any arguments, it will not load the saved setting and will not save the settings file also.

## Arguments

LevBotMonitoring -p <exe_path> -m <each|fix> -t <running_time (m)> -a

* -p: Specify the file path of the executable file. Please note that if there's space in the path, you have to enclose the path in the double quote ("").
* -m: Specify the monitoring type: There are 2 types
    * each: Restart the executable file each period of time.
    * fix: Run the executable file for a period of time.
* -t: Specify the running time in minutes for mode "each".
* -a: Automatically click the "Start" button when the bot is opened.
