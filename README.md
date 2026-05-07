# BO3 Zombies Infos for High Rounders

<p align="center">
  <a href="https://docs.google.com/document/d/1_YguF4tDvJxPxoACrdw3tF5WoLf1CRWfu4XE1TIK6VQ/edit?tab=t.wb7xttfpktcl#heading=h.pm0o615drx9w"><img src="https://img.shields.io/badge/Google%20Docs-Main%20Document-grey?style=for-the-badge&logo=googledocs&logoColor=white&labelColor=4285F4" alt="Main Document"></a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://docs.google.com/spreadsheets/d/1tZzWyMXOmVbWzf9ZrgWBRRMjJwL7Xfpze-X9_pz7PpU/edit?gid=0#gid=0"><img src="https://img.shields.io/badge/Google%20Sheets-Reset%20/%20Entities-grey?style=for-the-badge&logo=googlesheets&logoColor=white&labelColor=0F9D58" alt="Reset/Entities Spreadsheet"></a>
</p>

<br>

## Contents
**[Sleep / Hibernate](#sleep--hibernate)**
  - [Testing & Choosing What Works FOR YOU](#testing--choosing-what-works-for-you)
---
**[Workshop Mods](#workshop-mods)**
  - [Strat Tester - Highlight & SPH](#strat-tester---highlight--sph)
  - [Zombies Community patch](#zombies-community-patch)
  - [Zombies Community patch 4Modderz](#zombies-community-patch-4modderz)
  - [Aesthetic Mods](#aesthetic-mods)
---
**[Torso/Invisibles Rounds](#frozen-rounds)**

---
**[Errors](#errors)**
  - [Rags Slams / Nade Swap / Nade Cancel Error](#rags-slams--nade-swap--nade-cancel-error)
  - [Throwable Equipment Error](#throwable-equipment-error)
  - [“Hitmarker” Freeze](#hitmarker-freeze)
  - [Early Reset / G-Spawn](#early-reset--g-spawn)
  - [Shadows of Evil Error](#shadows-of-evil-error)
  - [Gorod Krovi Freeze](#gorod-krovi-freeze)
---
**[Read Error Tracker](#read-error-tracker)**
  - [How To Read Livesplit Error Tracker](#how-to-read-livesplit-error-tracker)
---
**[GK Freeze Detailed By Kxg124](#gk-freeze-detailed-by-kxg124)**

---
**[Darkness](#darkness)**
  - [Hibernate / Sleep PC (Suspending the game)](#hibernate--sleep-pc-suspending-the-game)
  - [Darkness Video + Images](#darkness-video--images)
---
**[25 Day Error Bypass](#25-day-error-bypass)**

---
**[Niche Knowledge](#niche-knowledge)**
  - [Instakill Drop Behavior](#instakill-drop-behavior)
  - [Bugs/Parasites Behavior on Shadows of Evil](#bugsparasites-behavior-on-shadows-of-evil)
  - [Spiders behavior on ZnS](#spiders-behavior-on-zns)
  - [Der Eisendrache dogs health behavior](#der-eisendrache-dogs-health-behavior)
  - [Zombies Health behavior from round 112+](#zombies-health-behavior-from-round-112)

---

# Sleep / Hibernate

*Disclaimer: While this method works for most players, results can vary depending on your specific PC configuration. Always test first.*

**1. Close Unnecessary Programs**
* Before putting your PC to sleep/hibernate, close **all programs** except:
  * **Black Ops 3** (required)
  * **Livesplit** (optional)
* **Crucially, close applications like OBS or Voicemeeter**, as they are known to cause instability during sleep/hibernate cycles.
* Running other applications in the background increases the chance of crashes.

**2. Configure Windows Power Settings**
This step is critical to prevent Windows from interfering with the suspended game.

**Part A: Basic Power & Sleep Settings**
1. Open Windows **Settings** (Windows Key + I).
2. Go to **System > Power & Sleep**. (You can also search for "**Power and Sleep Settings**" in the Start Menu).
3. Under **Screen**, set *"When plugged in, turn off after"* to Never.
4. Under **Sleep**, set *"When plugged in, PC goes to sleep after"* to Never.

**Part B: Advanced Power Plan Settings**
1. In the same Power & Sleep window, click "**Additional power settings**" on the right. (You can also search for "Choose a power plan" in the Start Menu).
2. Select the "**High performance**" plan, then click "**Change plan settings**" next to it.
3. On the next screen, click "**Change advanced power settings**".
4. A new window will open. Configure the following settings exactly:
   * **Hard disk** > **Turn off hard disk after:** Set to **0** (**Never**).
   * **Sleep** > **Sleep after**: Set to **0** (**Never**).
   * **Sleep** > **Allow hybrid sleep**: Set to **On**.
   * **Sleep** > **Hibernate after**: Set to **0** (**Never**).
   * **Sleep** > **Allow wake timers**: Set to **Disable**.
5. Click Apply and then OK.

**3. Lower FPS When Paused**

Once your game is paused, open the console (`~` key) and enter:

`/com_maxfps 10`

This reduces system load while the game is suspended.

![](https://github.com/user-attachments/assets/dc26d8d2-b58e-42fb-b35b-74cdea2e361e) 
![](https://github.com/user-attachments/assets/d6c0fefa-c1a2-4f06-852d-8160cf9fe6e7)

![](https://github.com/user-attachments/assets/7a1d39b3-45de-4515-912b-1cf814cf8180) 

![](https://github.com/user-attachments/assets/7f126f70-3302-4241-a7d1-c2a4878ac927)

![](https://github.com/user-attachments/assets/e1712922-317b-4f46-874f-cb53319871cc)
![](https://github.com/user-attachments/assets/54cca9bc-8709-4b0e-bb03-a252d9963092)

#

### Testing & Choosing What Works FOR YOU
**Important**: One method will reliably work for your system, but you need to test to determine which one.

1. **Test on Round 1**
   * Start a game, pause on Round 1, and put your PC to sleep/hibernate.
   * Wake the PC and check if the game is stable.
2. **Hibernate Test (Try First)**
   * Try to hibernate your PC 10 times in your Round 1 test.
   * If the game never crashes, hibernation is safe for you.
3. **Sleep Test (If Hibernate Fails)**
   * If hibernation causes **crashes**, repeat the test 10 times using **Sleep** instead.
   * For users where hibernate fails, sleep will work perfectly.

My Experience (Jumpy):
For me, hibernation crashes my game almost every time by the 3rd attempt. Sleep, however, has no issues. Your experience may differ, so testing is essential.

Note on Crashes: If your PC regularly crashes when attempting to sleep/hibernate *outside of the game*, it may indicate a system issue.

For the purpose of pausing your game overnight, there is no difference.
* Both will preserve your game.
* Both are resistant to power loss. If power goes out while your PC is asleep or hibernated, your game will not be lost.

---

# Workshop Mods

## [Strat Tester - Highlight & SPH](https://steamcommunity.com/sharedfiles/filedetails/?id=3715324145)
https://steamcommunity.com/sharedfiles/filedetails/?id=3715324145

Not the greatest strat tester, but it’s best we’ve got

## [Zombies Community patch](https://steamcommunity.com/sharedfiles/filedetails/?id=3003539961)
https://steamcommunity.com/sharedfiles/filedetails/?id=3003539961

## [Zombies Community patch 4Modderz](https://steamcommunity.com/sharedfiles/filedetails/?id=3228882538)
https://steamcommunity.com/sharedfiles/filedetails/?id=3228882538

### *Aesthetic Mods*

<br>

<table align="center">
  <tr>
    <th width="280" align="center">Ascendance</th>
    <th width="280" align="center">DS4C</th>
  </tr>
  <tr>
    <td align="center">
      <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3652135484">
        <img src="https://github.com/user-attachments/assets/d32f0b0f-4066-4ab1-b254-55facbc99a57" width="250"/>
      </a>
      <br><br>
      By <a href="https://steamcommunity.com/profiles/76561199211441639/myworkshopfiles?appid=311210">oJumpy</a>
    </td>
    <td align="center">
      <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3566816837">
        <img src="https://github.com/user-attachments/assets/29cb6bd4-1c44-4474-bba7-0e6a884989ad" width="250"/>
      </a>
      <br><br>
      By <a href="https://steamcommunity.com/id/Death_Storm44/myworkshopfiles?appid=311210">Death_Storm4</a>
    </td>
  </tr>
</table>

<br>

---

# Errors

<h1 align="center">
  <em><strong>
    I could be wrong about some of this.<br>
    Not everything here is 100% confirmed.<br>
    Reach out if something is wrong.<br>
    I’d love to have second opinions about any of this.<br>
    Corrections and second opinions are very welcome.
  </strong></em>
</h1>

## Rags Slams / Nade Swap / Nade Cancel Error:
- **NOT** *the same as Grenade / Widows CI Error -*

(Co-Op & Solo)
This is a **different error** from the usual **Nade Error / Widows Wine CI**.
The “Nade Error” is caused when you **SUCCESSFULLY** throw equipment.

### - What Causes This CI Error
Every time you **slam** with **Ragnarok DG-4**, **cancel** a grenade throw or **nade swap**, the game creates two threads that never get cleaned up. The game increases the **Child GSC** variable.

The `beginGrenadeTracking()` thread (waiting for `grenade_fire`)

The `watchGrenadeCancel()` thread (waiting for `grenade_fire`)

After ~**3000 rags slams/nade swaps**, you have ~6000+ stuck threads. The **Child GSC variable** tracks active threads and crashes when it reaches ~130,000.

### - The Fix
**Fully throw ONE grenade, monkey, or trip mine every round to keep it simple or every ~1000/~2000 slams/swaps. That's it.**

When you fully throw a grenade, the game finally triggers `grenade_fire`, and every waiting thread will terminate.

### - Simple Example
* Slam / nade swap **2000 times**
* Throw **1** grenade/monkey/trip mine
* All stuck threads are cleared
* You now can nade swap or slam another **~2000** times
* Repeat

### - Tools to Make This Easier
* [lveez Debugger](https://github.com/lveez/bo3-debugger/releases/tag/v1)
  ![](images/image12.png)
* [oJumpy’s Livesplit Script](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII) with Child variable monitor
  Shows the Child value so you can track when to reset.
  
---

## Throwable Equipment Error
- *This will **NOT** work for solo -*

Only works for non-host players. If you’re off-host, you can throw equipment, but you must leave the game afterward to clear up threads.

**Important:** This only clears threads created by non-host players, not the host. That’s why some co-op games still crash even if players leave.

Example:
Non-host players can throw ~2000 nades.
After that, they need to leave the game to reset the error.

For instance, if Player 1, 2, 3, and 4 throw 500 nades each, that accumulates to 2000 nades.
Player 2 and 3 left the game, count went down to 1000, cleared only player 2 and 3, player 1 will never get cleared, so you want the host to avoid throwing nades

Host contribution remains. The host should avoid throwing nades.

### Recommendations (Jug Side First Room):
I'd recommend using[oJumpy’s Livesplit Script](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII) and track `Child Server Variable`

[Here explains how to use the timer script if needed](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII)

**-Only Host can see this-**

it will show as:

`Child GSC: <Current_Value> MAX: <Current_MAX_Value> / 130000`

You wanna focus mostly on the max value
When you first launch Verruckt it will show up as `70000 / 130000`

That's what you want to pay attention to, I recommend most likely if the variable is around 100k and counting up, you want to have a non-host player that's throwing nades to leave and join back. and the variable will stabilise, if it was to start increasing again, repeat.

**-Non-Host Players-**

The player that's throwing nades, can also use the livesplit tracker, to show how many nades he's thrown, the error usually seems to occur around 3500 to 4000 nades thrown.
![](images/image3.png)
So i suggest whenever you have thrown 2000 nades, leave and join back the game.

---

## “Hitmarker” Freeze
*This issue is **global**, meaning all players in the match contribute to the buildup.*
*This is NOT to get confused with the Freeze that happens on Gorod Krovi, it’s unrelated.*

### - What Causes the “Hitmarker” Freeze
While it's still not 100% certain what exactly triggers the freeze, here's what we know:

When the game reaches around **55,000 - 60,000 hitmarkers**, it will eventually **freeze.**

From testing, I believe the issue appears to be in how **attackers and victims interact** during damage feedback

Every time a bullet hits a special enemy `_globallogic_vehicle.gsc` calls this function `Callback_VehicleDamage` to process the hit.
* Calls Callback_VehicleDamage
* Attacker being tracked (the game will store who hit what)

The way we track it is by brute force counting hitmarkers themselves. Since nothing else in the tracked variables shows errors or overflows when the “hitmarker” freeze happen., we only have an estimate which seems to be between 55k to 60k hitmarkers before freezing.

### - How to Avoid the Freeze
On **Zetsubou No Shima**, use mostly **Electric Cherry** and **Skull of Nan Sapwe** to kill spiders.

On **Shadows of Evil**, avoid shooting **bugs or meatballs** with bullet weapons.

Avoid using weapons that produce a large amount of hitmarkers to kill the special enemies, that’s what pushes the value toward 55k–60k.

As of **19/04/2026** Recently found out that the vesper and a few other smgs, actually triggers the thread differently, i believe it’s due to how it has a different “type weapon”.
Because of this some smgs, can actually reach in the 160k hitmarkers

### - Hitmarkers per Weapon (ZnS)
* Vesper = **4** Hitmarkers (This is actually 1.5) ![](images/image3.png)
* M8A7 = **3** Hitmarkers
* ICR-7 = **2** Hitmarkers
* RK5 = **1** Hitmarker

---

## Early Reset / G-Spawn
*(Mostly an issue on ZnS, but it can happen on any map if you spawn kill ground spawners)*

**ZnS Example:**
In the **Skull Room**, **ground spawners** will **add entities** only if they’re killed instantly before fully spawning, usually while using an instakill or Death Machines.

This can cause **G-Spawn** if the entity count builds too high.

Be careful using Instakills and Death Machines, try not to spawn kill zombies

The **Skull of Nan Sapwe is safe.** It plays an animation first, so it doesn’t instantly kill the zombies spawning and doesn’t cause G-Spawn or Entity buildup.

**Shadows of Evil Example:**
If you play the *Junction* Strategy and shoot directly at the ground spawner with an instakill or death machine, it will cause G-Spawn to build up.

Using the Sword Slam **is safe.** It plays an animation first, so it doesn’t instantly kill the zombies spawning and doesn’t cause G-Spawn or Entity buildup. ![](images/image3.png)

---

## Shadows of Evil Error
#### - What Causes the Error
This is what I believe is some **Animation Error,** if you shoot the Apothicon Servant **near the rail**, you’ll kill zombies while they’re in their **climb animation**, which causes the crash.

Doing this repeatedly for long periods (around **2 hours** of game time) builds up to an error.

#### - How to Avoid the Crash
*Can look at pictures to where you can safely shoot*
* **Do NOT shoot near the rail.**
* If you want to **spam safely**, shoot the **ground spawner itself**.
  This has been tested and safe to do, there’s been multiple 255s doing this
* If you're doing **single shots**, shoot nearly outside the ritual circle that’s in Junction (look pictures) Safe

<p align="center">
  <img src="https://github.com/user-attachments/assets/953a03dc-f14d-4493-b398-fd63b97021f8" width="490" />
  <br>
  <img src="https://github.com/user-attachments/assets/20991393-77e7-4648-969c-4edfa2e869a9" width="490" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/d5973acb-0c0c-4caa-9d56-f97a0ce9cd8e" width="490" />
</p>

---

# Gorod Krovi Freeze
Gorod Krovi Error, is Child CSC based, which has an overflow of 65000, once that’s reached the game will freeze. It is still unknown what 100% is the root cause of it.

#### - How to Avoid the Crash
With current knowledge, we know that Valks are mainly the cause of the Freeze, so you want to try to kill as few as possible.
Based on some real games that made it to 255, it is possible to still kill valks, so you don't have to strictly avoid killing them at all times. Just be careful not to kill too many.

#### - Playstyle Recommendations
These are strategies kxg uses and suggests all players do to ensure reaching round 255:
* Only use **Dead Wire** and **Turned**
* Only use the **MK3 until ~round 50**
* **DO NOT** go overboard spamming the left slowdown shot of the MK3 (this will increases your CI variable)

Shield Usage:
* **Always aim DOWN** when using the shield
* **NEVER blast** if a valk is right next to you

Turned Army (Round 159+):
* Avoid making more than **~6 turned army** on the map at one time
* More turned army = faster the CSC variable tends to increase
* You can EITHER:
  * Blast valks for most of the game carelessly and have ~4 turned army all game after 159+
  * OR be very careful blasting valks ALL GAME to be allowed 8+ turned on the map safely
* *(This still needs more testing for conclusive answers)*

Instakill/Death Machine Usage:
* Do **NOT** carelessly shoot on instakill/death machines when avoiding valk kills
* Electric Cherry **will** kill valks when instakill is active
* Death machine usage should **never** be used on valks, and ideally not on manglers
* Use Electric Cherry on manglers during instakill instead of shooting them directly ![](images/image1.png)

Other Notes:
* The shield melee bash on instakill *might* also increase the variable (unconfirmed)
* **NEVER** use the gauntlet or flamethrower unless required for Easter Egg steps
* The gauntlet punch **RAPIDLY** increases CSC variable

As of **20/04/2026** 

#### - What causes the leak?
* **Gauntlet**
  1 - The Gauntlet stores its visual effects, like the blue glow from the punch and green fire for the dragon, in **arrays**.
  Every time you pull the Gauntlet out or change its ability between punch and flamethrower, you are permanently adding FXs to this “list”.
  Their effects are handled in `_zm_weap_dragon_gauntlet.csc`, in the `function_3011ccf6` function.

  Because the script calls `stopfx` but fails to actually delete the contents of `self.var_4d73e75b`, every time you pull out the punch ability and every single time you punch it permanently adds 8 items to the list.

  The Flamethrower instead, “just” adds 4 FXs every time you pull it out, permanently, but actually using the flamethrower seems to be safe

* **Valks**
  2 - Valkyries are definitely the main cause of the freeze, but it's specifically because of two different bugs:
  * **The Shock / Beam Attack:** When a valk locks onto you, it fires an electric beam, which it applies a “Target FX” to whatever it is shocking, if you **kill** the valk while it’s actively shocking something, the script fails to delete the “Target FX” leaving it orphaned permanently.
  * **The Arms/Plates Dynamic Entities:** When you shoot off a valk’s arm, faceplate (i believe camera too seems to be an entity that can fall, not too sure though), it falls to the ground as a dynamic physics entity `dynEnt`. The code is supposed to clean up this entity once the piece hits the floor, however, it only cleans up the piece if it falls **less** than 15 units (inches), which I believe is a typo. 
  Since valks hover further than that, meaning the script hits the `else` block, breaks the loop, just abandons those entities and these invisible dynamic entities stay active on the map forever.

[15 Units btw…](https://github-production-user-asset-6210df.s3.amazonaws.com/87671800/588462207-ae3a66eb-f272-498d-b53d-1f4a26a789cd.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260506%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260506T180621Z&X-Amz-Expires=300&X-Amz-Signature=e82f23cbb672fede52b1b65547957c95b3aba29bb41601370dae0c7f9c0aac40&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng) This is why i wanna believe it was a typo

So you can actually safely kill valks, with shield blast, but you have to be careful to avoid the two leaks mentioned above.

#### - Suggestions
Kill valks as soon as they enter the bunker, while they are just hovering or moving.
If they start the “Charge” for the attack, you can still kill them within that window.
If they start zapping, you **DO NOT** kill them, wait about a second or two, for any zap to finish.
Killing manglers seems to actually be safe, they don’t seem to be leaking anything in CSC

# Read Error Tracker

### How To Read Livesplit Error Tracker

The tracker displays information like this example:

text
`Child GSC: <Current_Value> MAX: <Current_MAX_Value> / 130000`

What each tracker shows:
* **Child GSC**: Relates to CI (Connection Interrupted) errors from Widows Wine, rag slams, KT4 kills, MK3 slowdown shots
* **Child CSC**: The Gorod Krovi Freeze error - valks and misc actions contribute to this
* **MemTree**: Not an issue on BO3 yet, but can be tracked for science
* **Hitmarkers**: Broken on GK tracker (can be ignored)
* **Valk counter**: Mostly accurate (small things like going to PAP can change the value slightly)

#### - How to Read the Tracker Information
**Left number**: Constantly fluctuating - tracker reading the most current value
**MAX number**: Highest value the tracker has read for that variable

**Important**: The tracker doesn't update instantly. If you see the variable spike, it doesn't mean the last 5 seconds caused it. Look at the bigger picture of actions taken.

---

## GK Freeze Detailed By Kxg124

Things kxg avoids that he suggests all players do in order to ensure a 255 first try:
- Only use deadwire and turned
- Only use the mk3 until ~50. Do not go overboard spamming the left slowdown shot as that is a known way to rapidly increase your CI variable. People have been able to CI prior to 100 doing this.
- Aim DOWN when using the shield. NEVER blast if a valk is kissing you, any part of you
- 159+ turned army: Avoid making more than ~6 turned army on the map at one time. The more turned army on the map = faster the variable tends to increase. You can EITHER blast valks for the majority of the game carelessly and have ~4 turned army all game once on 159+ OR be very careful blasting valks ALL GAME in order to be allowed to have 8+ turned on the map safely. (This point still needs to be tested more in order to give a more conclusive answer, but in the megas science game that was played the more turned army = faster rate for variable increase)
- Do NOT carelessly shoot on instakill/death machines when trying to avoid valk kills. Electric cherry will kill valks when insta kill is active, but valks will ignore insta kill on valk rounds. (The valk health function seems to not be the same on valk rounds since the insta kill drop does not work properly on valk rounds.) ![](images/image1.png)
- I have been told that using the melee bash of the shield on insta kill is also a potential issue for variable increase, but this is unconfirmed.
- NEVER use the gauntlet or flamethrower unless required for the easter egg step. The punch from the gauntlet RAPIDLY increases csc variable.

_____

How the error tracker works:

There seems to be some misunderstanding regarding the tracker bo3 players have for errors. 

![](images/image8.png)

The above image is an example of information the error tracker can display. 

The child GSC relates to the CI (Connection Interrupted) error that is mostly associated with widows wine usage. Other items such as rag slams, kt4 kills, and the slow down shot of the ray gun mk3 can also directly increase this variable. 

The **Child CSC** is the error related to the **GK Freeze** directly. Several misc things can contribute to this variable increasing by a wide range. 

MemTree is not something seen to be an issue on Bo3 (as of yet), but kxg had it open in his megas 255 just to track.

Hitmarkers (for GK at least) are broken on the tracker and can be ignored

Valk counter was largely accurate, but not 100%. Small things such as going to pap changed the value for the counter, along with other small misc events in the game, but not nearly to the point where the value given is not useful. 

**SO HOW DO WE READ THIS INFORMATION???**

The number on the far left is constantly fluctuating. This is the tracker trying to read the most current value for the given variable. The next number (ie: Max: 103943) displays what the tracker has read as the **HIGHEST** value for said variable. The tracker does not update with the highest value instantaneously after doing an action that could directly increase the variable, but it will update frequently enough to show overall progression. What this means is that if you suddenly see the variable spike, it does not mean the action you did in that moment is the direct reason for the variable value increasing. For example, you could be blasting valks for over an hour with the tracker not updating with a new highest value having been read. However, you could be standing still waiting for zombies to get to you and suddenly see the tracker display a new highest variable value being read after said hour. This does NOT mean that you should look at the last 5 seconds of gameplay to see what made the value spike, but rather look at the larger picture of actions taken that could be problematic. 

_____

Testing is still inconclusive to give a 100% definitive answer, however all signs point towards valks being the MAIN contributing factor to avoid interacting with at all cost. This means that when playing, players should avoid damaging and killing valks carelessly. In the countless GK games kxg has played, all of the games that froze early ended because of this. 

In kxg’s classics 255 played at the end of 2020, he went out of his way to play as safe as possible to avoid valks dying. This meant that for the entire game the shield was pointed at the floor in order to control the shield blast to only kill what was directly surrounding the player. Accidental valk kills did still happen, and the player is forced to kill whatever valks are on the map at the end of the round in order to progress. Playing this way is the EXTREME safe way to avoid killing valks as much as possible. (It is also slow, boring as **FUCK**, and means the player cares more about the valk’s lives than their own.) kxg did still make a decent size turned army on 159, and killing valks every now and then to keep the army alive was required. This game was the first EVER to get past 228 in solo, (after kxg getting several 220+ games, and shelby having a 226 and 228 freeze,) with the expectation that this theory of avoiding valk kills would at most avoid freeze until the late 230s/early 240s.kxg was very surprised when he instead got 255 no freeze.

In kxg’s no gum 255 he was a bit more aggressive when killing valks at select points during the game, but the overall playstyle matched the classics. 1-159 was saving valks. 159-180ish valks blasted. 180-230ish valks saved. 230-255 valks blasted.kxg also played an additional ~3 hours to freeze to confirm that the freeze was in fact still just around the corner. 

In the time since kxg’s no gum 255 there have been only 2 more 255s. The first was a classics 255 that shelby/dadwonthugme played that has limited surviving gameplay. I can not speak much regarding the overall playstyle differences, but it is safe to say he was also close to freeze. The only other gk game that made it to 255 without freeze in this time was the megas 255 that kxg played earlier in 2025. Interest in this game came about because of the newly released error tracker that displayed peak values seen for the csc variable. This game was a “science game,” meaning that the point was to see what factors directly correlated with peak spikes for the csc variable increasing. kxg previously played a no jug game where he died on 186 with the tracker displayed, so a baseline estimate of expected variable increase with a playstyle of blasting valks the entire game was already established. kxg tracked the variable on a spreadsheet for every round in the no jug game to see how quickly on average the variable was going up. kxg then did the same thing with the megas 255 on the same spreadsheet to directly compare the rate of the csc variable increasing. The playstyle of the megas 255 was: 1-180 valks were not blasted. Accidental killing along with required blasting to maintain turned army did still occur. The life of valks were more important than the life of the player. 180-200 valks were blasted. 200-210 valks were kept alive. 210-end of game valks were blasted. The full list of the notable events and variable tracking are displayed on this sheet here: https://docs.google.com/spreadsheets/d/1XF08HkgcfjG8eCATmgzAIjjiy_XtfML61BHy-x6Lw0U/edit?usp=sharing ![](images/image1.png)

---

# Darkness

*This is how fast you will reach Darkness in BO3, since it’s dependent on your FPS, even while the game is paused.*
*Darkness does NOT occur on every map / level and it’s also zone / area dependent*

### Hibernate / Sleep PC (Suspending the game)
**Never** - If you hibernate you will not reach Darkness as game would be frozen at 0 Fps

#### 10 FPS
having the game at 10 Fps the whole time it would take **34.68days** - 832hours

#### 24 FPS
having the game at 24 Fps the whole time it would take **14.28days** - 342hours

#### 60 FPS
having the game at 60 Fps the whole time it would take **5.58days** - 133hours

#### 100 FPS
having the game at 100 Fps the whole time it would take **3.52days** - 84hours

#### 120 FPS
having the game at 120 Fps the whole time it would take **2.85days** - 68hours

#### 144 FPS
having the game at 144 Fps the whole time it would take **2.36days** - 56hours

#### 200 FPS
having the game at 200 Fps the whole time it would take **1.70days** - 40hours

*Darkness will occur once it reaches 22-bit limit at 4,194,303, once this number overflows*

Can easily track this value using this [oJumpy’s Livesplit Script](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII)

Right Click LiveSplit &rarr; Edit Layout &rarr; `+` button &rarr; Control &rarr; Scriptable Auto Splitter

Under **Options** and select Darkness ![](images/image3.png)

### Darkness Video + Images
*Video Showcase:*[https://www.youtube.com/watch?v=4GL_2VAVZUY](https://www.youtube.com/watch?v=4GL_2VAVZUY)

Darkness occurs **only** in these maps / levels:
Shadows of Evil -  Most of Waterfront area
The Giant - At Power Switch / Bowie Knife area (Only when power is on)
Der Eisendrache - At Rocket Launch area, only happens when you take the Wundersphere 
Zetsubou no Shima - Most of the entirety of Lab B
Gorod Krovi - At Hatchery where Pack-A-Punch is located
Revelations - It occurs mostly everywhere on the map, thankfully there’s workarounds for it
Origins – At Gen 6 and Crazy Place

There’s Workarounds to Not get Darkness on DE, ZnS and Revelations

DE - Instead of taking **Wundersphere**, you just **Teleport** to the Rocket Launch Area.[ZnS - Walk off the cliff go for ICR - Vesper ammo run first then M8 and Shield.](https://discord.com/channels/@me/530347473126948882/1445297752736268469)
Revelations - Take the teleporter from Verruckt to Spawn, then run back to Verruckt.

*Shadows of Evil - Most of Waterfront Area (No Workarounds)*
<p align="center">
  <img src="https://github.com/user-attachments/assets/9b9f2435-b5e5-48c3-9271-eedb226e6220" width="490" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/fdede43c-801b-4479-914c-384d7e866cde" width="490" />
</p>

*Origins - Gen 6 and Crazy Place (No Workarounds)*
<p align="center">
  <img src="https://github.com/user-attachments/assets/1315e4a8-172d-49ca-8213-c7f624d99a64" width="490" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/a8c12c95-5ede-4a2e-8101-43f362fe61bf" width="490" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0d8064cc-0761-4a99-a24a-67bfc225e090" width="490" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/63ac3a71-6ce8-46ef-967f-fd53fd23a757" width="490" />
</p>

![](images/image3.png)

---

# 25 Day Error Bypass

*This method **freezes the timer** during hibernation, it does NOT reset it.*

#### How does it work?
* When you hibernate with the correct steps, the frame timer stops counting
* When you wake the PC and continue playing, the timer **resumes** from where it paused
* The timer does NOT reset back to zero, it only pauses during hibernation

#### When to do it?
You need to use this **every time you hibernate**, not just when the timer is close to expiring.

#### How to do it:
1. Before hibernating:
   * Turn **automatic time** **OFF** in Windows settings
2. **Hibernate your PC**
3. When restarting from hibernation:
   * Enter BIOS immediately
   * Change the date **back one month**
   * Save and exit BIOS
4. When Windows boots:
   * Your frame timer should still be at the pre-hibernation time
   * Turn **automatic time** back **ON**
   * If time doesn't correct itself, **manually set** the correct date/time
5. **Repeat this process** every time you need to bypass the 25 day limit

If you Sleep instead, you can do this in order to still bypass the error:

1. To access BIOS after sleep:
   * Flip the **PSU switch** **OFF**
   * Wait till you are ready to play again
   * Flip PSU switch back **ON**
   * You'll now get BIOS prompt on boot
2. **Enter BIOS** and follow same date-change steps as above
3. **Repeat** as needed

Note
It's probably possible to wait until the timer is close to the limit before doing this, but how reliable that is hasn't been fully tested. Playing it safe by doing it every session is the recommended approach.

---

# Niche Knowledge

<h1 align="center">
  <em><strong>
    I could be wrong about some of this.<br>
    Not everything here is 100% confirmed.<br>
    Reach out if something is wrong.<br>
    I’d love to have second opinions about any of this.<br>
    Corrections and second opinions are very welcome.
  </strong></em>
</h1>

### Instakill Drop Behavior
#### - What Happens
When Instakill is active, killing zombies with bullet weapons drops NO powerups unless the zombie hits the player first.

This does **NOT** happen on any other map. On maps like Der Eisendrache, Gorod Krovi, and Origins, Instakill behaves normally.

#### - What Maps Are Affected
* The Giant
* Zetsubou No Shima
* Revelations
* Shangri-La

#### - What These Maps Have in Common
All four affected maps have side quests that reward players with "free perk bottles" or "free perk slots":
* **The Giant**, Teleporter can drop a free perk bottle (random perk, no slot)
* **ZnS**, Challenges and plants can reward free perk slots (slot only, and perk)
* **Revelations**, Wall run and challenge rewards can give free perk bottles (random perk, no slot)
* **Shangri-La**, Monkeys can flip max ammos into free perk bottles (random perk, no slot)

Why this is weird: Gorod Krovi has Challenges, free perk bottles and perk slots, yet Instakill works fine there. Origins has free perk slots (digs) like ZnS, yet Instakill works fine there too.

#### - Why does it happen?
**The Giant** idk
**ZnS** and **Revelations** registers permanent zombie death callbacks that never get deregistered
**Shangri-La** seems to be constantly monitoring for drops, so something happens there?

---

### Bugs/Parasites Behavior on Shadows of Evil
#### - What Happens
If you play a "Bug Round" (Bonus round) in one district, for example *Waterfront*, and then move to a different district, for example *Junction*, for the normal zombie rounds, every Parasite that spawns will instantly fly all the way back to the previous district before returning to you.

#### - The Cause
This is caused by a failure to update the Wasp Spawner's location during normal rounds, combined with a delay in the Wasp's teleportation script.

1. In `_zm_ai_wasp.gsc`, the function `special_wasp_spawn()` (which handles Wasps during normal rounds) calculates a spawn point but **fails** to move the actual spawner entity.

From `_zm_ai_wasp.gsc` :function  `special_wasp_spawn()`
```gsc
spawner = level.wasp_spawners[0];

if( isDefined( spawner_override))
{
    spawner = spawner_override;
}
ai = zombie_utility::spawn_zombie( spawner );
```

Because spawner location `.origin` isn't updated, the Wasp is spawned at whatever coordinates the spawner was left at during the last Bug Round.

2. Inside `wasp_spawn_init()`, the game attempts to teleport the Wasp to the player, but it includes a 1.5 second wait, during this wait, the Wasp is still physically sitting in the old zone:

From `_zm_ai_wasp.gsc`: function `wasp_spawn_init()`
```gsc
// Spawn in fx and initialization
// - ai.favoriteenemy = the wasps target
function wasp_spawn_init( ai, origin, should_spawn_fx = true )
{
    ai endon( "death" );

    ai SetInvisibleToAll();

    if ( isdefined( origin ) )
    {
        v_origin = origin;
    }
    else
    {
        v_origin = ai.origin;
    }

    if( should_spawn_fx )
    {
        PlayFx( level._effect["lightning_wasp_spawn"], v_origin );
    }

//  playsoundatposition( "zmb_hellhound_prespawn", v_origin );
    wait( 1.5 );
//  playsoundatposition( "zmb_hellhound_bolt", v_origin );

    Earthquake( 0.3, 0.5, v_origin, 256);
    //PlayRumbleOnPosition("explosion_generic", v_origin);
//  playsoundatposition( "zmb_hellhound_spawn", v_origin );

    // face the enemy
    if ( IsDefined(ai.favoriteenemy) )
        angle = VectorToAngles( ai.favoriteenemy.origin - v_origin );
    else
        angle = ai.angles;
    angles = ( ai.angles[0], angle[1], ai.angles[2] );

    //DCS 080714: this should work for an ai vehicle but currently doesn't. Support should be added soon.
    //ai ForceTeleport( v_origin, angles );
    ai.origin = v_origin;
    ai.angles = angles;
}
```

During this time, its AI logic (`state_combat_update` in `_parasite.gsc`) turns on. The AI detects the NavVolume in the **old district(Waterfront)** and picks a “flight node” to move to. It executes the engine command `SetVehGoalPos()` to start flying there.

When the 1.5s timer ends, the script snaps the Wasp’s position to the player in *Junction*, but the **original “flight node” goal remains active and does not clear the** flight goal that was already set.

I used “districts” as an example to make it easier to understand. but this is *zone* based.

**- Simple Summary of the cause**
1. Wasp spawns at the **old** district (*Waterfront*) because the spawner didn't move.
2. Wasp AI starts and picks a spot to fly to in that **old** district.
3. The game teleports the Wasp to your position (in another district *Junction*), but it still wants to finish its flight to the **old** district.
4. Wasp flies away, hits its "ghost" goal, then finally comes back to fight you.

---

### Spiders behavior on ZnS
1 - When you shoot a spider, it visually dies immediately and grants you +50 points. However, the spider entity itself stays alive for a full 10 seconds.

Their death state is handled in `_spider.gsc`, in `state_death_update` function:
`_spider.gsc`:
```gsc
// ----------------------------------------------
// State: death
// ----------------------------------------------
function state_death_update( params )
{
    self endon( "death" );

    self ASMRequestSubstate( "death@stationary" );
    vehicle_ai::waittill_asm_complete( "death@stationary", 2 );

    self vehicle_death::death_fx();

    vehicle_death::DeleteWhenSafe( 10 );
}
```

2 - When a spider is ready to spawn, it triggers `special_spider_spawn` in `_zm_ai_spiders.gsc` and at the end of the loop, it calls `waiting_for_next_spider_spawn`

```gsc
function waiting_for_next_spider_spawn()
{
    switch ( level.players.size )
    {
        case 1:
        {
            n_default_wait = 2.25;
            break;
        }
        case 2:
        {
            n_default_wait = 2;
            break;
        }
        case 3:
        {
            n_default_wait = 1.75;
            break;
        }
        default:
        {
            n_default_wait = 1.5;
            break;
        }
    }
    wait n_default_wait;
}
```

Because the `round_spawn` thread is actively processing this spider spawn, this “`wait n_default_wait;`” blocks the main `round_spawning`. Because the game calls the spider spawn logic as a direct function rather than starting it on a separate thread, `round_spawning` must wait for this `waiting_for_next_spider_spawn` function to finish before it can try to spawn the next zombie.

This issue is present on **Shadows of Evil** for meatballs and **Gorod Krovi** for Valks and Manglers

---

### Der Eisendrache dogs health behavior
On Der Eisendrache there’s a bug where if you use the **Teleporter** or **Wundersphere** to go to Rocket or viceversa, causing the dogs to de-spawn and re-spawn multiple times during the 2nd ever dog round of the game, the dog’s health will be permanently locked to the 2nd dog round health for the rest of the game. `level.dog_health = 900;`

This happens because in this function `function_1aaa22b5` in `zm_castle_dogs.gsc`
This function prevents dogs from getting stuck in a zone where they can’t reach the player, so the game kills the dog if you are in zone “v10” if they are not there, so they can spawn closer to the player

```gsc
function function_1aaa22b5()
{
    if(!isdefined(self.favoriteenemy))
    {
        return;
    }
    var_4b010f36 = self zm_utility::get_current_zone();
    var_3d24b4b1 = self.favoriteenemy zm_utility::get_current_zone();
    if(isdefined(var_4b010f36) && isdefined(var_3d24b4b1))
    {
        if(issubstr(var_4b010f36, "v10") && !issubstr(var_3d24b4b1, "v10") || (!issubstr(var_4b010f36, "v10") && issubstr(var_3d24b4b1, "v10")))
        {
            level.dog_round_count++;
            self kill();
        }
    }
}
```

At the start of every dog round, the game updates the dog's health based on that `level.dog_round_count` variable. This is handled in `_zm_ai_dogs.gsc` in the `dog_health_increase` function:

```gsc
function dog_health_increase()
{
    players = getplayers();

    if( level.dog_round_count == 1 )
    {
        level.dog_health = 400;
    }
    else if( level.dog_round_count == 2 )
    {
        level.dog_health = 900;
    }
    else if( level.dog_round_count == 3 )
    {
        level.dog_health = 1300;
    }
    else if( level.dog_round_count == 4 )
    {
        level.dog_health = 1600;
    }

    if( level.dog_health > 1600 )
    {
        level.dog_health = 1600;
    }
}
```

Because there is no “else” statement at the end. If level.dog_round_count is 5 or higher, none of these conditions are met, and the function finishes without doing anything, which is what happens in `function_1aaa22b5` when you teleport 2 or 3 dogs get killed from that function, because it does “`level.dog_round_count++;`” and you are on a second dog round the counter will go higher than 4, the health function `dog_health_increase` simply stops updating on all future dog rounds, The `level.dog_health` variable stays permanently locked at 900

---

### Zombies Health behavior from round 112+

---

# Frozen Rounds

### **Universal**
Things like Fireworks, Turned (explosion effect), Thunder Wall, Flogger, Ice Staff

These are the rounds where **Universal** things will **NOT** kill zombies properly:
> ## **121, 123, 127, 129, 133, 135, 140, 141, 143, 150, 152, 153, 154, 162+**

### Shadows of Evil - Unupgraded Sword

Rounds where the **Unupgraded Sword** kills zombies properly, with just **ONE** slam:
> ## **1-126, 128, 130-132, 134-139, 142, 144-149, 151, 155-161**

Rounds Where the **Unupgraded Sword** does NOT kill zombies with just **ONE** slam, makes zombies one shot:
> ## **127, 129, 133, 140, 141, 143, 150, 152-154, 162+**

### Der Eisendrache - Bows

Rounds where the **Bows** kills zombies properly:

**Lightning Bow:**
> ## **1-112, 116-121, 123, 126, 127, 131, 135, 137-139, 141, 143, 152, 154, 162+**

**Fire Bow:**
> ## **1-120, 122, 124-126, 128, 130-132, 134, 136-139, 142, 144-149, 151, 155-162**

**Shangri-La, Moon health of special enemies**
