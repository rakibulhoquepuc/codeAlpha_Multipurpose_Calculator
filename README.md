# Multipurpose Calculator Suite  
_A flexible, all-in-one web calculator — no installs, runs privately in your browser._  

The Multipurpose Calculator Suite is a single-file HTML app that combines a **Basic Calculator**, **Scientific Functions**, **Weight Converter**, **Currency Exchange**, and **Extras** (like a tip calculator and themes). Open it by double-clicking, and switch between tabs to handle anything from quick arithmetic to advanced calculations.  

---

## ✨ Features
- **Click-to-run:** one standalone `index.html` file. No build, no dependencies.  
- **Basic Calculator:** clean interface with keyboard support, percent, and parentheses.  
- **Scientific Mode:** functions for `sin`, `cos`, `tan`, `ln`, `log10`, `exp`, constants (`π`, `e`), and power/roots.  
- **Weight Conversion:** convert between kg, g, mg, lb, oz, and tonnes with swap + clear.  
- **Currency Exchange:** editable JSON rates (default base = USD). Swap currencies or paste updated rates.  
- **Extras:** quick tip calculator and instant theme toggle (Dark Neon / Light Pastel).  
- **Keyboard-friendly:**  
  - Basic: `0–9`, `+ - * / . % ( )`, **Enter**=equals, **Backspace**=delete, **Esc**=clear  
  - Scientific: adds `^ ,` and letters to type `sin`, `cos`, `tan`, `ln`, `log`, `exp`, `pi`, `e`  
- **Responsive:** adapts to mobile and desktop layouts.  
- **Privacy-first:** all calculations stay on your device, no servers, no network calls.  

---

## 🚀 Quick Start
1. Download `index.html` from the project ZIP.  
2. Double-click to open it in your browser.  
3. Use the tab bar at the top to switch modes:
   - **Basic** → everyday math.  
   - **Scientific** → advanced functions.  
   - **Weight** → convert units instantly.  
   - **Currency** → convert amounts with editable rates.  
   - **Extras** → tip calculator + themes.  

---

## ⌨️ Keyboard Shortcuts
- **Basic tab:**  
  - Digits / operators (`+ - * / . % ( )`) → append  
  - **Enter / =** → equals  
  - **Backspace** → delete  
  - **Esc** → clear  

- **Scientific tab:**  
  - Digits / operators (`+ - * / ^ . , ( )`) → append  
  - Type function names directly: `sin`, `cos`, `tan`, `ln`, `log`, `exp`, `pi`, `e`  
  - **Enter / =** → equals  
  - **Backspace** → delete  
  - **Esc** → clear  

> Keyboard input is automatically disabled while typing in Weight or Currency fields.

---

## 🧠 How it works
- Entire app is self-contained in a single HTML file with embedded CSS and JavaScript.  
- Tabs switch visible `<section>` panels dynamically.  
- Expressions are parsed and sanitized before safe evaluation.  
- Scientific functions map to `Math.*` in JavaScript.  
- Conversions are handled via simple multipliers (weight) or user-defined JSON (currency).  
- Themes use CSS custom properties toggled via JavaScript.  

---

## 🛠 Customization
Open `index.html` and look for:
- **Theme variables:** CSS `:root` defines color palettes.  
- **Default rates:** update the `defaultRates` object in the script for currency.  
- **Units:** add/remove items in the weight converter dropdown.  
- **Extras:** extend with new panels (length, temperature, etc.).  

---

## 🧪 Browser Support
- **Recommended:** Chrome 90+, Edge 90+  
- **Also works:** Firefox, Safari (some UI differences possible)  
- **Mobile:** Chrome/Edge on Android, Safari/Chrome on iOS  

---

## 🗺️ Roadmap
- [ ] Length and temperature converters  
- [ ] Memory functions (M+, M-, MR, MC) in calculators  
- [ ] History log of recent calculations  
- [ ] Live currency API integration  
- [ ] Additional themes  

---

## 🤝 Contributing
Issues, feature requests, and PRs welcome. Keep it **dependency-free** and test across browsers.  

## 📸 Screenshots
<img width="1017" height="578" alt="image" src="https://github.com/user-attachments/assets/c66a5a8f-2baa-4fb0-914a-0399e9b5714b" />
<img width="796" height="619" alt="image" src="https://github.com/user-attachments/assets/3da98173-5ead-4ed7-a950-b5cac6cd2fcb" />
<img width="818" height="279" alt="image" src="https://github.com/user-attachments/assets/854ae0a2-2a82-4e90-abdf-475e426fdbbd" />
<img width="817" height="323" alt="image" src="https://github.com/user-attachments/assets/73cb1266-3b77-4666-8c17-9f977ce9cf59" />
<img width="823" height="294" alt="image" src="https://github.com/user-attachments/assets/c5247645-ebc4-4678-8c44-c83491ae7f6b" />






---

## 🛡️ License
MIT — free to use, modify, and share.  

