# better-xkcd-bot

There exists an `@xkcdbot` on Telegram, but it appears to not work. I'm going to build a better one.

## Planned Features

 * **Search**: The whole point of this bot will be to search for XKCD comics. If it can't search, it's worthless.
 * **Display previews**: How are you supposed to know which search result is correct without looking? The bot will inline display image previews, which you can long press on in desktop or mobile, to view, before sending.
 * **Send direct links of the comics**: 'nuff said.

Sounds simple, right?

Yeah. We'll see.

## References and Resources

We'll be using the wildly popular [Python Telegram Bot framework](https://github.com/python-telegram-bot/python-telegram-bot) to power our telegram bot. This is a pretty fully-featured bot framework written in python.

*Why are you using python?* It's an easy language to work with, and I enjoy making lightweight projects in this. Performance isn't really a concern for me.

I've build some [other](https://github.com/bocajnotnef/telegram-sequence-bot) [bots](https://github.com/bocajnotnef/microcontrollers/tree/master/canary) before, so I'll be leaning on those repos as a reference throughout this project.