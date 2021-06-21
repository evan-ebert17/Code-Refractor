# Code-Refractor

Here are some of the revisions I have made to the Website.

## Changes

Nothing visually was changed on the page, however the HTML and CSS have been streamlined and have I have added the missing accessability requirements of a webpage, such as alt tags and semantic html elements (header, footer, main, aside and section tags.) Additonally, I have organized the CSS so that it is set according to the HTML document and read top-bottom (previously was just scattered and not corresponding or having any sort of structure). Lastly, I have deleted redundant classes on the HTML document and their related files in CSS file, 

these are;

`
.social-media-marketing
.online-reputation-management
.search-engine-optimization
`

and replaced them with one class named;

`
.content-blocks
`

then I replaced

`
.benefit-lead
.benefit-brand
.benefit-cost
`

with

`
.benefits
`

which resulted in the cleanup of all the previously associated classes and their *same* formatting.

and the last two changes are  the seo class in the span in the header to an id of #seo as it only gets used once and the title of the website now reading Horiseon Home Page (previously just "webpage".)