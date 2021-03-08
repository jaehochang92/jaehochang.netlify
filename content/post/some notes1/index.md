---
title: Notes on bash and git
subtitle: 

# Summary for listings and search engines
summary: Some notes on using bash and git.

# Link this post with a project
projects: []

# Date published
date: "2021-3-5T00:00:00Z"

# Date updated
lastmod: "2021-3-5T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
# image:
#   caption: ''
#   focal_point: ""
#   placement: 2
#   preview_only: false

authors:
- admin

tags:
- Academic

categories:
- programming
---

```c
# include<stdio.h>
int main() {
  printf("Hello, I'm Jae. Welcome to my github page!");
  }
```

<h2>Bash</h2>

`$ echo -e "-e allows\nescaping characters"`

```
-e allows
escaping characters
```

`$ cat -n test.txt`\
ㄴ `-n` enumerates each line

`$ bash .../target.sh`\
ㄴ runs inexecutable script

<h2>Gits</h2>

* `git log -n3 code.py` shows the last 3 commits within `code.py`
* `git show [commit-identifier]` shows the details of the commit
* `git revert [commit-identifier]` undoes the changes made in the commit
> in case of the immediate amending, use `git commit --amend`
* `git revert HEAD` undoes the most recent commit
* `git checkout [commit-id] [file-name]` also handles erroneous commits
* `git blame code.py`
> Sometimes you have to find someone to be blamed(but not seriously) for bugs or errors.