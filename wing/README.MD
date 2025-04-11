<h1 align="center">Wing Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft 1.19.4 (Fabric)</strong>
</p>

---

## 📌 Basic Information  
- **Minecraft Version:** `1.19.4`  
- **Loader:** `Fabric`  
- **Required JVM Args:** `N/A`   
- **Difficulty:** `2/10` (Beginner)  
- **Required Mods:**  
  - [Fabric API](https://modrinth.com/mod/fabric-api/versions?g=1.19.4)

---

## 🛠️ Setup Instructions  
1. **Install Fabric** for 1.19.4.  
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

2. **HWID Whitelist:**  
   - Valid HWIDs are stored in:  
     ```plaintext
     assets/mousetweaks/security.txt  
     ```  
</details>  

<details>  
<summary><strong>🚩 3rd Hint</strong></summary>  

3. **HWID Generation:**  
   - The client fetches HWID using a **PowerShell script** (check runtime commands).  
</details>  


---
