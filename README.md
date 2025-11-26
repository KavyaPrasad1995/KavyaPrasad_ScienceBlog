Now that you’ve activated GitHub Pages for your repository and your site is live, the next step is to customize your site. The _config.yml file is Jekyll’s configuration file that controls the basic settings and theming of your blog.

What is the _config.yml file?
It’s a YAML-formatted text file, named exactly _config.yml (with the underscore!).

It should be in the root directory of your repository.

This file tells Jekyll (the engine behind GitHub Pages blogs) how to build your site: what theme to use, its title, description, author, etc.

How to set up your _config.yml:
Create the file:

In your GitHub repository on GitHub.com, click "Add file" > "Create new file".

Name the file exactly _config.yml

Add some basic content. For a minimal blog, use:

text
title: "Kavya Prasad - Science Blog"
description: "Research, data, and product development insights for healthcare and biotech."
author: "Kavya Prasad"
theme: minima
Commit the changes:

Click "Commit changes" after you add/save the file.

What does the file do?
title: The webpage/blog’s headline.

description: Appears below the headline, in search results, and banner.

author: Your name or handle.

theme: “minima” is the simplest blog-ready theme GitHub suggests.

The settings will take effect after about 20 seconds, and you can now add content, posts, or further customize the look.

If you want to publish blog entries or add pages, create .md (Markdown) files or edit index.md/index.html in your repo. 
