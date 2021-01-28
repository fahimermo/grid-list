[![Netlify Status](https://api.netlify.com/api/v1/badges/0edc416e-7e09-46b9-b9b1-9f3c50d92604/deploy-status)](https://app.netlify.com/sites/ng-grid-list/deploys)

# Grid list that's mergeable

The tool helps users to merge any adjacent tiles in a grid list so that they can create customized views as they want. Once they customize the view, they can place whatever the content they would like, like images, videos, and livestreams into each tile. That experience is just WOW.

[Demo](https://ng-grid-list.netlify.app/)

## Tech stack

- Angular 10

- NgRx

- Angular Material

## How to use

The functionality is pretty much similar to `merge` in `Excel`.

1.  Generate a grid list using `Generate` button from the toolbar

        screen1.png

2.  Select adjacent cells holding on `meta` key

    _(Note: On Macintosh keyboards, this key is the command key (⌘). On Windows keyboards, this key is the Windows key (⊞))_

        screen2.png

3.  Once `Merge` button is enabled, merge selected cells

4.  Keep merging cells until you find a good-looking view

        screen3.png
