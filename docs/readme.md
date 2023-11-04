
(tempicon.png)
# linjaloje
a small engine for small games

## Engine Goals
The goal of this project is to make something to build 2d walkaround style games that include some action mechanics. Directly: this is targeting the niche between RPG Maker and Game Maker that want a simple tilemap with 4-way walking, a moderately advanced dialog system with animation integration, basic inventory/menu GUI, and a framework for creating relatively simple real-time mechanics and/or microgames.  

### Simplicity
The main pillar is currently simplicity. Out of the box, a new non-technical user should be able to grab the repo, compile successfully in vscode, and create a simple level with a character walking around and talking to NPCs with minimal friction.

### Speed
A secondary pillar is speed of production, both within the engine and of the engine itself. The first phase of engine produciton is getting an MVP up utilizing existing generic tools. Support for importing data from these tools is planned to continue as the engine matures.  
To facilitate quick creation and prototyping, there will be a continued effort to improve the user experience and keep commonly used features accessible and remove any points of friction. The integrated tools will be opinionated for this purpose, while still allowing and integrating nicely with common industry tools that users may be prefer or simply be more familiar with.

## Technologies
The engine uses GLFW for OpenGL context creation and management, some stb single-header libraries for image and font loading, dear imgui for editor GUI, and miniaudio for audio.
