---
description: >-
  Do you wish your group members get a cool role if they're in your group?
  Follow this guide!
---

# Group Role Bind 🧱

## What's a Group Role Bind?

Different than the Group Bind, a Group Rank Bind is when you bind, or link, one or multiple Discord role\(s\) to everyone in the Roblox group. This means, if you bind the Discord role "Group Member" to your group, everyone, no matter their group rank, will receive the role.

## Normal Usage

Firstly, let's start the bind process! Say `!bind` in your server. Make sure Bloxlink has permissions to view and talk in the channel.

Bloxlink offers different bind types, but we will use the `group` bind type. Use the dropdown, or simply type it.

![](https://dark.hates-this.place/f/rfjLnd.png)

Now, let's set a nickname-template for users who meet this bind requirement. If you do not want one, say `skip` or say the template you want. You can find the templates on the codeblock.

![](https://dark.hates-this.place/f/nb7Oe5.png)

{% hint style="warning" %}
🧠 **Note:** Templates must be spelled like Bloxlink shows you! You must include the curly brackets and dash. For example: `{smart-name}`
{% endhint %}

The next prompt is an **advanced option**! If you want Bloxlink to remove any additional role\(s\) the user has, if they meet the bind requirements, name those roles. If they are multiple roles, separate them with a comma. This option is commonly used to remove roles that are given by another bot.

![](https://dark.hates-this.place/f/oX2rM0.png)

{% hint style="warning" %}
🧠 **Note:** 95% of the time, you should `skip` this option.  
Roles that are bound **can not** be removed, they **must** be not bound roles!
{% endhint %}

Now provide your Roblox group ID. This one can be found on your group URL. They're between `/groups/` and `/YourGroupName/`. \(See second image\)

![](https://dark.hates-this.place/f/tVP9e5.png)

![Group ID example. Yours is different.](https://dark.hates-this.place/f/sLDdMG.png)

As we want to give one role to all our group members and not trying to link a group. We will select `Select specific rolesets`, use the dropdown or simply type it. 

![](https://dark.hates-this.place/f/jZenpF.png)

Now, let's provide the name\(s\) of the role\(s\) users should get if they meet the bind requirements. If there are multiple roles, separate them with a comma. For example: `Group Member, Real Member!`

![](https://dark.hates-this.place/f/ofMvXk.png)

We want to give this Discord role to every group member, no matter their rank. So, we won't provide a rank ID, instead we will provide `everyone` as response.

![](../../.gitbook/assets/image%20%282%29.png)

That's it. You have bound a Discord role to all your group members.

## Advanced Usage

You are actually able to make an entire group-role-bind just in 1 command. The `<>` and keywords are just to demonstrate, so **remove** them and replace with what you'd like.

You shall **not** remove the `""`.

`!bind group "<nicknameTemplate>" "<removeRoles>" <groupID> "select specific rolesets" "<addRoles>" everyone`

That's all! You have bound a role to all your group members in one command!

Thanks for using Bloxlink. [❤️](https://emojipedia.org/red-heart/)

### Return to Binding Tutorials

{% page-ref page="./" %}

