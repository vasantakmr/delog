---
template: BlogPost
path: /git daemon
date: 2021-07-18T16:25:33.937Z
title: git daemon
---
```shell
# starts daemon but doesnt allow us to push to that server. 
git daemon --base-path=. --export-all --reuseaddr --informative-errors --verbose

# starts daemon and allows us to push to server
git daemon --base-path=. --export-all --enable=receive-pack --reuseaddr --informative-errors --verbose

```
