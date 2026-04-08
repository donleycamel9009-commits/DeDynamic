# DeDynamic
Repo for the DeDynamic Roblox Module. Removes dynamic heads and brings back classic faces.

See youtube channel for tutorial on setup and use.

>>> https://youtube.com/@thew_rblx?si=wJZDNqQaxYAkeHJm <<<

DeDynamic works by comparing a dynamic head's AssetId from the Roblox Catalog, and replacing it with it's Classic Face equivalent.
Ideally this would just be a free model on Roblox, but because of restrictions on AssetService and InsertService its inelligble for sharing.

This script does use InsertService:LoadAsset() and AssetService:GetBundleDetailsAsync() STRICTLY FOR LOADING ALREADY PURCHASED AND EQUIPPED ACESSORIES ONTO A PLAYERS IN-GAME CHARACTER. There is no kind of malware, backdoors, or any intent of bypassing Roblox TOS. AssetService:GetBundleDetailsAsync() is used solely for the purpose of grabbing essential data from the dynamic heads on catalog, and InsertService:LoadAsset() is used only for loading accessories onto a player's new head. This script does not in any way grant player's free items, nor does it work to bypass paywalls set up by Roblox. It simply takes what the player has already purchased and equipped, and applies those assets to their avatar. 

Contributions made are monitored and screened to ensure absolutely no foul play or ill intent. 
Feel free to look over all the code, and ensure it will work for your game before adding this script.




