git init
vim info.txt
git add info.txt
git commit -m "adding info.txt as a basic self  introduction"
git remote -v
git remote add origin <url of https github repository>
git remote set-url origin https://PAT@github.com/url
git checkout -b main
git switch main
git push origin main




# Importance of Branching Strategies in Collaborative Development

Branching strategies are crucial in collaborative development because they allow developers to work on features and bug fixes in isolated branches, keeping the main branch stable. They enable parallel development by letting multiple team members work independently, reduce merge conflicts through organized integration, and support effective code reviews by providing a clear context for reviewing changes before merging. Overall, branching helps maintain workflow efficiency, code quality, and project stability.

## Key Benefits

- **Isolating features and bug fixes:** Keeps unfinished or experimental code separate from the stable main branch.  
- **Facilitating parallel development:** Allows multiple team members to work on different tasks simultaneously.  
- **Reducing merge conflicts:** Organized branches make merges more predictable and manageable.  
- **Enabling effective code reviews:** Pull requests from branches provide a clear context for reviewing changes.
  
