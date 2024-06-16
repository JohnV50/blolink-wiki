---
description: Know about Bloxlink's nickname templates.
---

# Nicknames Templates 🔬

## Changing your nickname template

There are two ways to set up a nickname template. Choose your preferred method below!

{% hint style="warning" %}
To set a nickname template, you need to have the `manage server` permission enabled for the intended server.
{% endhint %}



**Using the Bloxlink Dashboard:** \
The quickest way to set a nickname template for _**all users**_ who verify/join your server is to use the [Dashboard](https://blox.link/dashboard). Once on the dashboard and logged in, select your server under the `Manage Servers` tab. Next, click the `Verification` tab. Under `Default Nickname Template`, choose the nickname template that you would like to apply to your server, then click save.

\
**Using the Bloxlink Bot:**\
To set a nickname template for _**all users**_ that verify/join the server, you can run `/setup`. Under the prompt, select `next`. You should see a list of all available nickname templates for you to choose from. Once you find your preferred template, select the `Type Response` button and type in your template. You also have the option to select `Disable` if you don't want Bloxlink to change a user's nickname. Proceed with the prompt until the end by selecting `skip` to leave all other settings unchanged.

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
