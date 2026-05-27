# The Full Story
For a project that lasted for almost 2 years already, there has to be a story behind it. You can read all of it here.

## The First Test (512k² Overworld)
Our first goal was breaking
[the 256k² world download record](https://www.reddit.com/r/2b2t/comments/t287n9),
achieved in 2022, so a sidelength of 512,000 blocks was chosen, to get a rough idea of the process.
We estimated this to take over 20 days and require a minimum of 24 accounts, downloading a mix of new and old chunks.
This 512k² was funded by Fuch, and a smaller portion of it by Cody4687 and expunged. Members of the Enclave provided
their alternate Minecraft accounts for use in this project, and eventually used the data to steal countless stashes all
around the server.

The 512k² Overworld download was done using headless bot instances hosted on BMProxy, running a custom autopilot elytra
fly bot made possible using Fake Fly and Boost elytra fly. 24 accounts were used to download the outer sections past
256k², 3 accounts redownloading 256k², and 1 account redownloading 15k² over and over again, which was then used to
create the delta heatmap timelapse used at the beginning of the Enclave's Dofnear YouTube video. It shows all block
changes made within that area during a 1 month period, and served as a compression benchmark for our custom file format
(zvcr) that uses delta snapshots to store multiple snapshots of the world. That benchmark was absolutely worth it, as it
showed how effective this form of compression is, even for something as organic as 2b2t spawn. The filesize increase
from these snapshots is absolutely negligent, mission success.

The download was finished much quicker than the anticipated time, and only took 17 days, including the 256k²
redownload. The remaining time was used to attempt extending to 620k², which had so many new chunks, it lagged out the
server to the point of it not being worth extending. We switched focus to redownload 256k² yet again, as well as 256k²
of the End dimension, and as it was about to finish, the owner(s) of 2b2t patched Boost elytra fly. The data of the End
dimension was later unfortunately corrupted and lost.

In total, 1174029 region files were downloaded, amounting to 4.23 TB. This project lasted from November 11 2024 to
December 12 2024.

That was the end of that. 17 days for 512k² alone, and the previous record of 256k² already broken. But we weren't done.

We exported all signs of player activity such as hotspots of signs, beds, ender chests, shulker boxes, chests, as csv
files, as well as making a render of it all. Realizing this looked like the heatmap of something like Nocom or Randar,
we larped about it being an exploit, and started Operation Fact Check (OFC). I apologize for everyone that was deceived
by that insane larp. It was funny to us, but also kind of dishonest to the community. The project will remain open going
forward, and as fun as it was, our future world downloads won't be covered up under fake exploits. See OFC Credits below,
[Reddit post](https://www.reddit.com/r/2b2t_Uncensored/comments/1iq5qyf) and
[YouTube video](https://www.youtube.com/watch?v=0tsblY9MjrQ). If you're wondering why there is no mention of me; I
deleted all of my comments and pretty much all involvement in the Dofnear exploit larp afterwards. The world downloading
project was then cut off from the Enclave, and continued with just me, Fuch, and mahan leading operations from then on.

To clear up any confusion or deception about the fake exploit, the Enclave has finally come clean and they decided to
make a [YouTube video](https://youtu.be/ztiXYttX8mg) about the actual method to find bases (512k² world download).

## The Nether Roof (100k² Nether)
What followed after the 512k² Overworld download and OFC was a long break from downloading, largely focusing on
improving the software used, as well as updating everything in preparation for 1.21.4. Reality struck in June of 2025,
when the server updated from 1.20.4 to 1.21.4, and we still haven't finished updating all software. Panic ensued when
word started to spread that the nether roof was left enabled, but nothing worked up there other than basic movement.
We quickly patched up BMProxy to work through ViaVersion, stresstested whatever we were able to, and launched 6 accounts
that we happened to have on hand. To say this was extremely improvised was an understatement, but doing this was
absolutely worth it. Funnily enough, the bots were launched using TNT minecart cannons to shoot us far up above the
roof, then enabling us to use Pitch40 with Fake Fly from there. Infinite flight, no hunger and no interactions needed.

We initially downloaded 50k², skipping 15k² in the center (15k² has a lower render distance, and it being spawn meant
the area was way too active for our liking). This quickly finished, and we started extending to 100k². Seeing that the
nether roof was still enabled by this time, we got greedy and started extending to 300k². As luck would have it, the
nether roof was finally disabled midway through the 300k² extension. Thankfully, the 100k² was a project success,
although missing many chunks from the faulty improvised software we had to use, as well as still missing 15k² at spawn.

In total, 74646 region files were downloaded, amounting to 90.76 GB. This project lasted from June 9 2025 to
June 14 2025.

Of course, the data was scanned for water. Nothing was found. Incredibly sad. No illegal blocks were found either,
aside from the already publicly known illegal bedrock.

## Breaking our own Record and Brushing Up (1.024m² Overworld + 256k² End)
Seeing the flaws in my code, I started quickly cleaning up and refactoring everything. Around the same time, I got the
idea to make a public archival project anyone could contribute to (which is now 2b2t.place), and developed PlaceProxy.
mahan also properly updated BMProxy to 1.21.4, and the bug that caused bots to miss chunks was fixed. The months passed,
and fast forward to December of 2025, we were just about ready to start a new download project. The stars aligned, and
Fuch had enough funds to sustain a 1,024,000² Overworld download project (1m²), which was going to take over 3 months
and thousands of dollars in priority queue and server costs to complete. Now being separate from the Enclave also meant
we had to purchase our own large supply of Minecraft accounts, which was an additional cost to consider.

Right after Christmas of 2025, we launched 5 bots, just to test new chunk downloading speeds. Surprisingly, 2b2t had
noticeable performance improvements making this project even viable in the first place. More accounts were added every
few days, until we reached 20 accounts, downloading the outer sections of 1m², specifically past 512k². A few weeks
after that, we also decided to redownload the 256k² of the End dimension with 5 additional bot accounts, since we lost
the data last time. Later, 2 additional accounts were added to help redownload 256k² and 512k² during the 1m² project.

The 256k² End world download was also quickly completed in only 24 days, with 252175 region files in total, amounting to
merely 24 GB, thanks to the low entropy of the end (consisting out of only a few different blocks) and efficient palette
compression. The End world download lasted from January 23 2026 to February 15 2026.

Around the same time, I started manually redownloading our missing 15k² of Nether spawn with the help of candyking24 and
catgirlmatty. Most of it has been redownloaded, with only minor gaps remaining in the Nether data, mostly completing the
100k² Nether world download.

With everything else complete, all that remained was to wait for the 1m² Overworld download to finish. In the meantime,
we noticed something huge being built in the sky, relatively far away from spawn. It appeared as random stripes all
across the world download. Upon further investigation, we realized it was a new large obsidian megastructure, made by
a group called the Devs, of their group logo. Initially we trolled some of their bot accounts, but stopped not long
after. We kept their project a secret and I reached out to the leader of that obsidian logo project, offering to provide
them a render of their logo. This was eventually used in their announcement,
[Reddit Post](https://www.reddit.com/r/2b2t/comments/1szh4tl)
and upcoming YouTube video.

While the 1m² was nearing completion, we contacted SalC1 early to discuss the possibility of a video, and he agreed, 
despite originally being done with 2b2t. A lot of time and effort went into making this video possible, and he poured
his heart and soul into making it. Watch the SalC1 video about the topic [here](https://youtu.be/HDyze1YlOrI).

In total, an astonishing 16.081 TB of Overworld data was downloaded. The 1m² download project, alongside Nether gap
filling, and the End 256k² were all completed between December 25 2025 and April 13 2026, taking only 109 days. We used
the remaining prio to redownload 100k² to bring spawn up to date, as well as gap filling larger missing spots and then
extending to 1,074,000², but this extension was not fully finished.

Following the 1m², we searched the data for everything we could possibly think of. You can see all discoveries made
from the data gathered during this project [here](DISCOVERIES.md).
