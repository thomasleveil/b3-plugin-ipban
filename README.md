b3-plugin-ipban
===============

This plugin checks the  IP addresses of clients with an active ban or tempban. So in addition to the GUID check, it also
checks the IP address belonging to the client with the active (temp)ban and kicks if appropriate.

******
*NOTE: since B3 v1.10.1 beta this plugin has been included in the standard plugins set, thus all patches and updates will be performed in the official B3 repository.*
******

## Installation

1. copy the contents of the extplugins folder into your installations b3/extplugins folder.
2. add the plugin to your b3.xml config file:

        <plugin name="ipban" config="@b3/extplugins/conf/ipban.ini"/>

3. modify the config file to your preference
4. restart the bot
