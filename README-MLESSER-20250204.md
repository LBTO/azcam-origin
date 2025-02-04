Hi Folks,

Wrapping up a few things as I am about to be officially retired...

I just updated the MODS azcam code on the server to the final version which I have recently installed on all Steward telescopes.  I do suggest all the repos get copied/forked/cloned to somewhere and disconnected from my gihub repos. I am asking all the mountain and lab sites to do this since I will no longer be responsible for making sure all the systems work when/if there are azcam changes.

I did not try talking to the test dewar but if it can be powered on I can make sure the new code passes some basic tests sometime over the next week or so. I am not sure when as I am only in town a couple days here and there but will find some time.

There is a file in the installed azcam-mods repo called mods.py which can be the template for future MODS commands.  It is just a copy of the RTS2 version running at the 61”.  Any methods added there can be called by the MODS software which will talk to the server. You can also call the API commands directly (see https://azcam.readthedocs.io/autocode/api/). I can explain this more to someone in the future.

We tested things pretty well before so I don’t think there is any Archon work which is needed. The main archon code modification might be to optimize read noise and speed with the real instrument, that would be done entirely in the STA archon code .ncf file using the STA GUI. I am happy to help with this when the time comes.

I won’t be regularly checking email any longer but I will answer questions when I can.

Good luck and Go MODS!

-Mike

