BreakReminder
============
BreakReminder is an gnome indicator app that displays the number of minutes for which you have been working  and reminds you to take a break after every 1hr or so. Improve your productivity and keep your eyes healthy. 

### Installation

Follow these steps to run the Appindicator in your system.

```
sudo apt-get install xprintidle
git clone https://github.com/gupta-komal/break-reminder.git
cd Break-Reminder
sudo chmod +x breaktimeIndicator.py
nohup ./breaktimeIndicator.py &
```
If you want the indicator to run at startup , add an entry for the indicator at Startup Applications.
In the command field select the breaktimeIndicator.py file using Browse.

### Improvements

- Add pause/continue 
- Option to change alert, snooze, idle limit times 
- ~~Monitor idleness and adjust time accordingly~~

