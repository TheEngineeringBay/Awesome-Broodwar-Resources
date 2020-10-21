<div align="center">
  <h1>
    Awesome Broodwar Resources
  </h1>

![](https://badgen.net/github/last-commit/TheEngineeringBay/Awesome-Broodwar-Resources)
</div>


## Uncategorized
- [OpenBW](https://github.com/OpenBW/openbw): An open source port of Starcraft: Broodwar 1.16.1 written in C++.
  - [Website](http://www.openbw.com/)

## Replays
- [BWChart](https://bwchart.wordpress.com/): A Starcraft Broodwar replay analyzer.
- [OpenBW Online Replay Viewer](http://www.openbw.com/replay-viewer/): An online replay viewer backed by OpenBW compiled to Javascript.
- [StarData](https://github.com/TorchCraft/StarData): A 365GB replay dataset for AI training (65646 games).

## Mapping and Modding
- [Staredit.net](http://www.staredit.net/): Mapping and modding community forum and map/mod/tool hosting.
  - [Staredit.net Discord](https://discord.gg/rKs3NDc)

### Map Editors
- [Chkdraft](https://github.com/jjf28/Chkdraft): A C++ map editor based on ScmDraft 2 which contains distinct modules for map and chk manipulation that can be utilized by other projects.
- [ChkForge](https://github.com/heinermann/ChkForge): A C++ map editor primarily backed by Chkdraft, OpenBW, and Qt.
- [ScmDraft 2 - Stormcoast Fortress](http://www.stormcoast-fortress.net/): ScmDraft 2 homepage with some modding tools and resources.
 
### Map Triggers (Use Map Settings)
- [EUD Editor](https://github.com/Buizz/EUDEditor): A GUI for doing complex actions in triggers that would require the use of EUD (Extended Unit Deaths). Written in VB.
- [EUD Editor 3](https://github.com/Buizz/EUD-Editor-3): The successor to EUD Editor which also works for Starcraft: Remastered. Written in VB.NET.
- [euddraft](https://github.com/phu54321/euddraft): Tool/frontend for eudplib used to compile the language into a map
  - [eudplib](https://github.com/phu54321/eudplib): A programming language library based on EUD (Extended Unit Death) triggers, similar to Python syntax
- [LangUMS](https://github.com/LangUMS/langums): Programming language and compiler for StarCraft: Brood War triggers, similar to C syntax
- [LIT](http://www.staredit.net/topic/16432/): Lua Interpreted Triggers - Another triggering language based on Lua.
- [llvm-bw](https://github.com/heinermann/llvm-bw): In progress C++ to Broodwar EUD triggers transpiler.
- [Oreo Triggers](https://github.com/brandonlilly/oreo-triggers): Oreo is another triggering language that compiles to map triggers, based on PHP.
- [TrigEditPlus](https://github.com/phu54321/TrigEditPlus): A triggering plugin for ScmDraft 2.
- [YATAPI](https://github.com/sethmachine/yatapi): Yet Another Triggering API - as the name states, based on Python.

### Archive Management
- [Ladislav Zezula's Website](http://www.zezula.net/en/fstools/main.html): Home of MPQ and CASC archive editors which are formats used by Blizzard.
  - [CascLib](https://github.com/ladislav-zezula/CascLib): C/C++ library for CASC archive manipulation.
  - [StormLib](https://github.com/ladislav-zezula/StormLib): C/C++ library for MPQ archive manipulation.


## AI (Artificial Intelligence)
- [sc-docker](https://github.com/Games-and-Simulations/sc-docker): Starcraft 1.16.1 docker image set up for AI vs AI fights
- [StarCraft AI Wiki](http://www.starcraftai.com/): A Wiki for all things StarCraft AI.

### APIs and Wrappers
- [BWAPI](https://github.com/bwapi/bwapi): The BroodWar API, used to create AI that can play Broodwar through C++.
- [BWMirror](https://github.com/vjurenka/BWMirror): A Java wrapper for BWAPI.
- [JBWAPI](https://github.com/JavaBWAPI/JBWAPI): A more up-to-date Java wrapper for BWAPI.
- [TorchCraft](https://github.com/TorchCraft/TorchCraft): A bridge between [Torch](https://en.wikipedia.org/wiki/Torch_%28machine_learning%29) and Starcraft.
- [TorchCraftAI](https://github.com/TorchCraft/TorchCraftAI): An AI platform for Torchcraft.

### Utility Libraries
- [BWEB](https://github.com/Cmccrave/BWEB): BroodWar Easy Builder is a building placement manager written in C++ that depends on BWEM.
- [FAP](https://github.com/N00byEdge/FAP): An AI combat simulation library.
- [ASS](https://github.com/JavaBWAPI/ass): Agent Starcraft Simulator - A Java based combat simulation library.

### Terrain Analysis
- [BWEM](http://bwem.sourceforge.net/): BroodWar Easy Map - A much faster terrain analyzer than BWTA.
- [BWTA](https://code.google.com/archive/p/bwta/): BroodWar Terrain Analyzer written in C++, depends on BWAPI and some geometry libraries. (obsolete)
- [BWTA2](https://bitbucket.org/auriarte/bwta2): The successor to BWTA.
- [StarDraft](https://github.com/davechurchill/stardraft): A C++ Starcraft map visualizer.

### Competitions
- [AIIDE](http://www.starcraftaicompetition.com/): AAAI Conference on Artificial Intelligence and Interactive Digital Entertainment
- [IEEE CoG](https://cilab.gist.ac.kr/sc_competition/): The IEEE Conference on Games
- [SSCAIT](https://sscaitournament.com/): Student StarCraft AI Tournament, AI community open to more than just students.
  - [SSCAIT Discord](https://discord.gg/quCtpKe)
- [AIST](https://sites.google.com/view/aistarcrafttournament/aist) A human style structure (double elim BO3 / BO5) annual AI tournament


### Bots
- [AIUR](https://github.com/richoux/AIUR): Artificial Intelligence Using Randomness. An older C++ bot that plays Protoss.
- [Arrakhammer](https://github.com/avan994/Arrakhammer): Zerg bot forked from Steamhammer.
- [Ecgberht](https://github.com/Jabbo16/Ecgberht): A Terran bot written in Java using BWAPI4J.
- [Iron](http://bwem.sourceforge.net/Iron.html): A relatively strong Terran bot.
- [LetaBot](https://github.com/MartinRooijackers/LetaBot): A Terran bot forked from UAlbertaBot that uses build orders found on TeamLiquid.
- [Locutus](https://github.com/bmnielsen/Locutus): A C++ Protoss bot forked from Steamhammer.
- [McRave](https://github.com/Cmccrave/McRave): A general C++ bot.
- [Overkill](https://github.com/sijiaxu/Overkill): A C++ Zerg bot.
- [PurpleWave](https://github.com/dgant/PurpleWave): A Zerg bot written in Scala.
- [Stardust](https://github.com/bmnielsen/Stardust): A relatively strong and recent C++ Protoss bot.
- [Steamhammer](http://satirist.org/ai/starcraft/steamhammer/): Primarily a C++ Zerg bot forked from UAlbertaBot.
- [Stone](http://bwem.sourceforge.net/Stone.html): A SCV rushing bot that depends on BWEM.
- [UAlbertaBot](https://github.com/davechurchill/ualbertabot): A decent bot developed by Dave Churchill out of the University of Alberta, written in C++.
- [ZZZKBot](https://github.com/chriscoxe/ZZZKBot): C++ Zerg bot.
