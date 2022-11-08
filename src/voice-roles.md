---
label: Voice roles
icon: broadcast
order: 98
---
Voice roles (also called *connections*) are a way to assign users temporary roles while they are inside specific voice channels.  

==- 🦀 Example usage
![Assign a temporary role which lets the user see some text channel](https://astro-bot.space/role_link_demo.gif)
===

You can create a connection with [!badge /connection create], it will ask for a role and a channel (either a voice channel, a category or a stage channel)
, and then edit it via [!badge /connection edit].

!!!info
Non-[premium](premium.md) servers can setup one connection, while [premium](premium.md) ones have unlimited.
!!!

!!!warning
Delete a connection at anytime with [!badge /connection delete]
!!!

### Available actions
There are 3 different actions available for voice roles:
=== Assign role
Assigns the role when the user joins the channel and removes it when he leaves.
=== Remove role
Remove the role from the user when he joins the channel and add it back again when he leaves.
=== Toggle role
If the user already has the role when joining the channel Astro will execute the `Assign` action, otherwise the `Remove` one.
===
