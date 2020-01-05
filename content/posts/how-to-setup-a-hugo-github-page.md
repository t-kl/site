---
title: "How to Setup a Hugo Github Page"
date: 2020-01-05T15:16:31+01:00
draft: false
---
# Create a GitHub Account
## Getting started with GitHub
* [Set up Git](https://help.github.com/en/github/getting-started-with-github/set-up-git)
* [Create a repo](https://help.github.com/en/github/getting-started-with-github/create-a-repo)

Make sure to name the repository ```<user>.github.io```.

## Getting started with GitHub Pages
* [Creating a GitHub Pages site](https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site)

# Install Hugo
* [Quick Start](https://gohugo.io/getting-started/quick-start)

# Clone Repository
We want to push the generated files in ```public``` to _GitHub_.
Thus we clone the repository in there:
```
git clone https://github.com/<user>/<user>.github.io.git public
```

# Generate new static site
With the following command a new version is generated:
```
hugo
```

# Publish content to _GitHub_
Now the changes can be added and pushed to _GitHub_:
```
git -C public add --all
git -C public commit -m "<write a meaningful commit message>"
git -C public push
```
