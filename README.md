# Guide
1. Open Cheat Engine and select the game process (Only for Terraria 1.4.4.9)
2. Select the value type "Array of byte" and insert the following array: 
`8B 4D E8 39 09 E8 ?? ?? ?? ?? 85 C0 74 16`. Click First Scan.
3. 1 address should be found, selected it to the addresslist.
4. Enter any world in the game or, if you are already there, skip to step 5.
5. Right-click on this address and select "Disassemble this memory region"
6. Now you should see something like this
![picture](https://github.com/minost52/Terraria_Fullbright_CheatEngine/blob/main/picture.png)
7. We are interested in the end of the array that is written in step 2. You can see the similarities in the bytes column: 8B 4D E8, etc. The array ends at 74 and 16. **You need to right-click on the row with bytes 57 and select "Replace with code that does nothing"**
![picture](https://github.com/minost52/Terraria_Fullbright_CheatEngine/blob/main/picture2.png) **Do the same for the row with byte FF 75 0C.**
The table should look like this
![picture](https://github.com/minost52/Terraria_Fullbright_CheatEngine/blob/main/picture3.png)
8. hehehehehehehe
![picture](https://github.com/minost52/Terraria_Fullbright_CheatEngine/blob/main/picture4.png)