---
description: Link a new group to Bloxlink.
---

# Group Bind ⚖️

## What's a Group Bind?

A Group Bind is when you link a Roblox group to your Discord server. Different than the Group **Rank** Bind, the Group Bind makes Bloxlink add your Roblox group ranks to your users on Discord! This means, if a user has a group rank called "Customer", they will receive a role called "Customer" on Discord.

## Normal Usage

If you haven't ran the `!setup` command yet, you should configure your server first. You will be able to link a group trough the setup command.  
If you're looking to add a new group, keep reading!

{% page-ref page="../others/setup.md" %}

Firstly, let's start the bind process! Say `!bind` in your server. Make sure Bloxlink has permissions to view and talk in the channel.

Bloxlink offers different binds types, but we will use the `group` bind type to link our new group. Use the dropdown and select `group`, or simply type it.

![](https://dark.hates-this.place/f/rfjLnd.png)

You can provide a nickname template, so users that are in your Roblox group can get a different nickname if you wish. If you don't want one, you can say `skip`. You can find the nickname templates in the codeblock.

![](https://dark.hates-this.place/f/nb7Oe5.png)

{% hint style="warning" %}
🧠 **Note:** Templates must be spelled like Bloxlink shows you! You must include the curly brackets and dash. For example: `{smart-name}`
{% endhint %}

The next prompt is an **advanced option**! If you want Bloxlink to remove any additional role\(s\) the user has, if they meet the bind requirements, you can provide those roles. Old group roles will be already removed from the user! Don't worry about that. This option is commonly used to remove roles another bot can give.

![](https://dark.hates-this.place/f/oX2rM0.png)

{% hint style="warning" %}
🧠 **Note:** 95% of the time, you should `skip` this option.
{% endhint %}

Now provide your Roblox group ID. This one can be found on your group URL. They're between `/groups/` and `/YourGroupName/`. \(See second image\)

![](https://dark.hates-this.place/f/tVP9e5.png)

![Group ID example. Yours is different!](https://dark.hates-this.place/f/sLDdMG.png)

As we are linking a new Roblox group, we will select the `entire group` option. Use the dropdown, or simply type it.

![](https://dark.hates-this.place/f/jZenpF.png)

{% hint style="warning" %}
🧠 **Note:** Your Discord roles **must always match** with your group ranks names. Otherwise, Bloxlink will create the missing roles.
{% endhint %}

That's all! You have successfully bound a group to your Discord server! Users will now get their group ranks in your server.

## Advanced Usage

You are actually able to make an entire group bind just in 1 command. The `<>` and keywords are just to demonstrate, so **remove** them and replace with what you'd like.

You shall **not** remove the `""`.

`!bind group "<nicknameTemplate>" "<removeRoles>" <groupID> "entire group"`

That's all! You have bound your group in one command!

Thanks for using Bloxlink. [❤️](https://emojipedia.org/red-heart/)

### Return to Binding Tutorials

{% page-ref page="./" %}

