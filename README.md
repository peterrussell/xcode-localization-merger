# xcode-localization-merger
A simple script to create and merge Localization.strings files for use in Xcode

Apologies for any style or conventions that I have failed here, this is my first Ruby script, so be kind!

I chose Ruby for several reasons:
1. UTF-16 support
2. Preinstalled on all recent macOS versions
3. err, that's it

The primary issue is that reading, manipulating and writing data in UTF-16 is a painful thing to do and all-but impossible in some languages. Ruby seemed to have decent support and despite some head-banging-on-desk moments, it seems to have been a good choice.
Ultimately it makes little differnece what language is used to the end-user/developer as long as it works.

Please let me know if you have any questions - I built this for a particular need I had and does not really fit into a full localisation framework or process, if there is anything needed to make that easier ro better for you, please let me know and I'll do my best to accomodate any requests.
