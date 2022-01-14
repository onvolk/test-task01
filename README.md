# Project description

The goal of the test task is to design and implement the
sustainability report for Blanc & Fischer for the year 2022 in the
form of the subsite/landing page.
There was [already report for
2021](https://sustainability.blanc-fischer.com/), the version for the
next year should support the spirit and the visual style.

## The deliverables of the test task
- Main landing page (done)
- Sub-pages (layout done, HTML/CSS TBD)

## Implementation notes
- Idea behind visuals: support the message of diversity in a kitchen setting
- No stock photos were used, custom images were shot in my kitchen with DSLR
- The graphical layouts were designed in Adobe Illustrator
- HTML/CSS layout
    - Fully responsive (desktops/tablets/smartphones)
    - CSS Media Queries are used where appropriate
    - Extensive use of Flexbox
    - Vector graphics in SVG
    - Font Awesome for logos and icons of the social networks
    - Google Web fonts for custom fonts

## Todo

### First priority
- Page assembly for internal pages (with webpack?) 
    - github pages for subfolder?
    - local web server for mobile devices

### Second priority
- How to property specify image sizes
- Check if we need to close single tags in HTML5 (`/>`)
- Change links to placeholders (are `#` good?)
- Download and use local copy of Google fonts (do we really need all of them?)
- Remove UTF-8 encoding specification from CSS
- Check why `&nbsp;` does not work
- Favicon
- Meta-tags
- Check if anything can be taken from HTML5 Boilerplate project
- Fix front page header image (white border, artifact on the right)
- Extract only used icons from Font Awesome (using font or SVGs)
- Minimize SVGs
- Print CSS


### Ideas
- Accordion/image gallery 
- Combine and minimize CSS