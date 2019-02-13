# www.skyqrose.com

The source for my personal website. The build products are hosted by Github Pages over at skyqrose/skyqrose.github.io

Built with jekyll. To run locally,
* [Install jekyll](https://jekyllrb.com/docs/installation/)
* `bundle install`
* `bundle exec jekyll serve`
* visit `localhost:4000`

Because I use plugins, the site is built by Travis CI rather than Github. Commits pushed to master are automatically built by Travis and then pushed to the other repo, skyqrose/skyqrose.github.io

## New Posts

### Frontmatter

```
---
layout: post
title: Max 70 characters
description: For use in Twitter cards. Max 200 characters
date: e.g. 2018-01-01
last_modified: (optional) e.g. 2018-01-02
cover: Shown along with the title on the homepage and Twitter cards. e.g. /assets/2018-01-01-title/cover.png
cover_alt: Description for the cover image
tweet: (optional) Url of a tweet announcing, publishing, or discussing this article, in lieu of a comments section
github: (optional) Url of the GitHub page, if it's hosted on GitHub
---
```

### Assets

Put all assets for a post in `/assets/2018-01-01-title/`

Anything that's being rehosted/mirrored/archived from somewhere else can go in `/assets/rehosted/`
