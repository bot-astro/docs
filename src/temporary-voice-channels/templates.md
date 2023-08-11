---
icon: copy
order: 99
---
A templates simply holds a bunch of settings that can get applied to temporary voice channels all together.

### Creating a template
You can create a template with [!badge /template create], it will ask for a `name` which will be the name that users will see when they try to apply a template to their channel.
!!!info
Non-[premium](../premium.md) servers can create up to 3 templates, while [premium](../premium.md) servers have unlimited!
!!!

### Template settings  
A template has a name that can be modified with [!badge /template edit template-name].  
Other than that, a template holds the following settings for a voice channel:
- Name :icon-arrow-right: [!badge /template edit name]
- User limit :icon-arrow-right: [!badge /template edit limit]
- Region :icon-arrow-right: [!badge /template edit region]
- Bitrate :icon-arrow-right: [!badge /template edit bitrate]

!!!info
You can restrict a template to be usable only in temporary voice channels created from specific generators with [!badge /template enabled-generators].
!!!

!!!warning
You can delete a template an any time via [!badge /template delete]
!!!

### Using templates
Users can use templates either via [!badge /vc template] or the related [interface](interfaces.md) button.
