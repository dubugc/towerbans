## 1. How It Works
On February 19th 2024, MacDGuy confirmed that **cheating scores is a difficult problem to completely resolve**,

According to MacDGuy, any player who cheats will receive a leaderboard ban. This means the player is permanently banned from having their scores display on leaderboards and their current scores wiped. PixelTail mentioned that they receive 3 reports weekly regarding players cheating scores, and that they are actively removing entries quite often. <br> but this doesn't make sense to me, with only 3 reports a week, they should only wipe 3 entries. <br> Why is PixelTail actively removing and managing leaderboard bans quite often?

<div style="text-align:center;">
  <img src="https://i.imgur.com/8DghpLV.png" width="800"/>
</div>

## 2. How It Fails

A **leaderboard ban** (internally marked as _Flag64_) is supposed to prevent banned users from appearing on leaderboards.

But it doesn’t delete the player’s score. <br> Instead, it *tags* them, and a background system periodically hides those flagged users off the leaderboards. <br>Until that system runs again - the banned player remains visible, on every leaderboard across the game, not just the one they were banned from. Those reappearances then  **generate fresh reports** of cheating scores, which are later used against the player as evidence of repeated misconduct.

There’s no exploit, no hack, and no workaround involved.
The player has **zero control** over this reappearance. 

## 3. Reappearances Amplify Punishment
###  The Case of SuSu
In **April 2025**, **NixEmotions** raised a concern, a Chinese player named **SuSu** had cheated their way to the top of the **Trivia** leaderboard. The devs responded by applying a leaderboard ban and removing that specific score. 

<div style="text-align:left;">
  <img src="https://i.imgur.com/HSEbxPo.png" width="400"/>
</div>

<br>Weeks later, SuSu reappeared - this time ranking #3 in Bowling. The ban had been applied, yet the player’s scores kept returning. [(^1)](https://steamcommunity.com/app/394690/eventcomments/604153951183464508?snr=1_2108_9__2107&ctp=8#c604153951183496049) 

Nix believed if the Trivia score was wiped due to suspected cheating, it's only reasonable that **all** of SuSu’s scores be **scrutinised**, if not removed entirely, to maintain the **integrity of the leaderboards** and respect the time and effort of legitimate players. <br> SuSu's scores *were* removed, but the system allows reappearances onto the leaderboards within minutes after the server refresh.

Despite multiple reports and the ban still in place, **SuSu would later reclaim #1 in Trivia, again.**

It's now been **6 weeks** since the issue was first reported, and GateTheCat joined the conversation showing a screenshot of SuSu yet again returning to rank **#1 in Trivia**. <br> At this point, there's no question that **there's something wrong with the ban system**.  [(^2)](https://forums.pixeltailgames.com/t/1-0-0-0-suspicious-possibly-cheated-high-scores-by-a-specific-player-on-leaderboards-still-present-on-other-leaderboards/53241) 

SuSu's case isn't isolated - I've experienced the same issue firsthand.


##  4. My Own Case
<div style="text-align:center;">
  <a href="https://i.imgur.com/4jDaUSM.png" target="_blank" rel="noopener noreferrer">
    <img src="https://i.imgur.com/4jDaUSM.png" width="200" />
  </a>
</div>

In **March 2020**, I received *the first* leaderboard ban in the game. <br> By 2024, I had reappeared on the leaderboards **hundreds of times,**  [(^3)](https://web.archive.org/web/20250601003906/https://forums.pixeltailgames.com/t/1-0-0-0-suspicious-possibly-cheated-high-scores-by-a-specific-player-on-leaderboards-still-present-on-other-leaderboards/53241) - including reappearing at #1 in Laser Tag, the same position I held before the ban. The system still allows banned users to gain new score and passively climb the leaderboards - or simply reappear where they once were. I proved it with **before-and-after** screenshots showing my banned account reappearing at rank **#1,** unchanged since 2020. <br> It was proof that leaderboard bans were not working.
<div style="text-align:center;">
  <a href="https://i.imgur.com/73nTHSv.png" target="_blank" rel="noopener noreferrer">
    <img src="https://i.imgur.com/73nTHSv.png" width="1400" />
  </a>
</div>

><span style="color:grey"> Flag64 may be the worst flag you can receive, for the reason that PixelTails broken system enables repeat appearances on the leaderboard that inflates report counts, which then escalate into harsher bans like mutes, media restrictions, and server bans. </span>

The devs didn't respond. <br>Instead, my post exposing this flaw - and the repeated reappearance of banned players - was **deleted by MacDGuy**. He then locked Nix’s thread and left behind a vague message implying _everything was under control_. <br>
 But nothing changed. **SuSu was rank #1 again that same day.**

## 5. Leaderboard Loophole
Each reappearance triggers more reports on players with leaderboard bans - a pattern clearly visible with what's going on in Nix's thread.
PixelTail uses those additional new reports to justify further punishments like mutes and server bans - never questioning why a banned player was visible in the first place. 

In my own case, I was reported multiple times in **March 2024** for **cheating** my way onto the Laser Tag leaderboards **overnight**. 

<div style="text-align:center;">
  <a href="https://i.imgur.com/4zbAAeF.png" target="_blank" rel="noopener noreferrer">
    <img src="https://i.imgur.com/4zbAAeF.png" width="1400" />
  </a>
</div>

<div style="text-align:center;">
  <a href="https://i.imgur.com/V0utPz7.png" target="_blank" rel="noopener noreferrer">
    <img src="https://i.imgur.com/V0utPz7.png" width="400" />
  </a>
</div>

PixelTail cited these reports from **March 2024** in my ban appeal and stated I was banned due to an **accumulation of recent reports**, describing my behaviour as **part of an ongoing trend**. <br>They acknowledged that **one of the major reports was about exploits** - even though I’d been banned from the leaderboards 4 years earlier.

<div style="text-align:center;">
  <a href="https://i.imgur.com/wFhtaHM.png" target="_blank" rel="noopener noreferrer">
    <img src="https://i.imgur.com/wFhtaHM.png" width="1000" />
  </a>
</div>




## 6. Censorship & Gaslighting
I sought to understand the reasoning for my posts removal, by laying out the facts one more time, attaching the screenshot as proof again. I offered to demonstrate to MacDGuy in-game on how leaderboard bans currently fail to function.  [(^4)](https://web.archive.org/web/20250601074659/https://forums.pixeltailgames.com/t/moderation-impacting-mental-wellbeing/53401) 

Mac **edited my thread** instead, deleting the attached proof and pretends in the *'deleted-post'* that I never reported the leaderboard issue to the moderation team initially. [(^5)](https://web.archive.org/web/20250601092822/https://forums.pixeltailgames.com/t/moderation-impacting-mental-wellbeing/53401)
<div style="text-align:center;">
  <img src="https://i.imgur.com/fH6Ui7w.png" width="600"/>
</div>

When the broken system was exposed, MacDGuys response was **accusing me of spreading exploits** as justification for its removal. <br>  I reported a system that had not worked as intended for the last 5 years, dating back to **before the Arcade even existed.** I later called him a **liar** for deleting proof and painting me in a false light on his platform, I was swiftly banned from the forum for “Harassment.” [(^6)](https://web.archive.org/web/20250601115047/https://forums.pixeltailgames.com/t/regarding-forum-moderation-leaderboard-ban-report/53402)

<div style="text-align:center;">
  <img src="https://i.imgur.com/cPNa1hw.png" width="400"/>
</div>

## 7. Appeal Process Loophole
Here’s the second flaw they won’t acknowledge:  
They _can’t_ delete a banned player’s old score. 

MacDGuy led the community to believe that scores were wiped. That’s dishonest. <br> The truth is, **PixelTail doesn’t even have the infrastructure to reset scores**.

Your score is still stored in the database. The only fix they’ve come up with is a cheap patch job: They’ve set the system to auto-refresh and remove flagged players from the leaderboard every cycle. And that’s why leaderboard ban appeals **can never succeed**. <br> If they lift the ban, the same cheated score instantly reappears - exposing the fact that the system never actually removed it. It proves the “ban” was not working as intended to begin with.

With just a handful of users affected with this ban still playing the game, PixelTail can comfortably ignore the problem, knowing the chances of anyone exposing how broken the system is are practically zero.


<div style="text-align:center;">
  <img src="https://i.imgur.com/jWUFPAp.png" width="200"/>
</div>



---

I submitted my first ever leaderboard appeal after **five years**. They denied it in 3 hours. <br> The appeal system isn’t there to offer second chances - it’s there to look like one exists.



<div style="text-align:center;">
  <img src="https://i.imgur.com/KbM4bUW.png" width="600"/>
</div>

