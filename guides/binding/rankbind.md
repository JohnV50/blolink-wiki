---
description: >-
  Looking to give your users a role related to their rank? This is the correct
  guide!
---

# Rank Bind 📏

## What's a Rank Bind?

A Role Bind is when you bind one or multiple Discord role\(s\) to a specific roleset of ranks from your Roblox group! This means, if you link the role "MR" to the rolesets Manager, Staff Manager, users who are in those ranks will receive the "MR" Discord role.

## Normal Usage

Firstly, let's start the bind process! Say `!bind` in your server. Make sure Bloxlink has permissions to view and talk in the channel.

Bloxlink has different binds types, but we will go with the `group` bind type!

![](https://dark.hates-this.place/f/kfN5cE.png)

Now, let's set a nickname-template for the users who meet this requirement. If you do not want one, say `skip` or say the template you want! Bloxlink provides you all available templates.

![](https://dark.hates-this.place/f/HO50WU.png)

{% hint style="warning" %}
[🧠](https://emojipedia.org/brain/) **Note:** Templates must be spelled like Bloxlink shows you! You must include the curly brackets and dash. For example: `{smart-name}`
{% endhint %}

The next prompt is an **advanced option**! If you want Bloxlink to remove any additional role\(s\) the user has, if they meet the bind requirements, name those roles! If there are multiple roles, separate them with a comma.

![](https://dark.hates-this.place/f/U9a8VZ.png)

{% hint style="warning" %}
[🧠](https://emojipedia.org/brain/) **Note:** 95% of the time, you should `skip` this option.  
Roles that are bound **can not** be removed, they **must** be not bound roles!
{% endhint %}

Now, let's provide the group ID of your Roblox group!

![](https://dark.hates-this.place/f/OqHAJN.png)

Bloxlink has two `group` bind types. In this case, we will say `select ranks`.

![](https://dark.hates-this.place/f/9RKMMx.png)

Now, let's provide the name\(s\) of the role\(s\) users should get if they meet the bind requirements! If there are multiple roles, separate them with a comma.

![](https://dark.hates-this.place/f/BmeIyC.png)

Provide the rolesets, aka the ID\(s\) of the rank\(s\) that should receive the role\(s\)! Bloxlink provides an embed with your respective ranks and their IDs.  
It also provides examples on how to provide them!

* `1, 3`  Means ranks with the ID `1` and `3` will get the role\(s\). Rank with ID `2` won't!
* `1 - 3` Means ranks with the ID `1`, `2` and `3` will get the role\(s\)! This is a range.
* `-1` Means rank with the ID `1` and all ranks above it will get the role\(s\)! 
* `Staff Members` Means rank with the name `Staff Members` will get the role\(s\)!
* `everyone` Means everyone in your group will get the role\(s\).

![](https://dark.hates-this.place/f/vkfI8t.png)

That's all! You have successfully made a role bind! Enjoy.

## Advanced Usage

You are actually able to make an entire rank bind just in 1 command. The `<>` and keywords are just to demonstrate, so **remove** them and replace with what you'd like.

You shall **not** remove the `""`.

`!bind group "<nicknameTemplate>" "<removeRoles>" <groupID> "<select ranks>" "<addRoles>" rankIDs`

That's all! You have made a rank bind in one command.

Thanks for using Bloxlink. [❤️](https://emojipedia.org/red-heart/)

### Return to all Binding Tutorials

{% page-ref page="./" %}

