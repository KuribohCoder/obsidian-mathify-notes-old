# Mathify Notes (Fixed & Enhanced for iPad & Desktop)

Auto-convert plain math and chemistry shorthand into LaTeX in Obsidian notes on spacebar.

### Fixes & Enhancements in this release
- **Full engine restored**: Fixes the broken upstream 1.6.x truncated release.
- **Italian / Unicode support**: Typing `più` or other accented words will **not** turn into $\pi$ù.
- **Direct `beta` expansion**: Typing `beta` converts to $\beta$ (e.g. `foglietto beta` $\rightarrow$ `foglietto $\beta$`), while preserving words like `diabete` or `alfabeto`.
- **Protected `e/o`**: Common Italian congiunzione `e/o` is preserved and not converted to a fraction.
- **iPadOS Compatible**: Works seamlessly on iPad (M-series / A-series) and Mac/PC.

### How to install on iPad via BRAT
1. In Obsidian on iPad, install and enable the community plugin **BRAT** (Beta Reviewer's Auto-update Tool).
2. Open Obsidian Settings $\rightarrow$ **BRAT**.
3. Under **Add Beta plugin**, paste this repository link:
   ```
   https://github.com/KuribohCoder/obsidian-mathify-notes
   ```
4. Tap **Add Plugin**. BRAT will download `manifest.json`, `main.js`, and `styles.css`.
5. Enable **Mathify Notes** under **Community plugins**.
