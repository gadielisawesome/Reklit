# NoSchool. The anti-monitoring software for people who don't like work.
Stops LanSchool from running on your system using some sort-of simple PowerShell scripts and shortcuts.
This works on LanSchool Classic and LanSchool Air.

## How it works

This works by exploiting a very simple oversight that was left in LanSchool Classic/Air.
For some reason, LanSchool runs at the user-level without ANY escalation at all.
I'm assuming this is so it can capture your screen. Just a guess.

But I think you know the script does now.
(it literally just kills the process running on a loop so it can't restart)

### How to install it

How to install (Windows only - No administrator privs are needed for any of these)

If your computer allows regular ol' apps to be run on it, use the .NET Framework version. (Portable only, doesn't install)
If your computer uses anti-viruses or it a bit more locked down, use the Powershell version.
If your computer is very locked down, these methods may not work at all.

```
CONTINUE AT YOUR OWN RISK! I AM NOT RESPONSIBLE IF YOU GET CAUGHT FOR USING IT!
```
* [.NET Framework](http://www.dropwizard.io/1.0.2/docs/) - Used for computers with more freedom
Using this version takes no effort. Just open it, and it does all the magic in the background.
 
* [Powershell](https://maven.apache.org/) - Used for more locked down environments
For this one, it installs to "C:\NoSchool" after clicking the Install NoSchool shortcut.
You'll need to extract the ZIP file before you do this or it will not work!

## License (GNU Public License)

This project is licensed under the GNU License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* If you get caught, I AM NOT RESPONSIBLE. You wanted to do this, it's your fault!
* This was a project originally created back in 2019 as a challenge to myself. Now it's 2023, and I have 10 days suspension and 15 days in PASS. (basically detention but more depressing)
