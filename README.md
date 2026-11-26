# XBLIG Marketplace client

[Download the latest Windows x64 client](https://github.com/famousstu-beep/xblig-marketplace-client/releases/latest).

Extract the entire ZIP and run **Marketplace.exe**. Unity is not required. The public client is a **release build**, with Development Build, script debugging and profiler connection disabled.

## Automatic updates

Install the **latest client** manually once if you are using a build older than **2026.11.26.1**. After that, Marketplace checks for newer clients at startup and every 30 minutes, downloads verified updates automatically, and offers **Restart to update**. Updates wait until games and downloads are closed. Saves, profiles and installed games are preserved. You can disable automatic downloads or check manually under **Settings → Updates**.

Game packages update separately: changed installed games show **Update** in **Downloads**, with a notification in Marketplace. Select Update to install the latest package and keep your saves. A game that requires a newer client asks you to update Marketplace first.

## Included dashboards

Original Xbox 5960, Xbox 360 Blades, NXE, Kinect and Metro are included in the client. Open **Dashboards → Play**. The Metro avatar editor is included too. No separate dashboard download or package installation is needed. Personal profiles, saves and writable console disks stay in your user data folder.

Original Xbox Live is unavailable, and some original Xbox 360 service screens remain unsupported. Shared Marketplace services use the Marketplace guide. These are runtime limitations, not missing download packages.

## Game downloads

All game packages and the live catalogue are kept together in the separate [game downloads repository](https://github.com/famousstu-beep/xblig-marketplace-downloads). The client downloads, verifies and installs **End Of Days Infected Vs Mercs**, **Avatar Paintball**, **1 vs 100**, **Bully: Scholarship Edition**, and **20 Games to Play With Your Mates**.

Choose a category and game, select **Download**, then **Play** when installation finishes. The catalogue refreshes at startup, or use **Add Games → Refresh game catalogue**. Bully's three parts download automatically; allow at least 9 GB free for its download and installation.

## Paired updates

Update both the client and the affected game package. Replacements are published and verified before old downloads are removed. Keep using these two repositories; a new version does not create another repository.

Bully r3 shortens joined-checkpoint paths and offers **JOIN WITHOUT CHECKPOINT**, which uses an isolated copy of your own progress without requesting the host save. Repeated failed mission starts return to Marketplace with recovery guidance. **Full Bully campaign synchronization remains incomplete**; differing campaign progress can still prevent joining. This is not a verified four-player campaign release.

Windows x64 and the [Microsoft Visual C++ x64 runtime](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist) are required. Instructions and SHA-256 checksums accompany each release. Personal saves and account profiles are not distributed.

## Xbox One, Xbox Series X|S and coming-soon listings

Client **2026.11.26.2** adds Xbox One and Xbox Series X|S catalogue categories. GTA 6 appears under Xbox Series X|S with the supplied cover and **Coming soon** visible throughout its short cover animation. This is a catalogue preview; it does not download or install GTA 6 or add Xbox One/Series game execution. Existing game packages are unchanged.

Coming-soon entries use a separate `upcoming` catalogue array so older clients can continue reading the five published game downloads. Upgrade the client to see the new categories and preview. The original Xbox One dashboard is not implemented or included; any future working version will be a separate download.

