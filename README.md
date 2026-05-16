# The 1,024,000² 2b2t World Download Project (1m²). And More.
It's finally here. Around 24 TB total of 2b2t world data, which includes:
- a 1,024,000² (1m²) area of the Overworld (Dec 25 2025 - Apr 13 2026),
- a 512,000² (512k²) area of the Overworld (Nov 11 2024 - Dec 12 2024),
- a 256,000² (256k²) area of the End (Jan 23 2026 - Feb 15 2026),
- a 100,000² (100k²) area of the Nether (Jun 9 2025 - Jun 14 2025),
- high-resolution top-down renders of all dimensions with a NewChunks overlay

This wasn't easy to accomplish in the slightest, and took over a year of constant development and stresstesting. With
severe weaponized autism, the help of several people involved, thousands of dollars spent, and countless hours wasted,
we present you the largest world download project ever, on 2b2t, and in Minecraft. Let's break down what exactly
happened. This has been brought to you by crayne (me), Fuch, mahan, Steve3, and many more. Watch the SalC1 video about 
the topic [here](PLACEHOLDER).

# TLDR of what happened
- Fuch and I started a project to download a large area of the server. I created a custom file format to save on storage,
  along with a custom world download server, and a basic autopilot.
- At the end of 2024, we launched 28 bot accounts on BMProxy to download a 512k² Overworld area, with the intent to find
  bases, and covering up the entire thing as a fake larp coord exploit with the Enclave. This was achieved within 17 days.
- In June of 2025, 2b2t finally updated to 1.21.4, and the nether roof was accidentally left enabled. We decided to use
  this while it was possible, and promptly launched 6 accounts to download a 100k² Nether area, finishing in under a week.
- Right after Christmas Eve of 2025, we launched a project to download a 1m² Overworld area of the server. We also went
  and manually gapfilled some missing parts of the Nether. Lastly, we downloaded a 256k² area of the End at the same time.
  This final project took 109 days to complete, finishing in April of 2026.

You can read the full story about this project [here](STORY.md).

# Where's the Torrent?
Providing a Torrent for this amount of data is not easy whatsoever. We are currently working on creating a Torrent that 
includes all data, as well as the spreadsheets exported from datamining, and all the high-resolution renders, but this 
may take a few weeks. We ask you to be a little patient with downloading this for yourself, especially since many people
don't even have this amount of storage available.

In the meantime, you can join the 2b2t.place Discord (https://discord.2b2t.place), which is an extension project
dedicated to archiving as much of 2b2t as possible before it turns into a boring, censored SMP, or if it shuts down.
We will also be releasing renders, spreadsheets exported from the world download, more visualizations of data, and the
Torrents in our Discord server, so stay tuned. I will also edit this post to include the links to the Torrents once they
are public.

We also offer free services such as the 2b2t Wayback Machine (Server IP: `wayback.2b2t.place`) and a
[Map Website Viewer](https://2b2t.place) (https://2b2t.place). You can use these services right now to view the data for
yourself, while we are getting the Torrent ready. Both of these services are in a public beta, so please report any 
issues you may find, along with any suggestions you have, in our Discord server. Older snapshots are still in the 
process of being imported into the Wayback Machine server, but should be available relatively soon.

Many more open-source tools are coming to the public very soon, including PlaceProxy, the world download server, 
the zvcr file format, and much, much more. You can check out our GitHub here at https://github.com/2b2tplace.

You can support the project by beta testing, helping the moderation team, providing data, making cool software, or 
simply being part of the community. More large-scale world downloads are yet to come, and they will be posted in our 
Discord server.

# Discoveries
Many interesting things were found in this download, and many were unfortunately not found.

The Nether was scanned for playermade 1x2 tunnels, giving us a list and heatmap of almost all tunnels in the Nether.
This spreadsheet alone consists of over 171 million tunnel block positions. Insane.

We searched through many chunks marked as newly generated to create a list of all unique naturally generating blocks.
This was used to create a heatmap of all unnatural blocks within 512k radius in the Overworld. Of course, the Devs
obsidian logo is very visible in here, due to the high amount of crying obsidian. Collective sky isn't visible, as
obsidian and sea lanterns both generate naturally. We also made a spreadsheet listing all unnatural block types that were
found, along with the number of their occurrences.

A search for vertical 5x5 obsidian/crying obsidian pinwheels was also made, and only 1258 were found, with only 613
within a 25k radius of spawn. There were many more than this in December of 2025, so this is either a sign of other 
players removing them, or the owner(s) of 2b2t worldediting them all out at some point.

There is no water in the Nether. No holes in the Nether roof or any of the bedrock floors. No blocks placed above the 
Nether roof illegally. No illegal blocks such as barriers, end portals, etc. were found anywhere, aside from the publicly
known illegal bedrock in the Nether, as well as the bedrock floor in the End. To our susprise, though, we found 10 
illegal pig spawners that survived all the way until 2026. This is just unbelievable.

Sign text was also searched, and to noone's surprise, codysmile11 has placed a whopping 1 million signs across all 3 
dimensions in this download. This is followed by \_Lide\_ with over 263 thousand signs. What surprised me about signs is 
the sheer amount of signs with slurs of them still remaining even within a 10,000 radius of spawn. Newly placed ones are
censored in this region, but old ones remain. Some colored signs were also found, surviving from when they were possible 
to create in 1.12.2 (circa 2018). 86 colored signs were found in the Overworld, and only 11 in the End. 
These seem to be very rare nowadays.

There were 1683 illegal nether portal locations found in the Overworld, and 141 in the Nether, with the majority 
consisting out of fully flipped 2x3 portals. Many others were more interesting, with some flipped, some missing or other 
weird combinations. Aside from illegal nether portals, we found over 10.4 million nether portal blocks in the Overworld
and over 2.8 million nether portal blocks in the Nether in total.

We also found 6064 half doors, and 27343 half beds. I Guess those weren't as rare as FitMC claimed. The rarest half door 
type was iron half doors, only 5 were found, all in naturally generated woodland mansions. This is followed by only 6 
dark oak half doors, all generated in shipwrecks. Only 17 jungle half doors were found in newer desert villages. All 
other half door types were relatively common in comparison, with copper doors ironically being the most common, found in
1.21.4 trial chambers. Half beds seem to be extremely common, with most of them generating in half villages, cut off by
the active chunk culling/trimming, and others generating in broken trial chambers. Interestingly, the rarest half bed is
the pink half bed, with only 434 occurrences out of the 27351 total half beds.

Alongside half doors and half beds, there are also many half plants (half tallgrass, flowers, large plants). As weird as 
they seem, they are extremely common, with almost 6 million of them combined. The most common on the list here are half 
tall seagrass (over 2.6 million), half peonies and half tallgrass. On the less common side, there are half large ferns, 
half rose bushes, half lilacs and half small dripleafs, with half sunflowers being the rarest (still, 10830 of them).

We found many illegally floating/placed blocks, with many common ones, such as big dripleafs on deepslate and deepslate 
ores, dandelions and poppies on sand/gravel, wheat and other crops on grass/path blocks, and many more plants illegally 
placed or floating, caused by oddities in the world generation. Surprisingly many floating torches were found in very 
old mineshafts and villages (65935 of them). 

On the rarer side, there are not as many potato, carrot, beetroot or pumpkin crops that generated on top of the wrong 
block type. Only 6 attached melon stems were found to have generated wrongly like this.

Floating oak doors were also found (4417), as well as the more rare floating acacia doors (176), waxed oxidized copper 
doors (87), and the extremely rare, floating spruce doors (18), iron doors (12), waxed copper doors (7) and only a 
singular, one of a kind floating dark oak door. 

The rarest illegally floating/placed block types, and arguably the rarest block types on 2b2t altogether, are the one of 
a kind oak sapling on gravel, one of a kind acacia sapling on mossy cobblestone, and the one of a kind floating acacia 
sapling. Acacia saplings naturally generate in villages, with 87 of them found to have wronly generated on top of crops. 
(I accidentally broke the oak sapling on gravel, watch the SalC1 video about this project to see that.)

Surprisingly, only a single floating jungle sign, only a single floating birch sign, and only 11 floating oak signs were
found in the download (standing sign variant, not wall signs). These can be placed to this day, abusing retracting piston
heads that fail to retract their block not causing block updates properly. If you have the materials, go on 2b2t right now,
and place some floating signs. Seriously. If you know of a method that still works on Paper 1.21.4 to create illegal half 
doors, half beds, illegally floating blocks, illegally placed blocks such as saplings and others that can't be placed on 
piston heads, please let us know. Update suppression was one of our best guesses, but there is no publicly known method
that could work on 2b2t.

# Credits
First and foremost I want to thank Fuch, for funding most of the operation through his hard work and dedication. 
Spending this much money on block game archival is just absolutely insane and none of this would've ever happened
without his help. So much was spent on priority queue purchases alone, but also server rental costs, adding up to over
$3000. Beyond funding, our combined autism has been a great motivating factor to finish this project in particular, out
of all the other ideas we had in mind and never got around to.

Secondly, I want to thank Steve3 and mahan for their huge help providing a separate BMProxy instance just for us
throughout all the world downloads we have done over the years. A big thanks goes to mahan in particular, for helping me
extensively stresstest our private software (world download server, proxy, autopilot, zvcr file format), and having to
deal with porting my (honestly very horrible) autopilot code from the prototype Meteor addon to BMProxy. Along with
this, he provided a lot of great ideas that were implemented into the 2b2t.place software. Working with mahan has been 
the most enjoyable experience from all my previous development teamwork ever, and without his and Steve's help, this
project would have taken atleast another additional year to complete.

A huge thank you to SalC1 for making the YouTube video surrounding this world download project and spending countless
hours revising the script, editing, and going back and forth with us to make the video as high quality and perfect as
possible. This was despite him being originally done with 2b2t altogether, due to the censorship done by the server
owner(s) and of course due to Microslop. But given that he has a huge interest in archiving internet history, he was
still willing to make a video about our project, and I am very, very grateful for that. You can see he poured his heart
and soul into the video.

I want to thank all members of the Enclave that helped accomplish the initial 512k² project in 2024. Many members
contributed their alternate Minecraft accounts for use in the project, adding up to 28 accounts in total. Thanks to 
Fuch, Cody4687 and expunged, a large portion of the priority queue during that project was also funded ($600+). I want 
to especially thank catgirlmatty for being extremely supportive of this project and creating several videos about it. 
I want to thank her for also inviting me to the Enclave (given our shared interest in world downloading 2b2t, even if 
with entirely different motives), and introducing me to Steve3, mahan, expunged, candyking24, Cody4687, WhiteAtlas, 
and Highatwork. The entire "Dofnear Exploit 2" larp was the funniest shit I've ever been a part of (although it may have
slightly deceived the community... I guess this giant wall of text clears things up a little bit). Operation Fact Check
(OFC) as an organized project fueling Dofnear larp was extremely fun as well, and you can thank expunged and
catgirlmatty for the success of it; both of them leading the operation, with expunged managing most of the spreadsheet
work and sending batches of coordinates to fact checkers. An astounding 2100+ locations were manually checked in-game by
all contributors, giving a final yield of over 600 dubs of stolen items, which is simply absurd.

Lastly, a huge thank you to [AustinGraphics](https://austin.is-a-good.dev/), for creating the frontend for the 
https://2b2t.place website. Thanks to his dedication to this project, we can host the full map of this project for 
everyone to see. I have never personally done any frontend development on my own, and could have never made a website 
as cool as this.

**Additional thanks and shoutouts to the following people, that also helped in one way or another:**
- antonymph, for providing accounts during the 2024 512k², fact checking many locations during OFC, being supportive all 
  throughout and correcting me on some wrong info that I gave to SalC1
- EastAlpha and Philipp, and the other members of the Devs, for coordinating with us on properly timing the releases of 
  the world download, and the their group logo project, also making the final render of the map way more interesting
- candyking24 and Russianxd, for helping check and filter many locations from the 1m², providing many interesting ideas 
  for the datamining process, and being supportive in general throughout the project
- galicaea and candyking24 for their incredible singing used in the Enclave's Dofnear YouTube video
- H202 for staying supportive and not leaking the project, even after leaving the group, and for originally bringing up
  the funny idea to rename some of the used accounts after criminals named John.

**Thank you to the OFC fact checkers that contributed to the 600+ dubs of stolen items:**
mikuexpo, antonymph, galicaea, catgirlmatty, ilovelucki, Zandax, uh_sid, candyking24, browngirl, expunged, HighAtWork, 
KayQuack, WhiteAtlas and mahan.

### My role in the Project
It doesn't feel right to credit myself, but in case you're curious, I wrote the code for:
- the custom file format used to store the downloads (zvcr),
- PlaceProxy and the PlaceTools mod, which will soon allow anyone to contribute to our public archive,
- the 2b2t Wayback Machine, powered by PlaceViewer and zvcr, letting you flashback in time on the 2b2t map,
- the elytra autopilot(s) (an older version using the Boost elytra flight exploit, a newer version using Pitch40),
- the datamining program, to find all sorts of interesting things,
- core utilities to do operations with zvcr and mca region files (merge, render, upgrade, export, import, ...).

No AI/LLM's were used in the making of this project. Or writing this giant wall of text, if it gave you that impression.

## A Final Note
Although I probably spent the most time working on the code for this project, everyone involved deserves recognition,
regardless of how much effort they put in. I spent the better part of around ~1.5 years developing most the code used
for the world download, and this has been extremely exhausting. It would not have been possible to achieve all of this
if it wasn't for everyone mentioned above. I hope the community can make great use of the data provided by us, whether
to make the 2b2t experience more enjoyable, or having a backup plan to give the server into the hands of the community,
just in case the 2b2t server owner(s) decide to make changes noone likes. It'll be interesting to see what the players
can come up with.

\- crayne