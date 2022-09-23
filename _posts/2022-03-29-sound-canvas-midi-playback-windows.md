---
layout: post
title:  "Using Roland Sound Canvas emulation to playback MIDI files"
date:   2022-03-29
---
A while back I became interested in the Roland Sound Canvas line of devices, for music creation and recreational use
alike. Couple amazing effects with the classic sounds of the good old SC55, and you've got a MIDI junkie like me right
on the track of trying to emulate it.

## Why Emulate? Why not grab a physical copy of one of the Sound Canvas devices?

The reason is money (more specifically the lack of it)
and the fact I desperately wanted to experience these sounds in good quality with my own custom MIDI files. The need to
emulate the devices was also driven further because of the nostalgia that I have, caused by owning an old Roland E70
keyboard that unfortunately got destroyed when I was about 8 years old (around 2012 / 2013).

Roland themselves have officially released a software product called Sound Canvas VA. It's a [VST](https://en.wikipedia.org/wiki/Virtual_Studio_Technology) synthesiser you can use to make
music with the sounds of the Sound Canvas line of devices, all the way up to the SC8820.

We will utilise parts of this VST (more specifically the main library) to play our MIDI files in the Foobar2000 media
player.

## Important Disclaimer

I can not say I do not condone piracy whilst pirating software myself, however I will attempt to explain my view on
what we're doing here.

We're utilising the DLL library from the SCVA software to emulate the Sound Canvas devices in Foobar, but we do it for
media playback only. So, theoretically, we're only using the library, not the full software product.

The software is also being downloaded officially from Roland India, so we're not using any cracks or anything of that
sort.

Use your own judgement on whether or not you want to proceed here. I don't have much legal knowledge about this sort of
usage, and I haven't really tried researching it either.

With that out of the way, let's listen to some doom MIDIs! Or is it just me? HMM...

## Installing the Boring Stuff

Before we set off on the good part of the journey, we must go through the usual business of spamming the next button and
accidentally installing Avast Free Antivirus because some greedy app manufacturer wanted their sponsor money.

Fortunately, all of the software installed today does not have that sort of monstrosity so you can safely spam the next
button with no consequences.

1. Make sure you have [Foobar2000](https://www.foobar2000.org/) installed and ready to go. If you're like me and like
   converting your music to various formats, make sure to grab the free encoder pack while you're on the download page.
2. Download and install the [MIDI Player component](https://www.foobar2000.org/components/view/foo_MIDI)
3. Get Sound Canvas VA from Roland India
   [here](http://in.roland.com/support/by_product/sound_canvas_va/updates_drivers/351454)

Now that we have everything installed, it's time to set up Foobar2000!

## Foobar2000 Setup

In Foobar, launch your preferences window either by pressing CTRL + P or starting it from the file menu.

Go to the "Advanced" category, and scroll down to "Playback > MIDI Player"

In the "Secret Sauce path" enter your SCVA install location, default is "C:\Program Files\Roland\Sound Canvas VA\"

Now go to the "Playback > Decoding > MIDI Player" category and set "Plug-in" to "Secret Sauce".

If there is no option for Secret Sauce, click "OK" and restart Foobar. That seems to do the trick.

## Now Let's Play Some MIDI's!

Simply open a MIDI file in Foobar from Explorer, or use any other method of importing content to Foobar.

If the file plays, congratulations, you've set the Secret Sauce plug-in up properly and can now enjoy your Sound Canvas
goodness!

In the MIDI Player settings you can find additional options for changing your Sound Canvas model as well as a few other
tweaks to hopefully make your listening experience as good (Or bad) as you want it.

Foobar2000 is generally one of the best audio players I've ever had the pleasure to use, so if you are enjoying it so
far and have lots of other obscure formats you like listening to (Be it Amiga modules or other video-game console
specific music) make sure to browse through the [Foobar2000 components
repository](https://www.foobar2000.org/components) and you'll probably find something that suits your needs.
