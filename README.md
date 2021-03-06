# Let's make a Twitter Bot!
A Twitter bot workshop using Tracery and Cheap Bots Done Quick.

## Overview
- Look at some Twitter bots, and understand what they are.
- Learn Tracery, a simple method of Mad Libs-style text generation
- Make our own generators using Tracery
- Learn how to use Cheap Bots Done Quick, a beginner-friendly platform for hosting Twitter bots
- Turn our generators into real bots


## Let's look at some Twitter bots
(Note: Not all of these use CheapBotsDoneQuick)
- [@TwoHeadlines](https://twitter.com/TwoHeadlines) by [Darius Kazemi](https://twitter.com/tinysubversions)
- [@SortingBot](https://twitter.com/SortingBot) by [Darius Kazemi](https://twitter.com/tinysubversions)
- [@RapNameBot](https://twitter.com/RapNameBot) by [Darius Kazemi](https://twitter.com/tinysubversions)
- [@everyword](https://twitter.com/everyword) by [Allison Parrish](https://twitter.com/aparrish)
- [@gayeveryword](https://twitter.com/everywordisgay) by ??
- [@the_ephemerides](https://twitter.com/the_ephemerides) by [Allison Parrish](https://twitter.com/aparrish)
- [@thinkpiecebot](https://twitter.com/thinkpiecebot) by [Nora Reed](https://twitter.com/NoraReed)
- [@mothgenerator](https://twitter.com/mothgenerator) by [Everest Pipkin](https://twitter.com/everestpipkin) and [Loren Schmidt](https://twitter.com/lorenschmidt)
- [@ArtAssignBot](https://twitter.com/artassignbot) by [Jeff Thompson](https://twitter.com/jeffthompson_)
- [@autoflaneur](https://twitter.com/autoflaneur) by [Harry Giles](https://twitter.com/harrygiles)
- [@MagicRealismBot](https://twitter.com/magicrealismbot) by [Chris Rodley](https://twitter.com/chrisrodley)
- [@bot_teleport](https://twitter.com/bot_teleport) by [Rick Hoppmann](https://twitter.com/tinyruin)
- [@softlandscapes](https://twitter.com/softlandscapes) by [George Buckenham](https://twitter.com/v21)
- [@thetinygallery](https://twitter.com/thetinygallery) by [Emma Winston](https://twitter.com/deer_ful)
- [@tinycarebot](https://twitter.com/tinycarebot) by [Jonny Sun](https://twitter.com/jonnysun)
- [@Pentametron](https://twitter.com/pentametron) by [Ranjit Bhatnagar](https://twitter.com/ranjit)

## Tracery
[Tracery](http://tracery.io) is a text generation library created by [Kate Compton](http://www.galaxykate.com/).
It's basically a big list of lists and templates you use to generate text in a [Mad Libs](https://en.wikipedia.org/wiki/Mad_Libs)-style, where certain parts of a sentence are selected at random from a larger group.

- [Online Tracery Editor](https://beaugunderson.com/tracery-writer/)
- [Corpora](https://github.com/dariusk/corpora/tree/master/data) big lists of stuff!
- Lets looks at some of the JSON files included in this repo and plug them in!

Let's try making our own! Break into groups and come up with an idea for your generator. Good bots have a simple, narrow theme that is then expanded upon to have a lot of possibility. 

- Start with a recent news headline, a fun meme, or a subject you're interested. Don't overthink it!
- Make a starter template sentence
- Make lists of things that could be swapped out
- Generate!

## Cheap Bots, Done Quick

[Cheap Bots Done Quick](https://cheapbotsdonequick.com/) is a fantastic Twitter bot hosting platform by [George Buckenham](https://v21.io/) that lets you turn any Tracery generator into a Twitter bot. Here's all you need to do:

- Create a new [Twitter account](https://twitter.com/). If you can, putting in a phone number will keep your account from getting shut down.
- Log in to [Cheap Bots Done Quick](https://cheapbotsdonequick.com/) with your new Twitter account
- Paste in the grammar from your Tracery generator
- Test to make sure it works
- Set how often you want to tweet
- Go back into the Twitter account and make a nice profile and banner image and description. Make sure you let people know it's a bot.
- Done!

## Some Ethical Guidelines

To quote Leonard Richardson and an axiom of the botmaking community, ["Bots should punch up"](https://www.crummy.com/2013/11/27/0). If your bot makes jokes at someone's expense, make sure they're higher status than you, aka it's cool to make bots that make fun of corporations, politicians and celebrities, but its not cool to make bots that bully and harass regular people, especially groups of people that put up with a lot of that harassment already.

If your bot "accidentally", or you purposefully program it so that it generates text that is harmful in any way, for example, if the text is sexist, racism, ableism, and so on, that is a problem. It is your responsibility as a bot-maker to think about and prevent this. You are responsible for the actions of your bot, especially if it hurts another person. If you're unsure, err on the side of caution.

## Going Further
* [Tracery Github repository](https://github.com/galaxykate/tracery/tree/tracery2) - The source code for Tracery. You can use it in any JavaScript project!
* [Interruption Junction](http://squinky.me/interruption/) - a non-bot (a game!) using Tracery.
* Make a Tracery bot on Mastodon, using this [Glitch.com template](https://glitch.com/edit/#!/tracery-mastodon-bot).
* Dan Shiffman's The Coding Train has a great set of videos on making a [Twitter bot in Node.js](https://www.youtube.com/watch?v=RF5_MPSNAtU), without using Tracery/CBDQ. You can program one from scratch if you want, and do more complex stuff!
