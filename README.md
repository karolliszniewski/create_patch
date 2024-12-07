# create_patch

go to module directory


```bash
cd vendor/vertexinc/validator-module
```

create temporary git repo
```bash
 git init
```

```bash
 git init
```

```bash
git add .
git commit -m "Initial commit for patch generation"
```

```bash
git add .
git commit -m "Initial commit for patch generation"
```

and now generate patch (use ../ to back to the root directory)

```bash
git diff > ../../../patches/vertex-validator-missing-param.patch
```

