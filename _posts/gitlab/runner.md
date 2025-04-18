---
title: Setup GitLab Runner on Ubuntu
date: April 17, 2025
---

Steps to install a GitLab runner on an Ubuntu machine.

Add the official GitLab repository.

```
curl -L "https://packages.gitlab.com/install/repositories/runner/gitlab-runner/script.deb.sh" | sudo bash
```

Next, install the latest version of the GitLab runner.

```
sudo apt install gitlab-runner
```