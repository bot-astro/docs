---
label: Settings
icon: gear
order: 100
---
Astro has very few server settings, all available under `/settings`.  
You can get a list of those commands with `/commands category:Server settings`.

### Viewing your settings
You can view all your server settings at any time with `/settings info`.

### Get notified about issues and errors
You can set an error-logs channel with `/settins error-logs`.  
Astro will report all the issues and errors that it encounters in that channel.
!!!warning
It is recommended to set an error-logs channel!
!!!

### Ban specific commands
Astro commands can be managed directly via *Server settings :icon-arrow-right: Integrations :icon-arrow-right: Astro*.  
If you wanna ban specific `/vc` commands and not the whole group, you can use `/settings banned-commands`.  
[!ref Manage commands](temporary-voice-channels/user-commands.md)

### Fixing wrong settings
Astro can fix any wrong setting automatically with `/settings fix`.
