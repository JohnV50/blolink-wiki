---
description: Give users a Discord role based off their Roblox group rank.
---

# Rank Bind 📏

## What's a Rank Bind?

A Rank Bind is when you bind one or multiple Discord role\(s\) to a specific roleset of ranks from your Roblox group! This means, if you link the role "MR" to the rolesets Manager, Staff Manager, users who are in those ranks will receive the "MR" Discord role.

## Normal Usage

Firstly, let's start the bind process! Say `!bind` in your server. Make sure Bloxlink has permissions to view and talk in the channel.

Bloxlink offers different binds types, but we will use the `Group` bind type. Use the dropdown and select the `Group` bind type, or you can simply type it!

![](https://dark.hates-this.place/f/rfjLnd.png)

Now you can optionally select a nickname template to make Bloxlink name the users that meet the requirements. You can find the templates in the codeblock. If you do not wish one, say `skip`, Bloxlink will use the nickname template that's in your settings. \(`!settings view`\) 

![](https://dark.hates-this.place/f/nb7Oe5.png)

{% hint style="warning" %}
🧠 **Note:** Templates must be spelled like Bloxlink shows you! You must include the curly brackets and dash. For example: `{smart-name}`
{% endhint %}

This prompt is an **advanced option**. Bloxlink is able to remove roles from the user, if they meet the bind requirement. These roles that will be removed **must not** be a bind. This option is commonly used to remove non-binds, this means roles that are given by other bot in your server.

![](https://dark.hates-this.place/f/oX2rM0.png)

{% hint style="warning" %}
🧠 **Note:** 95% of the time, you should `skip` this option.
{% endhint %}

Now provide your Roblox group ID. This one can be found on your group URL. They're between `/groups/` and `/YourGroupName/`. \(See second image\)

![](https://dark.hates-this.place/f/tVP9e5.png)

![](https://dark.hates-this.place/f/sLDdMG.png)

As we are making a Rank Bind, and not linking a new group. We will select `Select specific rolesets`. You can use the dropdown, or simply type it.

Selecting specific rolesets, you can choose which specific roleset to bind with specific Discord roles. The Discord roles can be renamed and can be different from the roleset names.

![](https://dark.hates-this.place/f/jZenpF.png)

Now, let's provide the name\(s\) of the role\(s\) users should get if they meet the bind requirements. If there are multiple roles, separate them with a comma. These roles can be a secondary role, like divisions that your group has, or simply if you want to have different Discord roles names than your Roblox group ranks names.

![](https://dark.hates-this.place/f/ofMvXk.png)

Provide the rolesets, aka the ID\(s\) of the rank\(s\) that should receive the role\(s\)! Bloxlink provides an embed with your respective ranks and their IDs.  
It also provides examples on how to provide them!

* `1, 3`  Means ranks with the ID `1` and `3` will get the role\(s\). Rank with ID `2` won't!
* `1 - 3` Means ranks with the ID `1`, `2` and `3` will get the role\(s\)! This is a range.
* `-1` Means rank with the ID `1` and all ranks above it will get the role\(s\)! 
* `Staff Members` Means rank with the name `Staff Members` will get the role\(s\)!
* `everyone` Means everyone in your group will get the role\(s\).

![](https://dark.hates-this.place/f/acW2nu.png)

That's it. Now your respective rank ID's you provided will receive the Discord role\(s\) you set. You will see what ID's you bound to the Discord role on the success message.

![](https://dark.hates-this.place/f/kiwPXZ.png)

## Advanced Usage

You are actually able to make an entire rank bind just in 1 command. The `<>` and keywords are just to demonstrate, so **remove** them and replace with what you'd like.

You shall **not** remove the `""`.

`!bind group "<nicknameTemplate>" "<removeRoles>" <groupID> "select specific rolesets" "<addRoles>" <rankIDs>`

That's all! You have made a rank bind in one command.

Thanks for using Bloxlink. [❤️](https://emojipedia.org/red-heart/)

### Return to all Binding Tutorials

{% page-ref page="./" %}

