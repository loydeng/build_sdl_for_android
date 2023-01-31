build SDL for android with cmake

1. download repo

`git clone <this repo url> --recurse-submodules`

2. checkout branch to SDL releas

```
cd app/src/main/jni/SDL/
git checkout -b v2.26.x refs/remotes/origin/release-2.26.x
```

3. build SDL generate libs

`./gradlew :app:build`

4. Now can get libs and header files in "app/output" dir
