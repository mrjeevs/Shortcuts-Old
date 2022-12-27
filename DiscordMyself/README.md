[![Discord Myself Banner](https://i.imgur.com/6ApuYn3.png)](https://www.icloud.com/shortcuts/62ac3cf7f22e472d96e805a1547f82aa)


## Table of Contents

- [Motivation](#motivation)
- [How It Works](#how-it-works)
- [Benefits](#benefits)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Settings](#settings)
- [Conclusion](#conclusion)
- [Auto-Updater](#auto-updater)
- [Privacy](#privacy)
- [Disclaimer](#disclaimer)
- [Credits](#credits)


## Motivation
Let me ask you two questions:

1. When did it hit you that there was no good way to transfer files, images, and/or text from your phone to your PC (*or vice versa*)?
	- *Especially if you don't have the luxury of owning a MacBook where you can seamlessly use Airdrop to do so*.
2. Or the fact you want to save something to look back on later, but you have no convenient place to do so?

Most people simply resort to emailing themselves, since email supports majority of attachment types. There is even a shortcut called [Email Myself](https://www.icloud.com/shortcuts/dd6a0881316f478b951b2ef72c8a0d58) to do that! However, this ends up cluttering your inbox and leaving you to manually delete your *self-emails* every time.

Well, look no further because Discord is here to save the day! [Discord](https://discord.com/) is a instant messenger and social platform that offers channels to text, voice, video call with others, and much more! With a little bit of work, you can have your own *private* server with a channel dedicated to sending content from your phone to Discord, which you can access Discord from virtually any device!


## How It Works
Just like *Email Myself*, this shortcut lets you send anything to yourself, *through Discord*, from Share Sheet or from the clipboard, just with one tap! You can even select multiple items to be sent at a time (*each item will be sent as an individual message on Discord*)!

**Using with Share Sheet (<img src="https://i.imgur.com/KDyO3ny.png" alt="share-sheet-icon" width="2.5%"/>)**:
- Whether you are scrolling on the web, going through your photos, looking at PDF files, want to save a map location, if you see the Share Sheet icon, then you can send it to Discord in one tap!
	- *Just click on the icon, scroll to the bottom of the menu, and click on **Discord Myself***.

**Using with Clipboard**:
- If you want to send your clipboard to Discord, just run the shortcut.

This shortcut is essentially a streamlined process to sending content to a specific channel of your choice, from a server that you own. As opposed to either manually opening the app and sending content to the server/channel you want to, or using Share Sheet to manually do the same.

**NOTES**: 
- *Discord has a 2000-character limit and an 8 MB file size upload limit per message sent, without [Discord Nitro](https://discord.com/nitro). To learn more how this affects the shortcut, check out the [Settings](#settings) section*.
- *If you want to send more than 3 items at a time through the shortcut, be sure to enable **Allow Sharing Large Amounts of Data** in your phone's settings (Settings > Shortcuts > Advanced).*


## Benefits
- ⭐ Easy way to transfer content from your phone to PC (*for my non-MacBook users*). 
- ⭐ Convenient method to store files, media, and/or text somewhere to refer back to later.
- ⭐ Bypass the auto-conversion/compression Discord performs on any image/video uploaded.
- Send code blocks with syntax highlighting of your choice.
- See a full history of everything you've sent, all in a single place and decluttered!
- Send content to a computer you don't own, without going through the hassle of logging into your email.
	- *Discord's mobile app offers a QR code authenticator, which allows you to log in without having to enter your login or 2FA details*.


## Prerequisites
- [Discord](https://discord.com/) (*installed at least on your PC, but recommended to install on phone and PC*)
	- You are also more than welcome to use the web version of Discord instead, if you do not want to download it onto your PC.


## Setup
### Step 1: On Your PC (*Time: 2-3 min*)

**If you already have a dedicated private Discord server, feel free to skip steps 1-3.**

1. Create an account (*if you don't have one already*) and log into Discord.
2. Create your own private server (*if you already have your own private server, you can skip this step*).
	- Click on the green **+** icon on the left side of the screen. 
	- Click on **Create My Own**.
	- Click on **For me and my friends**.
	- Here, you can name your private server whatever you want and upload a server icon, if you wish to.
	- After you done, click **Create**.
3. Create a channel dedicated to transferring files and text between your phone and PC.
	- Click on the **+** button right next to the category *Text Channels*.
	- Make sure the channel type is *Text*.
	- Name the channel whatever you want it to be.
	- Click on **Create Channel**.
4. Create a webhook for the channel you just created and copy its URL.
	- Click on the dropdown arrow **V** right next to the name of your server on the top left.
	- Click on **Server Settings**.
	- Under the *Apps* category on the left side, click on **Integrations**.
	- Click on **Webhooks**.
	- Click on **New Webhook**.
	- On the newly created webhook that just popped up, click on *Channel* dropdown, and select the name of the channel you just created.
		- Feel free to change the name of the webhook and/or give it a profile image.
	- Click on **Save Changes** (*if it pops up*).
	- Click on **Copy Webhook URL** of the webhook you just created.
5. Send the webhook URL to your phone (*you might have to email yourself on this one...* 😅).

### Step 2: On Your Phone (*Time: <1 min*)
1. Download this shortcut onto your phone.
2. Follow the instructions on the setup page (*you can find what each setting does in the [Settings](#settings) section*).
3. Click **Done**.


## Settings
Here are the customizable settings you can tailor for your use case(s) of this shortcut.

1. **Webhook URL**
	- This is the URL that you created for your specific channel in your server's webhook settings page (*Server Settings > Integrations > Webhooks*). The Webhook URL is a direct link to post messages into a specific channel of your choice on that server. 
	- For the purpose of this shortcut, a Webhook URL is needed to know where to send content that you choose to upload.
2. **Character Limit**
	- This is the maximum number of characters Discord allows in a single message. By default, it’s **2000** characters per message for any Discord account. 
	- If a given text message exceeds the character limit, it will be uploaded as a **TXT** file, instead. 
	- Unless you are subscribed to Discord Nitro (*which elevates the limit to **4000** characters per message*), you can leave this setting on its default.
3. **Max File Size**
	- This is the maximum file size Discord allows to be uploaded in a single message. 
	- By default, it’s **8** MB per message for any Discord account. 
	- Unless you are subscribed to Discord Nitro (*which elevates the limit to **50** MB or **500** MB per message*), you can leave this setting on its default.
4. **Preserve Images**
	- This setting allows you choose whether to preserve an image or not. Here, preserving an image means your image ***will neither be converted nor compressed*** to image formats that Discord supports (*i.e. JPG, PNG, GIF*) and *metadata* is unchanged, as well. 
	- By default, images uploaded are **not preserved** and will be *slightly* converted/compressed from unsupported image types (*ex: HEIC*) to JPEG. Metadata will be removed, as well. 
	- **NOTE**: Any convertible image to JPEG becomes "**preview-able**" on the Discord app. If you want to be able to preview the uploaded image on the app itself, I suggest leaving this setting on its default.
5. **Preserve Videos**
	- This setting allows you choose whether to preserve a video or not. Here, preserving a video means your video ***will not be re-encoded*** to codec(s) that Discord supports (*ex: H.264*) and *metadata* is unchanged, as well. 
	- By default, videos uploaded are **not preserved** and will be re-encoded to H.264. Metadata will be removed, as well.
	- **NOTES**:
		- Videos smaller than 4K will not be downscaled.
		- Videos using the H.264 codec are "**preview-able**" on the Discord app (*[although not all video extensions are](https://www.reddit.com/r/discordapp/comments/f2kt5r/guide_file_formats_discord_can_embed/)*). If you want to be able to preview the uploaded video on the app itself, I suggest leaving this setting on its default.
6. **Send Text As Code**
	- This setting allows you to send text as a code block, with syntax highlighting of a language of your choice. 
	- By default, it's **disabled**.


## Conclusion
And, that's it! You have successfully setup the **Discord Myself** shortcut on your phone. Now, you will be able to send anything you want from your phone to Discord, either through the Share Sheet or with your clipboard.

If you happen to exceed the max file upload size while using the shortcut, I'd suggest trying to find ways to compress your file(s). If that's not feasible, then getting a hyperlink to your file(s) is another option. Or you can manually upload it to the Discord app, and see if it will get auto-compressed for you.

Feel free to leave any comments if you happen to run into unexpected errors, looking for improvements, or even let me know how it's working for you! More than happy to hear any type of feedback!


## Auto-Updater
This shortcut is powered by [UpdateKit API](https://www.mikebeas.com/updatekit-api/v1). UpdateKit API is not another standalone shortcut updater, rather one that is integrated in the shortcut itself. This means there is no need to install another shortcut to check for updates! The updates come to you!

Whenever a new update is released, the next time you run the shortcut, it will prompt you to either **Install** or **Skip** the update. If you choose to **Skip** the update, the shortcut will still run as intended.


## Privacy
- *This shortcut does not scrape for any sensitive or identifying information or install any sort of malware on your phone* ✅. *As always, I recommend my users to double check every action this shortcut performs, as it is your responsibility to be 100% sure of what you are using*.
- *If the shortcut asks you permission before sending, just click **Always Allow**. It will ask this from **every source** you use the shortcut from. You can remove sources from the privacy settings of the shortcut later, should you choose to change your mind.*
- *The UpdateKit API uses your device's model and iOS version to ensure new updates are compatible with your device. If your device and/or iOS is not compatible with the shortcut, future updates won't be presented to you.*


## Disclaimer
***As a general warning, Discord is not a safe place to store sensitive or identifying information. Please do not send passwords, addresses, or any other sensitive information in your private Discord server. But it is totally safe to use this shortcut if you want to transfer content that is not sensitive or identifying to you.***


## Credits
-  Graphics made with  [MediaKit](https://routinehub.co/shortcut/1911).
- Inspired by Apple's *[Email Myself](https://www.icloud.com/shortcuts/dd6a0881316f478b951b2ef72c8a0d58)* shortcut.
