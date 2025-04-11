<h1 align="center">Wing Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft 1.19.4 (Fabric)</strong>
</p>

---

## 📌 Basic Information  
- **Minecraft Version:** `1.21`  
- **Loader:** `Fabric`  
- **Difficulty:** `2/10` (Beginner)  
- **Required JVM Args:** `N/A`   
- **Required Mods:**  
  - [Fabric API](https://modrinth.com/mod/fabric-api/versions?g=1.21)  

---

## 🛠️ Setup Instructions  
1. **Install Fabric** for 1.21.  
2. Place the client JAR in your `mods` folder.  
3. Launch Minecraft with Fabric.

**Verification:**  
- 🏆 Success: Client fully loads into game without errors.  
- 🔒 Failure: Crashes your game.  

**Protection:**  
- 🧬 Obfuscation: ❌ 
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Auth Package:**
   - ```me.steinborn.krypton.api.auth```
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **HWID Whitelist:**  
   - Search for string contains "pastebin" (Find the correct link, there are 2 with different purpose each).  
</details>

<details>  
<summary><strong>🚩 3rd Hint</strong></summary>  

3. **Spoofing Values:**  
   - Spoof the fields/variables with your own infromation (UserInstance.class).
</details>  

---
