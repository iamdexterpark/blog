# blog
Hugo code base for https://iamdexterpark.github.io

All commands are meant to run under the `blog` directory.

# Add a new page

```shell
hugo new pages/about.md
```

# Add a new post

```shell
hugo new posts/my-first-post.md
```

# Verify changes locally 
```shell

hugo server

```

# Save website

```shell

hugo -t PaperMod
git add .
git commit -m "commit message"
git push origin main

# Update submodule pointing towards site repo
cd public
git add .
git commit -m "commit message"
git push origin main
```