# Push to GitHub Using GitHub Desktop

## Step-by-Step Instructions:

### Step 1: Open GitHub Desktop
1. Launch GitHub Desktop application

### Step 2: Add Your Local Repository
1. Click **File** → **Add Local Repository**
2. Click **Choose...** button
3. Navigate to and select your folder: `C:\Users\premc\OneDrive\Desktop\portfolio-main\portfolio-main`
4. Click **Add repository**

### Step 3: Connect to Your GitHub Repository
1. In GitHub Desktop, you'll see your files listed
2. At the top, you might see "Publish repository" button - **DON'T click it yet**
3. Instead, click **Repository** → **Repository Settings** → **Remote**
4. Or if you see "Publish repository", it will ask for the remote URL
5. Enter: `https://github.com/premchand93470/my_portfolio.git`
6. Click **Save**

### Step 4: Stage All Files
1. In the left panel, you'll see all your files
2. Make sure these files are checked (staged):
   - ✅ index.html
   - ✅ images/indiajoy-stage.jpg.png
   - ✅ script.js
   - ✅ styles.css
   - ✅ README.md
   - ✅ DEPLOYMENT-GUIDE.md
3. If any files are unchecked, check them all

### Step 5: Commit
1. At the bottom left, type a commit message: `Initial portfolio commit`
2. Click **Commit to main** (or **Commit to master**)

### Step 6: Push to GitHub
1. Click **Push origin** button (top right)
2. Or click **Repository** → **Push**
3. Wait for it to complete

### Step 7: Enable GitHub Pages
1. Go to https://github.com/premchand93470/my_portfolio
2. Click **Settings** tab
3. Scroll down to **Pages** in left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Branch: **main** (or **master**)
6. Folder: **/ (root)**
7. Click **Save**
8. Wait 1-2 minutes

### Step 8: Access Your Live Portfolio
Your portfolio will be live at:
**https://premchand93470.github.io/my_portfolio/**

🎉 **Your portfolio is now live and permanent!**

---

## Troubleshooting:

**If "Add Local Repository" doesn't work:**
- Click **File** → **Clone Repository**
- Go to **URL** tab
- Enter: `https://github.com/premchand93470/my_portfolio.git`
- Choose local path: `C:\Users\premc\OneDrive\Desktop\portfolio-main\portfolio-main`
- Click **Clone**
- Then copy your files into that folder
- Commit and push

**If files don't show up:**
- Make sure you're in the correct folder
- Check that `images/indiajoy-stage.jpg.png` exists in the `images` folder

