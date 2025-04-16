<h1 align="center">Virgin V4 Crackme</h1>

<p align="center">
  <strong>A not so beginner-friendly reverse engineering challenge for Minecraft 1.21.4 (Fabric). Uses JNIC but you will be shown full tutorial on how to defeat it.</strong>
</p>

---
### Download: https://workupload.com/file/3GeTCCxPjHM

### Patched DLL for Noobs: https://workupload.com/file/veQsQnUk6dL

## 📌 Basic Information  
- **Minecraft Version:** `1.21.4`  
- **Loader:** `Fabric`  
- **Difficulty:** `4.0/10` (Intermediate)  
- **Required JVM Args:** `N/A`   
- **Required Mods:**  
  - [Fabric API](https://modrinth.com/mod/fabric-api/versions?g=1.21.4)

---

## 🛠️ Setup Instructions  
1. **Install Fabric** for 1.21.4.  
2. Place the client JAR in your `mods` folder.  
3. Launch Minecraft with Fabric.

**Verification:**  
- 🏆 Success: Client fully loads into game without errors.  
- 🔒 Failure: Crashes your game.  

**Protection:**  
- 🧬 Obfuscation: ✅ JNIC & Skidfuscator
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Focus on the native:**  
   - Run the client in order to convert the ".bin" into a ".dll" (Unpacked) and focus on the ".dll" it self (Look into %temp% and find a "lib753897837573578375.tmp" looking like file).
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **Jar as Hint:**  
   - If you look at the class ```me.fallenbreath.fastipping.client.Main```, the method names can give you a Hint at what function you will be looking at in the ".dll"
</details>  

## Tutorial

![video](https://github.com/WalmartSolutions/MC-Crackmes/raw/refs/heads/main/virgin%20v4/Tutorial%20(By%20TwoNick))

---
