<h1 align="center">VegaLine Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft Standalone (MCP)</strong>
</p>

---
### Download: https://workupload.com/file/yzbLKfwasHZ

## 📌 Basic Information  
- **Minecraft Version:** `1.12.2 (Use JDK 17.0.6)`  
- **Loader:** `MCP`  
- **Difficulty:** `2.0/10` (Beginner)  
- **Required JVM Args:** `N/A`   
- **Required Mods:**  
  - N/A

---

## 🛠️ Setup Instructions  
1. **Install VegaLine**.  
2. Place the VegaLine folder in your `versions` folder.  
3. Launch Minecraft with VegaLine.

**Verification:**  
- 🏆 Success: Client fully loads into game without errors.   
- 🔒 Failure: Fail popup in russian + exit.

**Protection:**  
- 🧬 Obfuscation: ➖ Specific Classes, Very light.
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Hide & Seek:**
   - Do not let the Class or Method names fool you. They might appear as ordinary, but they are not.
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **"!dlroW ,olleH":**  
   - Search for "//:" in order to find backwards "https://" containing strings (Sensitive classes only).
</details>

<details>  
<summary><strong>🚩 3rd Hint</strong></summary>  

3. **Do not overthink:**  
   - Locate all references to the Auth class and replace any return values with your own. Some of the code might look like it is important in the Auth class in order for the client to function properly but no.
</details>  

---
