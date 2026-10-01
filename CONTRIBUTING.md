# Contributing — add your project

For SBGL at HCC members.

## Option A: Fork + Pull Request (recommended)

1. Fork: open https://github.com/neemlama/AWS-SBGL-at-HCC-Student-Builder-Group -> Fork
2. Clone your fork:
```
git clone https://github.com/YOUR-USERNAME/AWS-SBGL-at-HCC-Student-Builder-Group.git
cd AWS-SBGL-at-HCC-Student-Builder-Group
```
3. Make a branch:
```
git checkout -b project/my-project-name
```
4. Copy template:
```
Copy projects/_TEMPLATE to projects/my-project-name
Edit projects/my-project-name/README.md
```
Rules:
- One folder per project: `projects/<short-name>/` lowercase + dashes
- No secrets, no .env, no private photos
- Large files (>10MB): put on Drive + link only

5. Push + PR:
```
git add projects/my-project-name
git commit -m "feat(project): add my-project-name by YOUR-NAME"
git push origin project/my-project-name
```
Then on GitHub: Compare & pull request to `neemlama:master`.

6. Leader reviews + merges. Done.

## Option B: Direct collaborator

If leader added you as Collaborator (Settings -> Collaborators):
```
git clone https://github.com/neemlama/AWS-SBGL-at-HCC-Student-Builder-Group.git
git checkout -b project/my-project-name
# same copy/edit steps
git push origin project/my-project-name
# open PR
```

## After merge

Update `impact/metrics.md` count (leader does this).
