# crash-log
---- Minecraft Crash Report ----
// My bad.

Time: 03/02/17 1:26 PM
Description: Rendering Block Entity

java.lang.NullPointerException: Rendering Block Entity
	at com.voxelmodpack.hdskins.HDSkinManager.getSkinLocation(HDSkinManager.java:64)
	at bhk.redirect$onBindTexture$0(SourceFile:28)
	at bhk.a(SourceFile:86)
	at bhk.a(SourceFile:38)
	at bhk.a(SourceFile:21)
	at bhc.a(SourceFile:114)
	at bhc.a(SourceFile:102)
	at bfr.a(SourceFile:615)
	at bfk.a(SourceFile:1244)
	at bfk.b(SourceFile:1149)
	at bfk.a(SourceFile:1002)
	at ave.av(SourceFile:915)
	at ave.a(SourceFile:325)
	at net.minecraft.client.main.Main.main(SourceFile:124)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:483)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at com.voxelmodpack.hdskins.HDSkinManager.getSkinLocation(HDSkinManager.java:64)
	at bhk.redirect$onBindTexture$0(SourceFile:28)
	at bhk.a(SourceFile:86)
	at bhk.a(SourceFile:38)
	at bhk.a(SourceFile:21)

-- Block Entity Details --
Details:
	Name: Skull // alo
	Block type: ID #144 (tile.skull // ajm)
	Block data value: 5 / 0x5 / 0b0101
	Block location: World: (-433,67,-518), Chunk: (at 15,4,10 in -28,-33; contains blocks -448,0,-528 to -433,255,-513), Region: (-1,-2; contains chunks -32,-64 to -1,-33, blocks -512,0,-1024 to -1,255,-513)
	Actual block type: ID #144 (tile.skull // ajm)
	Actual block data value: 5 / 0x5 / 0b0101
Stacktrace:
	at bhc.a(SourceFile:114)
	at bhc.a(SourceFile:102)
	at bfr.a(SourceFile:615)
	at bfk.a(SourceFile:1244)
	at bfk.b(SourceFile:1149)

-- Affected level --
Details:
	Level name: MpServer
	All players: 2 total; [bew['pirate40'/1343751, l='MpServer', x=-451.42, y=73.00, z=-531.30], bex['Gridino_Gamer'/503456, l='MpServer', x=-449.48, y=75.27, z=-533.07]]
	Chunk stats: MultiplayerChunkCache: 289, 289
	Level seed: 0
	Level generator: ID 00 - default, ver 1. Features enabled: false
	Level generator options: 
	Level spawn location: 0.00,64.00,0.00 - World: (0,64,0), Chunk: (at 0,4,0 in 0,0; contains blocks 0,0,0 to 15,255,15), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,0,0 to 511,255,511)
	Level time: 383773474 game time, 1216444 day time
	Level dimension: 0
	Level storage version: 0x00000 - Unknown?
	Level weather: Rain time: 0 (now: false), thunder time: 0 (now: false)
	Level game mode: Game mode: adventure (ID 2). Hardcore: false. Cheats: false
	Forced entities: 14 total; [bex['Gridino_Gamer'/503456, l='MpServer', x=-449.48, y=75.27, z=-533.07], uo['entity.ItemFrame.name'/5447, l='MpServer', x=-432.97, y=68.50, z=-513.50], uo['entity.ItemFrame.name'/5448, l='MpServer', x=-432.97, y=68.50, z=-514.50], uo['entity.ItemFrame.name'/5449, l='MpServer', x=-432.97, y=68.50, z=-515.50], bew['pirate40'/1343751, l='MpServer', x=-451.42, y=73.00, z=-531.30], wi['Policeman Pam'/6186, l='MpServer', x=-438.75, y=137.50, z=-521.59], uo['entity.ItemFrame.name'/5450, l='MpServer', x=-432.97, y=68.50, z=-516.50], uo['entity.ItemFrame.name'/5451, l='MpServer', x=-432.97, y=68.50, z=-517.50], uq['Painting'/2352, l='MpServer', x=-471.50, y=64.00, z=-156.97], wi['§6Receptionist'/483216, l='MpServer', x=-446.28, y=66.00, z=-523.47], bex['Gridino_Gamer'/503456, l='MpServer', x=-449.48, y=75.27, z=-533.07], wi['Nice Nina'/6202, l='MpServer', x=-440.41, y=137.00, z=-524.72], wi['§6Barista'/483196, l='MpServer', x=-471.53, y=66.00, z=-514.47], wi['Robin'/6171, l='MpServer', x=-440.38, y=137.00, z=-521.31]]
	Retry entities: 0 total; []
	Server brand: BungeeCord (git:BungeeCord-Bootstrap:1.8-SNAPSHOT:79dbdea:unknown) <- Spigot
	Server type: Non-integrated multiplayer server
Stacktrace:
	at bdb.a(SourceFile:309)
	at ave.b(SourceFile:2311)
	at ave.a(SourceFile:334)
	at net.minecraft.client.main.Main.main(SourceFile:124)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:483)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)

-- System Details --
Details:
	Minecraft Version: 1.8.9
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_25, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 223106632 bytes (212 MB) / 456241152 bytes (435 MB) up to 1060372480 bytes (1011 MB)
	Mod Pack: 1.8.9-SNAPSHOT-r08134E7-b8-2016-04-14_16-33-58
	LiteLoader Mods: 2 loaded mod(s)
          - Mine Little Pony version 1.8.9.0
          - HD Skins version 4.0.0
	LaunchWrapper: 10 active transformer(s)
          - Transformer: org.spongepowered.asm.mixin.transformer.MixinTransformer$Proxy
          - Transformer: com.mumfrey.liteloader.transformers.event.EventProxyTransformer
          - Transformer: com.mumfrey.liteloader.launch.LiteLoaderTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.CrashReportTransformer
          - Transformer: org.spongepowered.asm.mixin.transformer.MixinTransformer$Proxy
          - Transformer: com.mumfrey.liteloader.transformers.event.EventTransformer
          - Transformer: com.mumfrey.liteloader.common.transformers.LiteLoaderPacketTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.MinecraftTransformer
          - Transformer: com.mumfrey.liteloader.transformers.event.json.ModEventInjectionTransformer
          - Transformer: org.spongepowered.asm.mixin.transformer.MixinTransformer$Proxy
	JVM Flags: 6 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx1G -XX:+UseConcMarkSweepGC -XX:+CMSIncrementalMode -XX:-UseAdaptiveSizePolicy -Xmn128M
	IntCache: cache: 0, tcache: 0, allocated: 13, tallocated: 95
	Launched Version: 1.8.9
	LWJGL: 2.9.4
	OpenGL: GeForce GTX 560 Ti/PCIe/SSE2 GL version 4.5.0 NVIDIA 378.49, NVIDIA Corporation
	GL Caps: Using GL 1.3 multitexturing.
Using GL 1.3 texture combiners.
Using framebuffer objects because OpenGL 3.0 is supported and separate blending is supported.
Shaders are available because OpenGL 2.1 is supported.
VBOs are available because OpenGL 1.5 is supported.

	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'LiteLoader'
	Type: Client (map_client.txt)
	Resource Packs: 
	Current Language: English (US)
	Profiler Position: N/A (disabled)
	CPU: 8x Intel(R) Core(TM) i7 CPU 920 @ 2.67GHz
