<h1 align="center">Xenon Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft 1.21/1 (Fabric)</strong>
</p>

---
### Download: https://workupload.com/file/sQQUkE7evuQ

## 📌 Basic Information  
- **Minecraft Version:** `1.21`  
- **Loader:** `Fabric`  
- **Difficulty:** `1.0/10` (Beginner)  
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
- 🧬 Obfuscation: ✅ Light
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Authentication System:**  
   - The client uses offline-mode auth (no server checks).  
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **HWID Generation:**  
   - References `System.getenv` & `System.getProperty`
</details>

---
