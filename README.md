# Nodeschool/Bratislava

<img alt="NodeSchool Bratislava Logo" src="https://raw.githubusercontent.com/nodeschool/bratislava/master/assets/logo/nodeschool_ba.png" width="400">

Feel free lurk public chatroom @
[![Join the chat at https://gitter.im/nodeschool/bratislava](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/nodeschool/bratislava?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Upcoming NodeSchool/Bratislava meetup

planned at **12.12.2015** as *all-day* event in **Progressbar** [(Michalská 3, Bratislava)](https://www.google.com/maps?q=michalska+3,+bratislava).

Please tell us, if you are coming to
**[this thread (issue)](https://github.com/nodeschool/bratislava/issues/2)**

##### Sponsors are welcome!

##### Pull Requests are welcome!

### [Knowledge Library](https://github.com/nodeschool/bratislava/tree/master/library)
*credits for logo goes to [d14](https://twitter.com/d14)*

## Installing NodeJS

For obvious reasons, having NodeJS installed on your work machine is a must. :smile:

##### Windows

Using Windows 10, however, workflow should be similar for most versions.

* download v4.2.2 from https://nodejs.org/en/ (5.1.0 has problems with npm and VS2015)
* install it regularly

Open up terminal (Windows + R -> 'cmd' -> Enter) and type `node -v`. If it works, you are good to go and you can ignore the stuff below. Otherwise, continue.

* open up **This PC**
* in that window, right click the **PC** icon located above all your hard drives and directories
* in the new window, click **Advanced system settings**
* in the newest window, click **Environment Variables...**
* find the **PATH** variable, click **edit**
* add the following: *YOUR_ABSOLUTE_NODEJS_INSTALL_DIRECTORY/;* and *C:\Users\YOUR_USERNAME\AppData\Roaming\npm;*
* please note that all PATH variables must be separated with **;**

##### Ubuntu

* open up terminal
* `sudo apt-get install nvm`
* `nvm install 5.1`
