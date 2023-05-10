This is a modified version of the up-to-date Lunar Client launcher and we are no way affiliated with Moonsworth, LLC and Mojang Studios.

![Screenshot](https://github.com/redefault/LunarReplay/raw/v1_12/images/client.png)

Ever needed to use ReplayMod inside of Lunar Client? No worries, with a custom version of the Lunar Client launcher, you can launch ReplayMod using the version module I have made. However, please note that I am still working on improving it. Currently, the only versions compatible with ReplayMod are 1.8.9 and 1.12.2. Also, it's important to take note that this is an older build of Lunar Client from August.

### Downloading custom asar
To download the `app.asar` file, head over to the releases section. Once downloaded, locate the Lunar Client launcher on your desktop and right-click on it. From there, click on "Properties" and click on "Open File Location". Afterwards go inside the resources folder where you will need to rename the current app.asar file, something like `app.backup.asar` will do. It's important in case you want to switch back to the original launcher. Next, drag in the new app.asar file into the resources folder. Congratulations, you have completed the setup!

![launcher](https://github.com/redefault/LunarReplay/raw/v1_12/images/launcher.png)


### TODO

- [x] Fix issues (Launching default Minecraft then crashing, random crashes in 1.12).
- [x] Make 1.8.9 work.
- [x] Make 1.12.2 work.
- [ ] Fix API so it actually launches lol
