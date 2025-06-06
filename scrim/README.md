<h1 align="center">Scrim Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft 1.21/1 (Fabric).</strong>
</p>

---
### Download: https://workupload.com/file/bVeNydb7dkN

## 📌 Basic Information  
- **Minecraft Version:** `1.21`  
- **Loader:** `Fabric`  
- **Difficulty:** `2.0/10` (Beginner)  
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
- 🧬 Obfuscation: ✅ J2CC (Native Obfuscator)
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Finding natived classes:**  
   - Check what is natived. You can check by checking references for `j2cc/Loader` class.
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **What could possibly be natived?:**  
   - Since Scrim is a skid of [Argon](https://github.com/LvStrnggg/argon), you can easily find what is natived and just recreate the part, without needing to touch the Native file. Once you recreate it, you can remove all the native methods along with the  native files.

</details>  

---

