<h1 align="center">Syracuse Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft 1.19.2 (Fabric). Obfuscation might be deceiving on the hardness of this crackme for some beginners.</strong>
</p>

---
### Download: https://workupload.com/file/rXXNnTzhvfm

## 📌 Basic Information  
- **Minecraft Version:** `1.19.2`  
- **Loader:** `Fabric`  
- **Difficulty:** `1.5/10` (Beginner)  
- **Required JVM Args:** `N/A`   
- **Required Mods:**  
  - [Fabric API](https://modrinth.com/mod/fabric-api/versions?g=1.19.2)

---

## 🛠️ Setup Instructions  
1. **Install Fabric** for 1.19.2.  
2. Place the client JAR in your `mods` folder.  
3. Launch Minecraft with Fabric.

**Verification:**  
- 🏆 Success: Client fully loads into game without errors.  
- 🔒 Failure: Crashes your game.  

**Protection:**  
- 🧬 Obfuscation: ✅ Skidfuscator
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **URL References:**  
   - Search for ```java/net/URL``` reference. Pay attention to the member names and the method it self that invokes it.  
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **Copy To Clipboard:**  
   - ```net.caffeinemc.phosphor.common.util.chunk.hashmap``` has a method ```copyToClipboard``` that copies your HWID into your clipboard.
</details>  

<details>  
<summary><strong>🚩 3rd Hint</strong></summary>  

3. **HWID Hashing:**  
   - ```MessageDigest``` is used in ```getHWID``` method to Hash your HWID.
</details>  

---
