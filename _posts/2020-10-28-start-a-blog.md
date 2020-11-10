---
title:  Starting Your Own Diary
tag:  tutorial
---

Just like deep learning, blogging is for anyone willing to give it a try. If you like the style and layout of my Deep Learning Diary and want to add a something like it to your own projects, I'll show you how in this post. 

My website and this blog are being hosted through [GitHub Pages](https://pages.github.com/). GitHub Pages are freely hosted, static websites tied to your GitHub repositories. That means there is no cost to you for making the site available on the internet.  

GitHub Pages is a great for starting blogs or writing documentation about your project. But, it's not recommended to use GitHub Pages to run your ecommerce business.

# Creating a Personal URL #

You must create a personal URL before creating sites for your projects. Just as your project repositories are found under your username, your project pages are also found under your personal URL.

A personal URL will be created when you create a GitHub repository with a very specific name. GitHub will then look for web content on a branch called `gh-pages` from this special repository. 

To create your personal URL, follow these steps:

1. Create a new GitHub repository named `USERNAME.github.io` replacing `USERNAME` with whatever your GitHub username is
    - Example:  I would create a repository called `nurriol2.github.io`
    - Suggestion:  Create the repository with the github.com GUI instead of the command line or terminal
2. Navigate to the repository's *Settings* tab then find a section called **GitHub Pages**
3. Under the **GitHub Pages** section, click *Choose Theme*, and choose a theme you like
    - Suggestion:  The theme and default website content can be changed later. So, don't worry too much about your choice.
4. On the next screen, add a helpful commit message and click *Commit Changes*.
    - Example:  'Initial GitHub Pages commit'
5. Wait about 10 minutes for your website to be served
6. In your preferred web browser, go to `USERNAME.github.io` to see your newly created site
    - Be sure to replace `USERNAME` with your GitHub username

## General Notes ##

**Making Changes to the Page**  
It was convenient to use the GUI on github.com to initialize the repository because we needed to navigate to *Settings* in the next step. Once the site is running, though, this method is not required for committing changes. You can clone the repository to your machine and manage it like any other GitHub repository because that's exactly what it is!

**GitHub Pages for Existing Repositories**  
You are not restricted to this single page for all of your content. As I mentioned earlier, creating a personal URL is only a prerequisite. To make a GitHub Pages website for your existing project, simply follow steps 2 through 6.

**Building "something more ambitious"**  
This entire post was written in a simple markdown file. But GitHub Pages lets me turn that file into a stylized website using a tool called Jekyll. In another post, I go over some examples of using Jekyll to personalize your blog.

**Learning Resources**  
I had a ton of help getting this started. Here are the resources I used.
- [What is GitHub Pages?](https://pages.github.com/)
- [Getting Started with GitHub Pages](https://guides.github.com/features/pages/)
- [How to Create & Host a Portfolio in 10 minutes with Github pages!](https://www.youtube.com/watch?v=u-RLu_8kwA0)
