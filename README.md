# Custom theme with gutenberg
### If website project is a Gutenberg Build
1. Use Gutenberg styled blocks and if needed Advanced Custom fields to build custom content areas and fields 
2. Use a styled gutenberg "group" object as a container for custom blocks.
3. Develop blocks locally then export/import json file to staging site
4. Save reusable blocks as either block-name-partial (a reusable part of a block) or block-name-panel (completed panel - usually consists of multiple blocks)
5. Manually Store block json file in "blocks-json" to keep block under version control
6. Build all website page components as self contained gutenberg blocks: ie testimonials block, contact form block, hero banner block, post slidershow block 
7. Save your blocks as resusable blocks when they are complete. (We train the clients to use the reusable blocks)
8. remove the default gutenberg colors and add a custom color pallette of brand colors https://www.billerickson.net/code/color-palette-setup-in-gutenberg/
9. Use this plugin to import/export json blocks and if needed convert reusable blocks to reusable block patterns, https://wordpress.org/plugins/reusable-blocks-extended/ this will help speed up builds
10. Only use gutenberg spacer block to add space between "variable content"
11. Develop the websites UI KIT using existing and new gutenberg blocks and components for:
  - buttons
  - titles
  - Media and text
  - image gallery
  - info cards
  - lists
  - slideshows
  - contact forms
  - header and footer
