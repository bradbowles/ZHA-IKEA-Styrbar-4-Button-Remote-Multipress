# IKEA Styrbar Multipress (ZHA) — Home Assistant Blueprint

This blueprint adds full multi‑press support for the IKEA Styrbar 4‑button remote when used with ZHA.  
It enables single, double, triple, quadruple, and quintuple presses for all four buttons, plus long‑press for left/right.

## ✨ Features
- 25 independent action slots  
- Adjustable press timeout  
- Reliable multi‑press detection  
- Works with IKEA Styrbar (Remote Control N2)  
- No hard‑coded entity IDs  

## 📦 Supported Buttons & Actions
| Button | 1x | 2x | 3x | 4x | 5x | Long |
|--------|----|----|----|----|----|-------|
| Up     | ✅ | ✅ | ✅ | ✅ | ✅ | — |
| Down   | ✅ | ✅ | ✅ | ✅ | ✅ | — |
| Left   | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Right  | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |

## 🔧 Installation
1. Copy the YAML file from the `blueprint/` folder.
2. In Home Assistant:  
   **Settings → Automations & Scenes → Blueprints → Import Blueprint**
3. Paste the raw URL: https://raw.githubusercontent.com/bradbowles/ZHA-IKEA-Styrbar-4-Button-Remote-Multipress/main/blueprint/ikea_styrbar_multipress.yaml
4. Save and create an automation.

## 📄 License
MIT License.

## Credits
This blueprint is based on work originally published by **Thomas Maurice**:  
https://gist.github.com/thomas-maurice/794d44ed2c0cef7909e2453759ba7a99

Significant restructuring, documentation, and repository packaging by Brad Bowles.
