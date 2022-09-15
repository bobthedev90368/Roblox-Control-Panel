# Roblox-Control-Panel
## Requirments
[Node.js](https://nodejs.org/en/)<br>
Computer with an open port or something like [repl.it](https://repl.it)<br>
Your favorite code editor like [Visual Studio Code](https://code.visualstudio.com/)

## Quickstart
### Step 1; Install dependancies.
Currently Dependancies must be manually installed dependancies are as follows:
noblox.js
```shell
npm install noblox.js
```
For the future:
Run the following command your project folder:
```shell
npm install
```

### Step 2; Configure your project files.
1. Go into your config folder.
2. Open the logincontrolls.json<br>
Default should look like this:
```
{
"usernames":["Admin", "Default", "Locked Account", "ReadONLY"],
"rightslevel":[6, 3, 0, 1],
"passwords":["password", "password", "password", "password"]
}
```
Usernames can be added or changed in the username section. Simply edit the list by adding or changing values to change the username. The rights level is the amount of rights a certain account has. The rights are in order of usernames, if a username has the index of 0 the rights for that username will be under the index of 0, passwords apply the same way.<br>
#### Rights level are as follows:
``` Level 0: Account disabled
Level 1: Can only read game stats
Level 2: Can only read game stats and settings
Level 3: Moderator privalleges; mute, kick, etc based on configuration
Level 4: 2nd level of moderation privalages (Must be enabled and configured using the rightslevelconfig.json file)
Level 5: Read and write game settings
Level 6: Complete control over all settings for game as well as for roblox manager ui (DANGEROUS)
```
# CHANGE ALL DEFAULT PASSWORDS BEFORE RUNNING CODE

