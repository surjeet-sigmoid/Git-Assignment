# Git-Assignment

Steps

1. Create a new repository in Github

```
used gui for creating repo
```

2. Add a commit to main branch

```
git add .
git commit -m "1st commit to main"
git push origin main
```

Create a feature-1 branch from the main

```
git checkout -b feature-1
```

Add a commit to feature-1 branch

```
git add .
git commit -m "1st commit to feature-1"
git push origin feature-1
```

Add a commit to main branch

```
git checkout main
git pull origin feature-1
git add .
git commit -m "2nd commit to main"
git push origin main
```

Create another feature-2 branch from main

```
git branch feature-2
```

Add a commit to main branch

```
git add .
git commit -m "3rd commit to main"
git push origin main
```

Merge feature-1 to main

```
git merge feature-1
```

Add a commit to main branch

```
git add .
git commit -m "4th commit to main"
git push origin main
```

Add a commit to feature-2 branch

```
git checkout feature-2
git pull origin main
git add .
git commit -m "1st commit to feature-2"
git push origin feature-2
```

Merge feature-2 to main

```
git checkout main
git merge feature-2
git push origin main
```

Delete feature-1 and feature-2 branches

```
git branch -d feature-1 feature-2
git push origin --delete feature-1 feature-2
```

History Graph

![History Graph](Screenshot%202023-02-10%20at%207.11.32%20PM.png)
