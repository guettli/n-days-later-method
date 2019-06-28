# n-days-later-method

This is a management method which is roughly based on [43Folders](https://en.wikipedia.org/wiki/Tickler_file) and 
[Getting Things Done](https://en.wikipedia.org/wiki/Getting_Things_Done).

You should focus one thing at once.... but not too long.

Goal: (Zero Inbox)[https://youtu.be/z9UjeTMb3Yk]

Up to now I know only one software which supports it ([modwork](https://www.tbz-pariv.de/produkte/modwork)).

GoogleMail has a "snooze" feature, but n-days-later is a bit more.

I use the term "issue". This could be an issue in a digital issue tracking system, an email or a piece of paper if you prefere this.

I use the term "inbox" to refer to all issues which are waiting for you to get read or done.

# Step1: Take the first issue of your inbox

Take the first issue of your inbox. Avoid looking at the list of all issues in your inbox. This issue should be the newest issue (the one that arrived just some minute ago).

# Step2: Act

Case1: If you can handle this issue in less than five minutes, then do it now. Mark the issue as "done". It should be possible to do this without moving the fingers from keyboard to the mouse. The keyboard shortcut should be easy since you will use it often. Goto Step1.

Case2: You need more information to handle this issue? Ask for more info. This reply should be a connected to your issue somehow. Here is an image of an issue thread in the mail user agent thunderbird. Don't forget to alter the subject if the content changes.

![MailThread in Thunderbird Mail User Agent](/thunderbird-mail-thread.png)

You replied and asked for infos. What now? We are all just humans. It is likely that your question will get lost because the other person is very bussy. This means we need a way to resubmit the current issue n days later (in short "+N"). It depends on the context how long. Maybe +3. This means: put this issue to hold and the system should resubmit this issue three days later. If today is monday, then on thursday should be automaticaly back in your inbox. Details for the +N spec are below. Now goto Step1

Case3: This is unimportant information? Delete it. Is there a way to avoid this in the future? (For example: unsubscribe from a useless newsletter). Again: It should be possible to do this without moving the fingers from keyboard to the mouse. Goto Step1.

Case4: A telephone call is needed. Write some notes of this conversation into the issue. Then mark the issue as "done" or +N.

Case5: You are unsure what to do. No problem, let's think about this again next week: +7. If it can't wait that long, then think about this again tomorrow: +1.

Case6: You want to do this today, but not now. Use "+" without a number. This will let the issue sleep one hour.

# Notes

As soon as you mark an issue as done or you use +N the next issue should be opened. Like a flipbook. The list of all issues in your inbox does not help you, that's why you should not see it while doing one issue after the other.

In the past I made a distinction between deleting an issue and marking it as done. Today I just mark everything as done. I try to save energy (if work can be avoided, then I avoid it). Creating two differnt groups ("done" and "deleted") does bring me hardly no value.




Avoid chats, since they create too many new items. A phone call might be better then writing a lot of small messages to the same person about the same topic.

# Compared to tennis or badminton

I compare this to playing tennis or badminton. There is **one** ball flying in to your direction. It is up to you to hint the ball forward. Then comes the next ball. There not several balls at once and there is no ball behind you.

# +N Details

+N with N being a number between 1 and 31. Greater numbers should not get accepted. This avoids typos. Example 311 if you mean "31".

+Nw "w" means "weeks"

+Nm "m" means "months".

# Create your own issues

Most issues in my systems get created by me. A lot of ideas come to my mind if I cycle from work to home. Then I stop at the next possible place and create a new issue for me. I do this by writing a mail to my email account at work. I think this is a good way to keep your head free. This way I know this won't get forgotten. Espescialy at friday evening and want to leave the work at work and be open for my wife and family.

# Low latency

If the system which does provide "n days later method" is slow, it won't be fun. Latency is crucial.

# Keyboard only mode

The basic actions need to be doable with your fingers resting on the keyboards. There should be no need to switch to the mouse.

# Mail-User-Agent?

At work I have ([modwork](https://www.tbz-pariv.de/produkte/modwork)), but at home I don't have it.

Some years ago I tried to implement something like this using IMAP Sub-Folders [ndayslater](https://github.com/guettli/ndayslater) but this needs support from the mail user agent.

I have a wife, a healthy child and a disabled child. A have no more spare time for coding for fun. Sad but true.

Even if I had time, I am unsure where to start. I could provide a plugin for thunderbird (PC) or [k9](https://k9mail.github.io/) (Mail user agent for android).

# Asking and Nagging

In the hope to find a n-days-later system for my personal mails I am asking and nagging from time to time:

https://softwarerecs.stackexchange.com/questions/62192/inbox-zero-for-android



