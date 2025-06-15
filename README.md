# JaneDistrict
====================================
Jane District UE5 Build
README 
====================================

PROJECT OVERVIEW:
-----------------
This Unreal Engine 5 project is part of an immersive browser-based FPS and digital card system called “Jane District: Horror Witch Reporter.” It integrates UE5 features with Solana blockchain utilities and pixel streaming deployment goals.

ENGINE & TOOLSET:
-----------------
- Unreal Engine Version: 5.4.0
- Blueprint + C++ Hybrid Project (C++ preferred for core systems)
- Pixel Streaming enabled
- Composure framework used for cinematic capture
- Plugins Used:
    • Easy Quest (for inventory/card logic)
    • Cesium (3D map support)
    • W3 Solana + Solana Pay (blockchain integration)
    • Avaturn (optional, avatar pipeline)
    • WebRTC (pixel streaming)
    • Possibly OpenXR for VR fallback support

PROJECT GOALS:
--------------
- Ensure build is clean and deployable to a pixel streaming service (Arcane).
- Test and validate card/NFT hooks, if applicable.
- Provide feedback on deployment config or missing assets.

FOLDER NOTES:
-------------
- /Content contains game logic, characters, environments, cards, UI
- /Source contains C++ logic for gameplay systems
- /Plugins contains external dependencies (some might need manual reinstallation)
- /Config contains pixel streaming and multiplayer settings

MISSING OR EXCLUDED:
--------------------
- Some NFT card images and assets replaced with placeholders
- API Keys for Solana and Web3 integrations are removed for security
- Custom Avaturn characters are not included in this test build

NEXT STEPS:
-----------
Please confirm:
1. Unreal Engine version is matching
2. You can open and package the project locally
3. Any missing dependencies or issues

