# graph-module-cleanup
PowerShell automation script to audit and remove Microsoft Graph modules for lab cleanup and enterprise environment resets.

🧹 Microsoft Graph Module Cleanup

PowerShell script to audit and remove Microsoft Graph modules from a system.

---

📌 Overview

This tool automates:

- Detection of installed Microsoft Graph modules
- Removal of all installed versions
- Verification of remaining module traces

Designed for IT environments, lab resets, and troubleshooting broken Graph installs.

---

⚙️ Features

- Bulk module processing
- Removes all versions automatically
- Post-cleanup verification
- Clean, readable console output

---

🚀 Usage

Run PowerShell as Administrator:

.\graph-cleanup.ps1

---

⚠️ Warning

This script will remove Microsoft Graph modules from your system.

Ensure you:

- Have proper permissions
- Can reinstall modules if needed

---

🧠 Development Note

Created with AI-assisted development and adapted for real-world IT operations.

---

🛠️ Future Improvements

- [ ] Logging to file
- [ ] Dry-run mode (-WhatIf)
- [ ] Parameterized module input
- [ ] Enhanced error handling

---

👤 Author

Wylie Wolf
Coyote Security LLC
