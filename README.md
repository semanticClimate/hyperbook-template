## Work plan

1. Implement a CSS style based on Vivliostyle template (Theme) https://vivliostyle.github.io/themes/spec.html
1. Copy a Vivliostyle Theme
1. Document this part (getting and starting a theme)
1. Make a plan about what to implement in the theme and decide on an example fo what we want it to look like

## Discussion

https://github.com/orgs/semanticClimate/discussions/5

## Skills needed

For the following specifications and software.

1. CSS Paged Media Module Level 3 (W3C Editor's Draft) - https://drafts.csswg.org/css-page-3/
1. Web Manifest (W3C Editor's Draft) - https://w3c.github.io/pub-manifest/ 
1. Vivliostyle Viewer - https://github.com/vivliostyle/vivliostyle.js/tree/master/packages/viewer

## Project source GitHub

Demo - https://github.com/semanticClimate/glossary-demo

IPCC #semanticClimate HTML source with ids - to be confirmed - Possibly this file: https://github.com/semanticClimate/semanticClimate/blob/main/ipcc/ar6/test/total_glossary/new_total_demo.html

## Tasks

1. Recreate Simon workflow: https://github.com/semanticClimate/glossary-demo
1. Describe what it does and shat it is made of 
1. Architectural diagram
1. GraphViz of workflow from IPCC website to publication
1. Define the project
1. Document the process: As step by step process - as it is done; Add review and testing 
1. Table of contents (ToC) generation: Vivliostyle support ToC function could generate a ToC from the H4s - https://docs.vivliostyle.org/#/vivliostyle-cli#creating-a-table-of-contents
1. Publication manifest creation
1. CSS Page Media CSS style: Create new from scratch using Vivliostyle Template guidelines - where possible
1. IPCC #semanticClimate HTML: Additional HTML tags to work with CSS Paged Media
1. How to integrate other content rather that only IPCC web glossary: Manual edits; Auomatic markup (dictionaries; Wikidata and Wikipedia)
1. How to manage translations: Mltilingual inline; Complete publication translation and typesetting R-L, Vertical.
1. Making Academic Deposits: Data (as: Code, source, or as supporting material) and publication

## Links

Vivliostyle info on manifests - https://docs.vivliostyle.org/#/vivliostyle-viewer#web-publications-multi-html-documents

## Support information

* How to: https://www.print-css.rocks/
* CSS Paged Media Module Level 3 [W3C Working Draft](https://www.w3.org/standards/types#WD), 14 September 2023
* W3C CSS Generated Content for Paged Media Module - Working Draft, 25 January 2024: https://www.w3.org/TR/css-gcpm-3/#document-sequence-selectors
* 2013 W3C Feature list - https://www.w3.org/Style/2013/paged-media-tasks.html
* Mozilla multi-column layout - https://www.w3.org/TR/css-multicol-1/ < Implemented by Vivlio . https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_multicol_layout
* W3C spec CSS Multi-column Layout Module Level 2
[Editor’s Draft](https://www.w3.org/standards/types#ED), 5 October 2021 - https://drafts.csswg.org/css-multicol-2/
* Page Floats - https://drafts.csswg.org/css-page-floats/

## Vivliostyle supports

More: https://docs.vivliostyle.org/#/supported-css-features

* CSS Multi-column Layout Module Level 1 - https://www.w3.org/TR/css-multicol-1/
* CSS Paged Media Module Level 3 - https://www.w3.org/TR/css-page-3/
* CSS Generated Content for Paged Media (GCPM) 3 - https://www.w3.org/TR/css-gcpm-3/
* CSS Fonts 3 - https://www.w3.org/TR/css-fonts-3/
* CSS Fragmentation 3 - https://www.w3.org/TR/css-break-3/
* CSS Text 3 - https://www.w3.org/TR/css-text-3/


## Vivliostyle: Using locally and online

### Locally

Use Vivliostyle [Latest Stable Release](https://github.com/vivliostyle/vivliostyle.js/releases/latest) Note: it is importent only to use the Latest Stable Release. See: Assets - vivliostyle-viewer-x.xx.x.zip (download this ZIP file)

Download the .ZIP file.

Check regularly for updates.

Overwrite your local install when updates available.

**IMPORTANT!**

Unzip the Vivliostyle install in the top level of the directory where you store all your Git repos, so that all the Git repos are one level below your Vivliostyle install. This is because the Localhost server can only access directories in the same directory, or directories below it.

This should look something like this:

`/All my Git repos directory/`

Install here:

Above all Git repo directories...

`/repo1/`

`/repo1/`

`/repo1/`

Once installed launch Vivliostyle from a terminal with:

`./start-viewer`

OR

`./start-webserver`

Vivlio will launch at

http://127.0.0.1:8000/

In the Vivlio console enter the path to your publication index.html file and have book mode and render all files turned on.

Your book path will be:

../repo-directory-name/uhtml/index.html

Your book will now render.





