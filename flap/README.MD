<h1 align="center">Flap Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft Standalone</strong>
</p>

---

## 📌 Basic Information  
- **Minecraft Version:** `1.8.9`  
- **Loader:** `MCP`  
- **Difficulty:** `1/10` (Beginner)  
- **Required JVM Args:** `N/A`   
- **Required Mods:**  
  - N/A

---

## 🛠️ Setup Instructions  
1. **Install Flap**.  
2. Place the Flap file in your `versions` folder.  
3. Launch Minecraft with Flap.

**Verification:**  
- 🏆 Success: Lets you into the Main Menu screen.  
- 🔒 Failure: Nothing happens.  

**Protection:**  
- 🧬 Obfuscation: ❌ 
- ⏰ Verification Timing: Login Screen (On Button Press)

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Auth Package:**
   - ```vestige.util.keyauth```
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **KeyAuth Reference:**  
   - Search for References on class ```vestige/util/keyauth/api/KeyAuth``` (LoginScreen will show up).  
</details>

<details>  
<summary><strong>🚩 3rd Hint</strong></summary>  

3. **What Method?:**  
   - Edit the ```mouseClicked``` method inside the ```LoginScreen``` class.
</details>  

---
