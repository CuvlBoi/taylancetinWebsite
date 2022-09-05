---
title: "Deneme 1 "
date: 2022-09-01T13:15:28+03:00
draft: false
tags: [ 'inceleme', 'amorf' ]
categories: 'music'
artist: 'Duman'
---


content
    All content for your website will live inside this directory. Each top-level folder in Hugo is considered a content section. For example, if your site has three main sections—blog, articles, and tutorials—you will have three directories at content/blog, content/articles, and content/tutorials. Hugo uses sections to assign default content types.
data
    This directory is used to store configuration files that can be used by Hugo when generating your website. You can write these files in YAML, JSON, or TOML format. In addition to the files you add to this folder, you can also create data templates that pull from dynamic content.
layouts
    Stores templates in the form of .html files that specify how views of your content will be rendered into a static website. Templates include list pages, your homepage, taxonomy templates, partials, single page templates, and more.
static
    Stores all the static content: images, CSS, JavaScript, etc. When Hugo builds your site, all assets inside your static directory are copied over as-is. A good example of using the static folder is for verifying site ownership on Google Search Console, where you want Hugo to copy over a complete HTML file without modifying its content.

From Hugo 0.31 you can have multiple static directories.

resources
    Caches some files to speed up generation. Can be also used by template authors to distribute built SASS files, so you don’t have to have the preprocessor installed. Note: resources directory is not created by default.