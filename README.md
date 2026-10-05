# NIGHTFALL SUBZERO Unity privacy and support

Static information site for the Unity Windows edition. Source audit date: 5 October 2026. Version: `0.44.0-preview` plus additive 045 runtime source. Separate from the native Godot game.

Publication target: `ResearchForumOnline/Nightfall-Subzero-Privacy`, GitHub Pages from `main:/`. Privacy URL: `https://researchforumonline.github.io/Nightfall-Subzero-Privacy/#privacy`. Support URL: `https://researchforumonline.github.io/Nightfall-Subzero-Privacy/#support`. Support requests use public repository Issues. No email address is invented.

Only this website folder is owned by this task. Game source, settings, provenance and other repositories must remain untouched. The page has inline CSS and no scripts, forms, analytics, cookies, external fonts or embedded media. Hosting and GitHub Issues have separate platform processing.

## Source evidence

Paths below are relative to `../../unity-rebuild`:

- `ProjectSettings/ProjectSettings.asset:15-16,150`: company/product names and 0.44.0-preview version.
- `Assets/Scripts/NightfallMission.cs:118-122,505-518,614,717`: preferences, checkpoint fields, backup/staging files, path and standalone save guard.
- `Assets/Scripts/MissionIntelArchive043.cs:11-25`: diagnostic isolation and local field-intelligence path.
- `Assets/Scripts/IntelArchiveStore043.cs:12-46`: 18 collection masks, SHA-256 corruption checksum, backup and temporary files.
- `ProjectSettings/UnityConnectSettings.asset:6,14-42`: disabled cloud diagnostics, analytics, purchasing, ads and performance reporting.
- `Packages/manifest.json:2-13`: built-in modules; a UnityWebRequest module is present but no gameplay network calls were found in Assets/Scripts.
- `Assets/Scripts/BrandIntro.cs:80,107-108`: VideoPlayer URL is a local StreamingAssets MP4 path.
- `Assets/Scripts/CampaignOperations.cs:11`; `Assets/Scripts/OperationAccess.cs:9-10,32-49`: 18 operations, 12 episode browsing groups, all available.
- `Assets/Scripts/TitleScreen.cs:164-176,499,538`; `Assets/Scripts/NightfallPlayer.cs:262-315`: campaign and standalone entry points, keyboard/mouse controls.
- `Assets/Scripts/MissionIntelRules042.cs:24`: 36 intelligence discoveries.
- `Assets/Scripts/NightfallPlayer.cs:344-357`; `Assets/Scripts/BloodFeedbackRules037.cs:48-50,72-75`: human hit/headshot blood, stronger lethal spray, corpse-hit feedback without new damage or rewards.
- `Assets/Scripts/NightfallEnemy.cs:594-617`: normal damage/death pipeline, fallen-body animation, kill and ammunition recovery.
- `Assets/Scripts/RoomAmbush045.cs:5-6,21,57-79,98-130`: armed adult off-duty guards, seated targets, seven-second breach focus, ammunition and two-grenade reward, decorative playing cards.
- `Assets/Scripts/TacticalExplosives035.cs:196-233`: explosions affect registered living enemies and player; no generic damage to civilian objects.
- `Assets/Scripts/CampaignStory044.cs:169,189,310`; `Assets/Scripts/CampaignOperations.cs:79-81,170-191,262-276`: adult patients, witnesses and custodians are protected story subjects; recovery occurs off site.
- `Assets/Scripts/CampaignBoss.cs:7,318-354`: fictional humanoid demon, coat, horns and glowing eyes; supernatural/religious combat context.
- `Assets/Scripts/CampaignWorld.cs:94`; `Assets/Scripts/CampaignEncounters.cs:459`: 045 environment/ambush integration.

## Content and listing audit

Source-supported play formats: connected campaign and standalone operation replay. Quick Play is the Winter Lance standalone shortcut. There are 18 operations grouped into 12 browsing episodes, not 12 extra modes. Optional seven-second breach focus is an encounter challenge in operations 7, 9 and 11 (zero-based), conditional on eligible guard placement.

Content answers: violence against realistic human adult combatants and a fictional humanoid demon; firearms, grenades, explosions and assassination objectives; visible blood, headshots, fallen bodies and corpse shooting. No implemented dismemberment, decapitation, exposed-organ/wound system. Do not deny violence against unaware or temporarily non-attacking people: the off-duty seated guards can be shot. Adult civilian detention/persecution appears in narrative; no shootable civilian/minor character implementation was found in the inspected runtime paths. No drug, sexual, nudity or profanity content was found in the searched runtime story/text. Decorative cards occur, with no wagering or player gambling system. Final audiovisual content still needs review; this is not an issued IARC rating.

Listing draft: "Trace forged military orders through an offline first-person action-adventure campaign. Follow the connected story or deploy into any of 18 operations, from guarded compounds and coastal archives to submarine compartments, winter trenches and temple expeditions. Recover evidence, confront fictional armed officers, sabotage equipment and solve temple mechanisms before a supernatural finale. Use six firearms, grenades, tactical support and local checkpoints, and collect 36 field-intelligence discoveries. Includes keyboard-and-mouse controls and Low-spec, Balanced and GPU graphics presets."

## Release boundaries and rights

The owner expressly confirmed commercial rights for all supplied MP4 footage and music during this task. This supersedes the earlier unresolved owner-confirmation gate for those supplied assets; the old game provenance file still says false and was not edited. This is an owner statement, not independent documentary rights verification.

No game build, account UI or browser interaction is authorized here. Source findings do not prove installed runtime network behavior, complete audiovisual content, Store certification, controller eligibility or sustained hardware performance. The previous 0.43 Store package does not establish packaging for 0.44 plus 045. Store product route, installed lifecycle and current submission/account eligibility remain unverified. No game release or age-rating claim is made by publishing this information site.
