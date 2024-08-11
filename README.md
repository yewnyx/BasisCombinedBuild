# BasisCombinedBuild
## Workflow
### Writing code
Just write code

### Pulling upstream commits
```bash
git subtree pull --prefix=Basis https://github.com/dooly123/Basis.git main --squash
git subtree pull --prefix=BasisServer https://github.com/dooly123/BasisServer.git main --squash
```

### Pushing commits downstream
```bash
git subtree push --prefix=Basis https://github.com/dooly123/Basis.git main
git subtree push --prefix=BasisServer https://github.com/dooly123/BasisServer.git main
```
(substitute username/branch name as needed)
