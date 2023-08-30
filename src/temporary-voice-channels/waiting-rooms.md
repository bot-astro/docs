---
icon: clock
order: 97
---
Waiting rooms are voice channels attached to temporary ones, that allow users to queue for a voice channel.  
The owner of the temporary voice channel can drag people inside its channel from the waiting room.  

==- 🦀 Waiting room
![Example default interface](../static/waiting-vc.png)
===

==- 🦀 Waiting room with user waiting
![Example gaming interface](../static/waiting-user.png)
===

!!!info
This is a [premium](../premium.md) feature as it requires many more requests to Discord to work.  
!!!  
### Configuration  
Here are the commands available to configure waiting rooms:  
- Category :icon-arrow-right: [!badge /generator-waiting category]
- Position :icon-arrow-right: [!badge /generator-waiting position]
- Name :icon-arrow-right: [!badge /generator-waiting name] (see [variables](variables.md)) (accepts [variables](./variables.md))
- User limit :icon-arrow-right: [!badge /generator-waiting limit]
- Bitrate :icon-arrow-right: [!badge /generator-waiting bitrate]
- Permission inheriting :icon-arrow-right: [!badge /generator-waiting permissions]

You can enable the creation of waiting rooms by default for all temporary voice channels with [!badge /generator-waiting creation].  

### User usage
Users can create a waiting room for their temporary vc with [!badge /vc waiting] or with the corresponding [interface](./interfaces.md) button.  
If a waiting room already exists for their channel, they will be prompted to delete it instead.  

### Name changes
Waiting room names will be re-computed **only** when the **owner** of the temporary voice channel changes.  
You can still use [variables](./variables.md) in the waiting room channel name.