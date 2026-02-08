# GitHub Pages Project

A modern, responsive website template ready for GitHub Pages deployment.

## 🚀 Features

- **Fully Responsive** - Works on desktop, tablet, and mobile devices
- **Modern Design** - Clean UI with CSS Grid and Flexbox
- **Smooth Animations** - Engaging user experience with CSS animations
- **Interactive Navigation** - Smooth scrolling and active link highlighting
- **Zero Dependencies** - Pure HTML, CSS, and JavaScript

## 📁 Project Structure

```
.
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Local Development

To preview the site locally:

1. **Option 1: Live Server Extension (Recommended)**
   - Install the "Live Server" extension in VS Code
   - Right-click on `index.html` and select "Open with Live Server"

2. **Option 2: Python HTTP Server**
   ```bash
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser

3. **Option 3: Simply open the file**
   - Double-click `index.html` to open in your default browser

## 📤 Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it (e.g., `my-github-pages-site`)
3. Don't initialize with README (you already have one)

### Step 2: Push Your Code

Run these commands in your terminal:

```bash
git init
git add .
git commit -m "Initial commit: GitHub Pages site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

### Step 4: Access Your Site

After a few minutes, your site will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

## 🎨 Customization

### Update Content

Edit [index.html](index.html) to change:
- Site title and meta description
- Hero section text
- About section content
- Feature cards
- Contact information

### Modify Styling

Edit [style.css](style.css) to customize:
- Colors (change CSS variables in `:root`)
- Fonts
- Layout and spacing
- Animations

### Add Functionality

Edit [script.js](script.js) to add:
- Form validation
- API integrations
- Custom interactions

## 🌐 Custom Domain (Optional)

To use a custom domain:

1. Buy a domain from a registrar (GoDaddy, Namecheap, etc.)
2. Add a `CNAME` file to your repository with your domain:
   ```
   www.yourdomain.com
   ```
3. Configure DNS settings with your registrar:
   - Add a CNAME record pointing to `YOUR-USERNAME.github.io`
4. In GitHub Settings → Pages, enter your custom domain

## 📝 Tips

- **Update `<title>` tag** in `index.html` for better SEO
- **Add meta tags** for social media sharing (Open Graph, Twitter Cards)
- **Include a favicon** by adding `<link rel="icon" href="favicon.ico">`
- **Optimize images** before adding them to keep the site fast
- **Test responsiveness** using browser dev tools (F12 → Device toolbar)

## 🔧 Troubleshooting

**Site not loading?**
- Wait a few minutes after enabling GitHub Pages
- Check the Actions tab for build status
- Ensure `index.html` is in the root directory

**Styles not applying?**
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check that file paths are correct (relative paths)

**404 error on links?**
- Use relative paths, not absolute paths
- Check file name capitalization (GitHub Pages is case-sensitive)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and customize it for your needs!

---

**Made with ❤️ and deployed with GitHub Pages**
