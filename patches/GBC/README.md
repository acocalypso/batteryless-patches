Supported Cartridges for Pokemon
```
Pokemon Gold en
AAA/A9

Pokemon Gold de
555/A9

Pokemon Silver en
AAA/A9

Pokemon Silver de
555/A9

Pokemon Crystal en Benn Venn Patched
AAA,A9
```
How to check if your cartridge supports that patch:

### FlashGBX
Open up FlashGBX -> Detect Cartridge -> Details

Flash ID Check will provide you the needed information
```
[     ROM     ] F3 C3 00 01 00 00 00 00 
[WR   / AAA/A9] 02 02 7D 7D 00 00 08 08 
[WR   /4AAA/A9] 02 02 7D 7D 00 00 08 08 
[WR   /7AAA/A9] 02 02 7D 7D 00 00 08 08
```
Here you can see if the method is supported.

### BGB Emulator
- Start the dumped game (patched game) 
- Save -> game should freeze
- Press ESC to open the debugger

you should see something similiar:
![image](https://user-images.githubusercontent.com/2846629/160379891-e8101086-4796-4472-bad1-337c6b0dd8f3.png)

The green highlighted lines are the information you are looking for.

F.e 
Pokemon Gold en would work on the cartridge
Pokemon Gold de would not as the method is 555/A9
