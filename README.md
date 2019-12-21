# esx_firejob


THIS IS ONLY A REPACKAGING OF THE MODULE CREATED BY kheire007 
which was just a rework of the module created by: ArkSeyonet

I TAKE NO CREDIT FOR THE CREATION OF THIS MODULE... I'VE ONLY MADE IT EASIER TO DEPLOY
AND ADDED LOCALE INFO FOR ENGLISH SQL IMPORTS.  ALL CREDIT GOES TO ArkSeyonet & kheire007 FOR
THE CREATION OF THIS MODULE.  THANK YOU FOR YOUR HARD WORK!!

FIND THE ORIGINAL REPO HERE: https://github.com/kheire007/esx_firejob

CHANGES IN THIS BRANCH:
    - Added english mysql imports
    - Configured for english
    - Repacked for easier deployment


FXServer ESX Fire Job " inspired by esx_policejob"

[REQUIREMENTS]

* Auto mode
  * esx_billing => https://github.com/FXServer-ESX/fxserver-esx_billing

* Player management (boss actions and armory with buyable weapons)
  * esx_society => https://github.com/FXServer-ESX/fxserver-esx_society
  * esx_datastore => https://github.com/FXServer-ESX/fxserver-esx_datastore
  
* ESX Identity Support
  * esx_identity => https://github.com/ArkSeyonet/fxserver-esx_identity

[INSTALLATION]

1) CD in your resources/[esx] folder
2) Clone the repository
```
git clone https://github.com/BeyondEarthRP/esx_firejob [esx]/esx_firejob
```
3) Import esx_firejob.sql in your database

4) Add this in your server.cfg :

```
start esx_firejob
```
5) * If you want player management you have to set Config.EnablePlayerManagement to true in config.lua
   * If you want armory management you have to set Config.EnableArmoryManagement to true in config.lua

