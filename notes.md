<H1> Notes </H1>
<p> - Listened to the weekly podcast. </p> 
<p> - Did the weekly readings. </p> 
<p> - Installed Anaconda. </p> 
<p> - Played around with the Anaconda PowerShell. </p>
<h3> wget </h3> 
<p> - Installed wget on my machine 
<p> - Tried to run the first command (wget http://activehistory.ca/papers/) but didn’t manage to get anything downloaded into my folder. 
<p> - I went on the discord to see if anyone had a solution. I saw that Dr. Graham had posted about people on PC having trouble, and it sounds like my problem. I’m going to try it and see if it works. 
<p> - I tried to move wget.exe to the same folder I was trying to download the papers to, but no luck. 
<p> - I’m going to try rebooting my PC as some people say that helps. (It didn’t) 
<p> - I posted about my issue on the discord. I feel a bit foolish since I’m sure the fix is something obvious that I’m missing. The professor did tell us to try and make something of failure though, so its worth a shot. 
<p>  - Matthew on the discord helped me with my problem. It was something super simple, I needed to as ‘.exe’ to ‘wget’ in the command. Tony pointed out that its always something small, isn’t that the truth. At least it wasn’t a missed semi-colon. 
<p> - $ wget.exe http://activehistory.ca/papers/ worked perfectly! 
<p> - $ wget.exe -r -np -w 2 --limit-rate=20k http://activehistory.ca/papers/  is taking longer to execute, but appears to be working fine. 
<p> - The download went well. It took 17m 5s and I downloaded 128 files. 
<p> - I used wget to download 4 images using a list of URLs.
