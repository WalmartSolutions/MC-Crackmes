<h1 align="center">Scrim Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft 1.21/1 (Fabric).</strong>
</p>

---
### Download: https://workupload.com/file/Z6nR2ujeWMz

## 📌 Basic Information  
- **Minecraft Version:** `1.21`  
- **Loader:** `Fabric`  
- **Difficulty:** `1.5/10` (Beginner)  
- **Required JVM Args:** `N/A`   
- **Required Mods:**  
  - [Fabric API](https://modrinth.com/mod/fabric-api/versions?g=1.21)
  
- **Note: This crackme makes connections to the original Auth Site!!!**

---

## 🛠️ Setup Instructions  
1. **Install Fabric** for 1.21/1.  
2. Place the client JAR in your `mods` folder.  
3. Launch Minecraft with Fabric.

**Verification:**  
- 🏆 Success: Client fully loads into game without errors.  
- 🔒 Failure: Closes/Crashes your game.  

**Protection:**  
- 🧬 Obfuscation: ✅ Skidfuscator
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Auth package name:**  
   - The auth package is called `Game`.
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **What method to look for:**  
   - Look for `System.exit` in the bytecode of certain classes.

</details>  

---

