+++
title = "How I Built My First Bot"
tags = [
    "Bot",
    "Telegram Bot",
    "Creation Story",
    "Project",
]
date = "2020-06-15"
categories = [
    "Projects",
]
[ author ]
  name = "Ananta Srikar"
+++

<style>
.image-center{
	display: block;
	margin-left: auto;
	margin-right: auto;
}
</style>

Bots. Who knows what they are? At least I didn’t until sometime ago. All that came to my mind when I heard the word robot was a mechanical machine that kind of resembles humans, might work on AI, blah blah blah. Let’s leave all that science fiction influenced thoughts behind to find out how I built my first bot.

Before I begin, you should probably know that I am a very big fan of custom ROMs. A detailed explanation about what a ROM is can be found [here](https://www.xda-developers.com/what-is-custom-rom-android/ "XDA Developers"). ROM development requires the developers to communicate with the users using the ROM for hunting bugs, taking feedback and much more. All this is done via the use of Telegram since it allows a lot of members and supports the use of bots. Back then these bots never really caught my attention until I joined a group which made the Open Source version of the default Xiaomi cameras, [ANXCamera](https://camera.aeonax.com/). I needed this because it was the only software developed that ensured the almost perfect functioning of my phone’s 48 MP camera (RN7P). I joined the group to raise a query about video recording as it wasn’t working on my phone. To do that, I was asked to invoke a command which would log my query after which an admin would then help me solve the issue. By then, I had seen a lot of bots like this and thought to myself, "Why don't I make one?" After submitting my query, I turned to google to know more about bots.

To my surprise, it wasn’t that hard. All I had to do was know a little bit of Python, import a library called `python-telegram-bot` and go through [the documentation](https://python-telegram-bot.readthedocs.io/en/stable/index.html). I made a simple bot which could say `Hello world!`, the standard way for any programmer to test their skills when starting something new. I christened it as TheNoobBot. But I wasn’t sure what I wanted my bot to do. Some things that came to my mind were weather updates, news reports and group moderation. After a few more days of work and learning how to use APIs, I was finally able to integrate the weather and news API. The news API was troublesome to deal with as there was no proper documentation and definitely wasn’t noob friendly. I was able to get international news. However, I specifically wanted Indian news because it’s home. Obviously. A few more days of searching and I was finally able to figure out the right way to get Indian data. The result was this: [telegramBot](https://github.com/AnantaSrikar/telegramBot). It still can’t do much. But yeah! I finally made my first bot!

The next challenge was something because of which I was able to learn a lot of new things (I can’t emphasize 'a lot' enough). I was supposed to make the bot run continuously (by running `python3 StartMyTelegramBot.py` on my laptop) so that it could listen for commands or messages and do what it was made to do. However, I couldn't keep my laptop switched on forever. That's practically impossible. I approached my senior, [Raghav](https://icecereal.github.io), who properly guided me on hosting the bot. It ran on my trusty Raspberry Pi 4 (4 GB RAM) for a while and it's now currently hosted on Heroku. You can head over to [TheNoob2001_bot](https://web.telegram.org/#/im?p=@TheNoob2001_bot) to chat with the bot.

<img src="/img/blog-images/how_I_built_my_first_bot/TelegramBot_Final.png" width="300vw;" style="max-width: 400px;" class="image-center">
<p style="text-align: center">The Bot in Action</p> <br>

The funny thing about this was that I made it during my End Semester Exams. Like always, the most interesting and attractive ideas/projects show up only when one has exams.
This whole learning made me realize that there’s *so much more* in Computer Science and not just Machine Learning or Computer Vision or just raw programming. There’s a whole big never ending ocean out there to sail and explore.

[Ananta Srikar](http://anantasrikar.github.io/)

