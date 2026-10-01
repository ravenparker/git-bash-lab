# Module 0 Git Terminal Lab
## Steps
1. Create new repository \
Created repo called "git-bash-lab" on GitHub: https://github.com/ravenparker/git-bash-lab (hi you're in here already since you're reading this)
2. Clone the repository 
```bash
git clone git@github.com:ravenparker/git-bash-lab.git
```
3. Open the repo
```bash 
cd git-bash-lab
```
4. Create a README.md file
```bash
touch README.md
```
5. Make changes to README.md 
These are all of these steps so far. Some of these steps were added by directly editing the README file in the code editor. The first few lines were added with the following command in the terminal instead:
```bash
echo "I wrote some things here to add to the bottom of the README file" >> README.md
```
6. Stage changes 
```bash
git add .
```
7. Commit changes
```bash
git commit -m "specified all changes here"
```
8. Upload changes to GitHub's remote repo
```bash
git push
```