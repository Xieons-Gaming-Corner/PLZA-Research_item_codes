# Legends ZA Item Codes
These files represent individual Legends ZA item codes for use with cheat tools on Switch CFW. I have been told these are compatible with emulation tools as well, however I cannot confirm.

I have manually tested all of these codes to confirm they do not cause save corruption.

## How to Use
The provided files should not be used as is unless you only need a very specific set of items and only those items.

1. Download the text file located in the folder matching the version of the game you are running (at time of writing, the only version available is 1.0.1 as that is the version I am playing/testing).
2. Open the downloaded file in a text editor.
3. Copy the desired item codes from the text files in the root of this repository into the downloaded text file. Save the file when you are finished.
4. Copy the downloaded text file into the following directory on your Switch: `atmosphere/contents/0100F43008C44000/cheats/`
  If the directory does not exist, create it manually.
5. Launch the game and press `L + Down + Right Stick` to open the cheat menu.

If you have an existing cheats file, you can add the item codes to the existing file.

If you are using Edizon overlay to manage your cheats, you can put cheats into subfolders in the cheat menu for better organization. I have included the section tags to make this work in the item code files. To use them in your cheat file, simply put section open and close tags around the codes you wish to put into a folder. For example:

```
[--SectionStart:XP/Leveling Items--]
00000000 00000000 00000000

[990x Rare Candy]
580F0000 041F0A60
780F0000 00000338
640F0000 00000008 00000002
580F0000 041F0A60
780F0000 0000033C
640F0000 00000008 000003DE

[990x Exp. Candy XL]
580F0000 041F0A60
780F0000 00004698
640F0000 00000008 00000002
580F0000 041F0A60
780F0000 0000469C
640F0000 00000008 000003DE

[--SectionEnd:XP/Leveling Items--]
00000000 00000000 00000000
```

The following will put the '990x Rare Candy' and '990x Exp. Candy XL' codes into a sub folder called "XP/Leveling Items" in the cheat menu.

## Credits
[Stoned](https://gbatemp.net/members/stoned.347253/) - Created the original known-wgood item codes that these item codes are based on.

All further work is my own. I took the full list of Gen9 item indexes and after adjusting the index to align with what we know of Legends ZA, I created a full list of codes for each of those indexes. I then tested the codes of items known to be in ZA and those suspected to be in the game, verifying that the codes added the item as described and that the codes did not corrupt the save file after use, regardless of prior item acquisition.
Following this, I then generated a further 500 indexes after the known end of the Gen9 item list, created codes for those 500 indexes and tested each one in game to confirm the item IDs for the items newly added in Legends ZA. As a result all inventory items newly added in ZA should be represented in the codes above.
Lastly, I manually tested each TM index to ensure the names of the codes matched the given TM, as the Gen9 TM numbers do not line up with ZA TM numbers based on indexes.

I am fine with these codes being posted elsewhere, however I ask that if you do so, please credit me (envyUK or entropiccodes) and/or link back to this repository.
