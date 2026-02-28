# Terraria On Android
This repo contains a script to deploy a Terraria server on Android using the Termux app.

## Installation
The script in this repo lets you run a Terraria server on Termux. It has been updated from the original script _(linked below)_ to enable choosing which version you would like to run. To change the server version download the tserver file, or fork this repo, and edit the "Version Config" section of the tserver script. 

Once you have chosen the server version for the first time use enter the following command:

``` cd && git clone https://github.com/kane9287/terraria-server-script-termux.git && chmod +x terraria-server-script-termux/tserver && ./terraria-server-script-termux/tserver  ```

Follow the prompts and after the server has installed type the following to start the server: 

``` tserver  ```

To stop the server type ``` exit ``` in the Termux terminal.

If you are updating the server to a new version you will need to delete the git clone folder. Use this command to delete and reclone 

``` cd && rm -rf terraria-server-script-termux && git clone https://github.com/kane9287/terraria-server-script-termux.git && chmod +x terraria-server-script-termux/tserver && ./terraria-server-script-termux/tserver ```

### Credits
The OG tserver script author: https://github.com/gediminas748/terraria-server-script-for-termux  
Author of an MC server script for Termux. This script was instrumental in putting server files in an editable folder on Android sans root: https://github.com/ramide1/mc-server-termux  

#### AI Disclaimer
Claude.ai - Helped mash the files together with a prompt and some cleanup.
