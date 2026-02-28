This script lets you run a Terraria server on termux. It has been updated to allow you to choose the server version you would like to run. To change the server version download the tserver file, or fork this github, and edit the "Version Config" section of the tserver script. 

Once you have chosen the server version for the first time use enter the following command:

``` cd && git clone https://github.com/kane9287/terraria-server-script-termux.git && chmod +x terraria-server-script-termux/tserver && ./terraria-server-script-termux/tserver  ```

Follow the prompts and after the server has installed type the following to start the server: 
``` tserver  ```

To stop the server type ``` exit ``` in the Termux terminal.

If you are updating the server to a new version you will need to delete the git clone folder. Use this command to delete and reclone 

``` cd && rm -rf terraria-server-script-termux && git clone https://github.com/kane9287/terraria-server-script-termux.git && chmod +x terraria-server-script-termux/tserver && ./terraria-server-script-termux/tserver ```
