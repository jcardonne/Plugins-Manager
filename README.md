![Logo - PluginsManager](https://i.imgur.com/sXKv0sZ.png)
# Plugins Manager
Hello and *thank you* for using **Plugins Manager**. In case you have a question or a problem I invite you to contact me via [Discord](https://discord.gg/FT4R2wf)!
If you like my plugin, I'll be very happy if you give it 5 stars on its thread! :)

## Commands & Permissions

**Admin Permissions** - **Gives all permissions** : `pluginsmanager.*`


 - **`/pmenu`** - *Perm*. `pluginsmanager.commands.menu`
 

>  Opens a menu listing the plugins present on your server. Giving you
> the possibility to deactivate, activate, reload and update them.

![Plugins List Menu - PluginsManager](https://i.imgur.com/qVkOJVs.png)
- **`/pluginsmanager reload <plugin>`** - *Perm*. `pluginsmanager.commands.reload`
> Reload the selected plugin.

- **`/pluginsmanager enable <plugin>`** - *Perm*. `pluginsmanager.commands.enable`
> Enable the selected plugin.

- **`/pluginsmanager enableall`** - *Perm*. `pluginsmanager.commands.enableall`
> Enables all plugins on the server.

- **`/pluginsmanager disable <plugin>`** - *Perm*. `pluginsmanager.commands.disable`
> Disable the selected plugin.

- **`/pluginsmanager disableall`** - *Perm*. `pluginsmanager.commands.disableall`
> Disables all plugins on the server.

## Potential issues

Some plugins (such as [ViaBackWard](https://www.spigotmc.org/resources/viabackwards.27448/) for example) cannot be reloaded correctly without a server reboot.

## Configuration file - settings.yml

    #  
    # <-----------------------------------PluginsManager----------------------------------->  
    #             Thank you for using PluginsManager, the Plugins management plugin.  
    #  
    #                        Here you can see the main parameters  
    #  
    #  If you like my plugin, we would be very happy if you write a review on our Spigot thread :)  
    #  
    #           If you have a question/suggestion/problem, please contact us on discord:  
    #                             https://discord.gg/FT4R2wf  
    # <------------------------------------------------------------------------------------>  
    #  
      
    Prefix: "&7[&bPlugins&3Manager&7] "  
    Command_Aliases: [pluginmanager, pr, pger]  

    #Not to be touched  
    Version: 1

