# Steps

## Step 1

Clone the repository

```bash
git clone https://github.com/popuga/automatisation-lab2.git
cd automatisation-lab2
```

## Step 2

Create a new branch

```bash
git checkout -b feature/add-steps
```

## Step 3

* Add steps to the `steps.md` file
* Add link to the steps to the `README.md` file

## Step 4

Commit the changes

```bash
git add steps.md README.md
git commit -m "Added steps"
```

## Step 5 (optional)

Push the changes to the remote repository

```bash
git push origin feature/add-steps
```

## Step 6

You can either:

**Option A:** Create a pull request on GitHub and merge

OR

**Option B:** Merge locally

```bash
git checkout main
git pull origin main
git merge feature/add-steps --no-ff -m "merge: add steps feature"
git push origin main
```

## Step 7

Delete the feature branch

```bash
git branch -d feature/add-steps
git push origin --delete feature/add-steps
```
