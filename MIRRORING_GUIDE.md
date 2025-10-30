GitLab → GitHub Repository Mirroring Guide

Objective:
To learn and demonstrate how to mirror a GitLab repository to GitHub, so that every commit pushed to GitLab automatically syncs to GitHub.
---
Step-by-Step Setup

1.Create a Repository in GitLab
Go to GitLab → New Project → Create Blank Project.
Initialize with a README file.

2.Create a Repository in GitHub
Create a new empty repository on GitHub.
Copy its HTTPS or SSH URL.

3.Configure Mirroring in GitLab
 3.1. Navigate to Settings → Repository → Mirroring repositories.  
 3.2. Under Push Mirror,paste your GitHub repo URL.  
 3.3. Select Push direction (GitLab → GitHub).  
 3.4. Add your GitHub Access Token or credentials.  
 3.5. Click Mirror Repository.

Now every push to GitLab will automatically appear on GitHub.

Verify the Mirroring
 - Make a commit in GitLab.
 - Wait for a few seconds.
- Check GitHub → the same commit appears there 🎉
