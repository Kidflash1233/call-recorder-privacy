# 🚀 GitHub Actions Setup Instructions

## Quick Setup (5 minutes)

### Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `call-recorder-privacy`
3. Description: `Privacy-first call recorder - zero telemetry`
4. Make it **Private** or **Public** (your choice)
5. **DO NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Download Source Code

The source code is ready at:
```
/root/projects/CallRecorder-GitHub-Ready.tar.gz
```

Download this file to your computer.

### Step 3: Extract and Upload

```bash
# Extract the archive
tar -xzf CallRecorder-GitHub-Ready.tar.gz

# Go into the directory
cd CallRecorder

# Initialize git
git init
git add .
git commit -m "Initial commit - Privacy Call Recorder with zero telemetry"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/call-recorder-privacy.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Actions

1. Go to your repository on GitHub
2. Click "Actions" tab
3. If prompted, click "I understand my workflows, go ahead and enable them"
4. The build will automatically start!

### Step 5: Download APK

**Option A: From Releases (Recommended)**
1. Wait for build to complete (~5-10 minutes)
2. Go to "Releases" on the right side
3. Download the APK from the latest release

**Option B: From Artifacts**
1. Click "Actions" tab
2. Click on the latest workflow run
3. Scroll down to "Artifacts"
4. Download `call-recorder-privacy-apk`
5. Unzip to get the APK

### Step 6: Install on batphone

1. Transfer APK to batphone
2. Enable "Install from Unknown Sources" if needed
3. Install APK
4. Grant permissions
5. Configure settings
6. Start recording!

---

## Manual Trigger

If you want to manually trigger a build:

1. Go to "Actions" tab
2. Select "Build Privacy Call Recorder" workflow
3. Click "Run workflow" → "Run workflow"

---

## Troubleshooting

### Build Fails

1. Check the Actions tab for error logs
2. Common issues:
   - Missing dependencies
   - SDK license not accepted (handled automatically)
   - Network issues (retry usually works)

### APK Won't Install

1. Make sure "Install from Unknown Sources" is enabled
2. Check Android version (needs 8.0+)
3. Uninstall previous versions first

---

## Need Help?

- Check GitHub Actions logs for build errors
- Make sure all files were uploaded correctly
- Verify the repository structure matches the source

---

**Built with 🐶 by Max!**
