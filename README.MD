<h1 align="center">⭐ Gute Nacht's RAT Builder Bot ⭐</h1>

<h1 align="center">Setting up your bot</h1>

1.) Visit [Discord's Developer Portal](https://discord.com/developers/applications) If it takes you to a login screen, log into your Discord and revisit the page

2.) Click the **"New Application"** button on the top right of your screen, choose the name of the application, agree to the terms and click "Create".

3.) Click **"Bot"** on the left settings sidebar and click **"Add bot"** (you may rename it and set a profile picture for it if you'd like)

4.) Press **"Reset Token"** and **"Yes, do it!"**, then copy the token by copying it manually or pressing the **"Copy"** button.

5.) Open the **"config.json"** file and add your bot's token to the **"token"** field

<h1 align="center">Setting up your mod</h1>
If you already have one, that's good! If you don't, I don't know what to tell you. Make one I guess?

1.) Open your rat's mdk and nagivate to **src/main/java** and then find your main class path. For me its' org/json/jsonLoader.java (the .java is necessary)

2.) go back to your mdk and find your build.gradle, then find **"archivesBaseName"** and write the name in the **"exportname"** field
  
3.) You need to open the code for your rat, and find which line the webhook is meant to be placed. After that put the line number into config.json in the **"line"**

4.) Go into your main class and find the name of the string where the webhook is expected (string name will be bold) like: String **pb** = "https://discord.com/api/..." **IT MUST BE JUST THE NAME, NOTHING ELSE.**

That's all, enjoy creating your server. 

<h1 align="center">Hosting</h1>

I personally recommend [Contabo](https://contabo.com/), you can also host it on your PC if you'd like.

<h1 align="center">Disclaimer</h1>
I am not liable for any malicious use of my builder, nor am I liable for any malicious use of the files created by my builder. This is made for educational purposes

You may edit this code all you want. If you want to post it somewhere, please give me credit. :)

**DO NOT DM ME FOR HELP, I'M NOT GOING TO HELP YOU. EVERYTHING YOU NEED TO SET IT UP IS HERE. CAN'T FIGURE IT OUT? DON'T DO IT.**

also I'm aware it sucks it was made in like 2 days

<h1>Enjoyed my bot? Please leave a ⭐!</h1>
