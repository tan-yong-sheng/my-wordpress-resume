# My Personal WordPress Resume Website Hosted on Github
Demo resume website here: https://tys203831.github.io/my-wordpress-resume/

WordPress is a drag-and-drop website editor which generate dynamic websites. But, since Github can only host static website without any backend available, WordPress as a dynamic website shall not work properly when hosted in Github. Thus, to have it hosted on Github, I need to convert this dynamic WordPress website to a static one using simply static plugin in WordPress.

## Benefits of serving WordPress as static site
Less server cost, if for low needs, you might get it FREE (e.g., use Github or Netlify to host the static website)!

- The static site runs faster than dynamic site.

## Cons of serving WordPress as static site
- More steps to deploy or update the changes, not beginner friendly - With dynamic website, you just need to access the backend (or wp-admin) to use the drag and drop editor to amend website. But, since static website does not deploy that backend (or wp-admin) online, so you can only amend and update your content on localhost, and then upload everytime the static part of website to your host (e.g., Github) for every update.

- Easier to lose your data - since you edit and update your WordPress on localhost, you would lose your data if you don't backup your localhost WordPress yourself (such as wp-content folder, wp-config file and your sql file exported from phpmyadmin).

## How I serve this WordPress website as static one?
- What I basically do is I install WordPress on localhost using XAMPP. Install simply-static plugin to convert dynamic WordPress website to static site. And then I create a new Github repository and Github Pages setup where the finished static website will be uploaded to.

## Plugins Used:

- Simply Static -> my go-to plugin to convert WordPress website to static one.
- [Elementor](https://wordpress.org/plugins/elementor/) -> This is the DRAG AND DROP WEBSITE EDITOR to create beautiful webpage.
- Blocksy Companion -> A companion for Blocksy theme. I am using it since I am using Blocksy theme for this project.
- Starter Templates -> Used together with Elementor, because inside got many templates available for Elementor to use.
- Code Snippet -> Simple to run additional css, html on the website.
- Here is a very useful video if you don't mind to dirty your hand and host your STATIC WordPress site on Github! Wala, good to go. 🤣
