# Cleanup GitHub — Release 0.0.3

## Goal

Remove duplicate legacy folders from GitHub.

## Important

Uploading a new ZIP to GitHub does not delete old files.  
To clean the repository, old folders must be deleted manually or through Git.

## Option A — Simple GitHub web cleanup

Delete these legacy folders/files from GitHub:

- `adr`
- `ai-context`
- `book`
- `governance`
- `prompts`
- `specs`
- root `VISION.md`

GitHub deletes folders only when their files are removed. Open each folder, delete the files inside, then commit the deletion.

## Option B — Cleaner way

Create a new repository and upload only this clean 0.0.3 release.

Recommended only if the manual deletion becomes annoying.

## After cleanup

The repository root should show only:

- `AI`
- `Book`
- `Foundation`
- `Governance`
- `Releases`
- `Templates`
- `CHANGELOG.md`
- `README.md`
- `RELEASE-NOTES.md`
- `ROADMAP.md`
