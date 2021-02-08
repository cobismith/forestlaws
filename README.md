International Forestry Law Infographic
==================================================

This infographic shows which countries are signatory to which international agreements and laws related to forestry governance. This is a work in progress as countries continue to ratify international laws. 

You can view it here: https://cobismith.github.io/forestlaws/

It's adapted from code made for the [HBO recycling project](https://github.com/zgrossbart/hborecycling), which is fun. 

It's made with [PaperJS](http://www.paperjs.org), [underscore.js](http://documentcloud.github.com/underscore), and a little [JQuery](http://www.jquery.com) with fonts from [Typekit](http://typekit.com).

## Developing locally

To support `https` in GitHub Pages, `paper.js`, `recycle.js`, and `data.json` now point directly to GitHub.

So to see changes locally to `data.json` on your development device, you'll need to change: 

`<script src="https://cobismith.github.io/forestlaws/data.json" type="text/javascript" charset="utf-8"></script>`

to

`<script src="data.json" type="text/javascript" charset="utf-8"></script>`
