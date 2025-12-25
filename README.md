# Portfolio Website

A modern, dark-themed portfolio website for data engineers.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right → **New repository**
3. Name it: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Example: If your username is `john-doe`, name it `john-doe.github.io`
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Your Files
You have two options:

#### Option A: Upload via Web Interface (Easiest)
1. In your new repository, click **uploading an existing file**
2. Drag and drop `index.html` from this folder
3. Scroll down and click **Commit changes**
4. Done! Your site will be live at `https://yourusername.github.io` in 1-2 minutes

#### Option B: Using Git (Recommended)
```bash
# Navigate to this folder in terminal
cd path/to/github-portfolio

# Initialize git
git init

# Add files
git add .

# Commit
git commit -m "Initial commit: Add portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages (if needed)
1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Your site will be live at `https://yourusername.github.io`

## 🎨 Customize Your Portfolio

Edit `index.html` and replace:
- **Your Name** - Update in header and throughout
- **Bio/Description** - Update the "About Me" section
- **Projects** - Replace the 3 project cards with your real projects
- **Experience** - Update with your actual work history
- **Contact Links** - Update email, GitHub, LinkedIn, Twitter URLs

### Quick Find & Replace:
- `Your Name` → Your actual name
- `your.email@example.com` → Your email
- `yourusername` → Your GitHub/social media username
- Project descriptions → Your actual projects

## 🌐 Custom Domain (Optional)

Want to use your own domain like `yourname.com`?

1. Buy a domain from [Namecheap](https://namecheap.com), [Google Domains](https://domains.google), or [Cloudflare](https://cloudflare.com)
2. In your repository, create a file named `CNAME` with your domain:
   ```
   yourname.com
   ```
3. In your domain registrar's DNS settings, add:
   - **Type**: A Record
   - **Name**: @ (or leave blank)
   - **Value**: 
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - **Type**: CNAME
   - **Name**: www
   - **Value**: `yourusername.github.io`

4. Wait 24-48 hours for DNS to propagate

## 📱 Features

✨ Dark, sophisticated theme with animated gradients  
🎭 Bold typography (Playfair Display + Plus Jakarta Sans + Sora)  
💫 Smooth animations and micro-interactions  
🎨 Glass morphism effects  
📍 Timeline-style experience section  
💎 Professional gradient accents  
📱 Fully responsive design  

## 🛠️ Tech Stack

- Pure HTML/CSS/JavaScript (no frameworks needed!)
- Google Fonts
- Vanilla JS for navigation
- CSS animations

## 📝 License

Feel free to use this template for your own portfolio!

---

**Need help?** Open an issue or contact me!
