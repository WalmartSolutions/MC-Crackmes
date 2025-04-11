<h1 align="center">Litka Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft Standalone (Fabric)</strong>
</p>

---

## 📌 Basic Information  
- **Minecraft Version:** `1.16.5`  
- **Loader:** `MCP`  
- **Difficulty:** `2/10` (Beginner)  
- **Required JVM Args:** `-noverify`   
- **Required Mods:**  
  - N/A

---

## 🛠️ Setup Instructions  
1. **Install Litka**.  
2. Place the Litka folder in your `versions` folder.  
3. Launch Minecraft with Litka.

**Verification:**  
- 🏆 Success: Client fully loads into game without errors.  
- 🔒 Failure: Crashes your game.  

**Protection:**  
- 🧬 Obfuscation: ✅ Light
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Editor Crashers:**  
   - If you are using Recaf 4X (You should), in the infromations tab click "Illgeal Signatures" so your decompiler does not crash.
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **HWID Whitelist:**  
   - Search for string contains "pastebin"
</details>  

<details>  
<summary><strong>🚩 3rd Hint</strong></summary>  

3. **The Finale:**  
   - Patch a boolean variable in ```<init>``` method **OR** make HWID List & HWID Getter methods return the same value/s (Harder but better).  
</details>  


---
