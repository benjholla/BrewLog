# BrewLog

## Background
[Jekyll](https://github.com/jekyll/jekyll) is a static site generator that's perfect for GitHub hosted blogs.

[Jekyll-now](https://github.com/barryclark/jekyll-now) makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup.

[BrewLog](https://github.com/benjholla/BrewLog) extends jekyll-now to create a version controlled homebrewing log/website.

- You don't need to touch the command line
- You don't need to install/configure ruby, rvm/rbenv, ruby gems :relaxed:
- You don't need to install runtime dependencies like markdown processors, Pygments, etc
- If you're on Windows, this will make setting up Jekyll a lot easier
- It's easy to try out, you can just delete your forked repository if you don't like it

In a few minutes you'll be set up with a minimal, responsive homebrew log giving you more time to spend on homebrewing or coding or whatever.

If your not sold already, checkout a **[Live Demo](https://benjholla.github.io/BrewLog/)**.

## Quick Start
BrewLog can be deployed as a Github Project page (`your_github_username_or_organization_name.github.io/BrewLog`) or as your User or Organization page (`your_github_username_or_organization_name.github.io`).  To deploy as a Project page follow Step 1A.  To deploy as a User or Organization page follow step 1B.

### Step 0)

Fork this repository to your Github User or Organization account.

### Step 1A) Deploy BrewLog as a Project Page

First, if you don't like the name `BrewLog` as your base URL then rename your repository to something you see more fitting.

Next delete the `gh-pages` branch.

Enter `BrewLog` (or whatever you entered for the base URL) in the `baseurl` field of the _config.yml file.

Once you've committed the change to _config.yml, create the `gh-pages` branch again fresh off of the latest master!

Your Jekyll based homebrew log should be viewable now at `your_github_username_or_organization_name.github.io/BrewLog` (or whatever base URL you changed your repo name to be in place of `BrewLog`.

### Step 1B) Deploy BrewLog as a User or Organization Page

Rename the repository to `your_github_username_or_organization_name.github.io`.

Your Jekyll based homebrew log should be viewable immediately at `your_github_username_or_organization_name.github.io` (if it's not, you can often force it to build by completing step 2.

Delete the `gh-pages` branch.  You won't be needing it.

### Step 2) Customize and view your site

Enter your site name, description, avatar and many other options by editing the _config.yml file. You can easily turn on Google Analytics tracking, Disqus commenting and social icons here too.

Making a change to _config.yml (or any file in your repository) will force GitHub Pages to rebuild your site with jekyll. Your rebuilt site will be viewable a few seconds later. If not give it a few more minutes as GitHub suggests and it'll appear soon or check your email for any build errors reported by Github.

There are 3 different ways that you can make changes to your blog's files:

1. Edit files within your new username.github.io repository in the browser at GitHub.com.
2. Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io). It's optimized for use with Jekyll making markdown editing, writing drafts, and uploading images really easy.
3. Clone down your repository and make updates locally, then push them to your GitHub repository.
  
### Step 3) Publish your first brew

Edit `/_posts/2014-12-5-oatmeal-stout.md` to replace the default content and log your first blog brew. This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

> You can add additional brews in the browser on GitHub.com too! Just hit the + icon in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog brew and make sure the brew's filename is in this format: `year-month-day-title.md`

## Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone git@github.com:yourusername/yourusername.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at http://0.0.0.0:4000
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.

## Features

✓ Command-line free _fork-first workflow_, using GitHub.com to create, customize and publicly log your homebrews  
✓ Fully responsive and mobile optimized base theme (**[Live Demo](https://benjholla.github.io/BrewLog/)**)  
✓ Customized homebrewing theme (with version control!)  
✓ Sass/Coffeescript support using Jekyll 2.0  
✓ Free hosting on your GitHub Pages user site  
✓ Markdown blogging  
✓ Syntax highlighting  
✓ Disqus commenting  
✓ Google Analytics integration  
✓ SVG social icons for your footer  
✓ 3 http requests, including your avatar  
✓ More time to brew/code other things...  

✘ No installing dependencies  
✘ No need to set up local development  
✘ No configuring plugins  
✘ No need to spend time on themes