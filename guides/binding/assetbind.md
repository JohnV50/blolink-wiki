---
description: Link a Roblox asset to a Discord role and know who owns it.
---

# Asset Bind 🧰

## What's an Asset Bind?

An Asset Bind is used to give a Discord role based off a Roblox asset. For example, catalog items or a paid game.

## Normal Usage

Make sure Bloxlink is able to view and type in the channel. Now say `!bind` and let's follow the prompts together.

Bloxlink offers different bind types, but we will use the `Asset` bind type. Use the dropdown or simply type it.

![](https://dark.hates-this.place/f/xOslCn.png)

Now you can provide an optional nickname template to name users who own this asset a special nickname, for example.

![](https://dark.hates-this.place/f/nb7Oe5.png)

This prompt is an **advanced option**. If you wish Bloxlink to remove any other Discord role, name it. This option is commonly used to remove roles given by another bot. These roles can't be a bind!

![](https://dark.hates-this.place/f/oX2rM0.png)

Now you can provide the respective asset ID of the item you want to bind. You can find the ID between `/catalog/` and `/YourItemName/` or between `/games/` and `/YourGameName/`, if it is a paid game. (See second image)

![](https://dark.hates-this.place/f/hiUCX7.png)

![Asset ID example](https://dark.hates-this.place/f/GrboRu.png)

Provide the Discord role name(s) users should get if they meet the bind requirement.

![](https://dark.hates-this.place/f/r13MqC.png)

That's it! You're going to see the asset ID and the bound Discord role on the success message.

![](https://dark.hates-this.place/f/krQptA.png)

## Advanced Usage

You are actually able to make an entire asset bind just in 1 command. The `<>` and keywords are just to demonstrate, so **remove** them and replace with what you'd like.

You shall **not** remove the `""`.

`!bind asset "<nicknameTemplate>" "<removeRoles>" <assetID> "<addRoles>"`

That's all! You have bound a role with an asset in one command!

Thanks for using Bloxlink. [❤️](https://emojipedia.org/red-heart/)

### Return to Binding Tutorials

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}
