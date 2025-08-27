# Apparmor Profiles

Keep in mind that this is my first time ever interacting with Apparmor, so therefore these profiles are not 100% perfect. <br>
They are designed to work better than the alternative (there is none lmao). <br>

## Navidrome
This profile is for the Navidrome Opensubsonic music server. <br>
This setup is relatively custom as I am running 2 instances on the same server (different ports) and all within a single directory (executable, config file, database). <br>
Although for your convenience, the profile has been simplified for 1 instance. <br>
Home location is: ```/etc/apparmor.d/navidrome```.
