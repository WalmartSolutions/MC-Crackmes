<h1 align="center">Biggie Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft Standalone (MCP)</strong>
</p>

---
### Download: https://workupload.com/file/8XWJsFfuPrT

## 📌 Basic Information  
- **Minecraft Version:** `1.8.9`  
- **Loader:** `MCP`  
- **Difficulty:** `2/10` (Beginner)  
- **Required JVM Args:** `-noverify`   
- **Required Mods:**  
  - N/A

---

## 🛠️ Setup Instructions  
1. **Install Biggie**.  
2. Place the Biggie folder in your `versions` folder.  
3. Launch Minecraft with Biggie.

**Verification:**  
- 🏆 Success: Lets you into the Main Menu screen.  
- 🔒 Failure: Nothing happens.

**Protection:**  
- 🧬 Obfuscation: ✅ Junkcode
- ⏰ Verification Timing: Login Screen (On Button Press)

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **Find the Login Screen:**
   - It looks like there is no string obfuscation. Try searching for some words that are in the Login Screen whenever you run the client.
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **GuiMainMenu References:**  
   - Search for References on class ```GuiMainMenu```, one of the resulting class is the Login Screen.
</details>

<details>  
<summary><strong>🚩 3rd Hint</strong></summary>  

3. **Some Getters and Setters:**  
   - I suggest you search for "127.0.0.1" (as we already removed the original connection for your safety) and look at 1 of the 2 resulting classes. There are some setter calls related to Auth.
</details>  

---
