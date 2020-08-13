# actions-auto-release
Automatically create a release on master push

## Workflow:

Command | Result
---|---
```git add .``` | Add files to commit
```git commit -m "message for commit"``` | Commit files
```git tag v1.0.0 -m "message for tag"``` | Tag version
```git push --follow-tags``` | Push commit along with tags




