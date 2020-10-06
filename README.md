# wklib

## Configuration
### Creation
```bash
go mod init github.com/rebirthmonkey/wklib
go mod tidy
```

### Pkg Version
```bash
git tag v1.0.0
git push --tags
``` 

### 大版本
wklib
```bash
git commit testmod.go -m "Change Hi to allow multilang"
git checkout -b v2 # optional but recommended
git tag v2.0.0
git push --tags origin v2 # push to the branch v2 instead of master
```

go.mod
```bash
module github.com/rebirthmonkey/wklib/v2
```
