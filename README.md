# BeatSaverUpdater
Alerts you of updates to maps and updates them to the latest version.

**Features**:
- Shows a button above a map if it is outdated, clicking on it will download an updated version
- Option to delete old map after download and migrate its references (all favourites and non syncable playlists will have the map replaced)

**Important:** 
- This uses a cache of the BeatSaver database by default (using SongDetailsCache) so map updates won't show up immediately! If you have SongDetailsCache installed and would like to turn this behaviour off, you can do so in Mod Settings. IF you don't have SongDetailsCache, this shouldn't apply to you.
- This only accounts for maps that use BeatSaver's update feature and are uploaded on the same key. Reuploads do not count as an updated map.

## Download
Download the latest version of the mod [here](https://github.com/ibillingsley/BeatSaverUpdater/releases/latest "here").
To install, move the dll to your Plugins folder.

**SongCore**, **BeatSaberMarkupLanguage (BSML)**, **SiraUtil** and **SongDetailsCache** are required for this mod, so please download the latest version from ModAssistant.

## Issues and Support
If you encounter any issues with this mod, file an Issue on GitHub and I'll fix it as soon as I can. For support with the mod, DM me or ask a question on the #pc-help channel on the BSMG discord

## Contribution
If you're a developer and would like to contribute to this mod, your contributions are welcome! Just submit a PR and I will take a look at it.

![Screenshot](https://github.com/user-attachments/assets/01e4b46c-37f0-4232-8673-320ecf4a710f)


## A note on how this fork was made

I'm not a professional programmer. I do some Android development, but Unity/Harmony
modding is new to me, so I know just enough to spot when something has gone wrong and
roughly how to fix it.

This fork's changes were made with AI assistance. I direct the work, review what it
produces, and test everything on real hardware before it goes into a release. I'm
sharing this because I'd rather be upfront about it than have you wonder. This
disclaimer covers this fork's own changes only — the original mod is the work of its
original author(s).

I understand not everyone is comfortable with AI-assisted code, and that's a fair
position; a lot of people here have spent years building real expertise. If you'd
rather check things yourself, everything is open and the commits are small. Bug
reports, reviews and corrections are very welcome, and I'll fix what I get wrong.
