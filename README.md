
## tracke some big extension
```
git lfs track "*.psd"
```

## create big file
```
dd if=/dev/zero of=test.psd bs=1024 count=0 seek=$[1024*100]
```
