# Practical: Create & Review a Merge Request on GitLab

## Objective
Create a feature branch, make changes, push to GitLab, create a Merge Request (MR), and complete a code review.

---

### 1. Terminal Commands (Git Bash)

```bash
# Configure user details
git config --global user.name "UserName"
git config --global user.email "user@gmail.com"

# Clone the remote repository
git clone [https://gitlab.com/user/hii.git](https://gitlab.com/user/hii.git)
cd hii

# Create and switch to a new feature branch
git branch k1
git checkout k1

# Create a sample file and stage changes
touch jk.txt
git add .

# Commit changes
git commit -m "Add jk.txt file for merge request practical"

# Push the branch to GitLab
git push origin k1
