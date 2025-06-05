<h1 align="center">Sakura Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft 1.20.4 (Fabric).</strong>
</p>

---
### Download: https://workupload.com/file/u8dsMaRSgvF

## 📌 Basic Information
- **Minecraft Version:** `1.20.4`
- **Loader:** `Fabric`
- **Difficulty:** `1.5/10` (Beginner)
- **Required JVM Args:** `N/A`
- **Required Mods:**  
  - [Fabric API](https://modrinth.com/mod/fabric-api/versions?g=1.20.4)

---

## 🛠️ Setup Instructions
1. **Install Fabric** for 1.20.4.  
2. Place the client JAR in your `mods` folder.
3. Launch Minecraft with Fabric.

**Verification:**
- 🏆 Success: Login Screen closes and allows you to open GUI.
- 🔒 Failure: Nothing changes.

**Protection:**
- 🧬 Obfuscation: ✅ ???
- ⏰ Verification Timing: Login Screen (On Login Button Press, RShift In Game)

---

## 🔍 Hints (Click to Reveal)
<details>
<summary><strong>🚩 1st Hint</strong></summary>

1. **Finding the auth class:**
   - Search for `java/net/URL` or `java.net.HttpURLConnection` references (2nd option for 100% accuracy).
</details>

<details>
<summary><strong>🚩 2nd Hint</strong></summary>

2. **"This is not a boolean auth...":**
   - Focus on...
		```
		sakurasakurkaef info = new sakurasakurkaef(license, user, expiry);
		onResult.accept(true, info);
		```
	All parameters are `Strings`. Set in any values. and make sure the `onResult.accept` has the "true" value in the first param.
</details>

---

