<h1 align="center">Krypton Client Crackme</h1>

<p align="center">
  <strong>A beginner-friendly reverse engineering challenge for Minecraft 1.21 (Fabric)</strong>
</p>

---
### Download: https://workupload.com/file/MPmdcgbFK3q

## 📌 Basic Information  
- **Minecraft Version:** `1.21`  
- **Loader:** `Fabric`  
- **Difficulty:** `2/10` (Beginner)  
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
- 🧬 Obfuscation: ✅ Skidfuscator
- ⏰ Verification Timing: Initialization

---

## 🔍 Hints (Click to Reveal)  
<details>  
<summary><strong>🚩 1st Hint</strong></summary>  

1. **URL... Socket... What do I look for?:**  
   - Search for [```java/net/Socket```](https://www.geeksforgeeks.org/java-net-socket-class-in-java/) references as they use Socket for their Auth.
</details>  

<details>  
<summary><strong>🚩 2nd Hint</strong></summary>  

2. **Booleans everywhere!:**  
   - There are 4 methods which you need to modify. 2 are "boolean" return types and 2 "CompletableFuture"
</details>  

<details>  
<summary><strong>🚩 3rd Hint</strong></summary>  

3. **Comptabdsfs what?:**  
   - The code for the 2 methods (You can compile this code and just view the compiled code in Recaf and paste over the bytecode into Krypton):
   ```
		CompletableFuture<Boolean> success = new CompletableFuture<Boolean>();
		success.complete(true);
		return success;
	```
</details>  

---
