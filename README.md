# Jekyll Wiki
Nope, this isn't a wiki about Jekyll -- it's a repo using Jekyll to generate a wiki (based on the Digital Garden Jekyll Template). To fork your own wiki from this example, change the `baseurl` and `url` to your own hosting solution in `_config.yml`, and change the `edit_base_url` there to your version control. Then fill out the `/_wiki/` folder with your words.

## Features
- GitHub Pages out of the box
- Write your wiki in MarkDown
- Navigate the wiki on static site *or* from GitHub itself -- links get converted
- Link previews on hover
- Instant search, surfacing page titles and content
- Sidebar has list of every page that links here
- Random-page button
- Edit button, to edit page on GitHub
- 404 page has link to create the file
- Site map of all pages (non-standard format -- for humans)

You may choose to enable a plugin that colours links to nonexistent files red, in `_config.yml`, but take heed that the plugin may not be particularly stable.

## Demo
You can see a [demo of the site here](https://ifcoltransg.github.io/jekyll-wiki-template/).

## Advice
Make sure filenames are in snake-case and have no other punctuation. For links, use the format `[link text](/_wiki/filename.md)` including the leading slash, to ensure links work on both GitHub's file previewer and the static site itself.
