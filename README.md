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
- Download and use local copy of Google fonts (do we really need all of them?)
- Favicon and Apple Touch icon (let's take one from Report-2021)
- `<meta name="theme-color" content="#fafafa">`,
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name/theme-color
- CSS for printing

### Done
- Put all fonts into `layout.css`
- Remove UTF-8 encoding specification from CSS
- `<meta charset="UTF-8">` should be put on top
- Different titles on different pages
- Check that all CSS files are included everywhere (and check that all
selectors are properly scoped (`p`, `section` etc))
- Style "current" page in both header and footer menu (let's consider
removing `href` attribute and styling via `a:link` pseudo-selector,
like here https://www.enovate.co.uk/blog/2013/07/16/html5-placeholder-links)
- Check why `&nbsp;` does not work (this?
https://stackoverflow.com/a/25233914/118810)
- Extract SVG from `.article_individually_center`
- `...` -> `&hellip;`
- Rename HTML files in one style

### Ideas
- Accordion effect in menu
- Use HTML templating to reduce duplication
- Local web server
- Combine and minimize CSS
- Subset Font Awesome
