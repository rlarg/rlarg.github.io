---
layout: page
title:  Setting up your own personal website
permalink: info
---

We'll be using [Jekyll][jekyll-docs] to make the website and hosting it through [Github Pages](https://docs.github.com/en/pages/quickstart).

Follow the [installation guide](https://jekyllrb.com/docs/installation/) for your operating syste. You can continue from part **2. Setup**, after you've succesfully installed Jekyll. I will go through the Windows guide as that's what I'm using.


The requirements you will need are:
- [Ruby](https://rubyinstaller.org/downloads/)
- gems
- Jekyll
- a decent code editor, such as [VSCode](https://code.visualstudio.com/)

# 1. Installation

1. Go to the [Ruby Installer Downloads](https://rubyinstaller.org/downloads/) website and download Ruby+Devkit 2.7.X (x64) - I got the 2.7.5 version.
2. Click the through the defaults for the Installation Wizard and make sure the checkbox is ticked to launch `ridk install` on the last page of the installer. This will install gems and any other extensions you might need.
3. `ridk install` will open a command prompt. Press `1` then `Enter`. Wait for the downloads to complete, then press `3` then `Enter`. After the downloads have finished, exit the command prompt.  
4. Open powershell or a new command prompt and check you've sucessfully installed gems by typing `gems -v`. Finally install Jekyll and the bundler by typing `gem install jekyll bundler`
5. Check you've sucessfully installed gems by typing `jekyll -v`.

# 2. Setup

- Open your terminal (or powershell for Windows) and `cd` to a directory you can easily access. You will need to go to this directory later in a terminal to run the website. Your home directory is fine.

- Type `jekyll new FILE` where `FILE` is what you want to name your jekyll project. (I put mine as `profile`).

- This will create a new Jekyll project with all the files required to build a website.

Open up the project in VSCode. You should see a file structure similar to the follwing:

```
FILE
  _posts
  _site
  .jekyll-cahce
  _config.yml
  .gitignore
  404.html
  about.markdown
  Gemfile
  Gemfile.lock
  index.markdown
```

- There are quite a few but at the but you'll only really need to use and edit a few of them to get a basic website running.

- To run the website, press `ctrl '` in VSCode to open up a terminal.

- `cd` into  the directory where you saved your `FILE`

- Type `bundle exec jekyll serve` in the terminal and follow the link to the server to see your website in your default browser.

---
_In progress:_
> #### 3. Customisation
> #### 4. Hosting

Follow [this YouTube seminar](https://www.youtube.com/watch?v=8NkxcaxRacA) to complete your setting up your own website while I work on the last part of this guide, which was based on this video.  

---


[jekyll-docs]: https://jekyllrb.com/docs/home

