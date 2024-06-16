---
description: Know about Bloxlink's nickname templates.
---

# Nicknames Templates 🔬

## Changing your nickname template

_**Option one:**_ To setup a nickname for **all users** that verify/join the server, you can run `/setup`. This will then create a prompt that will allow you to setup the nickname template, from the dropdown menu select which nickname template you would like to use. A common one to use is `{smart-name}`, this will name people their Roblox name (and their Display name, if they have any).  After selecting you may click the `skip, leave unchanged button` to skip through the rest of the prompts. Once completed select done, and then your settings will be saved for your nickname template.

_**Option Two:**_ The second way to setup the nickname template for _**all users**_ that verify/join the server. Navigate to the [Dashboard](https://blox.link/dashboard) and ensure you are signed into the correct account, once you ensure you are signed into the correct account click `manage servers` on the left side of your screen from the selection menu. You will then be taken to a list of your servers that you own or can manage, click on your server then select the `verification` tab, you will then be greeted with many options, choose the nickname template that you would like to apply to your server, then select save. Now your template has been saved!

{% hint style="info" %}
[🧙](https://emojipedia.org/mage/) **Tips:** Did you know you can combine more than one nickname template? `{group-rank} | {roblox-name}`, for example!
{% endhint %}

## Nickname Templates

#### Roblox Related Templates

```
{roblox-name} -> changes to their Roblox username (unique)
{display-name} -> changes to their Roblox display name (not unique)
{smart-name} -> changes to their Roblox display name (roblox username) if the user has a display name; otherwise, changes to their Roblox username
{roblox-id} -> changes to their Roblox ID
{roblox-age} -> changes to their Roblox user age in days
{roblox-join-date} -> changes to their Roblox join date
```

#### Group Related Templates

```
{group-rank} -> changes to their current rank in the linked group
{group-rank-id} -> changes to their rank in THAT group specified by group ID <id>, example: {group-rank-1337}
```

#### Discord Related Templates

```
{discord-name} -> changes to their Discord display name; works on unverified users
{discord-nick} -> changes to their Discord nickname; works on unverified users
```

#### Templates Commonly used on the WelcomeMessage

```
{server-name} -> replaces with the server name (Typically used for the !welcomemessage command)
{prefix} -> changes to the server prefix; works on unverified users
```

#### Others Templates

```
{disable-nicknaming} -> overrides all other options and returns a blank nickname. Note that this ONLY APPLIES TO NICKNAMES.
{clan-tag} -> replaces with the user's custom clantag, set with !clantag
```

{% hint style="warning" %}
[🧠](https://emojipedia.org/brain/) **Note:** Templates must be spelled like Bloxlink shows you! You must include the curly brackets and dash. For example: `{smart-name}`
{% endhint %}

{% hint style="info" %}
[🧙](https://emojipedia.org/mage/) **Tips:** **Bind Nickname** → when you link groups, you're given the option to change nicknames of group members. Bloxlink will choose the person's **highest role** which has an available Bind Nickname. Bind Nicknames can be applied from /`bind`. If no bind nicknames apply to the user, then the **Global Nickname** is used instead.

**Global Nickname** → the default nickname used if someone has **NO** available Bind Nicknames. This can be applied from this command and `/settings` (look for "NicknameTemplate").
{% endhint %}

That's all! You have changed/edited your nickname template.

Thanks for using Bloxlink. [❤️](https://emojipedia.org/red-heart/)

### Return to Verification Tutorials

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}
