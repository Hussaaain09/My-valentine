# Valentine's Memory Lane 💜

A personalized, interactive Valentine's Day proposal website with a quiz about your relationship, designed with a lavender theme for a talented data analyst and artist.

## ✨ Features

### 🎯 Interactive Quiz
- 3 personalized questions about your relationship:
  - Favorite food together (Momos 🥟)
  - Favorite place to roam (Burhanpur 🏰)
  - Her favorite ice cream (Orange Popsicle 🍊)
- Progress tracking with beautiful lavender animations
- Wrong answer shake effect, correct answer celebration

### 💜 Main Proposal Screen
- Data analyst/database themed code blocks and SQL queries
- Highlights her talents: Arts 🎨, Drawing ✏️, BSc IT 💻
- References her work at Toothsi Aligners with "smile alignment" query
- Beautiful lavender gradient design throughout

### 🎉 Yes Response
- Your couple photo displays with heart burst animation
- 20+ hearts fly out in all directions with rotation effect
- Continuous sparkle overlay on the photo
- Animated success code blocks
- Romantic final message

### 😿 No Response (Playful Warnings)
- Every 2-3 rejections shows a sad kitten image
- Progressive warning messages about "data corruption"
- Database error messages that escalate:
  - "WARNING: Your memories might get corrupted!"
  - "CRITICAL: Database integrity at risk!"
  - "FATAL: All romantic data will be lost!"
- Technical error codes like "HEART_BROKEN_EXCEPTION"
- Option to reconsider and go back

## 🎨 Design

- **Color Scheme**: Lavender gradients (#e6e6fa, #d8bfd8, #dda0dd)
- **Theme**: Data analyst/developer with SQL queries and code blocks
- **Mobile-First**: Fully responsive card design
- **Animations**: Smooth transitions, heart bursts, sparkles, shake effects

## 📁 Files Needed

You need to upload these files to GitHub:
1. `index.html` - The main website file
2. `couple-photo.jpeg` - Your couple photo (the one you uploaded)
3. `README.md` - This file

## 🚀 Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon (top right) → **"New repository"**
3. Repository name: `valentine-2025` (or any name you like)
4. Set to **Public**
5. **Don't** check "Add a README file"
6. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop all 3 files:
   - `index.html`
   - `couple-photo.jpeg`
   - `README.md`
3. Scroll down and click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
# Navigate to your folder with the files
cd path/to/your/folder

# Initialize git
git init

# Add all files
git add index.html couple-photo.jpeg README.md

# Commit
git commit -m "Valentine's proposal website"

# Add your GitHub repository as remote
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/valentine-2025.git

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top navigation)
3. Scroll down and click **"Pages"** (left sidebar)
4. Under **"Source"**, select **"Deploy from a branch"**
5. Under **"Branch"**, select **"main"** and **"/ (root)"**
6. Click **"Save"**
7. Wait 1-2 minutes for deployment

### Step 4: Access Your Live Site! 🎉

Your website will be available at:
```
https://YOUR-USERNAME.github.io/valentine-2025/
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## 📱 How It Works

### Quiz Flow
1. Welcome screen with "Let's Begin" button
2. Three questions in sequence (must answer correctly to proceed)
3. Progress bar shows 33%, 66%, 100%
4. After all correct answers → Main proposal screen

### Main Proposal
- Shows all her talents and achievements
- SQL query themed for her data analyst background
- Two buttons: "YES!" and "No"

### Yes Path ❤️
- Your couple photo appears
- Hearts burst out from the center in a circular pattern
- Sparkle effect overlays the photo continuously
- Success message with code block
- Infinite loading animation

### No Path 💔
- Shows ERROR 404 screen
- After 2nd and 3rd rejection, shows sad kitten images
- Warning messages get progressively more "severe"
- Error codes like technical exceptions
- Always has option to reconsider

## 🛠️ Customization Options

Want to personalize it more? Here's what you can easily change:

### Change Colors
Find these lines in the `<style>` section and modify:
```css
background: linear-gradient(135deg, #e6e6fa 0%, #d8bfd8 50%, #dda0dd 100%);
```

### Update Questions
Edit the question text and options in the HTML:
```html
<p class="question-text">What's our favorite food to eat together?</p>
```

### Add More Talents
Add more badges in the proposal screen:
```html
<span class="talent-badge">🎵 Music Lover</span>
```

### Change Messages
Update the final success message or error warnings in the JavaScript section.

## 💡 Tips

- **Test locally first**: Open `index.html` in your browser before uploading
- **Photo size**: Make sure your photo isn't too large (under 2MB is good)
- **Mobile view**: Most people will view this on their phone, so test it there!
- **Share link**: Once deployed, share the GitHub Pages URL with her

## 🎁 What Makes This Special

- Personalized quiz about YOUR relationship memories
- References her actual job and talents
- Lavender theme (presumably her favorite color)
- Fun, playful interactions without being pushy
- Beautiful heart burst effect with your actual photo
- Tech-themed for her data analyst background

## ❤️ Good Luck!

Hope she says yes! The website is designed to be charming, personal, and fun. The quiz shows you remember your special moments together, and the tech theme shows you appreciate her skills and profession.

---

Made with 💜 for someone special
