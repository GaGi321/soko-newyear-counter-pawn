# soko-newyear-counter-pawn
A system for counting down the time until the New Year for SA:MP 0.3.7 server!

<ins>**Only if it is December 1st does the timer start working!**</ins> (1.12 - 31.12.)

***You don't need to change anything,*** it's automatically set to count down the last 10 seconds until the new year.
When the last ten seconds tick, the countdown audio is played and at the end the New Year audio greetings.
Then the audio we wish you a merry christmass... is played immediately.

System language and audio: **Serbian**

YoutTube presentation, [click here](https://youtu.be/khSTsYd6hCs).

Requried includes:<br>
- a_samp
- foreach
- timerfix (Unsupported latest v1.1.2 by KashCherry)<br><br>

If you want to test the system, adjust here to your liking, recompile and run!  
_Don't forget to revert it back to how it was, otherwise it won't count down the last 10 seconds until the new year!_
```
stock IsCountdownTime(month, day, hour, minute, second)\ 
{   
    // Check if it's countdown time
    return (month == 12 && day == 31 && hour == 23 && minute == 59 && second >= 50);
}
```

Developed by Dragan Avdic (Dragi)<br>
Discord: @gangulax
