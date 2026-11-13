"# primeirocodigo" 
git checkout -b branch-a
git add. git && commit -m "Branch A"
git checkout main
git checkout -b branch-b
git commit -m "Branch B"
git checkout main
git merge branch-a
git merge branch-b
git add README.md
git commit -m "Resolve conflito"
