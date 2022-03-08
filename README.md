# RHVoice-NVDA-Dictionaries

NVDA dictionaries to fix the way RHVoice pronounces many words.

## How to use?

Paste the speechDicts folder from this repository into your NVDA configuration folder, and restart NVDA.

## Supported voices.

**Note**: Currently, these dictionaries only support English voices.

The following voices are currently supported:

* Alan
* Bdl
* Clb
* Evgeniy-Eng
* Lyubov
* Slt

## Contributing.

Currently, each voice has its own dictionary file. This is because NVDA doesn't let us have dictionaries for specific synth drivers, and also, certain voices might break the hack used to make it speak correctly for other voices (e.g. Evgeniy-Eng broke the saying of the name Jaylin that was used for other voices, so we had to change it in that dictionary file alone). 

Because of this, when adding new voices, please remember to put it in all 6 dictionary files, and to also test with all 6 voices ot make sure that nothing broke.

The easiest way to get it into all 6 dictionary files currently is to create it in one, then copy/paste into others. I plan to make a script to somehow automate this after it is added to only one of the files, but it doesn't take a huge amount of time to copy/paste anyways.
