# صبا کوچولو 🍓

A magical, interactive website featuring Barry the Strawberry with 3D effects, animations, and sparkles!

## 🚀 Deployment Guide - GitHub Pages

### Prerequisites
- Git installed on your computer
- A GitHub account

---

## 📦 Step 1: Prepare Your Files

Make sure you have these files in the `صبا کوچولو` folder:
- `index.html` ✅
- `barry.webp` ✅
- `README.md` (this file)

---

## 🔧 Step 2: Initialize Git Repository

Open **Git Bash** or **Terminal** in the `صبا کوچولو` folder and run:

```bash
# Initialize git
git init

# Add all files
git add .

# Make first commit
git commit -m "Initial commit: صبا کوچولو website"
```

---

## 🌐 Step 3: Create GitHub Repository

1. Go to [GitHub.com](https://github.com)
2. Click the **"+"** button (top right) → **"New repository"**
3. **Repository name:** `saba-kocholo` (or any name you like)
4. **Description:** "A magical website for صبا کوچولو 🍓"
5. Keep it **Public** (required for free GitHub Pages)
6. **Don't** initialize with README (we already have one)
7. Click **"Create repository"**

---

## 📤 Step 4: Push to GitHub

Copy the commands from GitHub's "push an existing repository" section, or use:

```bash
# Add GitHub remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/saba-kocholo.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

**Example:**
```bash
git remote add origin https://github.com/AmirMahdi/saba-kocholo.git
git branch -M main
git push -u origin main
```

Enter your GitHub username and password (or personal access token) when prompted.

---

## 🌟 Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top menu)
3. Scroll down to **"Pages"** (left sidebar)
4. Under **"Source"**, select:
   - Branch: **`main`**
   - Folder: **`/ (root)`**
5. Click **"Save"**

---

## ✅ Step 6: Access Your Website

Wait 1-2 minutes, then your website will be live at:

```
https://YOUR_USERNAME.github.io/saba-kocholo/
```

**Example:**
```
https://AmirMahdi.github.io/saba-kocholo/
```

🎉 **Done! Your website is now live!**

---

## 🔄 Updating Your Website

If you make changes to the website:

```bash
# Add changes
git add .

# Commit changes
git commit -m "Update website"

# Push to GitHub
git push
```

Changes will appear on GitHub Pages within 1-2 minutes!

---

## 🎨 Features

- ✨ **3D Particle System** with strawberries, hearts, and sparkles
- 🍓 **Custom Strawberry Cursor** (desktop)
- 💫 **Magical Particle Trails** following Barry
- ⭐ **Twinkling Background Stars**
- 🎊 **Confetti Explosion** on hidden message reveal
- 👀 **Interactive Barry** that reacts to cursor
- 💥 **Click Effects** creating ripples and sparkle bursts
- 📱 **Fully Responsive** for mobile and desktop

---

## 🛠️ Troubleshooting

### Problem: Git not recognized
**Solution:** Install Git from [git-scm.com](https://git-scm.com)

### Problem: GitHub authentication failed
**Solution:** Use a Personal Access Token instead of password:
1. Go to GitHub → Settings → Developer settings → Personal access tokens
2. Generate new token (classic)
3. Select `repo` scope
4. Use token as password

### Problem: Website not showing
**Solution:** 
- Wait 2-3 minutes
- Check GitHub Pages settings
- Ensure repository is Public
- Hard refresh browser (Ctrl+F5)

### Problem: Images not loading
**Solution:** 
- Ensure `barry.webp` is in the same folder as `index.html`
- File names are case-sensitive!

---

## 📝 Notes

- Keep repository **Public** for free GitHub Pages
- Use lowercase and hyphens for repository name (e.g., `saba-kocholo`)
- The website works offline - just open `index.html` in browser!
- All animations and effects work without internet (CDN fallbacks included)

---

## 💝 Made with Love

Created for صبا کوچولو 🍓💖✨

---

## 📱 Sharing

Once deployed, simply share the link:
```
https://YOUR_USERNAME.github.io/saba-kocholo/
```

Your friend can access it from any device - phone, tablet, or computer!

---

**Enjoy! 🎉**
