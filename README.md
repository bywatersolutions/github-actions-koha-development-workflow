# github-actions-koha-development-workflow
GitHub Actions workflow to check if Koha branch needs to be rebased

## Add workflow to your branch
```bash
curl --create-dirs -O --output-dir .github/workflows https://raw.githubusercontent.com/bywatersolutions/github-actions-koha-development-workflow/main/devel.yml && git add .github/workflows && git commit -m 'GitHub Actions - Add workflow for Koha development"
```

## NOTE
You should add this commit on top of master, but before the commits for your bug(s)
