# Once you Delete your Discord Account what happens to it?
- Well, Your account becomes unaccessable as you would expect, your friends get removed, servers are left, and your account gets renamed with deleted_user_ joined with random strings of characters and your profile picture gets changed to the default discord profile picture. That's pretty much it.

- Now you're probably wondering what about my messages? does discord actually delete anything? **No, They Dont.** all of your messages are still stored in Discord's servers. 

### This tool is designed solely for the purpose of removing those messages for you.

<br>

## ❗LIMITATIONS ❗:
- ⚠️ **DISCLAIMER: If you already deleted your account, you cannot remove messages.**

- Discord **doesnt allow the deletion of messages from channels you are no longer apart of**. this includes servers or groupchats you've left or deleted.

- System Messages such as Call Notifications, Pinned Message Notifications, etc. Cannot Be Removed either.

<br>
<br>

# ℹ️ How to Use 

## There are 2 methods of deleting your messages
### 1. Deleting The Data from your current Servers & Direct Messages
- First, you will need to find your Discord Token by [following these steps](#finding-your-discord-token)
- Then Open the **config.json** file and Paste your Token in the **"discord_token"** Value.
- Then Run **main.py** and select the 1st option, then it will go through all of your current servers and Direct Messages and help you delete all the content.
- this option is kind of just a fall back for circumstances where you no longer have access to your account email, or something else.

<br>

### 2. Downloading A Copy of your data from Discord.
- Once you Open Discord, open settings. Then head over to the **Data & Privacy** Tab
- Press **"Request Data"** In the "Request My Data" Field.
- Then **Select Account** and **Messages**, then press Request My Data.
- You may then have to wait up to 30 Days to recieve your data
- in the meantime [follow these steps to get your discord token](#finding-your-discord-token)
- Once you have recieved your data, you can run the **main.py** and select the 2nd option which will help you remove all of the messages you are able to delete.

<br>
<br>

## Finding your Discord Token
- Using a PC/Laptop, Log into your discord if you havent already, (app or browser) doesnt matter

- once youre logged in Press **CTRL + SHIFT + I** which will then open the Network window, wait for one of the requests named **science**, click on that request and make sure the request method is **POST**
- Scroll Down Until you Reach the **Request Headers** Field, then find **Authorization**, copy the value of that and there you go, you have your discord token.
- then open **config.json** and change the **"discord_token"** value to your token.

<br>

- if you need to find/create a discord bot token,  follow these steps:
- head over to https://discord.com/developers/home, make sure you are logged in.
- click on the applications tab, and press **"New Application"** and give it a name, doesnt really matter what it is
- head over to the **bot tab** and press **"Reset Token"** under the token field
- after entering your password or doing another verification method, you can then copy the bot token.
- then open **config.json** and change the **"discord_bot_token"** value to your token.

<br>

- **⚠️ WARNING: DO NOT SHARE THESE TOKENS WITH ANYONE AS IT WILL GIVE THEM ACCESS TO YOUR ACCOUNT/BOT.**