RECCOMAI — QUICK INSTALLATION CHECKLIST
=======================================

   BEFORE YOU BEGIN
   - Make sure **Python 3.10.8** is installed on your PC
     → https://www.python.org/ftp/python/3.10.8/python-3.10.8-amd64.exe
   - During installation, CHECK the option: “Add Python to PATH”
   - If you have an NVIDIA GPU with at least 6 GB VRAM, consider the GPU version.
   - If your CPU doesn’t support AVX2 (pre-2014), download the AVX-free version.

0) LET’S GET STARTED
   - Extract the ZIP file to a folder (do not run the EXE inside the ZIP).
   - Inside the extracted folder, you MUST see:
     • ReccomAI_Installer.exe
     • ReccomAI_Installer-1.bin, -2.bin, ... (all .bin files present)
   - Keep EXE and BIN files together in the SAME folder.

1) INSTALL
   - Double-click: ReccomAI_Installer.exe
   - If Windows warns you (SmartScreen): “More info” → “Run anyway”
   - Choose a destination folder (default is fine)
   - Wait: it will automatically install Python 3.10.8 if missing
   - At the end, check: “Start ReccomAI now” (recommended)

2) LAUNCH
   - You can always launch from: “ReccomAI” icon on Desktop
   - Keep the black window open (this is the engine)
   - Open your browser and check:
     • Model:  http://127.0.0.1:8091/health → should return {"status":"ok"}
     • WebUI:  http://127.0.0.1:8000/      → chat interface should open
   - If the firewall asks: allow access on PRIVATE NETWORKS

3) USE
   - Go to http://127.0.0.1:8000/ and start chatting
   - Everything runs LOCALLY. No data is sent online.
   - Free version = CPU only (answers may take a few seconds)

4) EXIT
   - To close ReccomAI: simply close the black console window
   - To reopen: double-click “ReccomAI” icon on Desktop

5) COMMON ISSUES (QUICK FIXES)
   - “Corrupted file” or missing files? Did you extract the ZIP? Are EXE + .BINs together?
   - Port 8000 not loading? Wait 10–20s and try again. Restart if needed.
   - Firewall alert? Allow access on PRIVATE networks.
   - Slow? That’s expected — CPU version. Be patient!
   - Missing DLLs (VCRUNTIME/MSVCP)? Contact support. (The Pro version will auto-fix this.)

6) UNINSTALL
   - Windows → Settings → Apps → ReccomAI → Uninstall
   - Or from Start menu → “Uninstall ReccomAI”

7) NEED HELP?
   - Send us: Windows version, installation folder, error message
     and (if possible) the last 20 lines of the black console window.
