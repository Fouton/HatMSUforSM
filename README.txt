To use this MSU pack, you must purchase both soundtracks from the Hat in Time game on Steam, both Original Soundtrack, and B-Side. Once you have these [Steam > steamapps > music > Soundtrack & Soundtrack (B-Side)], copy all files, or just the files listed in hit_sm.json into the Tracks folder. Then, drag the hit json onto the msupcm app to automatically generate the pcm files needed.

If you'd like to determine what tracks are what, just open hit.json in your favorite text/code editor and read through it. Note that you can change the options within the json to change songs.

If there's a song that you'd prefer for a situation, I recommend getting the MSU Scripting app: https://github.com/MattEqualsCoder/MSUScripter/releases/tag/v4.0.0  as well as pyMusicLooper (pip install pyMusicLooper) [requires python], as it will be able to automatically find a loop point in a song for you.

HAVING A PROBLEM?
You may not have the hat_sm blank file needed to make the MSU work. To fix this, create a blank text file, then go to Save As, select all file types as its save type, and name it hat_sm.msu. This should create a blank, 0KB file, which will help make it all work.

MSU Guide: https://www.zeldix.net/t1607-msu-1-getting-started-guide
