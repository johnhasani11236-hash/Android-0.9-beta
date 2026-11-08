# Android 0.9 Beta SDK (Windows & macOS Archival)

Benvenuto! Questo repository contiene gli SDK originali di **Android 0.9 Beta** per **Windows** e **macOS**, rilasciati originariamente ad agosto 2008. Questi file sono stati preservati per scopi storici, di studio e per l'emulazione dell'archeologia software di Android.

---

## ⚠️ Important Warning / Attenzione

*   **ENG:** **NOT FOR FLASHING!** These are SDK development tools from 2008. They are **NOT** custom ROMs and cannot be flashed onto any modern smartphone or Android device. Doing so may brick your device.
*   **ITA:** **NON DA FLASHARE!** Questi sono strumenti SDK di sviluppo del 2008. **NON** sono ROM personalizzate e non possono essere installate su nessuno smartphone. Usarli su un telefono reale rischia di danneggiarlo permanentemente.

---

## 🛠️ How to run the historical Emulator

### For Windows Users:
1. **Extract:** Download the Windows SDK zip and extract it to a folder (e.g., `C:\Android-SDK-0.9`).
2. **Java Requirement:** This 2008 software requires a legacy Java environment. It is **not compatible** with modern Java (Java 11, 17, 21, etc.). You must install **Java Runtime Environment (JRE) 5 or 6**.
3. **Launch via Command Prompt:**
   * Open the Command Prompt (`cmd`).
   * Navigate to the `tools` directory:
     ```bash
     cd C:\Android-SDK-0.9\tools
     ```
   * Start the emulator:
     ```bash
     emulator.exe
     ```

### For macOS Users:
1. **Extract:** Download the macOS archive and extract it to a folder (e.g., your Desktop).
2. **Java Requirement:** Just like the Windows version, it requires a legacy Java installation (Java 5 or 6) to interpret the old SDK tools.
3. **Launch via Terminal:**
   * Open the **Terminal** app.
   * Navigate to the `tools` directory (adjust the path based on where you extracted it):
     ```bash
     cd ~/Desktop/android-sdk-mac_x86-0.9_beta/tools
     ```
   * Grant execution permissions to the binary:
     ```bash
     chmod +x emulator
     ```
   * Start the emulator:
     ```bash
     ./emulator
     ```
   *(Note for modern Macs with M1/M2/M3 chips: Since this is an ancient x86 32-bit binary, it may require an older Intel Mac or a specific x86 emulation layer to execute).*

---

## 📜 Project Purpose
This repository aims to preserve the early history of the Android Operating System across different platforms before its official commercial release (Android 1.0) on the HTC Dream.

Feel free to star ⭐ the repository if you appreciate software preservation!


