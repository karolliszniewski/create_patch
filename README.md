# create_patch

1. go to module directory


```bash
cd vendor/vertexinc/validator-module
```

2. create temporary git repo
```bash
 git init
```

```bash
git add .
git commit -m "Initial commit for patch generation"
```

3. Now make changes

4. and now generate patch (use ../ to back to the root directory)

```bash
git diff > ../../../patches/vertex-validator-missing-param.patch
```

