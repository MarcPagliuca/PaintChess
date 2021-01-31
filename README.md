# PaintChess

Paint Chess is a concept combining both Splatoon and Chess into one game. You have 2 goals either playing chess normally in under 30 shared turns OR you win by painting the most tiles. 

The paint works in areas, meaning you combine all the ranks and files together. 

Knights paint 6 tiles, Bishops and Queens are very powerful and can paint an entire board when moving diagonally. Totally a feature not a bug, though this seemed to be more fun and interesting.

From testing, good strategies involve playing aggresively at the end game to sneak in and score the most paint, or distract the opponent with beutiful colours and forget they're playing normal chess and checkmating them. That also seems to work lol. 

NOTE: There is a bug where if you drag and let go of your piece it paints the tiles accidentally (only to your end if you do it, it doesn't show on the opponent's side) so please be careful when accurately measuring the score

This uses MIT Licensed code from Radek Lžičař (rlzicar on Github) to do most of the groundwork including multiplayer (Photon Unity Networking 2 (PUN 2)) and special rules for chess. Without it I wouldn't be able to do this, so thanks if you are reading this!

![PaintChess_Screenshot01](https://user-images.githubusercontent.com/25293097/106382890-9530e600-6416-11eb-8044-ebdb1f5177e0.jpg)

Building:
(This is if you want to test the multiplayer yourself. You'll need a Photon Engine account which is free)
1. Open project using Unity 2019.2.2f1
2. Import PUN 2 from the Asset Store into the project (https://assetstore.unity.com/packages/tools/network/pun-2-free-119922)
3. Configure your App Id in PhotonServerSettings.asset (How to Obtain Your App ID). This can be found in Assets\Photon\PhotonUnityNetworking called: PhotonServerSettings.asset
4. Build and test the game

Credits:
Radek Lžičař (for the use of rlzicar/Chessticle open source code)
Cburnett for the chess piece graphics (License: CC BY-SA 3.0)

Designed by Marc Pagliuca
Thanks for reading,
You're cool!
