# 🏆 JUDGES - QUICK START GUIDE

## 🚀 How to Run Finance Tracker Light

### ⚡ EASIEST METHOD (100% GUARANTEED TO WORK)

**Simply double-click: `finance-tracker-standalone.html`**

That's it! This version has everything embedded and works in ANY browser without any setup.

---

### ✅ RECOMMENDED METHOD (Most Reliable)

1. **Extract all files** to a folder (ensure folder structure is preserved)
2. **Open terminal/command prompt** in the project folder
3. **Run ONE of these commands:**
   ```bash
   # If you have Python installed:
   python -m http.server 8000
   # OR
   python3 -m http.server 8000
   
   # If you have Node.js installed:
   npx http-server
   
   # If you have PHP installed:
   php -S localhost:8000
   ```
4. **Open browser** and go to: `http://localhost:8000`
5. **Click on `start.html`** for compatibility check, then launch the app

### 🔄 ALTERNATIVE METHOD (Direct File)

1. **Double-click `start.html`** (this checks compatibility)
2. **Click "Launch Finance Tracker"**
3. **If styling is missing:** Try opening `index.html` directly in different browsers

### 📁 Required File Structure
```
Finance-Tracker/
├── finance-tracker-standalone.html  ← EASIEST OPTION: DOUBLE-CLICK THIS!
├── start.html          ← START HERE FOR BEST EXPERIENCE
├── index.html          ← Main application
├── readme.md
├── css/
│   └── style.css       ← Styling (must be in css folder)
└── js/
    └── app.js          ← JavaScript (must be in js folder)
```

### 🐛 Troubleshooting

**Problem:** Page looks unstyled or broken
**Solution:** 
- Use the web server method above
- Check if files are in correct folders
- Try a different browser (Chrome, Firefox, Edge)
- Check browser console (F12) for error messages

**Problem:** JavaScript not working
**Solution:**
- Ensure js/app.js exists in the js folder
- Try refreshing with Ctrl+F5 (or Cmd+Shift+R on Mac)
- Use the start.html compatibility checker

### 🎯 Demo Instructions
- **No installation needed** - everything runs in the browser
- **Register a new account** or test the demo functionality
- **All data is stored locally** - no server or database required
- **Fully responsive** - works on desktop and mobile

### 📊 Key Features to Test
1. **User Authentication** - Register/Login system
2. **Transaction Management** - Add income and expenses
3. **Categories** - Add/delete custom categories in Settings
4. **Charts** - Visual analytics in Charts section
5. **Filtering** - Filter transactions by category, type, month
6. **Responsive Design** - Resize browser window to test mobile view

---
**Need Help?** The application includes detailed error logging in the browser console (F12 → Console tab)

**Built with:** Pure HTML, CSS, JavaScript - No frameworks or dependencies except Chart.js CDN
