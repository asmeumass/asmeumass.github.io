---
title: "Our Student Chapter"
permalink: "/about/"
layout: page
---

## Our Mission
The mission of our student chapter is to help bridge the gap between the academic classroom and a career in mechanical engineering. Through extracurricular activities, student members will be able to build and apply their engineering skills, as well as see how they can integrate these skills into a professional setting.  


## The Structure of our Club

- There are two main pillars to our club: our general body, which meets monthly and our student run design team
- Our organization runs monthly general body meetings which generally consist of technical workshops, guest speakers, tours of on campus labs and facilities, and more
- General body meetings are open to the public, but first priority to sign up is given to general body members
- To join our general body, where you will receive updates and announcements from our club, simply join our [microsoft teams page]([url](https://teams.microsoft.com/l/team/19%3aDHkgpghuyXZ8H6htUGmDoRcSz-teU-yLhA2tUeKfuhI1%40thread.tacv2/conversations?groupId=b665bb64-1293-40b0-87bd-a82b8cfc4575&tenantId=7bd08b0b-3395-4dc1-94bb-d0b2e56a497f))

## Student Design Team

- Our UMass Student Design Team competes anually against other ASME student groups from colleges and universities across the country in a competition run by the national ASME chapter
- Our group consists 

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
