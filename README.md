<or create a new repository on the command line>
echo "# My-first-github-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nmf-wasi/My-first-github-repo.gitgit push -u origin main


<or push an existing repository from the command line>
git remote add origin https://github.com/nmf-wasi/My-first-github-repo.gitgit branch -M main
git push -u origin main


<From begininning>
git init
git add .
git commit -m "first commit"
git branch -M main
git push -u origin main


<in the middle>

git push -u origin main
