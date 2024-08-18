---

# TikTok Username Changer

Effortlessly update your TikTok username, even with restricted characters.

## 🚀 Quick Start Guide

### 1. **Create a New TikTok Account**
   - Ensure it is not registered as a US-based account.
   - Use a VPN set to a non-US location for optimal results.
   - Recommended free VPN, no sign-up required:
     - For Firefox: [Urban VPN](https://addons.mozilla.org/en-US/firefox/addon/urban-vpn/)
     - For Chrome: [Urban VPN Proxy](https://chromewebstore.google.com/detail/urban-vpn-proxy/eppiocemhmnlbhjplcgkofciiegomcon)

### 2. **Obtain Your Session ID**
   - Open Developer Tools (press `F12` or `Ctrl+Shift+I`).
   - Navigate to the **Application** tab, then **Storage**, and find **sessionID**. Copy this value.
   - In Firefox, go to Developer Tools > Storage.

### 3. **Install Python** 
   - **Windows**: 
     - Download and install the latest version of Python from [Python.org](https://www.python.org/downloads/windows/). 
   
   - **Linux**: 
     ```bash
     sudo apt-get update
     sudo apt-get install python3.11
     ```

### 4. **Run the Script**
   - Open your terminal or command prompt.
   - Navigate to the directory where the script is located. For example:
     ```bash
     cd path/to/your/script
     ```
   - Execute the script with Python.
     ```bash
     python tiktok.py
     ```
     - On some systems, you might need to use `python3` instead of `python`:
       ```bash
       python3 tiktok.py
       ```
   - When prompted, paste the copied sessionID (`Ctrl+Shift+V` to paste).
   - Enter your desired username. If the username is already in use, add spaces (by pressing the space key) and two random characters after the username.

### 5. **Use an existing username**
   - If the username is already in use, add spaces (keep the space key pressed until it's long, about 20 characters) and add two random characters after the username.

### 6. **Verify Success**
   - You should see a confirmation message: **"Successfully changed username."** ✅

---

**Note:** This tool also allows you to change your username before the standard 30-day cooldown.

---
