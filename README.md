# awesome-unity3d
A categorized collection of awesome opensource unity3d resources (including some projects related to game development)

[**Open Source Repositories**](#open-source-repositories)
- [2D](#2d)
- [2D Bones](#2d-bones--ik)
- [3D Bones](#3d-bones--ik)
- [AI](#ai)
- [Analyzer](#analyzer)
- [Animation](#animation)
- [Anti-Cheat](#anti-cheat)
- [Art Tools](#art-tools)
- [Asset Bundle / Addressable Assets](#asset-bundle--addressable-assets)
- [Audio Manager](#audio-manager)
- [Bolt](#bolt)
- [Build Tools and CI](#build-tools-and-ci)
- [Camera](#camera)
- [Character Controllers 2D](#character-controllers-2d)
- [Character Controllers 3D](#character-controllers-3d)
- [Code Gen](#code-gen)
- [Controller Mappings](#controller-mappings)
- [Console](#console)
- [Dependency Injection](#dependency-injection)
- [Document Reader](#document-reader)
- [DOTS](#dots)
- [ECS Framework](#ecs-framework)
- [Editor](#editor)
- [Effect and Shaders](#effect-and-shaders)
- [Effect-Highlighter](#effect-Highlighter)
- [Effect-Ocean](#effect-ocean)
- [Effect-Toon](#effect-toon)
- [Embedding](#embedding)
- [Feedback Libraries](#feedback-libraries)
- [Framework](#framework)
- [Gameplay](#gameplay)
- [Gizmos](#gizmos)
- [Input](#input)
- [Job System](#job-system)
- [Level Editor](#level-editor)
- [Light](#light)
- [Lua](#lua)
- [Lua Utilities](#lua-utilities)
- [Machine Learning](#machine-learning)
- [Media Player](#media-player)
- [Meshes](#meshes)
- [Modding](#modding)
- [Monetization](#monetization)
- [Networking](#networking)
- [Node Graph](#node-graph)
- [Obfuscation](#obfuscation)
- [Package Manager](#package-manager)
- [Physic](#physic)
- [Playable](#playable)
- [Plugins](#plugins)
- [Procedural Generation Systems](#procedural-generation-systems)
- [Pooling System](#pooling-system)
- [Project Management](#project-management)
- [Runtime Editor](#runtime-editor)
- [Scriptable Object](#scriptable-object)
- [Scriptings](#scriptings)
- [Scene Transition](#scene-transition)
- [Serializer](#serializer)
- [Services](#services)
- [Sounds](#sounds)
- [Terrain](#terrain)
- [Theading](#theading)
- [Timeline](#timeline)
- [Tweening](#tweening)
- [Vehicle](#vehicle)
- [UI](#ui)
- [Utilities](#utilities)
- [VR/XR](#vrxr)
- [Web View](#web-view)

[**Assets**](#assets)
- [Icons](#icons)
- [Collections / Forums](#collections--forums--shops)
- [Creation Tools](#creation-tools)
- [Audio](#audio)

[**Articles**](#articles)

[**Books**](#books)

## Open Source Repositories
### 2D
* [Unity2D-Components](https://github.com/cmilr/Unity2D-Components) - A constantly evolving array of Unity C# components for 2D games, including classes for pixel art cameras, events & messaging, saving & loading game data, collision handlers, object pools, and more.
* [DeadSimple-Pixel-Perfect-Camera](https://github.com/cmilr/DeadSimple-Pixel-Perfect-Camera) - An exceedingly easy-to-use pixel perfect orthographic camera script for 2D scenes in Unity. Punch in a few specs and you've got a working pixel perfect camera. It's that easy
* [StaticBluredScreen](https://github.com/mob-sakai/StaticBluredScreen) - Non-realtime (=static) screen blur for Unity. Easy to use background for dialogs
* [AtlasImage](https://github.com/mob-sakai/AtlasImage) - AtlasImage is a graphic component use SpriteAtlas for uGUI. In addition, add useful sprite selector and border editor to the inspector
* [SpriteDicing](https://github.com/Elringus/SpriteDicing) - Extension for Unity game engine to work with diced sprites
* [DataRenderer2D](https://github.com/geniikw/DataRenderer2D) - make mesh like line, polygon, etc in unity3d
* [UnitySpline2D](https://github.com/sinbad/UnitySpline2D) - 2D spline utility for Unity
* [Aseprite Importer for Unity](https://github.com/2YY/aseprite-importer-for-unity) - Generate Animator Controller and Animation Clip from JSON that exported from Aseprite.

### 2D Bones / IK
* [DragonBonesCSharp](https://github.com/DragonBones/DragonBonesCSharp) - DragonBones C# Runtime
* [Spine Runtimes](https://github.com/EsotericSoftware/spine-runtimes) - Collection of Spine runtimes including with Unity3d version.
* [UnityVoxelTools](https://github.com/meniku/UnityVoxelTools) - Collection of Voxel Utilities for Unity

### 3D Bones / IK
* [EZSoftBone](https://github.com/EZhex1991/EZSoftBone) - A simple kinetic simulator for Unity, you can use it to simulate hair/tail/breast/skirt and other soft objects
* [Automatic-DynamicBone](https://github.com/OneYoungMean/Automatic-DynamicBone) - unity bone cloth spring system,base by jobs.
* [Aim-IK](https://github.com/ehsan-mohammadi/Aim-IK) - A Unity package, to procedurally orientate the character's head (and spine) in a direction without using any animation data.
* [Hairibar.Ragdoll](https://github.com/hairibar/Hairibar.Ragdoll) - A package for animating ragdolls through keyframed animations.
* [TurboSequence](https://github.com/LukasFratzl/TurboSequence) - Skeletal Based GPU Crowds for UE5 🚀

### AI
* [Unity Movement AI](https://github.com/antonpantev/unity-movement-ai) - A library of common movement AI scripts known as Steering Behaviors. You can use these scripts to help your NPCs move around your game.
* [Crystal AI](https://github.com/igiagkiozis/CrystalAI) - A Utility AI for C# and Unity
* [EpPathFinding.cs](https://github.com/juhgiyo/EpPathFinding.cs) - A jump point search algorithm for grid based games in C#
* [EpPathFinding3D.cs](https://github.com/juhgiyo/EpPathFinding3D.cs) - A 3D jump point search algorithm for cube based games in C#
* [UnitySteer](https://github.com/ricardojmendez/UnitySteer) - Steering, obstacle avoidance and path following behaviors for the Unity Game Engine
* [A Star Pathfinding for Unity](https://github.com/sharpaccent/Astar-for-Unity) - A Star Pathfinder, 3 axis, multithreaded for Unity
* [openpath](https://github.com/mrzapp/openpath) - Open source pathfinding for Unity
* [unity-path-finding](https://github.com/mattatz/unity-path-finding) - Shortest path finding with Dijkstra's algorithm for Unity.
* [NPBehave](https://github.com/meniku/NPBehave) - Event Driven Behavior Trees for Unity 3D
* [fluid-behavior-tree](https://github.com/ashblue/fluid-behavior-tree) - A pure code behavior tree micro-framework built for Unity3D projects. Granting developers the power to dictate their GUI presentation
* [Unity3d-Finite-State-Machine](https://github.com/thefuntastic/Unity3d-Finite-State-Machine) -
An intuitive Unity3d finite state machine (FSM). Designed with an emphasis on usability, without sacrificing utility
* [Path-Creator](https://github.com/SebLague/Path-Creator) - Path creation asset for Unity game development
* [NavMeshPlus](https://github.com/h8man/NavMeshPlus) - Unity NavMesh 2D Pathfinding
* [NavMeshSurface2DBaker](https://github.com/SharlatanY/NavMeshSurface2DBaker) - NavMeshSurface2DBaker is a Unity Package that provides functionality to bake 2D colliders into NavMeshSurface components.
* [Brainiac](https://github.com/daemon3000/Brainiac) - Behaviour tree editor for Unity3D
* [behaviac](https://github.com/Tencent/behaviac) - behaviac is a framework of the game AI development, and it also can be used as a rapid game prototype design tool. behaviac supports the behavior tree, finite state machine and hierarchical task network(BT, FSM, HTN)
* [ainav](https://github.com/gamemachine/ainav) - Recastnavigation in C#
* [UnityBehaviorTreeImplementation](https://github.com/naelstrof/UnityBehaviorTreeImplementation) - An example of how to implement behavior trees within Unity.
* [unity-navgen](https://github.com/idbrii/unity-navgen) - Tools for working with Unity's NavMeshComponents and generating navmesh: link generation, mesh cleanup, etc.
* [Unity-Character-Mechanism](https://github.com/MorelAntoine/Unity-Character-Mechanism) - Framework aiming to facilitate the code development of a character in Unity
* [CustomNavMesh](https://github.com/jadvrodrigues/CustomNavMesh) - Alternative to Unity's NavMesh system where the agents avoid each other.
* [PathFinder3D](https://github.com/TheCyaniteProject/PathFinder3D) - 3D A* Pathfinding that doesn't need baked navmeshes and can be used with dynamically created terrain (MapMagic or other)
* [UniTaskStateMachine](https://github.com/k-okawa/UniTaskStateMachine) - StateMachine for UniTask. StateMachine Editor Included.
* [NavMeshAvoidance](https://github.com/OlegDzhuraev/NavMeshAvoidance) - About
Custom Nav Mesh Avoidance to replace default one in Unity.
* [CustomNavMesh](https://github.com/jadvrodrigues/CustomNavMesh) - Alternative to Unity's NavMesh system where the agents avoid each other.
* [AICommand](https://github.com/keijiro/AICommand) - ChatGPT integration with the Unity Editor.
* [GOAP](https://github.com/crashkonijn/GOAP) - A multi-threaded GOAP system for Unity3D
* [DotRecast](https://github.com/ikpil/DotRecast) - A port of Recast & Detour, navigation mesh toolset for games, Unity3D, servers, C#
* [UnityBehaviorTreeVisualizer](https://github.com/Yecats/UnityBehaviorTreeVisualizer) - A tool built in Unity that draws a graph representation of behavior trees running in the scene
* [MonoBehaviourTree](https://github.com/Qriva/MonoBehaviourTree) - Simple event driven Behaviour tree for Unity projects
* [N:ORCA](https://github.com/Nebukam/com.nebukam.orca) - ORCA / RVO2 Implementation for Unity — Multithreaded using the job system.

### Analyzer
* [UnityHeapExplorer](https://github.com/pschraut/UnityHeapExplorer) - A Memory Profiler, Debugger and Analyzer for Unity 2019.3 and newer.
* [CrashReporter](https://github.com/nskrkmz/CrashReporter) - This tool is employed to swiftly detect unhandled errors occurring within Unity projects and to save detailed reports of these errors to a remote redis database. (Suitable for beta testing and demo)

### Animation
* [unity-animator-helpers](https://github.com/ashblue/unity-animator-helpers) - A micro-framework for changing Unity 3D's Animator parameters with ScriptableObject(s). Designed to make going from custom scripts to Animator parameters easy. Works with 2D or 3D projects
* [UrMotion](https://github.com/beinteractive/UrMotion) - A flexible motion engine for non time-based animation in Unity
* [Automatic-DynamicBone](https://github.com/OneYoungMean/Automatic-DynamicBone) - Unity bone cloth spring system,base by jobs
* [reanimation](https://github.com/aarthificial/reanimation) - An alternative animator for Unity tailored for traditional animation
* [AnimeTask](https://github.com/kyubuns/AnimeTask) - Task Animation Library for Unity
* [Unity-Procedural-Animation](https://github.com/Sopiro/Unity-Procedural-Animation) - Procedural Animation in Unity
* [unity-antagonistic-controller](https://github.com/edualvarado/unity-antagonistic-controller) - Generating Upper-Body Motion for Real-Time Characters Making their Way through Dynamic Environments 
* [Mesh-Animation](https://github.com/codewriter-packages/Mesh-Animation) - Fast GPU vertex shader based animation library for Unity (VAT, Vertex Animation Texture, Morphing Animation)

### Anti-Cheat
* [SafeValues](https://github.com/ookii-tsuki/SafeValues) - A simple Unity library for cheating prevention

### Art Tools
* [XdUnityUI](https://github.com/itouh2-i0plus/XdUnityUI) - AdobeXd to UnityUI converter
* [Baum2](https://github.com/kyubuns/Baum2) - Psd to Unity UI(uGUI)
* [UnityPSDLayoutTool](https://github.com/GlitchEnzo/UnityPSDLayoutTool) - A tool used to import a Photoshop Documents (.psd files) into the Unity Game Engine.
* [Materialize](https://github.com/BoundingBoxSoftware/Materialize) - Materialize is a program for converting images to materials for use in video games and whatnot
* [Unity Psd Importer](https://github.com/ChemiKhazi/UnityPsdImporter) - Advanced PSD importer for Unity3D
* [StableDiffusionUnityTools](https://github.com/KonH/StableDiffusionUnityTools) - Editor assets generation via Stable Diffusion

### Asset Bundle / Addressable Assets
* [AssetBundleManager](https://github.com/SadPandaStudios/AssetBundleManager) - An asset bundle manager for Unity
* [unity-addressable-importer](https://github.com/favoyang/unity-addressable-importer) - A rule based addressable asset importer
* [KEngine](https://github.com/mr-kelly/KEngine) - A unity asset bundle framework with LGPL license
* [UnityAutoBundles](https://github.com/perholmes/UnityAutoBundles) - Extension to Unity's Addressables for making it easier to distribute large projects and keep mobile download size small.
* [EZAddresser](https://github.com/Haruma-K/EZAddresser) - Automatic addressing system for Unity Addressable Asset System.
* [SmartAddresser](https://github.com/CyberAgentGameEntertainment/SmartAddresser) - Automate Addressing, Labeling, and Version Control for Unity's Addressable Asset System.

### Audio Manager
* [LucidAudio](https://github.com/AnnulusGames/LucidAudio) - Simple audio player for unity
* [Unity_AudioRig](https://github.com/debox-dev/Unity_AudioRig) - Provides better AudioSource management from scripts, pooling, looping, fading, following object in 3d space and more.
* [Unity-Audio-Manager](https://github.com/MathewHDYT/Unity-Audio-Manager) - Plugin, that allows to easily play/change/stop/mute/... sounds in 2D/3D

### Bolt
* [Bolt.Addons.Community](https://github.com/RealityStop/Bolt.Addons.Community) - A community-driven project for extending Unity Bolt

### Build Tools and CI
* [UnityMultiBuild](https://github.com/sinbad/UnityMultiBuild) - Batch build for multiple platforms from within the Unity editor
* [UnityBuildManager](https://github.com/Team-on/UnityBuildManager) - Utility for running builds sequence & pushing them to markets & keeping changelog
* [buildtool](https://github.com/superunitybuild/buildtool) - A powerful automation tool for quickly and easily generating builds with Unity.
* [setup-unity](https://github.com/pCYSl5EDgo/setup-unity) - Set up your GitHub Actions workflow with a specific version of the Unity Editor
* [unity-actions](https://github.com/webbertakken/unity-actions) - Github actions for testing and building Unity projects
* [trimmer](https://github.com/sttz/trimmer) - An editor, build and player configuration framework for the Unity game engine.

### Camera
* [Unity Pixel Camera](https://github.com/ChemiKhazi/UnityPixelCamera) - A resolution independent pixel perfect camera for Unity
* [DeadSimple Pixel-Perfect Camera](https://github.com/cmilr/DeadSimple-Pixel-Perfect-Camera) - An exceedingly easy-to-use pixel perfect orthographic camera script for 2D scenes in Unity. Punch in a few specs and you've got a working pixel perfect camera. It's that easy.
* [Dynamic Multi Target Camera for Unity](https://github.com/lopespm/unity-camera-multi-target) - Concise Unity library which dynamically keeps a set of objects (e.g. players and important objects) in view.
* [FulldomeCameraForUnity](https://github.com/rsodre/FulldomeCameraForUnity) - Fulldome Camera for Unity 2019
* [Unity_SceneCameraController](https://github.com/XJINE/Unity_SceneCameraController) - Control a camera or any other object like SceneView camera.
* [Camera-Shake](https://github.com/gasgiant/Camera-Shake) - Camera shake for Unity

### Character Controllers 2D
* [CharacterController2D](https://github.com/prime31/CharacterController2D) - is similar to the built-in Unity CharacterController component. It has a similar API (mainly a move method that takes a delta movement) and provides a firm base with which to make a super solid controller using Unity's 2D system.
* [Unity 2D Platformer Controller](https://github.com/cjddmut/Unity-2D-Platformer-Controller) - A customizable 2D platformer motor that handles mechanics such as double jumps, wall jumps, and corner grabs. Includes a player controlled prefab that can be dropped into any scene for immediate support.
* [2D-Platformer-Hunter](https://github.com/ta-david-yu/2D-Platformer-Hunter) - A 2D Platformer Controller in Unity
* [Ultimate-2D-Controller](https://github.com/Matthew-J-Spencer/Ultimate-2D-Controller) - A great starting point for your 2D controller. Making use of all the hidden tricks like coyote, buffered actions, speedy apex, anti grav apex, etc

### Character Controllers 3D
* [SuperCharacterController](https://github.com/IronWarrior/SuperCharacterController) - Custom Character Controller for Unity. Fulfills all common character controller functions such as collision detection and pushback, slope limiting and collider ignoring.
* [NaughtyCharacter](https://github.com/dbrizov/NaughtyCharacter) - Third Person Controller for Unity
* [Advanced Rigidbody FirstPerson Controller](https://github.com/Moe-Baker/Advanced-Rigidbody-FirstPerson-Controller) - Rigidbody Based FirstPerson Controller
* [Erbium](https://github.com/mikhomak/Erbium) - Third Person Character Controller for unity
* [unity-genshin-impact-movement-system](https://github.com/Wafflus/unity-genshin-impact-movement-system) - A movement system made in Unity that attempts to replicate Genshin Impact Movement.
* [Project_TCC](https://github.com/unity3d-jp/Project_TCC) - TCC stands for Tiny Character Controller. TCC is the best way to make your own game. This repository contains all packages and examples for TCC projects.

### Code Gen
* [UnityCodeGen](https://github.com/AnnulusGames/UnityCodeGen) - Code Generation Library for Unity Editor

### Controller Mappings
* [Dualshock 3 (PS3)](https://forum.unity.com/threads/ps3-button-map.89288/)
* [Dualshock 4 (PS4)](https://twitter.com/erik_tellier/status/1071457079854944256)
* [Nintendo Joy Con](https://www.reddit.com/r/Unity3D/comments/60wh7g/nintendo_switch_joycon_controller_mapped_for_unity/)
* [Nintendo Pro Controller](https://answers.unity.com/questions/1419842/nintendo-switch-pro-controller-mapping.html)
* [Xbox 360](http://wiki.unity3d.com/index.php?title=Xbox360Controller)
* [Xbox One](https://answers.unity.com/questions/1350081/xbox-one-controller-mapping-solved.html)

### Console
* [Unity3d-BeastConsole](https://github.com/pointcache/Unity3d-BeastConsole) - Console for all your unity needs
* [consolation](https://github.com/mminer/consolation) - In-game debug console for Unity.
* [Lunar Unity Mobile Console](https://github.com/SpaceMadness/lunar-unity-console) - High-performance Unity iOS/Android logger built with native platform UI 

### DOTS
* [unity-ecs-navmesh](https://github.com/zulfajuniadi/unity-ecs-navmesh) - A demo implementation of Unity Entity Component System with NavMesh
* [ECS-Tween](https://github.com/Xerios/ECS-Tween) - Simple Unity tweening system using ECS that works with GameObjects!
* [PlasticTween](https://github.com/PlasticApps/PlasticTween) - Tween Library for Unity3D(ECS+JOBS)
* [unity-jtween](https://github.com/jeffcampbellmakesgames/unity-jtween) - A job-based tween library for Unity
* [KNN](https://github.com/ArthurBrussee/KNN) - Fast K-Nearest Neighbour Library for Unity DOTS
* [SpriteSheetRenderer](https://github.com/fabriziospadaro/SpriteSheetRenderer) - A powerful Unity ECS system to render massive numbers of animated sprites
* [NativeCollections](https://github.com/jacksondunstan/NativeCollections) - Native Collection Types for Unity https://jacksondunstan.com/articles/tag/native-collection
* [EntitySelection](https://github.com/JonasDeM/EntitySelection) - A minimal solution for selecting entities in the unity sceneview.
* [Hydrogen.Entities](https://github.com/periodyctom/Hydrogen.Entities) - A collection of helpers for work with Unity's ECS framework, used in our games.
* [Unity-2D-Pathfinding-Grid-ECS-Job](https://github.com/Omniaffix-Dave/Unity-2D-Pathfinding-Grid-ECS-Job) - ECS Burst Job System 2D Pathfinding
* [EntitySelection](https://github.com/JonasDeM/EntitySelection) - A minimal solution for selecting entities in the unity sceneview
* [Easy-Road-3D-ECS-Traffic](https://github.com/Blissgig/Easy-Road-3D-ECS-Traffic) - Unity DOTS/ECS traffic using Easy Roads 3D for the data
* [IcSkillSystem](https://github.com/yika-aixi/IcSkillSystem) - A simple and reusable skill system
* [EntitiesBT](https://github.com/quabug/EntitiesBT) - Behavior Tree for Unity ECS (DOTS) framework
* [NativeOctree](https://github.com/marijnz/NativeOctree) - An Octree Native Collection for Unity DOTS
* [NativeQuadtree](https://github.com/marijnz/NativeQuadtree) - A Quadtree Native Collection for Unity DOTS
* [UGUIDOTS](https://github.com/InitialPrefabs/UGUIDOTS) - Converting uGUI to be DOTS compliant
* [dotsnav](https://github.com/dotsnav/dotsnav) - A fully dynamic planar navmesh Unity package supporting agents of any size
* [unity-deterministic-physics](https://github.com/Kimbatt/unity-deterministic-physics) - Cross-platform deterministic physics simulation in Unity, using DOTS physics and soft floats
* [ECSPowerNetcode](https://github.com/actionk/ECSPowerNetcode) - Library to power up your experience with the DOTS Unity Netcode.
* [ECSEntityBuilder](https://github.com/actionk/ECSEntityBuilder) - Unity ECS Entity Builder/Wrapper
* [Simple-ECS](https://github.com/AkanshDivker/Simple-ECS) - An example using the core features of the Entity Component System (ECS), part of DOTS, for Unity, inspired by Roll-a-ball. This project utilizes the Unity Physics, Hybrid Renderer, and Entities packages.
* [Unity_ECS_GPUSkinning](https://github.com/dreamfairy/Unity_ECS_GPUSkinning) - ECS boost GpuSkinning
* [UnityDotsCharacterController](https://github.com/ssell/UnityDotsCharacterController) - Basic Character Controller Using ECS and Unity.**Physic**s Packages
* [VertexAnimation](https://github.com/maxartz15/VertexAnimation) - Vertex animation baking tool, shaders and animation system for Unity DOTS/ECS.
* [NSprites](https://github.com/Antoshidza/NSprites) - Unity DOTS Sprite Rendering Package
* [Latios-Framework](https://github.com/Dreaming381/Latios-Framework) - A Unity DOTS framework
* [DMotion](https://github.com/gamedev-pro/dmotion) - A high level Animation Framework for Unity DOTS
* [Spatial-Hashing](https://github.com/Sylmerria/Spatial-Hashing) - Spatial hashing for Unity using ECS/DOTS
* [NativeTrees](https://github.com/bartofzo/NativeTrees) - Burst compatible Octree and Quadtree for Unity
* [Pathfinding](https://github.com/bustedbunny/Pathfinding) - Pathfinding - using Unity Navmesh, ECS and Burst
* [DOTS-Hybrid-Simulation-Worlds](https://github.com/tbg10101/DOTS-Hybrid-Simulation-Worlds) - A framework for using FixedUpdate in a simulation world which is linked to a GameObject-based presentation layer.

### Dependency Injection
* [Zenject](https://github.com/modesttree/Zenject) - Dependency Injection Framework for Unity3D
* [adic](https://github.com/intentor/adic) - Lightweight dependency injection container for Unity
* [CatLib](https://github.com/CatLib/CatLib) - CatLib lightweight dependency injection container
* [VContainer](https://github.com/hadashiA/VContainer) - The extra fast, minimum code size, GC-free DI (Dependency Inject) library running on Unity (IL2CPP).
* [AtreeboosterDI](https://github.com/kubpica/AtreeboosterDI) - The Hierarchy-based Dependency Injection tool for Unity game engine. Intuitivly manage dependencies of your MonoBehaviours with simple but powerfull [Attributes]
* [reflex](https://github.com/gustavopsantos/reflex) - Minimal dependency injection framework for Unity

### Document Reader
* [GoogleSheetsUnity](https://github.com/5argon/GoogleSheetsUnity) - Get data from your private Google Sheets to Unity!! (Read-only)
* [UnityCsvUtil](https://github.com/sinbad/UnityCsvUtil) - Lightweight but type safe CSV serialise/deserialise of objects
* [UnityGoogleDrive](https://github.com/Elringus/UnityGoogleDrive) - Google Drive SDK for Unity game engine
* [UnityEditorGoogleDriveIntegration](https://github.com/yasirkula/UnityEditorGoogleDriveIntegration) - Access your Google Drive™ files from within Unity editor

### ECS Framework
* [Entitas-CSharp](https://github.com/sschmid/Entitas-CSharp) - Entitas is a super fast Entity Component System (ECS) Framework specifically made for C# and Unity
* [ecsrx.unity](https://github.com/EcsRx/ecsrx.unity) - A simple framework for unity using the ECS paradigm but with unirx for fully reactive systems
* [ecs](https://github.com/chromealex/ecs) - ECS for Unity with full game state automatic rollbacks
* [Morpeh](https://github.com/X-Crew/Morpeh) - Fast and Simple ECS Framework for Unity3d
* [NanoECS](https://github.com/SinyavtsevIlya/NanoECS) - c#-Unity ECS framework
* [DefaultEcs](https://github.com/Doraku/DefaultEcs) - DefaultEcs is an Entity Component System framework which aims to be accessible with little constraints while retaining as much performance as possible for game development
* [LeoECS](https://github.com/Leopotam/ecs) - LeoECS is a fast Entity Component System (ECS) Framework powered by C# with optional integration to Unity
* [actors.unity](https://github.com/PixeyeHQ/actors.unity) - Actors is a framework empowering developers to make better games faster on Unity.
* [Arch](https://github.com/genaray/Arch) - A high-performance C# based Archetype & Chunks Entity Component System (ECS) with optional multithreading.
* [Friflo.Engine.ECS](https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md) - High-performance C# ECS 🔥 with simple API. Supports .NET, WASM/WebAssembly, Native AOT, Unity, Godot, MonoGame, ...

### Editor
* [Unity-QuickSheet](https://github.com/kimsama/Unity-QuickSheet) - Unity-QuickSheet enables you to use spreadsheet file data within Unity editor.
* [Unity3D Rainbow Folders](https://github.com/PhannGor/unity3d-rainbow-folders) - This asset allows you to set custom icons for any folder in unity project browser.
* [Reorderable List Editor Field for Unity](https://bitbucket.org/rotorz/reorderable-list-editor-field-for-unity) - Reorderable List Editor Field for Unity
* [Reorderable Inspector](https://github.com/ChemiKhazi/ReorderableInspector) - Automatic reorderable lists for Unity game engine components
* [Vexe Framework (VFW)](https://github.com/vexe/VFW) - an editor extension that offers much more advance editor extensibility features than what comes out of the box with Unity.
* [Tidy Up](https://github.com/Nutshell-Hack/Tidy-Up) - Neat little tool! to help you keep your Unity projects organised by throwing assets in their designated folders.
* [property-drawer-collection](https://github.com/anchan828/property-drawer-collection)
* [unity-symlink-utility](https://github.com/karl-/unity-symlink-utility) - A small extension that adds a menu item to add folders as symlinks in Unity
* [UnityDefineManager](https://github.com/karl-/UnityDefineManager) - Easily manage global defines in Unity
* [Texture3DPreview-for-Unity](https://github.com/raphael-ernaelsten/Texture3DPreview-for-Unity) - This package enables interactive previews of Texture3D assets in Unity's Inspector window.
* [unity-colourlovers-importer](https://github.com/shelleylowe/unity-colourlovers-importer) - Unity editor tool to load colours and palettes directly from COLOURlovers.com
* [shortcuter](https://github.com/intentor/shortcuter) - Shortcut utility for Unity
* [unity-editor-spotlight](https://github.com/marijnz/unity-editor-spotlight) - MacOS-like Spotlight file search in Unity
* [Unity-Reorderable-List](https://github.com/cfoulston/Unity-Reorderable-List) - Extended version of the Reorderable List in Unity
* [UnityEditorJunkie](https://github.com/roboryantron/UnityEditorJunkie) - Editor scripts to make working with the Unity Editor better
* [UniOmni](https://github.com/lochrist/UniOmni) - Global search for Unity
* [Readme](https://github.com/TinyPhoenix/Readme) - Readme component for Unity, attachable to any GameObject to document what you can't in a script or the file system
* [Unity-AssetDependencyGraph](https://github.com/Unity-Harry/Unity-AssetDependencyGraph) - An Asset Dependency Graph for Unity
* [MyBox](https://github.com/Deadcows/MyBox) - MyBox is a set of attributes, tools and extensions for Unity 
* [Unity-Finder](https://github.com/litefeel/Unity-Finder) - Find Asset in Unity.
* [Unity-Editor-Toolbox](https://github.com/arimger/Unity-Editor-Toolbox) - Tools, custom attributes, drawers and extensions for Unity Editor.
* [enhancer](https://github.com/xeleh/enhancer) - A collection of utilities to enhance the Unity Editor
* [EasyEventEditor](https://github.com/Merlin-san/EasyEventEditor) - Drop in replacement for the default Unity event editor drawer that allows listener reordering
* [UnitySceneViewNotification](https://github.com/staggartcreations/UnitySceneViewNotification) - Notification log for Unity's scene view.
* [SearchStringInAssets](https://github.com/baobao/SearchStringInAssets) - SearchStringInAssets is an Editor extension that allows you to search the UnityEditor for strings stored in a scene, Prefab, or ScriptableObject.
* [UnityScreenShooter](https://github.com/Team-on/UnityScreenShooter) - Screenshot utility for Unity runtime & editor
* [CustomToolbar](https://github.com/smkplus/CustomToolbar) - Custom toolbar with ability do add new toolbars and reorganize it
* [SuperEditor](https://github.com/UnitySuperEditor/SuperEditor) - Super Editor is a versatile Unity editor extension that includes a powerful, easy-to-use built-in IDE, Hieararchy enhancements, and Favorites enhancements
* [hierarchy-2](https://github.com/truongnguyentungduy/hierarchy-2) - Editor extension to improve Unity hierarchy window. Makes the hierarchy more detail, but still clean and easy to organize.
* [one-line](https://github.com/slavniyteo/one-line) - One line property drawer for Unity3d
* [NaughtyAttributes](https://github.com/dbrizov/NaughtyAttributes) - Attribute Extensions for Unity
* [unity-toolbar-extender](https://github.com/marijnz/unity-toolbar-extender) - Extend the Unity Toolbar with your own Editor UI code.
* [meshpreview](https://github.com/AscendingMan/meshpreview)
* [unity-mulligan-renamer](https://github.com/redbluegames/unity-mulligan-renamer) - Mulligan Renamer tool for the Unity Editor allows for quick and safe renaming of many assets and gameobjects at once
* [WhatUsesThis](https://github.com/Facepunch/WhatUsesThis) - Right click an asset and get a list of assets that use it
* [Smart-Hierarchy](https://github.com/neon-age/Smart-Hierarchy) - Human-friendly hierarchy for Unity
* [Smart-Inspector](https://github.com/neon-age/Smart-Inspector) - Keeps your screen real-estate clean with refined, compact UX.
* [EasyButtons](https://github.com/madsbangh/EasyButtons) - Add buttons to your inspector in Unity super easily with this simple attribute
* [HierarchyDecorator](https://github.com/WooshiiDev/HierarchyDecorator) - Lightweight Unity Plugin transforming the Hierarchy into what it should be. Adds headers, styles, icons and more.
* [Markup-Attributes](https://github.com/gasgiant/Markup-Attributes) - A Unity Editor extension for customizing inspector layout with attributes.
* [Atlas](https://github.com/david-knopp/Atlas) - Atlas Utility library for Unity
* [LucidEditor](https://github.com/AnnulusGames/LucidEditor) - Powerful Editor Extensions for Unity
* [UnityGitPackageUpdater](https://github.com/QuantumCalzone/UnityGitPackageUpdater) - Easily update Unity packages hosted via git
* [FastScriptReload](https://github.com/handzlikchris/FastScriptReload) - Hot Reload implementation for Unity. Iterate on code insanely fast without breaking play session. Supports any editor. 1. Play 2. Make change 3. See results

### Effect and Shaders
* [Unity 5 Effects](https://github.com/i-saint/Unity5Effects) - Effect storage space for Unity 5.
* [unity-frosted-glass](https://github.com/andydbc/unity-frosted-glass) - frosted glass material made in unity
* [unity-delaunay](https://github.com/OskarSigvardsson/unity-delaunay) - A Delaunay/Voronoi library for Unity, and a simple destruction effect
* [Helicopter effect](https://twitter.com/unity3dexpert/status/1050240849085431808)
* [SSMS](https://github.com/OCASM/SSMS) - Screen space multiple scattering for Unity
* [KinoGlitch](https://github.com/keijiro/KinoGlitch) - Video glitch effects for Unity
* [Temporal](https://github.com/playdeadgames/temporal) - Temporal Reprojection Anti-Aliasing for Unity 5.0+
* [SMAA](https://github.com/Chman/SMAA) - A highly customizable implementation of Subpixel Morphological Antialiasing for Unity
* [Typogenic](https://github.com/Chman/Typogenic) - Signed-distance field text rendering for Unity
* [AtmosphericScattering](https://github.com/SlightlyMad/AtmosphericScattering) - Atmospheric Scattering for Unity
* [HologramShader](https://github.com/andydbc/HologramShader) - Hologram Shader and Material Editor for Unity
* [ShaderlabVS](https://github.com/wudixiaop/ShaderlabVS) - ShaderlabVS is a Visual Studio plugin for Unity Shaderlab programming
* [Kamakura Shaders](https://github.com/kayac/kamakura-shaders) - Kamakura Shaders is a collection of shaders and components focusing on Non-Photorealistic Rendering for Unity with a bunch of features and adjustable parameters in a user-friendly interface.
* [ShaderProject](https://github.com/ellioman/ShaderProject) - A container for all sorts of handy shaders.
* [ShaderForge](https://github.com/FreyaHolmer/ShaderForge) - Shader visual scripting
* [Texture Panner](https://github.com/AdultLink/TexturePanner) - Awesome shader collection
* [AnisotropicStandardShader](https://github.com/Kink3d/AnisotropicStandardShader) - A modified version of Unity's Standard Shader using an Anisotropic GGX BRDF.
* [SpriteGlow](https://github.com/Elringus/SpriteGlow) - A sprite glow effect for Unity game engine
* [Mirror (Script)](https://github.com/nkjzm/Mirror) - A mirror script
* [HoloShield](https://github.com/AdultLink/HoloShield) - Highly customizable sci-fi shield / force field shader for Unity3D. Allows you to set edge power & color, inner texture scrolling, waviness, scale pulsation and procedural intensity noise. Implements tessellation for low-poly base meshes.
* [VerticalDissolve](https://github.com/AdultLink/VerticalDissolve) - Procedural vertical dissolve shader. Highly customizable. Tweak edge color, noisiness & waviness, rim light, emission scrolling and more.
* [SphereDissolve](https://github.com/AdultLink/SphereDissolve) - Customizable procedural spherical dissolve shader for Unity3D, for all your customizable procedural spherical dissolve needs!
* [TexturePanner](https://github.com/AdultLink/TexturePanner) - This repository hosts a shader for Unity3D whose main goal is to facilitate the creation of neon-like signs, conveyor belts and basically whatever based on scrolling textures
* [RadialProgressBar](https://github.com/AdultLink/RadialProgressBar) - Customizable radial progress bar shader for Unity3D. Allows you to set arc range, minimum and maximum colors, textures, radius, and a few more things. Create HP Bars, Speedometers, rank progress, etc!
* [Unity-ShaderSketches](https://github.com/setchi/Unity-ShaderSketches) - Sketches made with ShaderLab in Unity.
* [Unity-Shaders](https://github.com/knapeczadam/Unity-Shaders) - Shader demo - More than 300 examples
* [unity-delaunay](https://github.com/OskarSigvardsson/unity-delaunay) - A Delaunay/Voronoi library for Unity, and a simple destruction effect
* [BNAO](https://github.com/Fewes/BNAO) - A tiny, GPU-based Bent Normal and Ambient Occlusion baker for Unity.
* [ezy-slice](https://github.com/DavidArayan/ezy-slice) - An open source mesh slicer framework for Unity3D Game Engine. Written in C#.
* [UnityPCSS](https://github.com/TheMasonX/UnityPCSS) - Nvidia's PCSS soft shadow algorithm implemented in Unity
* [JourneySand](https://github.com/AtwoodDeng/JourneySand) - An Unity project to reproduce the sand rendering in Journey's style
* [OBNI3D](https://github.com/alexbourgeois/OBNI3D) - Graphical pipeline allowing mesh deformation through shader and 3D noise volume
* [FXAA](https://github.com/AmplifyCreations/FXAA) - FXAA Fast Approximate Anti-Aliasing 
* [AmplifyColor](https://github.com/AmplifyCreations/AmplifyColor) - Full source-code for Amplify Color plugin for Unity
* [AmplifyOcclusion](https://github.com/AmplifyCreations/AmplifyOcclusion) - Full source-code for Amplify Occlusion plugin for Unity
* [AmplifyMotion](https://github.com/AmplifyCreations/AmplifyMotion) - Full source-code for Amplify Motion plugin for Unity
* [X-PostProcessing-Library](https://github.com/QianMo/X-PostProcessing-Library) - XPL : High Quality Post Processing Effects Library For Unity
* [MeshDecal](https://github.com/Fewes/MeshDecal) - A simple mesh decal component for Unity
* [fluviofx](https://github.com/fluviofx/fluviofx) - Fluid dynamics for Unity's VFX graph
* [Unity-Built-in-Shaders](https://github.com/TwoTailsGames/Unity-Built-in-Shaders) - Unity Built in Shaders
* [DynamicDecals](https://github.com/EricFreeman/DynamicDecals) - Decal solution for Unity's Built-In Render Pipeline
* [Unity_LightBeamPerformance](https://github.com/kodai100/Unity_LightBeamPerformance) - This package can create light beam performance with Unity's timeline functionality.
* [NovaShader](https://github.com/CyberAgentGameEntertainment/NovaShader) - Multi-functional shader for the Particle System that supports Universal Render Pipeline (URP) of Unity.
* [MinimalCompute](https://github.com/cinight/MinimalCompute) - Minimal test scenes contains compute shaders, compute buffers etc Playing with the transport between CPU <-> GPU
* [unity-soft-walks](https://github.com/edualvarado/unity-soft-walks) - Soft Walks: Real-Time, Two-Ways Interaction between a Character and Loose Grounds - 2021 - Eurographics (Short-Paper)
* [unity-universal-shadergraph-extensions](https://github.com/Zallist/unity-universal-shadergraph-extensions) - This plugin simply adds a Simple Lit material (SubTarget) to the Universal target for Shader Graph for URP
* [foliage-wind](https://github.com/happy-turtle/foliage-wind) - Foliage wind shader implementations for Unity's render pipelines HDRP and URP. Based on the demo project Book of the Dead by Unity.
* [oit-unity](https://github.com/happy-turtle/oit-unity) - Order-independent Transparency Implementation in Unity with Per-Pixel Linked Lists
* [AmplifyOcclusion-URP](https://github.com/neon-age/AmplifyOcclusion-URP) - Amplify Occlusion V2 ported to URP 2022.2
* [VFX-Lab](https://github.com/neon-age/VFX-Lab) - Shaders and VFX experimentation in URP and BIRP
* [URP_ShaderGraphCustomLighting](https://github.com/Cyanilux/URP_ShaderGraphCustomLighting) - Some custom lighting functions/sub-graphs for Shader Graph, Universal Render Pipeline
* [FSR2Unity](https://github.com/ndepoel/FSR2Unity) - FSR 3.0 Upscaler integration for Unity built-in render pipeline, with support for DX11, Mac, Linux and consoles.
* [HoyoToon](https://github.com/Melioli/HoyoToon) - Shader for Unity (Built-in Rendering Pipeline) attempting to replicate the shading of miHoYo developed games. This is for datamined assets, not custom-made ones nor the MMD variants.

### Effect-Highlighter
* [Outline-Effect](https://github.com/cakeslice/Outline-Effect) - Outline Image Effect for Unity
* [UltimateOutline](https://github.com/Shrimpey/UltimateOutline) - The easiest way to achieve outlines in unity.
* [Outlined-Diffuse-Shader-Fixed](https://github.com/Shrimpey/Outlined-Diffuse-Shader-Fixed) - This is a fixed version of diffused outline shader from http://wiki.unity3d.com/index.php/Outlined_Diffuse_3
* [UnityFx.Outline](https://github.com/Arvtesh/UnityFx.Outline) - Screen-space outlines for Unity3d.
* [Unity-URP-Outlines](https://github.com/Robinseibold/Unity-URP-Outlines) - A custom renderer feature for screen space outlines
* [Facepunch.Highlight](https://github.com/Facepunch/Facepunch.Highlight) - Mesh outline effect
* [dx-highlighter](https://github.com/nothke/dx-highlighter) - A Deus Ex/System Shock inspired pulsing bounds item highlighter for Unity

### Effect-Ocean
* [crest-oceanrender](https://github.com/huwb/crest-oceanrender) - An advanced ocean system implemented in Unity3D
* [Ocean_Community_Next_Gen](https://github.com/eliasts/Ocean_Community_Next_Gen) - Next gen iteration of the unity community ocean shader
* [Ceto](https://github.com/Scrawk/Ceto) - Ceto: Ocean system for Unity
* [FFT-Ocean](https://github.com/gasgiant/FFT-Ocean) - FFT ocean for Unity

### Effect-Toon
* [ToonShading](https://github.com/Kink3d/ToonShading) - A collection of "Toon" shaders for Unity based on a stepped PBR approximation.
* [Arktoon-Shaders](https://github.com/synqark/Arktoon-Shaders) - Alternative Unity shaders made by synqark
* [JasonMaToonRenderPipeline](https://github.com/Jason-Ma-233/JasonMaToonRenderPipeline) - JTRP : Unity HDRP ToonShading Render Pipeline
* [UniToon](https://github.com/yoship1639/UniToon) - Physically-based Toon Shader for game applications. Compliant with Unity standard rendering functions. It is not targeted to be multifunctional in order to keep performance, but to be universally usable.
* [MToon](https://github.com/Santarh/MToon) - Toon Shader with Unity Global Illumination
* [StarRailNPRShader](https://github.com/stalomeow/StarRailNPRShader) - Fan-made shaders for Unity URP attempting to replicate the shading of Honkai: Star Rail.
* [GenshinCelShaderURP](https://github.com/Gaolingx/GenshinCelShaderURP)

### Embedding
* [react-native-unity-view](https://github.com/f111fei/react-native-unity-view) - Show an unity view in react native
* [react-native-unity-view](https://github.com/asmadsen/react-native-unity-view) - This is a fork of https://github.com/f111fei/react-native-unity-view to make it work with React Native >= 0.60.
* [flutter-unity-view-widget](https://github.com/snowballdigital/flutter-unity-view-widget) - Embeddable unity game engine view for Flutter.

### Feedback Libraries
* [Juce-Feedbacks](https://github.com/Juce-Assets/Juce-Feedbacks) - Open-source feedbacks library that's part of the Juce Unity tools framework.

### Framework
* [Fungus](https://github.com/snozbot/fungus) - https://github.com/snozbot/fungus
* [Node_Editor_Framework](https://github.com/Seneral/Node_Editor_Framework) - Node Editor framework for Unity3D
* [uFrame.Complete](https://github.com/uFrame/uFrame.Complete) - All in one repo, includes: Kernel, Designer, Architect, MVVM, ECS
* [QFramework](https://github.com/liangxiegame/QFramework) - Your first K.I.S.S Unity 3D Framework
* [GameFramework](https://github.com/FlipWebApps/GameFramework) - A free framework for Unity that will help drastically increase the development speed and feature set of your games.
* [gocs](https://github.com/lazlo-bonin/gocs) - GameObject Component System for Unity
* [actors](https://github.com/PixeyeHQ/actors) - The Entity Component System framework for Unity. Ease the pain of decoupling data from behaviors
* [Zinnia.Unity](https://github.com/ExtendRealityLtd/Zinnia.Unity) - A collection of design patterns for solving common problems.
* [Red](https://github.com/X-Crew/Red) - Reactive Toolchain for Unity
* [JEngine](https://github.com/JasonXuDeveloper/JEngine) - JEngine is a streamlined and easy-to-use framework designed for Unity Programmers which contains powerful features, beginners can start up quickly and making hot update-able games easily
* [KSFramework](https://github.com/mr-kelly/KSFramework) - KSFramework = KEngine + SLua(or xLua) , Unity3D Framework/Toolsets focus on hot reload
* [UniGame.ViewSystem](https://github.com/UniGameTeam/UniGame.ViewSystem) - MVVM Views System for Unity3D
* [UnityMvvmToolkit](https://github.com/ChebanovDD/UnityMvvmToolkit) - Brings data-binding to your Unity project
* [PlayerLoopInterface](https://github.com/Baste-RainGames/PlayerLoopInterface) - A simple interface for interacting with Unity's player loop system
* [CosmosFramework](https://github.com/DonnYep/CosmosFramework) - CosmosFramework is a medium-lightweight plug-in Unity development framework . Has a rich Unity method extensions and toolchain. async/await syntax support, multi-network channel support.

### Gameplay
* [UnityArcRayCast](https://github.com/williamrjackson/UnityArcRayCast) - Arc raycast utility using projectile formulas
* [UnityGameplayAbilitySystem](https://github.com/sjai013/UnityGameplayAbilitySystem) - A unified framework for implementing ability systems in Unity
* [Inventory-Pro](https://github.com/devdogio/Inventory-Pro) - The best-selling Inventory System for Unity - now free and open-source!
* [Quest-System-Pro](https://github.com/devdogio/Quest-System-Pro) - The powerful Quest and Conversation Tree System for Unity - now free and open-source!
* [lospro](https://github.com/devdogio/lospro) - The Lightweigt Line-of-Sight & Hearing System for Unity - now free and open-source!
* [Inventory](https://github.com/FarrokhGames/Inventory) - A Diablo 2-style inventory system for Unity3D
* [RPGCore](https://github.com/Fydar/RPGCore) - RPGCore is a toolkit for producing RPG games and mechanics for Unity
* [SanAndreasUnity](https://github.com/GTA-ASM/SanAndreasUnity) - Open source reimplementation of GTA San Andreas game engine in Unity
* [NoteEditor](https://github.com/setchi/NoteEditor) - Note editor for rhythm games.
* [FogOfWar](https://github.com/kitepro/FogOfWar) - A plugin for Unity3D to add Fog of War to a game.
* [Unity3d-PhysicsGun](https://github.com/Laumania/Unity3d-PhysicsGun) - Unity3d sample implementation of a Half-life 2 / Garry's mod/ Gmod Physics Gun
* [Piranha](https://github.com/keenanwoodall/Piranha) - A very simple tool to make rigidbodies swarm a mesh in Unity
* [Grapple-Effect](https://github.com/keenanwoodall/Grapple-Effect) - An example of a simple grapple effect in Unity
* [Traverser](https://github.com/AitorSimona/Traverser) - Traverser is a free and open source player traversal toolkit featuring Locomotion, Parkour and Climbing. Includes procedural animation, physical animation, custom motion warping and root motion. It is self-contained in a set of scripts. Use the given abilities or expand the system through its shared ability workflow.
* [ezy-slice](https://github.com/DavidArayan/ezy-slice) - An open source mesh slicer framework for Unity3D Game Engine. Written in C#.
* [UnityTimeRewinder](https://github.com/SitronX/UnityTimeRewinder) - Unity time rewind solution, that is easily customizable for any project.
* [Depiction Engine For Unity](https://github.com/VIZ-Interactive/Depiction-Engine-Unity) - Versatile engine to create and stream large 3D worlds for game or geospatial applications

### Gizmos
* [UGizmo](https://github.com/harumas/UGizmo) - Highly efficient gizmo drawer for Unity.

### Input
* [InputManager](https://github.com/daemon3000/InputManager) - Custom InputManager for Unity
* [InControl](https://github.com/pbhogan/InControl) - An input manager for Unity that tames the cross-platform controller beast.
* [InputBinder](https://github.com/RyanNielson/InputBinder) - Easily bind input events to methods in Unity.
* [TouchKit](https://github.com/prime31/TouchKit) - Gestures and input handling made sane for Unity
* [TouchScript (Recommend)](https://github.com/TouchScript/TouchScript) - Complete multitouch solution for Unity: Win8, TUIO, Mobile.

### Job System
* [ZeroAllocJobScheduler](https://github.com/genaray/ZeroAllocJobScheduler) - A high-performance alloc free c# Jobscheduler.

### Level Editor
* [Tiled2Unity](https://github.com/Seanba/Tiled2Unity) - Export Tiled Map Editor (TMX) files into Unity
* [UnityTile3D](https://github.com/NoelFB/UnityTile3D) - Simple 3D Tile Editor
* [2DTileMapLevelEditor](https://github.com/GracesGames/2DTileMapLevelEditor) - 2D Tile Map Level Editor for Unity
* [HexTiles](https://github.com/RoryDungan/HexTiles) - Unity Hex Tile Editor
* [giles](https://github.com/procore3d/giles) - GILES: A Runtime Level Editor for Unity3D
* [floorplan](https://github.com/alexismorin/floorplan) - A Sims-Like Unity Level Design Plugin
* [realtime-CSG-for-unity](https://github.com/LogicalError/realtime-CSG-for-unity) - Realtime-CSG, CSG level editor for Unity 
* [PrefabPainter](https://github.com/AlexanderAmeye/PrefabPainter) - A basic prefab painter for the Unity3D game engine
* [hedera](https://github.com/radiatoryang/hedera) - paint 3D ivy in the Unity Editor, watch procedurally generated meshes simulate growth and clinging in real-time
* [Photosynthesizer](https://github.com/alexismorin/Photosynthesizer) - Unity plugin to procedurally sprout foliage throughout your scene.
* [Terrain-Stamps](https://github.com/Roland09/Terrain-Stamps) - Stamps for the Unity Terrain Stamp Tool.
* [StampToolExtended](https://github.com/Roland09/StampToolExtended) - Extended version of the Unity Terrain Stamp Tool.
* [YAPP - Yet Another Prefab Painter](https://github.com/Roland09/PrefabPainter) - Tool for conveniently and flexibly adding huge amounts of prefabs to your Unity scene.
* [RoadArchitect](https://github.com/MicroGSD/RoadArchitect) - Road Architect for Unity
* [roadbuilder](https://github.com/guotata1996/roadbuilder) - Easy-to-build realistic roads in Unity. Foundation of any simcity game
* [roadcreator](https://github.com/MCrafterzz/roadcreator) - A free road creation tool for unity
* [LDtkUnity](https://github.com/Cammin/LDtkUnity) - A package for easy Unity-integration with the Level Designer Toolkit, created by deepnight: https://github.com/deepnight/ldtk
* [Chisel.Prototype](https://github.com/RadicalCSG/Chisel.Prototype) - Work in progress prototype for the Chisel Level Editor, for Unity
* [Grid-Placer](https://github.com/JanMalitschek/Grid-Placer) - A Unity3D package to alleviate the pain of creating grid-based maps by hand
* [RuntimeTransformHandle](https://github.com/pshtif/RuntimeTransformHandle) - Runtime transform handle for Unity

### Light
* [Aura](https://github.com/raphael-ernaelsten/Aura) - Volumetric Lighting for Unity
* [Simple Light Probe Placer](https://github.com/AlexanderVorobyov/simple-light-probe-placer) - it is simple tool for Unity3d and it help you easily place Light Probes in your scene
* [VolumetricLights](https://github.com/SlightlyMad/VolumetricLights) - Volumetric Lights for Unity
* [Rimlight](https://github.com/AdultLink/Rimlight) - Customizable rimlight shader for Unity that includes pulsation and noise scrolling. Give your scenes that extra oomph!
* [unity-volumetric-fog](https://github.com/SiiMeR/unity-volumetric-fog) - A volumetric fog implementation in Unity.
* [VolumetricTracer](https://github.com/Fewes/VolumetricTracer) - A simple way to render soft, volumetric bullet tracers in Unity. Only needs a unit cube and a material to render and supports instancing.

### Lua
* [slua (Recommend)](https://github.com/pangweiwei/slua) - Fastest lua binding via static code generating for Unity3D and mono.
* [xLua (Recommend)](https://github.com/Tencent/xLua) - xLua is a hot-fix solution plugin for Unity3D, it supports android, ios, windows, osx, etc.
* [UniLua](https://github.com/xebecnan/UniLua) - A pure C# implementation of Lua 5.2 focus on compatibility with Unity3D.
* [MoonSharp](https://github.com/xanathar/moonsharp/) - An interpreter for the Lua language, written entirely in C# for the .NET, Mono, Xamarin and Unity3D platforms, including handy remote debugger facilities

### Lua Utilities
* [LuaProfiler-For-Unity](https://github.com/ElPsyCongree/LuaProfiler-For-Unity) - LuaProfiler-For-Unity

### Machine Learning
* [MediaPipeUnityPlugin](https://github.com/homuler/MediaPipeUnityPlugin) - Unity plugin to run MediaPipe

### Media Player
* [Vimeo Unity SDK](https://github.com/vimeo/vimeo-unity-sdk) - Easily stream your Vimeo videos into Unity or record and publish out to Vimeo
* [LibVLCSharp](https://github.com/videolan/LibVLCSharp) - LibVLCSharp is a cross-platform audio and video API for .NET platforms based on VideoLAN's LibVLC Library.
* [FFmpegUnityBind2](https://github.com/Spirit30/FFmpegUnityBind2) - FFmpeg Unity Bind 2 is the most powerful Video, Audio, Images Editor for your app.

### Meshes
* [UnityMeshSimplifier](https://github.com/Whinarn/UnityMeshSimplifier) - Mesh simplification for Unity.
* [MeshDecimator](https://github.com/Whinarn/MeshDecimator) - A mesh decimation library for .NET and Unity.
* [SplineMesh](https://github.com/benoit-dumas/SplineMesh) - A Unity plugin to create curved content in real-time with bézier curves
* [UnityGLTF](https://github.com/KhronosGroup/UnityGLTF) - Runtime GLTF Loader for Unity3D
* [Deform](https://github.com/keenanwoodall/Deform) - A fully-featured deformer system for Unity
* [unity-ray-marching](https://github.com/TheAllenChou/unity-ray-marching) - Ray marching sandbox
* [Hull-Delaunay-Voronoi](https://github.com/Scrawk/Hull-Delaunay-Voronoi) - Hull, Delaunay and Voronoi algorithms in Unity
* [IsoMesh](https://github.com/EmmetOT/IsoMesh) - IsoMesh is a group of related tools for Unity for converting meshes into signed distance field data, raymarching signed distance fields, and extracting signed distance field data back to meshes via surface nets or dual contouring.
* [mesh-cutter](https://github.com/hugoscurti/mesh-cutter) - Simple mesh cutting algorithm that works on simple 3d manifold objects with genus 0
* [unity-mesh-builder](https://github.com/mattatz/unity-mesh-builder) - Primitive mesh builder for Unity.
* [unity-fracture](https://github.com/ElasticSea/unity-fracture) - Fracture any mesh at runtime
* [OpenFracture](https://github.com/dgreenheck/OpenFracture) - Open source mesh slicing/fracturing utility for Unity
* [UnityBVA](https://github.com/bilibili/UnityBVA) - A 3D cross-platform format for Unity
* [VoxReader](https://github.com/sandrofigo/VoxReader) - Library to read .vox files created with MagicaVoxel.
* [BMeshUnity](https://github.com/eliemichel/BMeshUnity) - A Unity package to make runtime procedural mesh generation more flexible.

### Modding
* [dotPeek](https://www.jetbrains.com/decompiler/) - Free .NET Decompiler and Assembly Browser.
* [OpenSesame](https://github.com/mob-sakai/OpenSesame) - A custom Roslyn compiler that allows access to internals/privates in other assemblies. Say "Open, Sesame!"
* [CSharpCompilerSettingsForUnity](https://github.com/mob-sakai/CSharpCompilerSettingsForUnity) - Change the C# compiler (csc) used on your Unity project, as you like!.
* [Unity-Bridge-API](https://github.com/neon-age/Unity-Bridge-API) - Exposes private Unity APIs for direct access
* [Fody](https://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies.
* [Harmony](https://github.com/pardeike/Harmony) - A library for patching, replacing and decorating .NET and Mono methods during runtime.
* [dnSpy](https://github.com/0xd4d/dnSpy) - .NET debugger and assembly editor.
* [ILSpy](https://github.com/icsharpcode/ILSpy) - .NET Decompiler with support for PDB generation, ReadyToRun, Metadata (&more) - cross-platform!
* [AssetStudio](https://github.com/Perfare/AssetStudio) - AssetStudio is a tool for exploring, extracting and exporting assets and assetbundles.
* [UtinyRipper](https://github.com/mafaca/UtinyRipper) - GUI and API library for working with Engine assets, serialized and bundle files.
* [MelonLoader](https://github.com/LavaGang/MelonLoader) - The World's First Universal Mod Loader for Unity Games that is Compatible with both Il2Cpp and Mono.
* [UnityDoorstop](https://github.com/NeighTools/UnityDoorstop) - Doorstop -- run C# before Unity does!
* [MonoHook](https://github.com/Misaka-Mikoto-Tech/MonoHook) - hook C# method at runtime without modify dll file (such as UnityEditor.dll)
* [ThunderKit](https://github.com/PassivePicasso/ThunderKit) - Mod Project Development Environment for Unity and Unity Games

### Monetization
* [unity3d-levelup](https://github.com/soomla/unity3d-levelup) - Unity3D F2P game progression library - worlds, levels, missions, scores, records and more. Part of The SOOMLA Framework - for game design, economy modeling and faster development.
* [unity3d-store](https://github.com/soomla/unity3d-store) - Unity in-app purchase & virtual economy library. Part of The SOOMLA Framework - for game design, economy modeling and faster development.
* [Google Mobile Ads Unity Plugin](https://github.com/googleads/googleads-mobile-unity) - Official Unity Plugin for the Google Mobile Ads SDK

### Networking
* [UnitySocketIO](https://github.com/NetEase/UnitySocketIO) - socket.io client for unity3d.
* [websocket-sharp](https://github.com/sta/websocket-sharp) - A C# implementation of the WebSocket protocol client and server
* [Hazel-Networking](https://github.com/DarkRiftNetworking/Hazel-Networking) - A low level networking library for C# providing connection orientated, message based communication via TCP, UDP and RUDP.
* [MassiveNet](https://github.com/jakevn/MassiveNet) - Unity3d UDP networking library focused on high-CCU, multi-server architecture.
* [Nakama](https://github.com/heroiclabs/nakama) - An open-source distributed social and realtime server for games and apps by [Heroic Labs](https://heroiclabs.com). It includes a large set of services for users, data storage, and realtime client/server communication; as well as specialized APIs like realtime multiplayer, groups/guilds, and chat.
* [Barebones Master Server](https://github.com/alvyxaz/barebones-masterserver) - Master Server framework for Unity
* [Forge Networking Remastered](https://github.com/BeardedManStudios/ForgeNetworkingRemastered) - In short, Forge Networking is a free and open source multiplayer game (multi-user) networking system that has a very good integration with the Unity game engine. You wanna make a multiplayer game or real time multi-user application? This is the library for you.
* [Facepunch.Steamworks](https://github.com/Facepunch/Facepunch.Steamworks) - Another fucking c# Steamworks implementation
* [MagicOnion](https://github.com/neuecc/MagicOnion) - gRPC based HTTP/2 RPC Streaming Framework for .NET, .NET Core and Unity.
* [lidgren-network-gen3](https://github.com/lidgren/lidgren-network-gen3) - Lidgren.Network is a networking library for .NET framework, which uses a single UDP socket to deliver a simple API for connecting a client to a server, reading and sending messages.
* [LiteNetLib](https://github.com/RevenantX/LiteNetLib) - Lite reliable UDP library for Mono and .NET
* [LiteNetLibManager](https://github.com/insthync/LiteNetLibManager) - Higher level implementation for LiteNetLib
* [UNet-Controller](https://github.com/GreenByteSoftware/UNet-Controller) - A CharacterController based controller for Unity's new Networking system
* [Steamworks.NET](https://github.com/rlabrecque/Steamworks.NET) - Steamworks wrapper for Unity / C#
* [UnityHTTP](https://github.com/andyburke/UnityHTTP) - A TcpClient-based HTTP library for Unity
* [SocketIoClientDotNet](https://github.com/Quobject/SocketIoClientDotNet) - Socket.IO Client Library for .Net
* [Networker](https://github.com/MarkioE/Networker) -
A simple to use TCP and UDP networking library for .NET. Compatible with Unity
* [SmartFoxServer 2X](http://docs2x.smartfoxserver.com/ExamplesUnity/introduction) - A comprehensive SDK for rapidly developing multiplayer games and applications with Adobe Flash/Flex/Air, Unity, HTML5, iOS, Windows Phone 8, Android, Java, Windows 8, C++ and more
* [Colyseus](http://colyseus.io/) - Multiplayer Game Server for Node.js. [Demo with Unity3D](https://github.com/gamestdio/colyseus-unity3d)
* [UnityWebSocket](https://github.com/Unity3dAzure/UnityWebSocket) - Web Socket client for Unity
* [RESTClient](https://github.com/Unity3dAzure/RESTClient) - REST Client for Unity with JSON and XML parsing. (Features JSON helper to handle nested arrays and deserializing abstract types)
* [SpeedDate](https://github.com/proepkes/SpeedDate) - SpeedDate Masterserver: Connecting Players
* [UnityLockstep](https://github.com/proepkes/UnityLockstep) - Deterministic Lockstep with serverside framerate for Unity
* [ET](https://github.com/egametang/ET) - Unity3D Client And C# Server Framework
* [unity-fastpacedmultiplayer](https://github.com/JoaoBorks/unity-fastpacedmultiplayer) - Features a Networking Framework to be used on top of Unity Networking, in order to implement an Authoritative Server with Lag Compensation, Client-Side Prediction/Server Reconciliation and Entity Interpolation
* [Entitas-Sync-Framework](https://github.com/RomanZhu/Entitas-Sync-Framework) - Networking framework for Entitas ECS. Targeted at turnbased games or other slow-paced genres
* [RestClient](https://github.com/proyecto26/RestClient) - Simple HTTP and REST client for Unity based on Promises, also supports Callbacks! 
* [Teleport](https://github.com/debox-dev/Teleport) - A fast, lightweight, pure C# Unity realtime-game-networking framework
* [EuNet](https://github.com/zestylife/EuNet) - Peer to peer network solution for multiplayer games.
* [HouraiNetworking](https://github.com/HouraiTeahouse/HouraiNetworking) - Transport level library for peer-to-peer networking with multiple backends for the Unity.
* [Backroll](https://github.com/HouraiTeahouse/Backroll) - Unity C# Port of GGPO built atop Hourai Networking
* [sand-socket-unity](https://github.com/ccadori/sand-socket-unity) - Sand Unity is a Unity3D client for [Sand](https://github.com/ccadori/sand-socket)
* [Pun2Task](https://github.com/TORISOUP/Pun2Task) - This library enables async/await in Photon Unity Networking 2.
* [UnityWebSocket](https://github.com/psygames/UnityWebSocket) - The Best Unity WebSocket Plugin for All Platforms.
* [graphQL-client-unity](https://github.com/Gazuntype/graphQL-client-unity) - This repository houses a unitypackage that can be included in your Unity Project to enable it communicate with a graphQL server.
* [zapnet](https://github.com/deadgg/zapnet) - ⚡ Zapnet is a Unity framework for game networking built with Lidgren
* [Httx](https://github.com/whitesharx/httx/) - X-force HTTP/REST library for Unity. Zero dependency, fluent and extensible
* [open-netcode](https://github.com/polartron/open-netcode) - Open Netcode is a feature rich networking package for Unity DOTS.
* [Master Server Toolkit](https://github.com/aevien/master-server-toolkit) - This is a framework that allows you to create game servers and services for your game inside Unity. It allows you to avoid using third-party services such as Playful, PAN, or Smartfox server. This framework does not claim to be a substitute for all these systems. No way!
* [EntityNetworkingSystems](https://github.com/AncientEntity/EntityNetworkingSystems) - A networking framework for Unity.
* [promul](https://github.com/jacksonrakena/promul) - An open-source networking & relay implementation for Unity Netcode for GameObjects

### Node Graph
* [xNode](https://github.com/Siccity/xNode) - Lets you view and edit node graphs inside Unity
* [UnityRuntimeNodeEditor](https://github.com/cemuka/UnityRuntimeNodeEditor) - Unity runtime node editor using with Unity UI
* [NodeGraphProcessor](https://github.com/alelievr/NodeGraphProcessor) - Node graph editor framework focused on data processing using Unity UIElements and C# 4.6
* [Dialogue](https://github.com/Siccity/Dialogue) - Node based dialogue system
* [NodeBasedDialogueSystem](https://github.com/merpheus-dev/NodeBasedDialogueSystem) - Node Based Dialogue System for Unity
* [unity-dialogue-system](https://github.com/Wafflus/unity-dialogue-system) - A basic node based dialogue system made for Unity.

### Obfuscation
* [Ether-Uprotector](https://github.com/Ether2023/Ether-Uprotector)

### Package Manager
* [Projeny](https://github.com/modesttree/Projeny) - A project and package manager for Unity.
* [NuGetForUnity](https://github.com/GlitchEnzo/NuGetForUnity) - A NuGet Package Manager for Unity
* [OpenUPM](https://github.com/openupm/openupm) - OpenUPM - Open Source Unity Package Registry (UPM)

### Physic
* [BulletSharpUnity3d](https://github.com/Phong13/BulletSharpUnity3d) - A fork of the BulletSharp project to make the Bullet Physics Engine usable from C# code in Unity3d
* [Graphics-Raycast](https://github.com/Jonny10/Graphics-Raycast) - GPU-based raycaster for Unity
* [Bepuphysics-Unity](https://github.com/AntoineCharton/Bepuphysics-Unity) - A bridge for Bepuphysics and Unity
* [UnityNativeCollision](https://github.com/jeffvella/UnityNativeCollision) - SAT Collision in C# for Unity3D Burst Compiler
* [Fusion](https://github.com/Ninjajie/Fusion) - Unity Physics on GPU
* [unity-physics-constraints](https://github.com/TheAllenChou/unity-physics-constraints) - Minimalistic educational constraint-based physics framework
* [Unity-SensorKit](https://github.com/3DI70R/Unity-SensorKit) - Utility classes for headache-free raycasting configuration in Unity
* [UnityJigglePhysics](https://github.com/naelstrof/UnityJigglePhysics) - A unity addon for adding stretchy bouncy physics to bones and meshes.
* [unity-deterministic-physics](https://github.com/Kimbatt/unity-deterministic-physics) - Cross-platform deterministic physics simulation in Unity, using DOTS physics and soft floats
* [RaycastVisualization](https://github.com/nomnomab/RaycastVisualization) - This asset allows users to view raycasts as the user fires them.
* [JoltPhysicsUnity](https://github.com/seep/JoltPhysicsUnity) - Jolt Physics bindings for Unity
* [Cable-physics](https://github.com/Hrober0/Cable-physics) - Cable physics made with unity

### Playable
* [YJZPlayableGraphView](https://github.com/terrynoya/YJZPlayableGraphView) - playable visualizer with GraphView
* [UnityPlayableGraphMonitorTool](https://github.com/SolarianZ/UnityPlayableGraphMonitorTool) - PlayableGraph monitor tool inspired by PlayableGraph Visualizer and implemented in UIElements.

### Plugins
* [Reign Unity Plugin](https://github.com/reignstudios/Reign-Unity-Plugin5) - This Reign API is a cross-platform, unified API for the Unity game engine.
* [google-analytics-plugin-for-unity](https://github.com/googleanalytics/google-analytics-plugin-for-unity) - Google Analytics plugin for the Unity game creation system
* [unity-native-sharing](https://github.com/ChrisMaire/unity-native-sharing) - A Unity plugin to open native sharing dialogs on iOS and Android, primarily for sharing screenshots.
* [Unity3D Android notification plugin](https://github.com/Agasper/unity-android-notifications) - Unity3D Plugin for Android local notifications with example project
* [PuppeteerSharp.Unity3D](https://github.com/uta-org/PuppeteerSharp.Unity3D) - Puppeteer Sharp is a .NET port of the official
* [uLipSync](https://github.com/hecomi/uLipSync) - https://github.com/hecomi/uLipSync
* [NatShare](https://github.com/natmlx/NatShare) - Cross-platform social sharing for Unity Engine.
* [Unity-Native-Sharing](https://github.com/NicholasSheehan/Unity-Native-Sharing) - A Unity plugin to open native sharing dialogs on iOS and Android, primarily for text and files
* [UnityNativeDialogPlugin](https://github.com/asus4/UnityNativeDialogPlugin) - Show iOS/Android native dialog from Unity.

### Procedural Generation Systems
* [DungeonGenerator](https://github.com/jongallant/DungeonGenerator) - A dungeon generator for Unity
* [Procedural-Cave-Generator](https://github.com/AK-Saigyouji/Procedural-Cave-Generator) - Unity scripts that procedurally generate ready-to-use cave meshes.
* [unity-procedural-tree](https://github.com/mattatz/unity-procedural-tree) - Procedural tree builder for Unity.
* [unity-procedural-flower](https://github.com/mattatz/unity-procedural-flower) - Procedural flower generator for Unity.
* [ProceduralToolkit](https://github.com/Syomus/ProceduralToolkit) - Procedural generation library for Unity
* [wavefunctioncollapse](https://github.com/marian42/wavefunctioncollapse/) - Walk through an infinite, procedurally generated city
* [ProceduralLevelGenerator-Unity](https://github.com/OndrejNepozitek/ProceduralLevelGenerator-Unity) - Unity plugin from procedural dungeon generation
* [Edgar-Unity](https://github.com/OndrejNepozitek/Edgar-Unity) - Unity Procedural Level Generator
* [InstantPipes](https://github.com/leth4/InstantPipes) - Unity editor tool for quickly generating pipes—with pathfinding
* [makegeo](https://github.com/kurtdekker/makegeo) - Make Geometry - Procedural Unity3D Geometry

### Pooling System
* [kPooling](https://github.com/Kink3d/kPooling) - Customizable Object Pooling for Unity
* [Replicator](https://github.com/ettmetal/Replicator) - Whooshy GameObject pooling / reuse for Unity
* [Eflatun.Pooling](https://github.com/starikcetin/Eflatun.Pooling) - Object pooling utilities for Unity

### Profobuf
* [protobuf-net](https://github.com/mgravell/protobuf-net) - Protocol Buffers library for idiomatic .NET
* [protobuf-unity](https://github.com/5argon/protobuf-unity) - Automatic .proto files compilation in Unity project to C# as you edit them

### Project Management
* [unity-desktop-lite](https://github.com/gblikas/unity-desktop-lite) - Unity in the browser, via Github Codespaces.

### Runtime Editor
* [UnityRuntimeInspector](https://github.com/yasirkula/UnityRuntimeInspector) - Runtime Inspector and Hierarchy solution for Unity for debugging and runtime editing purposes
* [RuntimeUnityEditor](https://github.com/ManlyMarco/RuntimeUnityEditor) - In-game inspector and debugging tools for applications made with Unity3D game engine
* [Unity3DRuntimeTransformGizmo](https://github.com/HiddenMonk/Unity3DRuntimeTransformGizmo) - A runtime transform gizmo similar to unitys editor so you can translate (move, rotate, scale) objects at runtime

### Scriptable Object
* [unity-atoms](https://github.com/AdamRamberg/unity-atoms) - Tiny modular pieces utilizing the power of Scriptable Objects
* [Scriptable-Framework](https://github.com/pablothedolphin/Scriptable-Framework) - A Unity Framework for modular app creation based on ScriptableObject architecture, data oriented design and event driven programming to help programmers and designers adhere to the 5 SOLID programming principals.
* [yaSingleton](https://github.com/jedybg/yaSingleton) - A singleton pattern implementation for Unity3d. Based on ScriptableObjects instead of the conventional MonoBehaviour approach.
* [SOFlow](https://github.com/BLUDRAG/SOFlow) - A ScriptableObject oriented design SDK.
* [ScriptableObject-Architecture](https://github.com/DanielEverland/ScriptableObject-Architecture) - Makes using Scriptable Objects as a fundamental part of your architecture in Unity super easy
* [ScriptableObjectCollection](https://github.com/brunomikoski/ScriptableObjectCollection) - A library to help improve the usability of Unity3D Scriptable Objects by grouping then into a collection and exposing then by code or nice inspectors!
* [GenericUnityObjects](https://github.com/SolidAlloy/GenericUnityObjects) - Generic ScriptableObjects

### Scriptings
* [UnityNativeScripting](https://github.com/jacksondunstan/UnityNativeScripting) - Unity Scripting in C++
* [unity-python](https://github.com/exodrifter/unity-python) - Python plugin for Unity3D
* [YarnSpinner](https://github.com/YarnSpinnerTool/YarnSpinner) - Yarn Spinner is a tool for building interactive dialogue in games! 
* [UniScript](https://github.com/pjc0247/UniScript) - Brings C# scripting into Unity which acts as native code.
* [SlowSharp](https://github.com/pjc0247/SlowSharp) - C# interpreter written in C#
* [hybridclr](https://github.com/focus-creative-games/hybridclr) - a full-platform native c# hot update solution for Unity with complete features, zero cost, high performance, and low memory.

### Scene Transition
* [UnityScreenNavigator](https://github.com/Haruma-K/UnityScreenNavigator) - Library for screen transitions, transition animations, transition history stacking, and screen lifecycle management in Unity's uGUI.

### Serializer
* [fullserializer](https://github.)om/jacobdufault/fullserializer) - A robust JSON serialization framework that just works with support for all major Unity export platforms
* [odin-serializer](https://github.com/TeamSirenix/odin-serializer) - Fast, robust, powerful and extendible .NET serializer built for Unity
* [UnitySerializedDictionary](https://github.com/Prastiwar/UnitySerializedDictionary) - Serialized and drawed in editor Dictionary

### Services
* [Devtodev](https://github.com/devtodev-analytics/unity-sdk) - A full-cycle analytics solution for game developers.
* [eos_plugin_for_unity](https://github.com/PlayEveryWare/eos_plugin_for_unity) - The eos_plugin_for_unity repository contains the source code for development and support of the Epic Online Services Plugin for Unity (UPM Package) package.
* [line-sdk-unity](https://github.com/line/line-sdk-unity) - Provides a modern way of implementing LINE APIs in Unity games, for iOS and Android.
* [Google Play Games plugin for Unity](https://github.com/playgameservices/play-games-plugin-for-unity) - Google Play Games plugin for Unity
* [Playerloop](https://github.com/playerloop/playerloop-unity) - The fastest way to start collecting bug reports from your players.
* [Aptabase](https://github.com/aptabase/aptabase-unity) - Open Source, Privacy-first and lightweight analytics for Unity Games.

### Sounds
* [usfxr](https://github.com/zeh/usfxr) - a C# library used to generate and play game-like procedural audio effects inside Unity. With usfxr, one can easily design and synthesize original sound in real time for actions such as item pickups, jumps, lasers, hits, explosions, and more, without ever leaving the Unity editor.
* [Unity-Beat-Detection](https://github.com/allanpichardo/Unity-Beat-Detection) - Musical beat detection and audio spectrum analysis for use with the Unity game engine.
* [LibNoise.Unity](https://github.com/ricardojmendez/LibNoise.Unity) - Coherent noise library for Unity, a port of LibNoise
* [Reaktion](https://github.com/keijiro/Reaktion) - Audio reactive animation toolkit for Unity
* [MusicEngine](https://github.com/geekdrums/MusicEngine) - make music synced game with Unity / ADX2 / Wwise
* [Unity-Audio-Manager](https://github.com/MathewHDYT/Unity-Audio-Manager) - Plugin, that allows to easily play/change/stop/mute/... sounds in 2D/3D

### Theading
* [UnityMainThreadDispatcher](https://github.com/PimDeWitte/UnityMainThreadDispatcher) - A simple, thread-safe way of executing actions (Such as UI manipulations) on the Unity Main Thread
* [UnityAsyncRoutines](https://github.com/TorVestergaard/UnityAsyncRoutines) - An extremely lightweight Unity library for creating and managing asynchronous coroutines for easy, straight-forward multi-threading and parallellism
* [Unity-Threading](https://github.com/Enderlook/Unity-Threading) - A helper library for Unity Jobs, System.Threading, Async/Await and Coroutines in Unity.

### Terrain
* [MightyTerrainMesh](https://github.com/jinsek/MightyTerrainMesh) - A Unity Plugin for Converting Terrain 2 Mesh & Terrain 2 Data for Runtime Virtual Texture.
* [Unity--voxel-terrain-generator](https://github.com/michalczemierowski/Unity--voxel-terrain-generator) - 3D game with procedural world made of cubes. (world generation/mesh creation/physx baking is multi threaded)

### Timeline
* [SpineTimeline](https://github.com/5argon/SpineTimeline) - Animate SkeletonAnimation or SkeletonGraphic with Unity's Timeline

### Tweening
* [DOTween (Recommend)](https://github.com/Demigiant/dotween) - A Unity C# animation engine. HOTween v2
* [MagicTween](https://github.com/AnnulusGames/MagicTween) - Extremely fast tween library implemented in Unity ECS
* [LitMotion](https://github.com/AnnulusGames/LitMotion) - Lightning-fast and Zero Allocation Tween Library for Unity.
* [PrimeTween](https://github.com/KyryloKuzyk/PrimeTween) - High-performance, allocation-free tween library for Unity. Create animations, delays, and sequences in one line of code.
* [TweenPlayables](https://github.com/AnnulusGames/TweenPlayables) - Tween Animation Library for Unity Timeline
* [LeanTween](https://github.com/dentedpixel/LeanTween) - LeanTween is an efficient animation engine for Unity
* [GoKit](https://github.com/prime31/GoKit) - Lightweight tween library for Unity
* [Uween](https://github.com/beinteractive/Uween) - Lightweight tween library for Unity
* [ZestKit](https://github.com/prime31/ZestKit) - Tween library for Unity. The best of GoKit and GoKitLite combined in an easy to use API
* [Animation-Sequencer](https://github.com/brunomikoski/Animation-Sequencer) - A visual tool that allows you to create animated sequences of tweens and tweak them on editor time.

### Vehicle
* [Tork](https://github.com/adrenak/Tork) - Vehicle system for Unity
* [Randomation-Vehicle-Physics](https://github.com/JustInvoke/Randomation-Vehicle-Physics) - Vehicle physics system for the Unity engine.
* [Aircraft-Physics](https://github.com/gasgiant/Aircraft-Physics) - Fixed wing aircraft physics for Unity

### UI
* [FairyGUI-unity](https://github.com/fairygui/FairyGUI-unity) - A flexible UI framework for Unity
* [MiniMap](https://github.com/Area730/MiniMap) - Unity3D mini map (radar) system (Asset Store link - https://www.assetstore.unity3d.com/en/#!/content/33729 )
* [LoopScrollRect](https://github.com/qiankanglai/LoopScrollRect) - UGUI ScrollRect reusing cells, to improve performance, loading time and draw calls.
* [MaterialUI](https://github.com/InvexGames/MaterialUI) - MaterialUI is a UI kit for Unity that follows Google's official material design guidelines.
* [Unity-UI-Extensions](https://bitbucket.org/UnityUIExtensions/unity-ui-extensions)
* [EnhancedScrollView](https://github.com/tinyantstudio/EnhancedScrollView) - Cool 3d scoll view for Unity(NGUI 3D UGUI support)
* [Beautiful Text Outline for Unity UI](https://github.com/n-yoda/unity-vertex-effects) - Beautiful text outline for Unity UI.
* [uGUI-Effect-Tool](https://github.com/WestHillApps/uGUI-Effect-Tool) - Vertex color UI Effect for Unity UI (uGUI).
* [Unity-UI-Polygon](https://github.com/CiaccoDavide/Unity-UI-Polygon) - Polygon renderer for the new Unity UI
* [muip](https://github.com/Michsky/muip) - Modern UI Pack for Unity engine
* [lomenui](https://github.com/Michsky/lomenui) - Stylish UI package for Unity engine
* [ultimatehudskins](https://github.com/Michsky/ultimatehudskins) - Stylish HUD layouts for Unity engine
* [looader](https://github.com/Michsky/looader) - Loading screen solution for Unity engine
* [UIEffect](https://github.com/mob-sakai/UIEffect) - UIEffect is an effect component for uGUI element in Unity. Let's decorate your UI with effects!
* [ParticleEffectForUGUI](https://github.com/mob-sakai/ParticleEffectForUGUI) - This plugin provide a component to render particle effect for uGUI in Unity 2018.2+. The particle rendering is maskable and sortable, without Camera, RenderTexture or Canvas
* [ShinyEffectForUGUI](https://github.com/mob-sakai/ShinyEffectForUGUI) - Shiny effect of uGUI, which does not need mask or normal map
* [FancyScrollView](https://github.com/setchi/FancyScrollView) - A scrollview component that can be implemented flexible flexible animation
* [Juicy Healthbar](https://twitter.com/AntonPantev/status/1140063685655826432) - "I made the Juicy Health Bar from @reuno’s Unite LA talk. It’s pretty great!"
* [UIWidgets](https://github.com/UnityTech/UIWidgets) - UIWidget is a Unity Package which helps developers to create, debug and deploy efficient, cross-platform Apps.
* [PageTurningUIEffect](https://github.com/lobeyjon/PageTurningUIEffect) - A page turning UI effect made with unity, the paper deformation is determined by the pins' position on it
* [Unity-WinForms](https://github.com/Meragon/Unity-WinForms) - Windows Forms wrapper for Unity
* [Delight](https://github.com/delight-dev/Delight) - Component-oriented UI framework for Unity https://delight-dev.github.io/
* [CharTweener](https://github.com/mdechatech/CharTweener) - Unity3D - DOTween extensions for tweening TextMeshPro characters
* [UnityRecyclingListView](https://github.com/sinbad/UnityRecyclingListView) - A fast scrolling list component for Unity UI which recycles its child elements
* [sci-fi-ui](https://github.com/devdogio/sci-fi-ui) - The uGUI Sci-Fi UI Design for Unity - now free and open-source!
* [LiquidSwipeUnity](https://github.com/FaizanDurrani/LiquidSwipeUnity) - Butter smooth full page swiping animation with a masked wave effect in Unity
* [Unity-UI-Rounded-Corners](https://github.com/Nobinator/Unity-UI-Rounded-Corners) - This components and shaders allows you to add rounded corners to UI element
* [RapidGUI](https://github.com/fuqunaga/RapidGUI) - Unity OnGUI(IMGUI) extensions for Rapid prototyping/development
* [ugui-mvvm](https://github.com/jbruening/ugui-mvvm) - Unity3D uGUI mvvm databinding via the standard IXChanged interfaces used in wpf (INotifyPropertyChanged, INotifyCollectionChanged, etc)
* [Recyclable-Scroll-Rect](https://github.com/MdIqubal/Recyclable-Scroll-Rect) - Recyclable Scroll Rect reuses or recycles the least number of cells required to fill the viewport. As a result a huge number of items can be shown in the list without any performance hit. 
* [UnityGUI](https://github.com/coryleach/UnityGUI) - UGUI Panel Systems for navigation, animation and more
* [UGUIExtend](https://github.com/L-Lawliet/UGUIExtend)
* [unity-ugui-XCharts](https://github.com/monitor1394/unity-ugui-XCharts) - A charting and data visualization library for Unity.
* [ugx](https://github.com/adrenak/ugx) - UGX: UGUI Extended is a high-level library over Unity's inbuilt uGui. Currently a work in progress
* [dear-imgui-unity](https://github.com/realgamessoftware/dear-imgui-unity) - Unity package for Dear ImGui.
* [UIForia](https://github.com/klanggames/UIForia) - UIForia - a new UI framework written for Unity
* [TMP-Text-Juicer](https://github.com/brunomikoski/TMP-Text-Juicer) - Text Juicer for Text Mesh PRO
* [Text-Juicer](https://github.com/brunomikoski/Text-Juicer) - Simple tool to create awesome text animations
* [PoiPoiTooltip](https://github.com/arket/PoiPoiTooltip) - PoiPoiTooltip is a simple tooltip. (Unity Asset)
* [Auto9Slicer](https://github.com/kyubuns/Auto9Slicer) - Auto 9 slice sprite generator on Unity.
* [UnityAccessibilityPlugin](https://github.com/mikrima/UnityAccessibilityPlugin) - The UI Accessibility Plugin (UAP) allows you to make your UI accessible to blind and visually impaired players on Windows, Android, iOS, Mac and WebGL.
* [ReactUnity](https://github.com/ReactUnity/core) - React and HTML framework for Unity UI & UIToolkit.
* [uPalette](https://github.com/Haruma-K/uPalette) - Centralized management & batch change system of colors for Unity.
* [Rewired.UI.Hotkeys](https://github.com/am1goo/Rewired.UI.Hotkeys) - a plugin for Guavaman's Rewired Unity Asset that provides an easy-to-use API for showing controller hotkeys to the player at runtime based on their bindings and input method.

### Utilities
* [LINQ to GameObject](https://github.com/neuecc/LINQ-to-GameObject-for-Unity) - Traverse GameObject Hierarchy by LINQ
* [Moments](https://github.com/Chman/Moments) - A quick GIF replay recorder for Unity
* [FrameCapture](https://github.com/Chman/FrameCapture) - A simple frame-by-frame capture tool for Unity to record perfectly smooth, supersampled replays or cinematics.
* [UniGif](https://github.com/WestHillApps/UniGif) - GIF image decoder for Unity.
* [unityassets](https://github.com/fholm/unityassets) - Assorted assets previously on sale on the Unity Asset Store, now free on github.
* [UnityToolbag](https://github.com/nickgravelyn/UnityToolbag) - Variety of Unity scripts and tools.
* [C-Sharp-Promise](https://github.com/Real-Serious-Games/C-Sharp-Promise) - Promises library for C# for management of asynchronous operations.
* [3DMath](https://github.com/GregLukosek/3DMath) - Unity C# 3D Math methods library.
* [Unity Size Explorer](https://github.com/aschearer/unitysizeexplorer) - Visualize how much space each asset in your Unity game takes and quickly optimize your game's file size.
* [UnityStudio](https://github.com/RaduMC/UnityStudio) - Unity Studio is a tool for exploring, extracting and exporting assets from Unity games and apps.
* [InGameReplay](https://github.com/FeNo/InGameReplay) - Allow you to record the transform of any objects to replay it
* [UniRx](https://github.com/neuecc/UniRx) - Reactive Extensions for Unity
* [Rant](https://github.com/TheBerkin/rant) - Robust text engine for procedural generation and postprocessing
* [E7Unity](https://github.com/5argon/E7Unity) - Common Unity resources
* [mmd-for-unity](https://github.com/mmd-for-unity-proj/mmd-for-unity) - MikuMikuDance for Unity
* [Unity.Library.eppz](https://github.com/eppz/Unity.Library.eppz) - Collection of libraries for Unity
* [Alchemy-Circles-Generator](https://github.com/CiaccoDavide/Alchemy-Circles-Generator) - A simple procedural generator of alchemy circles
* [IMP](https://github.com/xraxra/IMP) - billboard imposter baking for Unity
* [UDBase](https://github.com/KonH/UDBase) - module-based game template for Unity. Modules in UDBase are called Controllers, their implementation can be replaced without changing your project source code
* [graphy](https://github.com/Tayx94/graphy) - Graphy is the ultimate, easy to use, feature packed stats monitor and debugger for your Unity project
* [unity-routines](https://github.com/tomblind/unity-routines) - Replacement for Unity coroutines that supports hierarchical routines and pooling
* [CropTexture](https://github.com/natsupy/CropTexture) - Crop and resize texture in unity editor! Open it: Press F1
* [demilib](https://github.com/Demigiant/demilib) - A library of various utilities and tools for Unity (alpha)
* [SerializableCallback](https://github.com/Siccity/SerializableCallback) - UnityEvent and System.Func had a child
* [bitstrap](https://github.com/bitcake/bitstrap) - BitStrap is BitCake's collection of Unity tools that improve our workflow
* [UnityPack](https://github.com/HearthSim/UnityPack) - Python deserialization library for Unity3D Asset format
* [UnityOctree](https://github.com/Nition/UnityOctree) - A dynamic, loose octree implementation for Unity written in C#
* [MathUtilities](https://github.com/zalo/MathUtilities) - A collection of some of the neat math and physics tricks that I've collected over the last few years.
* [CoroutineChain](https://github.com/geniikw/CoroutineChain) - Unity3d, Coroutine, scripting
* [disruptor-unity3d](https://github.com/dave-hillier/disruptor-unity3d) - Basic implementation of Disruptor for Unity3d
* [InkPainter](https://github.com/EsProgram/InkPainter) - Texture-Paint on Unity
* [WaveformProvider](https://github.com/EsProgram/WaveformProvider) - Provide a texture to simulate waves with Unity. Require InkPainter.
* [DataBind](https://github.com/tinrab/DataBind) - Simple data binding for Unity
* [GradientGenerator](https://github.com/5argon/GradientGenerator) - A Unity script to generate multiple variants of evenly distributed `Gradient` based on input `AnimationCurve`.
* [Unity-EasingLibraryVisualisation](https://github.com/noisecrime/Unity-EasingLibraryVisualisation) - Front end visualisation of 40 common easing equations.
* [Xamarin.Forms.Unity](https://github.com/aosoft/Xamarin.Forms.Unity) - Xamarin.Forms for Unity (Platform implementation for Unity Game Engine)
* [UnityTimer](https://github.com/akbiggs/UnityTimer) - Powerful and convenient library for running actions after a delay in Unity3D
* [PixelSpriteGenerator-Unity](https://github.com/Shogan/PixelSpriteGenerator-Unity) - A port of the PixelSpriteGenerator to C# for use with the Unity3D game engine
* [WeightedRandomSelector](https://github.com/viliwonka/WeightedRandomSelector) - Very fast C# class for weighted random picking.
* [SmartAssembler](https://github.com/Electronic-Brain/SmartAssembler) - Smartly Assembly your Project
* [GetComponentAttribute](https://github.com/m3rt32/GetComponentAttribute) - A simple DI plugin for getting MonoBehaviour components just with an attribute over fields.
* [unity-utils](https://github.com/nubick/unity-utils) - Different help scripts for Unity engine.
* [csharp-eval-unity3d](https://github.com/deniszykov/csharp-eval-unity3d) - C# Expression Parser for Unity3D
* [UnityNativeGallery](https://github.com/yasirkula/UnityNativeGallery) - A native Unity plugin to interact with Gallery/Photos on Android & iOS (save and/or load images/videos)
* [ThreeDPoseUnityBarracuda](https://github.com/digital-standard/ThreeDPoseUnityBarracuda) - Unity sample of 3D pose estimation using Barracuda
* [UnityStandaloneFileBrowser](https://github.com/gkngkc/UnityStandaloneFileBrowser) - A native file browser for unity standalone platforms
* [Mathfs](https://github.com/FreyaHolmer/Mathfs) - Expanded Math Functionality for Unity
* [Unity3D-Histogrammer](https://github.com/Thundernerd/Unity3D-Histogrammer) - A tool for Unity3D to help you pinpoint redundant data
* [Unity3D-Humanizr](https://github.com/Thundernerd/Unity3D-Humanizr) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities.
* [unity-scene-reference](https://github.com/starikcetin/unity-scene-reference) - A SceneReference wrapper class that uses ISerializationCallbackReceiver and a custom PropertyDrawer to provide safe, user-friendly scene references in scripts.
* [SceneKeeper](https://github.com/brunomikoski/SceneKeeper) - A simple tool that keeps your scene state (Hierarchy/Selection) exactly as you left in between switching scenes on editor or play mode.
* [Unity3D-save-audioClip-to-MP3](https://github.com/Team-on/Unity3D-save-audioClip-to-MP3) - Save an audioclip to mp3 in unity3d. Also plugin can save audioclip to wav and convert wav to mp3.
* [CandyCoded](https://github.com/CandyCoded/CandyCoded) - Custom Unity Components that are delightful
* [PrefabLightmapping](https://github.com/Ayfel/PrefabLightmapping) - Script for saving lightmapping data to prefabs. Used through the Assets tab in Unity.
* [unimgpicker](https://github.com/thedoritos/unimgpicker) - Image picker for Unity iOS/Android
* [GCFreeClosure](https://github.com/lujian101/GCFreeClosure) - About
A gc-free closure implementation for unity
* [Evolunity](https://github.com/Bodix/Evolunity) - Well-designed package with useful scripting tools for Unity development
* [UniRate](https://github.com/renanwolf/UniRate) - A Unity plugin to easily manage the application frame rate and rendering interval.
* [UnityMarkdownViewer](https://github.com/gwaredd/UnityMarkdownViewer) - A markdown viewer for unity
* [UnityClipboardImage](https://github.com/NullTale/UnityClipboardImage) - Small lib to read clipboard image data from unity
* [UnityAsyncImageLoader](https://github.com/adrenak/UnityAsyncImageLoader) - Asynchronous Image Loader for Unity
* [LucidRandom](https://github.com/AnnulusGames/LucidRandom) - Enhanced random number generator for Unity
* [Unity-Ripgrep-Search-Tool](https://github.com/prime31/Unity-Ripgrep-Search-Tool) - Helper class for making your own search tools along with a built-in transient Ripgrep search window.
* [Scene Reference Attribute](https://github.com/KyleBanks/scene-ref-attribute) - Unity C# attribute for serializing component and interface references within the scene or prefab during OnValidate.
* [UnityPythonMediaPipeAvatar](https://github.com/ganeshsar/UnityPythonMediaPipeAvatar) - Creating a multi-threaded full body tracking solution supporting arbitrary humanoid avatars for Unity using Google Mediapipe Pose Python bindings.
* [RapidEnum](https://github.com/hanachiru/RapidEnum) - Enum utility with SourceGenerator for C#/.NET

### VR/XR
* [VRTK](https://github.com/thestonefox/VRTK) - A productive VR Toolkit for rapidly building VR solutions in Unity3d.
* [NewtonVR](https://github.com/TomorrowTodayLabs/NewtonVR) - A virtual reality interaction system for unity based on physics.
* [MixedRealityToolkit-Unity](https://github.com/Microsoft/MixedRealityToolkit-Unity) - MixedRealityToolkit-Unity uses code from the base MixedRealityToolkit repository and makes it easier to consume in Unity.
* [Google VR SDK for Unity](https://github.com/googlevr/gvr-unity-sdk) - Google VR SDK for Unity http://developers.google.com/vr/unity/
* [TButt](https://github.com/turbobutton/tbutt-vr) - A lightweight multiplatform VR interface for Unity
* [VRWorksAudio-Unity](https://github.com/Andy260/VRWorksAudio-Unity) - Unofficial implementation of NVIDIA's VRWorks - Audio for Unity3D
* [Lightweight-VR](https://github.com/Spatial-Cinematics/Lightweight-VR) - An open sourced, light weight, VR input framework. This is basically an empty Unity project that's been setup for easy VR integration without having to pull down any packages. No need for Steam VR or OVR plugins.
* [HPTK](https://github.com/jorgejgnz/HPTK) - Hand Physics Toolkit (HPTK) is a toolkit to build physical hand-driven interactions in a modular and scalable way.
* [XRTK](https://github.com/XRTK/XRTK-Core) - The Official Mixed Reality Framework for Unity 
* [unity-webxr-export](https://github.com/De-Panther/unity-webxr-export) - Develop and export WebXR experiences using Unity WebGL
* [Simple-WebXR-Unity](https://github.com/Rufus31415/Simple-WebXR-Unity) - SimpleWebXR is a lightweight library that exposes the WebXR javascript API in your C# Unity code.
* [ultimatexr-unity](https://github.com/VRMADA/ultimatexr-unity) - UltimateXR is a free, open source framework that facilitates the creation of VR applications.
* [VisualProfiler-Unity](https://github.com/microsoft/VisualProfiler-Unity) - The Visual Profiler provides a drop in solution for viewing your mixed reality Unity application's frame rate, scene complexity, and memory usage.

### Web View
* [servo-unity](https://github.com/MozillaReality/servo-unity) - This project constitutes a Unity native plugin and a set of Unity C# script components allow third parties to incorporate Servo browser windows into Unity scenes.
* [unity-webview](https://github.com/gree/unity-webview) - A plugin for Unity 5 that overlays WebView components on Unity view. It works on Android, iOS, Unity Web Player, and OS X (Windows is not supported for now).

### Icons

* [I made 700+ RPG icons free for use for your game](https://www.reddit.com/r/IndieGaming/comments/ifmie/i_made_700_rpg_icons_free_for_use_/) - 700+ RPG Icons(The _filesonic_ URL ending with "Lorc_RPG_icons.zip" still works)
* [game-icons.net](https://game-icons.net) 3443+ Game Icons licensed under CC BY 3.0
* [EffectCore's VFX Packs](https://assetstore.unity.com/publishers/25749) - Paid AAA visual effects.

### Collections / Forums / Shops

* [Armedunity](https://armedunity.com/) - Shooter focused forum
* [itch.io](https://itch.io/game-assets)
* [Game Assets](https://game-asset.net/)
* [Game Dev Market](https://www.gamedevmarket.net/)
* [Kenney](https://kenney.nl/assets) - Free 2D, 3D, and Audio assets for personal and commercial use.
* [Open Game Art](https://opengameart.org/)
* [Unity Assetstore](https://assetstore.unity.com/) - Official asset store for unity.
* [Unitylist](https://unitylist.com/) - Search for everything.

### Creation Tools

* [Aseprite](https://www.aseprite.org/) - Animated sprite editor & pixel art tool.
* [AssetForge](https://kenney.itch.io/assetforge) - Easily create simple assets in seconds (Paid).
* [BFXR](https://www.bfxr.net/) - Make sound effects for computer games (Flash required)
* [MagicaVoxel](https://ephtracy.github.io/) Free to use Voxel editor (even for commercial).
* [Mixamo](https://www.mixamo.com/) - Free to use animation mixing tool with free animations. Not allowed to use in open source projects.

### Audio

* [Sonniss GDC 2018 Pack](https://sonniss.com/gameaudiogdc18/) - Free to use 30GB worth of audio files

## Articles
* [50 Tips and Best Practices for Unity (2016 Edition)](https://www.gamasutra.com/blogs/HermanTulleken/20160812/279100/50_Tips_and_Best_Practices_for_Unity_2016_Edition.php)
* [Unity Package Manager 2018.3+](https://blogs.unity3d.com/2018/05/09/unity-packages-life-cycle/)
* [Cracked Ice Shader](https://80.lv/articles/how-to-build-cracked-ice-in-material-editor/)
* [Unity-Addressable](https://github.com/Wenrong274/Unity-Addressable)

## Books
* [Game Programming Patterns](http://gameprogrammingpatterns.com/) Free and Paid available
* [Unity in Action, Third Edition](https://www.manning.com/books/unity-in-action-third-edition) A book about creating 2D, 3D, and AR/VR games with the awesome Unity game platform.
* [Framework design guidelines](https://learn.microsoft.com/en-us/dotnet/standard/design-guidelines/)
