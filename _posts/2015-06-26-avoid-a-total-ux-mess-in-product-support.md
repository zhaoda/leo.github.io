---
layout:         post
title:          "Avoiding a total UX-mess in product support"
date:           2015-06-27 14:22
categories:     usability
---

I'm not a "Well, they might fix it in the future" kind of a person. If my process of interaction with a specific product is being interrupted by some nasty bug or a missing feature, I will make sure to let the creator know about this - no matter if it's made by a single person or a company like Apple (I still believe that the folks over there will take their time to read it and sometimes even write back).

And what I really like is, that many companies and independent creatives actually encourage this behaviour of mine by providing me with easy ways to contact them if I need help or want to provide feedback for a definite part.

However, there are still enough projects out there who's creators don't spend much time thinking about how they can leverage the user's experience and make him believe in the value of his feedback. If you ask me, they're just cutting themselves with this kind of not-giving-a-shit-behaviour. I mean, the could definitely use the user's ideas to save time and therefore also money. They can make the product better without needing to think about how to do so[^1].

## Common mistakes

Firstly, let's start off with the way the user needs to go to contact the makers. Most companies are offering multiple contacting ways like e-mail, social networks or live-chats (and some even a hotline with 30 minutes waiting time). Among those methods, there's also the well-known *contact form*. You're basically forced to provide pre-defined amounts of information which will then mostly just be converted into a freaking email reaching the creator, in turn. *Why? Really - why?*

I know why. You're basically afraid that the user is too dumb to provide the necessary amount of information (or you just like generating extra effort for your fellow developers, which will need to code the "Drop us a message" page), right? Okay, then you're at least caring about this process a bit.

But not enough! Just think about it, there's always some information left. You can't cover all scenarios by simply forcing the user to think about which category is the most fitting one for his problem and then allowing him to choose it from a `select`-element (as an example).

You need to leave him space for creativity. You need to allow him to use his own ways of explaining to show you what he's missing or where he needs help from you. You need to let him digress from the explanation of his initial problem to maybe also think about a possible solution by himself, too. And yes; I AM looking on you, products with only this one contacting-method.

## Make use of the user's existing tools

I already mentioned the first one in the paragraphs above: e-mail. Why even bother setting up a contact form if the user is able to send out mails directly from his own mail-client? Therefore, he would be able to keep track of his sent messages and easily follow the conversations.

1. **Allow the user to follow up:** You might see this as a naturalness, but I've experienced many cases in which the UI forced me to write my feedback or support question over a pre-defined contact form. And the best thing: After I had received the answer, it didn't even contain the text I had initially sent. How the fuck should I know what I sent days ago? Exactly! I guess I'm not the only person who's sending much more than just one message each day — please make sure to provide the user with the question he had asked before (just add it as quotation to the end of the mail, for example).

2. **One conversation for each question:** I know this might sound stupid, but there definitely are companies out there which are using some really neat ticketing-systems that are basically opening a new e-mail-conversation for each answer. What the heck? Just use the exact same thread the user wrote from to answer back.

3. **Don't repeat yourself:** I'm talking about information which has already been shown once - don't waste space and use the same text again. A great example for this is the mail I recently automatically received from [CodePen][1] because my test for the premium package has expired: ![CodePen Mail](/assets/posts/codepen-support.png)
Why did they add the "CodePen" lettering to the subject line? It's already the content of the "sender" meta-item. Just leave it out, thanks! 🐶

4. **You don't need 30-line-long signatures:** I know you want to provide the user with all details about your company - but stop it, you don't need to! The fact that the user already contacted you over e-mail means that he doesn't need to know your freaking hotline-number or postal address (and even if he wants those, he just needs to open your website). Just be a bit more personal and use signatures which simply contain the name of the support staff who wrote the answer. For example: `Cheers, Scott` — Thats it! You don't need more[^2].

### Other tools the user already knows about

As I already said, please don't force the user to write with you over your damn platform. He should be able to follow up whenever he wants to and shouldn't need to log into your site to do so first. Just make use of things like Facebook, Twitter and the good-ol' [e-mail][2].

Every single one of your users writes messages to multiple completely different services and I don't think he wants to have all those messages scattered around different platforms (at least I personally don't think that's purposeful in any way). Take your time and make sending feedback and support questions more comfortable! You'll quickly see that more users are spending their extremely valuable time to make your product better, because they want to be able to use it without disorders.

---

**EDIT:** Regarding the "one conversation for each question" [argument][3]: Please also make sure to not force the user to proceed with the dialogue over a completely different medium. The conversation should be started and finished in one stream (or "thread" if that makes more sense to you).

For example, if a user asks reports a bug over Twitter, don't advise him to fill out a freaking bug report. That just makes the user's effort on getting the feedback to you redundant. — If you're out of luck, he might even loose the incentive of writing you once again completely.

*Thanks to @e2b for letting me know about this.*

---

[^1]: Please don't get me wrong here. Of course they should already do what they can to make the product awesome by themselves.

[^2]: And if you have more than one "Scott" in your company, just add their last name.

[1]: http://codepen.io
[2]: http://www.guinnessworldrecords.com/60/images/records/1971.jpg "Ray Tomlinson — a.k.a. the guy who wrote the first ever email"
[3]: #make-use-of-the-users-existing-tools