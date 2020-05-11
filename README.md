# Welcome to GitHub

Welcome to GitHub—where millions of developers work together on software. Ready to get started? Let’s learn how this all works by building and publishing your first GitHub Pages website!

## Repositories

Right now, we’re in your first GitHub **repository**. A repository is like a folder or storage space for your project. Your project's repository contains all its files such as code, documentation, images, and more. It also tracks every change that you—or your collaborators—make to each file, so you can always go back to previous versions of your project if you make any mistakes.

This repository contains three important files: The HTML code for your first website on GitHub, the CSS stylesheet that decorates your website with colors and fonts, and the **README** file. It also contains an image folder, with one image file.

## Describe your project

You are currently viewing your project's **README** file. **_README_** files are like cover pages or elevator pitches for your project. They are written in plain text or [Markdown language](https://guides.github.com/features/mastering-markdown/), and usually include a paragraph describing the project, directions on how to use it, who authored it, and more.

[Learn more about READMEs](https://help.github.com/en/articles/about-readmes)

## Your first website

**GitHub Pages** is a free and easy way to create a website using the code that lives in your GitHub repositories. You can use GitHub Pages to build a portfolio of your work, create a personal website, or share a fun project that you coded with the world. GitHub Pages is automatically enabled in this repository, but when you create new repositories in the future, the steps to launch a GitHub Pages website will be slightly different.

[Learn more about GitHub Pages](https://pages.github.com/)

## Rename this repository to publish your site

We've already set-up a GitHub Pages website for you, based on your personal username. This repository is called `hello-world`, but you'll rename it to: `username.github.io`, to match your website's URL address. If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.

Let's get started! To update this repository’s name, click the `Settings` tab on this page. This will take you to your repository’s settings page. 

![repo-settings-image](https://user-images.githubusercontent.com/18093541/63130482-99e6ad80-bf88-11e9-99a1-d3cf1660b47e.png)

Under the **Repository Name** heading, type: `username.github.io`, where username is your username on GitHub. Then click **Rename**—and that’s it. When you’re done, click your repository name or browser’s back button to return to this page.

<img width="1039" alt="rename_screenshot" src="https://user-images.githubusercontent.com/18093541/63129466-956cc580-bf85-11e9-92d8-b028dd483fa5.png">

Once you click **Rename**, your website will automatically be published at: https://your-username.github.io/. The HTML file—called `index.html`—is rendered as the home page and you'll be making changes to this file in the next step.

Congratulations! You just launched your first GitHub Pages website. It's now live to share with the entire world

## Making your first edit

When you make any change to any file in your project, you’re making a **commit**. If you fix a typo, update a filename, or edit your code, you can add it to GitHub as a commit. Your commits represent your project’s entire history—and they’re all saved in your project’s repository.

With each commit, you have the opportunity to write a **commit message**, a short, meaningful comment describing the change you’re making to a file. So you always know exactly what changed, no matter when you return to a commit.

## Practice: Customize your first GitHub website by writing HTML code

Want to edit the site you just published? Let’s practice commits by introducing yourself in your `index.html` file. Don’t worry about getting it right the first time—you can always build on your introduction later.

Let’s start with this template:

```
<p>Hello World! I’m [username]. This is my website!</p>
```

To add your introduction, copy our template and click the edit pencil icon at the top right hand corner of the `index.html` file.

<img width="997" alt="edit-this-file" src="https://user-images.githubusercontent.com/18093541/63131820-0794d880-bf8d-11e9-8b3d-c096355e9389.png">


Delete this placeholder line:

```
<p>Welcome to your first GitHub Pages website!</p>
```

Then, paste the template to line 15 and fill in the blanks.

<img width="1032" alt="edit-githuboctocat-index" src="https://user-images.githubusercontent.com/18093541/63132339-c3a2d300-bf8e-11e9-8222-59c2702f6c42.png">


When you’re done, scroll down to the `Commit changes` section near the bottom of the edit page. Add a short message explaining your change, like "Add my introduction", then click `Commit changes`.


<img width="1030" alt="add-my-username" src="https://user-images.githubusercontent.com/18093541/63131801-efbd5480-bf8c-11e9-9806-89273f027d16.png">

Once you click `Commit changes`, your changes will automatically be published on your GitHub Pages website. Refresh the page to see your new changes live in action.

:tada: You just made your first commit! :tada:

## Work with GitHub on your computer using GitHub Desktop

**GitHub Desktop** is a free app from GitHub for Windows and Mac that allows you to easily work with your GitHub repositories from your computer. You just saw how you can commit to a repository from GitHub.com, but most developers do the majority of their work from their computer (locally) before pushing it up to GitHub. So let’s try that out!

[Download GitHub Desktop](https://desktop.github.com/)

## Practice: Use GitHub Desktop and an editor to make a change from your computer

Start by downloading GitHub Desktop if you haven’t already done so, and install it on your computer. Go through the GitHub Desktop onboarding steps, and when you get to the “Let’s get started” screen, go ahead and choose the repository you were just working with on GitHub.com, and click “Clone.”

### Using an editor to make changes

Let’s make sure you have a text editor on your computer - this is what you'll use to actually make changes to your files. If you already know you have an editor, then skip to the next step. Otherwise, download and install either [Visual Studio Code](https://code.visualstudio.com/) or [Atom](https://atom.io/) and restart GitHub Desktop before proceeding to the next step.

Let’s make a change to your GitHub Pages site, just like you did on GitHub.com, except this time we’re going to do it all from your computer. From GitHub Desktop, click the “Open in…” button in the middle of the screen to “open the repository in your external editor” that you just downloaded. 

![Open-in-editor](https://user-images.githubusercontent.com/721500/63188833-82fb9600-c030-11e9-8777-a67c1713d59f.png)

In the left sidebar, click the `index.html` file to open it, and go ahead and add another line. Maybe, “Building websites is fun! You should try it too!” or whatever you want to add. 

![Make-changes](https://user-images.githubusercontent.com/721500/63188832-82fb9600-c030-11e9-9f7b-7d15385a16f0.png)

Now switch back to GitHub Desktop, and you should see the change you made.

![View-changes](https://user-images.githubusercontent.com/721500/63188835-82fb9600-c030-11e9-8980-43a8231ca23a.png)

### Commit your changes

Now you can commit your changes by typing a message in the `Summary` box at the bottom left, and then click the blue `Commit` button below that.

![Commit-changes](https://user-images.githubusercontent.com/721500/63188831-8262ff80-c030-11e9-809a-f87d8b544935.png)

### Push your changes to GitHub.com

One of the great things about working on things on your computer is that you get to control when other people see them. Now let’s push your commit to GitHub.com as well so it’s saved there and you can publish it to your site. Click the “Push origin” button to push your commit to GitHub.com. 

![Push-to-GitHub](https://user-images.githubusercontent.com/721500/63188834-82fb9600-c030-11e9-9d8e-6c6ed6d48504.png)

Now click the “View on GitHub” button to get back to your repository’s page on GitHub.com.

![View-on-GitHub](https://user-images.githubusercontent.com/721500/63188836-82fb9600-c030-11e9-9bc5-cf304398500d.png)

### Deploy and see your changes live on your GitHub Pages website!

Once you commit your changes, they are automatically published on your GitHub Pages website. Refresh your browser to see it live!

### Celebrate!

Hooray! Now you have your repository linked between your computer and GitHub.com. In the future, you can use GitHub Desktop to push any changes you decide to make from your computer.

## Extra Credit: Keep on building!

Change the placeholder Octocat gif on your GitHub Pages website by [creating your own personal Octocat emoji](https://myoctocat.com/build-your-octocat/) or [choose a different Octocat gif from our logo library here](https://octodex.github.com/). Add that image to line 12 of your `index.html` file, in place of the `<img src=` link.

Want to add even more code and fun styles to your GitHub Pages website? [Follow these instructions](https://github.com/github/personal-website) to build a fully-fledged static website.

![octocat](./images/create-octocat.png)

## Everything you need to know about GitHub

Getting started is the hardest part. If there’s anything you’d like to know as you get started with GitHub, try searching [GitHub Help](https://help.github.com). Our documentation has tutorials on everything from changing your repository settings to configuring GitHub from your command line.
# Get started building your personal website

### Showcase your software development skills

This repository gives you the code you'll need to kickstart a personal website that showcases your work as a software developer. And when you manage the code in a GitHub repository, it will automatically render a webpage with the owner's profile information, including a photo, bio, and repositories.

Your personal website is waiting to be personalized, though. It includes space to highlight your specific areas of interest in software development, like languages or industries. And it's standing by to publish your next great blog post.

It's all possible using the combination of [Jekyll](https://jekyllrb.com/docs/) (for building your website), [GitHub Pages](https://pages.github.com/) (for hosting your website), and [GitHub's API](https://developer.github.com/v3/) (for automatically populating your website with content).

## Installation

### Fork the `github/personal-website` repo

You'll be making your own copy of the "personal website starter" repository so you have your own project to customize. A "fork" is a copy of a repository. So select "Fork" atop [the `github/personal-website` repository](https://github.com/github/personal-website).

Once you've found a home for your forked repository, it's yours. You're the owner, so you're ready to publish, if you wish.

### Install in your local development environment

If you want to manage your website in a local web development environment, you'll be using [Ruby](https://jekyllrb.com/docs/installation/).

Once you've found a home for your forked repository, **[clone it](https://help.github.com/articles/cloning-a-repository/)**.

#### Install Jekyll

Jekyll is a [Ruby Gem](https://jekyllrb.com/docs/ruby-101/#gems) that can be installed on most systems.

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)
2. Install Jekyll and [bundler](https://jekyllrb.com/docs/ruby-101/#bundler) [gems](https://jekyllrb.com/docs/ruby-101/#gems)
```
gem install jekyll bundler
```
3. Change into your new directory
```
cd personal-website
```
4. Install missing gems
```
bundle install
```
5. Build the site and make it available on a local server
```
bundle exec jekyll serve
```

You should see something like:

```
Configuration file: /octocat/personal-website/_config.yml
            Source: /octocat/personal-website
       Destination: /octocat/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
                    done in 14.729 seconds.
 Auto-regeneration: enabled for '/octocat/personal-website'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
```

Don't worry about the "No GitHub API authentication could be found" message. [API authentication is only necessary](https://github.com/jekyll/github-metadata/blob/master/docs/authentication.md) if you intend to display more detailed metadata, like a branch name.

6. Now browse to [http://localhost:4000](http://localhost:4000)

### Publish

When you host your personal website's code on GitHub, you get the support of free hosting through GitHub Pages.

**The fastest approach** is to rename your repository `username.github.io`, where `username` is your GitHub username (or organization name). Then, the next time you push any changes to your repository's `master` branch, they'll be accessible on the web at your `username.github.io` address.

**If you want to use a custom domain**, you'll want to add it to your repository's "Custom domain" settings on github.com. And then register and/or [configure your domain with a DNS provider](https://help.github.com/articles/quick-start-setting-up-a-custom-domain/).

## Customization

It's your website, and you control the source code. So you can customize everything, if you like. But we've provided a handful of quick customizations for you to consider as you get your website off the ground.

### Quick configuration changes

Most customizations can be done in a matter of seconds, by revising your repository's `_config.yml` file. Just remember to restart your local server each time you save new changes so your Jekyll-powered website rebuilds correctly:

1. Shut down your server by entering the keyboard command <kbd>CTRL</kbd>+<kbd>c</kbd>
2. Restart your server: `bundle exec jekyll serve`


#### Layout

Your website will display in a two-column layout by default on larger-screen devices, with your photo, name, and basic information displayed in a left-aligned "sidebar." You can quickly switch to a "stacked" single-column layout by changing the line in your `_config.yml` file that reads `layout: sidebar` to `layout: stacked`.

#### Style

Your website appears with a "light" white and gray background by default, with dark text. You can quickly switch to a "dark" background with white text by changing the line in your `_config.yml` file that reads `style: light` to `style: dark`.

#### Projects

The "My Projects" section of your website is generated by default with your nine most recently "pushed" repositories. It also excludes repositories that you forked, by default. But each of these parameters can be quickly customized in your repository's `_config.yml` file, under the `projects` dictionary line.

Parameters include:

- `sort_by`: The method by which repositories are sorted. Options include `pushed` and `stars`.
- `limit`: The maximum number of repositories that will be displayed in the "My Projects" section of your website. Out of the box, this number is set to `9`.
- `exclude`:
   - `forks`: When `true`, repositories you've forked will be excluded from the listing.
   - `projects`: A list the repository names you want to exclude from the listing.

#### Topics

Your website comes pre-configured with three topics (e.g. "Web design" and "Sass") that appear in a section titled "My Interests." These are also stored in your repository's `_config.yml` file, where you can define each topic's name and two other optional details:

- `web_url`: The web address you'd like to your topic to link to (e.g. `https://github.com/topics/sass`).
- `image_url`: The web address of an (ideally square) image that you'd like to appear with your topic.

#### Social media

Your website supports linking and sharing to social media services you're using, including Behance, Dribbble, Facebook, LinkedIn, Medium, Stack Overflow, Twitter, and YouTube. To identify the services you use:

1. Edit your repository's `_config.yml` file.
2. Edit the `social_media` dictionary line, and represent the services you like in a simple `key: value` form:

```
social_media:
  behance: your_username
  dribbble: your_username  
  facebook: your_username
  hackerrank: your_username
  instagram: your_username
  keybase: your_username
  linkedin: your_username
  medium: your_username
  stackoverflow: your_user_id
  telegram: your_username
  twitter: your_username
  unsplash: your_username
  vk: your_username
  website: http://your_website_url
  youtube: your_username
```

Links to your profile for each of the services you define will appear in the `<header>` of your website, appended to your bio. And if those services support sharing, any blog posts that you publish will include links to share that post using each social media service.

**Note**: This feature is supported by two files in your repository:

- `/_data/social_media.yml`: Defines each of the supported services, including variable name, display name, URL path, and SVG icon.
- `/_includes/social_media_share_url.html`: Outputs the share URL required for any of the supported social media services that support sharing URLs.

If you're interested in adding a social media service that's not already supported in this repo, you can edit these two files to build that support.

## Adding pages

To **add a page** to your website (e.g. detailed resume):

1. Create a new `.html` or `.md` file at the root of your repository.
2. Give it a filename that you want to be used in the page's URL (e.g. `http://yoursite.dev/filename`).
3. At the start of your file, include the following [front matter](https://jekyllrb.com/docs/front-matter/):

```
---
layout: default
---
```

## Adding blog posts

To **add a blog post** to your website:

1. Create a new `.md` file in your repository's `/_posts/` directory.
2. Give it a filename using the following format:

```
YEAR-MONTH-DAY-title.MARKUP
```

3. At the start of your file, include the following [front matter](https://jekyllrb.com/docs/front-matter/):

```
---
title: "The title of my blog post"
---
```

Your website comes with a placeholder blog post that you can reference. Notably, its [front matter](https://jekyllrb.com/docs/front-matter/) declares `published` as `false`, so that it won't appear on your website.

While you can define a `layout` in the front matter, your website is pre-configured to assign the `post` layout to all of the posts in your `/_posts/` directory. So you don't have to declare that in your posts.

Jekyll's conventions for authoring and managing blog posts is very flexible. You can [learn more in Jekyll's documentation for "Posts."](https://jekyllrb.com/docs/posts/)

## Content and templates

To give you a sound foundation to start your personal website, your repository includes a handful of "includes" -- dynamic `.html` files that are re-used throughout your website. They're all stored in the `/_includes/` directory.

There are the usual suspects, like `header.html` and `footer.html`. But there are few more worth pointing out:

- `interests.html`: A heading and dynamic list of "My Interests," which is populated with the [topics](#topics) you list in your `_config.yml`.
- `masthead.html`: A collection of your avatar, name, bio, and other metadata that's displayed prominently on all your webpages to help identify what the website is about.
- `post-card.html`: A compact, summarized presentation of a blog post, re-used to display a listing of your latest blog posts.
- `projects.html`: A heading and dynamic list of "My Projects," which is populated with a listing of your newest GitHub repositories.
- `repo-card.html`: A compact, summarized presentation of a repository, re-used to display a listing of your GitHub repositories.
- `thoughts.html`: A heading and dynamic list of "My Thoughts," which is populated with a listing of your latest blog posts.
- `topic-card.html`: A compact, summarized presentation of a topic (defined in your `_config.yml`), re-used to display a listing of your interests.

### Layouts

Your repository comes with three layouts:

- **default**: Not used by any of the built-in pages or posts, but useful for any new pages you create.
- **home**: Used by your `index.html` homepage to display listings of your projects, interests, and (optionally) your blog posts.
- **post**: Used by default by the posts in your `/_posts/` directory.

Jekyll's convention for defining layouts is very flexible. You can [learn more about customizing your layouts in the Jekyll "Layouts" docs.](https://jekyllrb.com/docs/layouts/)

## Styles

Your website is pre-configured to use [GitHub's very flexible CSS framework called "Primer,"](https://styleguide.github.com/primer/). It's currently referenced within your `styles.scss` file, using the CSS import at-rule:

```
@import url('https://unpkg.com/primer/build/build.css');
```

You are, of course, welcome to remove it or replace it with another framework. Just bear in mind that the HTML that your website came pre-packaged with references multiple Primer "utility classes" to define things like column widths, margins, and background colors.

You also have the option to add on to and extend Primer's styles by adding custom CSS to your `/assets/styles.scss` Sass stylesheet. By editing this file, you can customize your website's color scheme, typography, and more.


## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
