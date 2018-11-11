# lungo-off ☕

I use [Lungo](https://sindresorhus.com/lungo) to keep my mac awake, it is very useful whenever I'm presenting something or when I need to leave my desk for a short period of time, watching YouTube videos in non-full screen mode and all those kinds of stuff.

## The problem

Since I use the Lungo's default duration to be indefinitely, sometimes I forget to turn it off and well, sometimes I just fall asleep 😴

So I leave my Macbook turned on all night! 😱

And I don't want my precious machine's battery health to diminish 🔋🔌

## The solution

This script solves just that, since it's most likely for me to fall asleep at midnight or so, I wrote a cron script that turns off Lungo automatically every day at 12:00 😄

Some days ago [Sindre Sorhus](https://twitter.com/sindresorhus) (the creator of Lungo) made a `cli` tool to control Lungo 🎉

And it was a perfect fit in my case to build this cron task.

To get started just install the `lungo-cli`.

`yarn add global lungo-cli`

Then, add the cronfile to crontab 👉 `crontab path/to/cronfile` ⏳

And you're all set! ✨

Now you can sleep without worries 💤
