# How to Install the Nutrition Calculator on Your iPhone

## Method 1: Quick Local Installation (Easiest)

### Step 1: Transfer Files to iPhone
1. **Using AirDrop (Mac users):**
   - Select all files in the `nutrition-app` folder
   - Right-click and choose "Share" > "AirDrop"
   - Select your iPhone
   - Files will open in Safari

2. **Using Email:**
   - Zip the `nutrition-app` folder
   - Email it to yourself
   - Open on iPhone and tap to view

3. **Using iCloud Drive:**
   - Upload the `nutrition-app` folder to iCloud Drive
   - Open Files app on iPhone
   - Navigate to the folder

### Step 2: Install as App
1. Open `index.html` in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Name it "Nutrition" 
5. Tap "Add"

The app icon will appear on your home screen and work offline!

## Method 2: Host Online (More Professional)

### Free Hosting Options:

#### Option A: GitHub Pages (Recommended)
1. Create a GitHub account at github.com
2. Create a new repository
3. Upload all files from `nutrition-app` folder
4. Go to Settings > Pages
5. Select "Deploy from branch" > main
6. Your app will be at: `https://[username].github.io/[repo-name]`

#### Option B: Netlify Drop
1. Go to https://app.netlify.com/drop
2. Drag the entire `nutrition-app` folder to the page
3. Get instant URL
4. Open URL on iPhone Safari
5. Add to Home Screen

#### Option C: Vercel
1. Go to vercel.com
2. Sign up for free account
3. Import project (upload folder)
4. Get instant URL

### Install from Web URL:
1. Open the URL in Safari on iPhone
2. Tap Share button
3. Tap "Add to Home Screen"
4. Name it and tap "Add"

## Method 3: Using a Local Web Server

If you want to test locally with your computer and iPhone on same WiFi:

### On Windows:
```bash
cd C:\Users\jfama\nutrition-app
python -m http.server 8000
```

### On Mac:
```bash
cd ~/nutrition-app
python3 -m SimpleHTTPServer 8000
```

Then on iPhone:
1. Find your computer's IP address (run `ipconfig` on Windows or `ifconfig` on Mac)
2. On iPhone Safari, go to: `http://[your-computer-ip]:8000`
3. Add to Home Screen

## Features Once Installed:
- Works offline
- Full-screen experience (no browser bars)
- Fast loading
- Touch-optimized interface
- Saves your selections locally

## Troubleshooting:
- Make sure you use Safari (not Chrome) on iPhone
- Clear Safari cache if app doesn't update
- For offline use, open the app once while online first
- Icons will show as generic until you add icon image files

## Creating App Icons (Optional):
To add custom icons, create PNG images:
- `icon-192.png` (192x192 pixels)
- `icon-512.png` (512x512 pixels)

Place them in the same folder as index.html.