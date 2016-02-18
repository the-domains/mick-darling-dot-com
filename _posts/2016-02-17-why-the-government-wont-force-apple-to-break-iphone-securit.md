---
inFeed: true
hasPage: true
inNav: true
inLanguage: null
starred: true
keywords: []
description: "There is a VERY big economic reason that the Government won't force Apple 's hand to brute force the iPhone or future devices."
datePublished: '2016-02-18T03:29:21.754Z'
dateModified: '2016-02-18T03:28:53.225Z'
title: "Why the Government won't force Apple to break iPhone security in the end."
author: []
sourcePath: _posts/2016-02-17-why-the-government-wont-force-apple-to-break-iphone-securit.md
published: true
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
url: why-the-government-wont-force-apple-to-break-iphone-securit/index.html
_type: Article

---
Below is a selection of somewhat technical text of the instructions given to Apple in the recently discussed case where the FBI wants Apple's help to break the security on the iPhone.  These excerpts are taken from a [techdirt article][0] which also has some excellent comentary

> Apple's reasonable technical assistance shall accomplish the following three important functions: (1) it will bypass or disable the auto-erase function whether or not it has been enabled; (2) it will enable the FBI to submit passcodes to the SUBJECT DEVICE for testing electronically via the physical device port, Bluetooth, Wi-Fi, or other protocol available on the SUBJECT DEVICE and (3) it will ensure that when the FBI submits passcodes to the SUBJECT DEVICE, software running on the device will not purposefully introduce any additional delay between passcode attempts beyond what is incurred by Apple hardware.

Basically if the phone were an Apple branded safe it has a this nasty (for the government) feature (1) that sets all documents inside on fire if someone tries the wrong combination more than 10 times.  They want that feature deactivated.  But they want more than that.

Sections (2) and (3) describe how they also want Apple to create a super duper high speed autotumbler spinner that will try as many combinations that that the FBI can give it as fast as physically possible.

> Apple's reasonable technical assistance may include, but is not limited to: providing the FBI with a signed iPhone Software file, recovery bundle, or other Software Image File ("SIF") that can be loaded onto the SUBJECT DEVICE. The SIF will load and run from Random Access Memory and will not modify the iOS on the actual phone, the user data partition or system partition on the device's flash memory. The SIF will be coded by Apple with a unique identifier of the phone so that the SIF would only load and execute on the SUBJECT DEVICE. The SIF will be loaded via Device Firmware Upgrade ("DFU") mode, recovery mode, or other applicable mode available to the FBI. Once active on the SUBJECT DEVICE, the SIF will accomplish the three functions specified in paragraph 2\. The SIF will be loaded on the SUBJECT DEVICE at either a government facility, or alternatively, at an Apple facility; if the latter, Apple shall provide the government with remote access to the SUBJECT DEVICE through a computer allowing the government to conduct passcode recovery analysis. 

There is a lot of pseudo technical detail here that is really just trying to make it seem like this new super speed auto safe cracker and content immolation defuser will only work on this one particular safe.

> If Apple determines that it can achieve the three functions stated above in paragraph 2, as well as the functionality set forth in paragraph 3, using an alternate technological means from that recommended by the government, and the government concurs, Apple may comply with this Order in that way.

Can Apple even build this crazy thing? It is interesting that the order isn't even sure if this is possible, which means Apple hasn't made it clear if they even have the capability to create the safe cracker the government wants, or which of the three tasks, if any they can or cannot do.

But the most important part of why Apple will not be creating this anti-security device is at the very end of the order (with highlights added below by me):

> To the extent that Apple believes that compliance with **this Order would be****unreasonably burdensome**, **it may make an application to this Court for relief** within five business days of receipt of the Order.

This is the crux of the whole order that Apple and (likely a lot of other tech companies) will be hanging their arguments on to refuse to build magic high speed safe cracking devices or software to there globally, and it is only vaguely being talked about in the press about this issue.

Tim Cook alludes to it in his [Customer Letter][1] talking about the "threat to data security" and  the "dangerous precedent" it sets.

**The Crux** (aka: it is all about the money)

If the government can use the All Writs Act to require any company to build something like this super speed safe cracker that explicitly undoes all the security that is designed into their devices in the first place the burden to their brand and technology in the marketplace turns into a multi-billion dollar.  For a company the size of their present market base is plenty to say this would cut into their value as a company massively.

For a smaller company that is building an encrypted communication app, the argument on burdensomeness is that you are too small to build a hacking tool against your own security process.

Building a tamper proof safe that you have proved can be tampered with  is the biggest burden a tamper proof safe company can be placed under.  The monetary value of that burden for Apple to do this would be some significant share of its $**624 Billion dollar** value.  As much as the government wants Apple to break that, and set the precedent for other companies, I doubt they will ever pay a bill that high.

[0]: The%20order%20also%20sets%20out%20that:%0ATo%20the%20extent%20that%20Apple%20believes%20that%20compliance%20with%20this%20Order%20would%20be%20unreasonably%20burdensome,%20it%20may%20make%20an%20application%20to%20this%20Court%20for%20relief%20within%20five%20business%20days%20of%20receipt%20of%20the%20Order.
[1]: http://www.apple.com/customer-letter/