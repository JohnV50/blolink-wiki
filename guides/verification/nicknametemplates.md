---
description: Know about Bloxlink's nickname templates.
---

# Nicknames Templates 🔬

## Changing your nickname template

To change your nickname template, simply use `!settings change nicknameTemplate <template>`

For example: 

```text
!settings change nicknameTemplate {roblox-name}
!settings change nicknameTemplate {smart-name}
!settings change nicknameTemplate {roblox-name} | {group-rank}
```

{% hint style="info" %}
[🧙](https://emojipedia.org/mage/) **Tips:** Did you know you can combine more than one nickname template? `{group-rank} | {roblox-name}`, for example!
{% endhint %}

## Nickname Templates

### Roblox Related Templates

```text
{roblox-name} -> changes to their Roblox username (unique)
{display-name} -> changes to their Roblox display name (not unique)
{smart-name} -> changes to their Roblox display name (roblox username) if the user has a display name; otherwise, changes to their Roblox username
{roblox-id} -> changes to their Roblox ID
{roblox-age} -> changes to their Roblox user age in days
{roblox-join-date} -> changes to their Roblox join date
```

### Group Related Templates

```text
{group-rank} -> changes to their current rank in the linked group
{group-rank-id} -> changes to their rank in THAT group specified by group ID <id>, example: {group-rank-1337}
```

### Discord Related Templates

```text
{discord-name} -> changes to their Discord display name; works on unverified users
{discord-nick} -> changes to their Discord nickname; works on unverified users
```

### Templates Commonly used on the WelcomeMessage

```text
{server-name} -> replaces with the server name (Typically used for the !welcomemessage command)
{prefix} -> changes to the server prefix; works on unverified users
```

### Others Templates

```text
{disable-nicknaming} -> overrides all other options and returns a blank nickname. Note that this ONLY APPLIES TO NICKNAMES.
{clan-tag} -> replaces with the user's custom clantag, set with !clantag
```

{% hint style="warning" %}
[🧠](https://emojipedia.org/brain/) **Note:** Templates must be spelled like Bloxlink shows you! You must include the curly brackets and dash. For example: `{smart-name}`
{% endhint %}

{% hint style="info" %}
[🧙](https://emojipedia.org/mage/) **Tips:** **Bind Nickname** → when you link groups, you're given the option to change nicknames of group members. Bloxlink will choose the person's **highest role** which has an available Bind Nickname. Bind Nicknames can be applied from `!bind`. If no bind nicknames apply to the user, then the **Global Nickname** is used instead.

**Global Nickname** → the default nickname used if someone has **NO** available Bind Nicknames. This can be applied from this command and `!settings change` \(look for "NicknameTemplate"\).
{% endhint %}

That's all! You have changed/edited your nickname template.

Thanks for using Bloxlink. [❤️](https://emojipedia.org/red-heart/)

### Return to Verification Tutorials

{% page-ref page="./" %}

