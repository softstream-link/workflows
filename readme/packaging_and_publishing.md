# Move v1 tag
```shell
git tag --delete v1
git push --delete origin v1
git tag --annotate v1 --message "moving v1"
git push --tags
```
