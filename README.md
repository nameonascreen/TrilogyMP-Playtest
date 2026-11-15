# TrilogyMP playtest builds

This repo is an [OpenGOAL Launcher](https://opengoal.dev) mod source for TrilogyMP playtest builds.

## Install

You need the OpenGOAL Launcher, Steam running for online play, and ISOs made from your own discs of
Jak 3, Jak II and Jak and Daxter: The Precursor Legacy. Nothing from the games is included here.

1. In the Launcher, install **Jak 3** the normal way, if you haven't already.
2. Go to **Settings > Mods** and add this source URL:

   ```
   https://raw.githubusercontent.com/nameonascreen/TrilogyMP-Playtest/main/mods.json
   ```

3. Go to **Jak 3 > Features > Mods**, pick **TrilogyMP (playtest)** and install it.
4. While it installs, TrilogyMP asks for your Jak and Daxter ISO, then your Jak II ISO. If the window doesn't
   show up, check the taskbar, since it may be behind the Launcher. If Jak 1 or Jak II is already installed in
   the Launcher, it uses that copy and doesn't ask.
5. The first install takes a while because all three games are unpacked and converted.

## Updating

When a new build is out, TrilogyMP's page in the Launcher shows that you're out of date. Pick the newest
version to update. Older builds stay listed, so you can go back to one if a new build breaks something.

## Reporting bugs

In the game's main menu, go to **Options** and turn on **Debug Mode**. When something goes wrong, press **~**
(the key left of 1), describe what happened, save, and send the report zip. With Debug Mode on, crashes and
freezes save a report by themselves.
