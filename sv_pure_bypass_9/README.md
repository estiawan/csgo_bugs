## sv\_pure bypass \#9

A slightly different exploit - works only on non-official servers. That means it works on any community server, ESEA (note: untested), ~~Faceit~~ (fixed), ~~Esportal~~ (fixed) etc.

**Note**: Still works as of 28th January 2021.

### Steps

1. Extract the [`materials.zip`](https://fromsmash.com/UPOFNGkRXq-dt) file inside the `csgo` directory.
2. Launch CS:GO.
3. Load an offline map you will be connecting to later.
4. Connect to any non-official server. It can run `sv_pure 1` - it does **not** have any effect!
5. Profit!

On Mirage you can see both Ts and CTs through walls. Additionally, enjoy looking through bench on B.

### How it works?

When connecting to an offline server, CS:GO loads *some* VMTs inside the `materials` directory. When you try to play official matchmaking, you will get `third party files have been loaded` error. But it doesn't happen when you connect to a non-official server!

### Screenshots

![image](https://user-images.githubusercontent.com/36894700/101847854-791a7200-3b54-11eb-88a1-38c43de5f61a.png)

![image](https://user-images.githubusercontent.com/36894700/101848012-c72f7580-3b54-11eb-8ac6-c51cf3e535ae.png)

### Credits

* [@szmarczak](https://github.com/szmarczak) for discovering the bug.
