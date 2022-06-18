THIS PROJECT REQUIRES SETUP!

Open project in Unreal Engine
Go to Edit - Project Settings - Online Subsystem EOS

Edit Default Artifact Name
Add an artifact and set all ids/secrets
Use product data which was set up in the Epic Games Developer Portal https://dev.epicgames.com/

IMPORTANT: Make sure the product has its client policy type set to "Peer2Peer"!

Close Unreal Engine

In subfolder "Config", edit DefaultEngine.ini

Change
[OnlineSubsystemEOS]
bEnabled=false

to
[OnlineSubsystemEOS]
bEnabled=true

Have fun!

Copyright 2022 by Lothar May
https://www.maygames.net/