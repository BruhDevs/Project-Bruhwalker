# Never forget change the versions in .lua and .version 

------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------
# Example add new luas in Champion table:
```css
Ark_Champs = {
	{Dev = "UnkleArk", Char_Name = "...", FileName = "...", url = "...", IsVip = ...},
}
```
```css
Dev = Developer-Name <--- We need for the Option: Available luas for the currently ingame champion
Char_name = game.local_player.champ_name
FileName = the name from file -->Example.lua<--
url = the Url from your github/lua file
IsVip = true or false
```
------------------------------------------------------------------------------------------------------------------------------
# Example add new luas in Utility and Lib tables:
```css
Ark_Utility = {
	{Char_Name = "Orbwalker", FileName = "Orbwalker.lua", url = "........", IsVip = false},
}

Ark_Lib = {
	{Char_Name = "Prediction", FileName = "Prediction.lib", url = ".........", IsVip = false},
}
```
```css
Char_Name = add the name you want to see in the menu here
FileName = the name from file -->Example.lua<--
url = the Url from your github/lua file
IsVip = true or false
```
-----------------------------------------------------------------------------------------------------------------------------
# Example Draw Message for new DownloadManager Update:
```css
Update_Msg = "..."

Example:
Update_Msg = "IceyBabyLissandra Released"
```
