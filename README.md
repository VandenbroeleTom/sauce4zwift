# Sauce for Zwift without the Patreon block
Use Sauce for Zwift without the annoying Patreon prompt that prevents you from
using it unless you make financial contributions to the author.

### Is this fair?
That's a judgement call for each of you to make. The important question is...

### Is this legal?
Yes. The original Sauce for Zwift is distributed under the
[https://www.gnu.org/licenses/gpl-3.0.en.html](GNU General Public License v3),
which allows for redistribution of the source code with any modifications under
the same license, which is what I'm doing here.

### But the poor guy has to eat!
And you're still free to donate to him if you so wish, to show your appreciation for the program he created.

## Installation instructions (Mac)
I'm planning to generate the binaries as soon as I have some time for it, but
for now, you can follow these instructions to run it:

### Install brew and npm
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install npm
```

### Build and run Sauce
```sh
npm run
```

***

Sauce for Zwift™
===========
![Sauce](pages/images/logo_horiz_320x120.png)
#### A collection of add-ons and replacement widgets for Zwift
Sauce for Zwift™ extends the zwift cycling and running simulator with more stats and
pretty things.


Requirements:
--------
As of July 2022 Sauce emulates a full encrypted game client that "watches" your real
Zwift account.  As such, you'll need to create a second login (free is fine).  Although
a bit annoying this does allow you to run S4Z on any device anywhere.

<img src="assets/images/screenshot.jpg" width="640"/>
<img src="assets/images/slideshow.webp" width="400"/>


Download for Mac / Windows:
--------
### https://saucellc.io/products/sauce4zwift/download

If you want a Linux build let me know and I'll consider doing releases for it too.
All my development happens on a Linux machine, I just don't know how much interest
people will have in it.


Feature Highlights
--------
 * Draft %:
   * Don't ask me how it's used in the engine, I don't know, but it's infinitely
     interesting and everyone loves it.
 * Groups view:
   * See the size of your group and others nearby
   * Show the time gap to the groups ahead and behind
   * Accurate gap measurement with virtual checkpoints.  All road positions are
     continually recorded with timestamps for all nearby riders.  The gaps are
     real values from when riders crossed the same point.  Geometric based estimates
     are only used as a fallback when road positions are not yet available (rare).
 * Real stats:
   * Average and Max for power, HR, cadence, speed and event draft
   * Rolling Averages (5s, 5min, etc) for most metrics (power, hr, etc)
   * Peak Averages (5s, 5min, etc) for most metrics (power, hr, etc)
   * NP, TSS, kJ
   * Laps
 * Highly configurable:
   * Dynamic scaling of almost every component to suit all needs
   * Chroma key support for OBS streamers
   * Almost every field can be changed
   * Pick and choose which windows you want visible and configure each of them with unique custom settings
 * Gauges:
   * Power (with zones), Draft, Speed, HR
 * Improved chat client:
   * Avatar
   * Gap to athlete
   * Real time power, hr of athlete
   * Support to mute people
 * Nearby riders/runners table with extensive field options.
 * Web server access to all the widgets.
   * Port 1080 by default (configurable) e.g. http://localhost:1080
   * REST / WebSocket API for programmers


Release Notes
--------
https://saucellc.io/products/sauce4zwift/release_notes


Disclaimer
--------
I don't work for Zwift nor do I represent them.  I assume no liability bla
bla bla.  You get the idea.


Support the creator of Sauce 4 Zwift
--------
<a href="https://www.patreon.com/bePatron?u=32064618" target="_blank">
    <img src="pages/images/become_a_patron_button@2x.png" width="150"/>
</a>
