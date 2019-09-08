# SatelliteRecorder
An audio router/mixer to connect an HT with "Kenwood" speaker mic pinout, a PC (eg: gaming) headset, and a phone (eg: iPhone) to make working and recording Amateur Radio FM Satellites easier.

## THIS DESIGN IS PROBABLY BROKEN!!!
People have asked me to post this file, so I am.  But I do not claim it works perfectly.  It PROBABLY works pretty well, but I can't guarantee anything.  There are almost certainly improvements that can, and should be made.

If you're downloading this, do a `git log`.  If you only see one or two commits from me talking about "initial commit" or "warning!" or whatever, you probably don't want to just build this without reviewing it and making sure you understand what you're building first.

## The Idea
The goal was to build a device that routes audio to and from:
* An HT. I have an AnyTone 868, which has the "Kenwood Standard" speaker mic connection that so many radios use, so that's what this is. Use a straight through 3.5mm male to male cable, and a straight through 2.5mm male to male cable between the "Radio" ports on this board and your HT.  If you have an HT with a different pin out, you're on your own.
* A Headset.  PC gaming head sets are common, cheap, and can interface with radios pretty easily.  Electret mics, dynamic headphones, etc. Easy peasy. And they're cheap.
* A phone.  I use an iPhone, but I think the 4 pin 3.5mm TRRS connector is pretty standard.  Of course, iPhones don't HAVE this connector anymore, but the Lightning to 3.5mm headphone jack dongles work fine.
  * Tip: Left speaker audio 
  * Ring 1: Right speaker audio.
  * Ring 2: Shield and common ground.
  * Sleeve: Mic audio.
* A remote PTT button, probably mounted on the handle of your antenna.

Audio is routed and mixed in what I consider to be "ideal" ways:
* Receive audio from the radio goes to your headphones, and the mic input to the phone so it can be recorded.
* Mic audio from your headset goes to the radio for transmit, and is mixed and set to the mic input to the phone so it is recorded too.
* Speaker audio from the phone is mixed and set to your headhpones too.  So you can hear both the radio, and play-back audio from the phone.

This way, you can record the whole pass, both your audio and the receive audio.  And you can hear play-back from your phone without having to change anything.

That's about all the support I'm going to give on it right now. If you have any questions or want to discuss it with me, find me on Twitter: @SmittyHalibut.

Good luck!  And let me know if you do anything useful with it!

73 de KR6ZY
-Mark
