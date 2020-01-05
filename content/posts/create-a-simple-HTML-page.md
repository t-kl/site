---
title: "Create a Simple HTML Page"
date: 2020-01-05T22:34:59+01:00
draft: false
---

# Album Covers
## Absolute Beginners
The goal is to create a simple web-site where you can show your favorites album.
You will learn a bit of _HTML_, _CSS_ and _JavaScript_ on this tour.

## Setup
We're using _Google Chrome_ both for writing and displaying the page.

### Directory
Create a new directory `album-covers` somewhere, for instance on your _Desktop_ or in your _Documents_.

### Developer Tools
* Start _Google Chrome_ and drag and drop that folder to the browser.
* Open up the _Developer Tools_ with: `alt+cmd+I` (`⌥ ⌘ I`).
* Switch to _Filesystem_ and _+ Add folder to workspace_.
* Allow _Chrome_ access to this directory.
* Dock _DevTools_ to the right or left. Whatever you prefer.
* Set _Appearance_ to _Dark Theme_ in the _Preferences_.

## Create an HTML File
* Right-click in the _Filesystem_ on the directory `album-covers` and create a _New File_.
* Name the file `index.html` and open it in the browser window as well.

## Skeleton for an HTML File
You can copy and paste the following code-snippet to your `index.html` file and then reload the browser:
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Album Covers</title>
    </head>
    <body>
        <h1>Albums</h1>
    </body>
</html>
```
You should see now `Album Covers` in the tab of the browser and `Albums` as heading in the page.

We also need an `index.css` file for _CSS_ and an `index.js` file for _JavaScript_.

## Development Cycle
You can now add more tags and content to the page.

You will end up in a loop where you:
* edit the `index.html` page
* save the page
* reload the page

![Developer Tools](/images/album-covers-chrome-developer-tools.png)

## Result
The final page can be seen here: [Albums](https://t-kl.github.io/album-covers)

Here's how to clone the repository:
```
git clone https://github.com/t-kl/album-covers.git
```
You can search for a song. Only matching albums are shown.

## GitHub Pages
Once the repository is on _GitHub_ you can publish the page in:

_Settings_ -> _GitHub Pages_ -> _Source_ -> _master branch_

Cf. [Choosing a publishing source](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source)