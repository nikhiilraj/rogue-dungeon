🧙‍♂️ Rogue Dungeon — ASCII Rogue-Lite in the Terminal
======================================================

_A procedurally generated dungeon crawler built with Node.js + Blessed._

🚀 Overview
-----------

**Rogue Dungeon** is a **fully interactive terminal game** featuring:

*   Procedural dungeon generation
    
*   Turn-based combat
    
*   Basic enemy AI
    
*   Animated attack flashes
    
*   Dungeon levels that get harder
    
*   Stats panel, log panel, and a retro ASCII interface
    

This project was built to learn:

*   Real-time terminal UI using **Blessed**
    
*   2D grid-based game architecture
    
*   State machines & turn loops
    
*   Procedural world generation
    
*   Event-driven keyboard handling in Node.js
    

It’s fast, fun, and highly extensible.

✨ Features
----------

### 🎲 Procedural Dungeon Generation

Every run creates a brand-new map using a “random walk” algorithm.

### ⚔️ Turn-Based Combat

Attack enemies when adjacent — enemies chase & hit back.

### 👺 Enemy AI

Goblins track the player using Manhattan distance or wander randomly.

### 💥 Attack Animations

Cells flash with color when you or an enemy hits.

### 🧭 Full Terminal UI

Built using Blessed:

*   Colored map
    
*   Side stats panel
    
*   Dynamic HP bar
    
*   Enemy list
    
*   Action log
    

### 📈 Level Progression

Clear a floor → move to the next, where enemies grow stronger.

🕹️ Gameplay Preview
--------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   ╔═══════════════════╗  ║     Dungeon 1     ║  ╚═══════════════════╝  ###########################  #@....g...$...............#  #.....###.....G...........#  #...T.....E...............#  ############################  Stats:  HP: ##########---------- (10/20)  ATK: 5  Gold: 3  Log:  You hit goblin for 3 dmg.  Goblin died.   `

📦 Tech Stack
-------------

*   **Node.js**
    
*   **Blessed** (for rendering UI)
    
*   Plain JavaScript (no frameworks)
    
*   Procedural generation
    
*   Event-driven architecture
    

📁 Project Structure
--------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   rogue-dungeon/  │  ├── package.json  └── src/      ├── dungeon.js   # Procedural generation      └── game.js      # UI, logic, combat, rendering   `

🛠️ Installation & Setup
------------------------

### 1\. Clone the repo

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   git clone https://github.com/YOUR_USERNAME/rogue-dungeon.git  cd rogue-dungeon   `

### 2\. Install dependencies

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   npm install   `

### 3\. Run the game

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   npm start   `

🎮 Controls
-----------

ActionKeysMoveArrow Keys / WASD / HJKLNext floor**N**Restart after death**R**Quit**Q / Esc / Ctrl+C**

🔮 Future Enhancements (Planned)
--------------------------------

*   Fog of War (Field of View)
    
*   Items: potions, weapons, armor
    
*   Inventory menu & equipment
    
*   More enemy types (archers, trolls, mages)
    
*   Boss fights on milestone floors
    
*   Save & load system (JSON)
    
*   Mini-map
    
*   Smooth movement animations
    

🧠 What I Learned
-----------------

This project taught me:

*   Designing interactive CLI apps
    
*   Managing game loops & rendering cycles
    
*   Modeling entities and game state
    
*   Procedural content generation
    
*   Building complex interfaces with **Blessed**
    
*   Writing cleaner, modular JavaScript architecture
    

🤝 Contributing
---------------

Feel free to:

*   Submit bugs
    
*   Suggest new mechanics
    
*   Open PRs
    
*   Add new enemies, items, or spells
    

Let’s build a full roguelike universe together ⚔️

📜 License
----------

MIT License free to use, modify, and share.