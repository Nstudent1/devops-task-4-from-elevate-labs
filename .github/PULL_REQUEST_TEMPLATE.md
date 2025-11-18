## Summary
This pull request introduces the initial setup for the Task 4 DevOps Git project.  
It adds the required project structure, documentation files, Git workflow templates,  
and prepares the repository for proper branching, version control, and collaboration.

## What changed
- Added `README.md` with project description, objectives, and workflow details  
- Added `.gitignore` with MacOS, VS Code, Python, Node, and environment ignores  
- Added `CONTRIBUTING.md` with branch naming rules and commit message guidelines  
- Added `CHANGELOG.md` with initial placeholders for version tracking  
- Added `docs/tasks.md` to document Task 4 steps, commit history, and notes  
- Added `.github/PULL_REQUEST_TEMPLATE.md` for standardized PR formatting  
- Added `LICENSE` file placeholder (to be updated with selected license) 

## Related issues / tasks
- Task 4: Build a Version-Controlled DevOps Project with Git  
- Repository initialization and documentation setup  
- Branching and workflow preparation  
- DevOps assignment requirement: PR usage and documentation  

## Testing
- Verified file structure in VS Code  
- Confirmed all Markdown renders correctly in GitHub preview  
- Ensured `.gitignore` successfully ignores expected files on macOS  
- Tested branch creation and merges locally using `git checkout -b`, `git merge`, and PR previews  
- Confirmed no merge conflicts on test runs  

## Notes
- This PR should be merged into the `dev` branch before merging into `main`  
- The project is now ready for feature branches (`feature/*`)  
- After merging, update the `CHANGELOG.md` with commit hash and PR number  
- Once license text is finalized, update the `LICENSE` file accordingly  

