# Changelog
Note that this changelog refers to major changes from the original assets. You can view the original files in this snapshot of this repo <a href="https://github.com/inknsharps/horiseon_website_code_refactor/tree/73f8fc45c93b3985969be8f250c571f90521e2ca">here</a>.

## index.html Changes 

    Added <alt> tags to all images. Background image had a title attribute added in place of alt.

    Added <nav>, <figure>, <section>, <article>, <aside>, <footer> semantic HTML tags in place of <divs>.

    Update <title> tag with relevant title. 

    Line 44 - Remove unreferenced id="online-reputation-management" ID

    Line 53 - Remove unreferenced id="social-media-marketing" ID

    Line 68 - Remove unecessary </img> tag.


## style.css Changes

    Line 13 add '' to Arial and sans-serif.

    Line 31 add '' to sans-serif.

    Line 50 change a{} to .header a{} in case differently styled <a> tags need to be used in the page in the future.

    Line 146 add '' to Arial and sans-serif.

    Line 85 add '' to Calibri.

    Line 117 add '' to Calibri.

    Move content class to line 68 to reflect order of appearance in HTML file.

    Move p class to line 74 to reflect order of appearance in HTML file.

    Selectors and styling have been adjusted for all the redone semantic HTML tags.

**the following are not relevant at the current code refactor due major changes to classes and selectors**

    ~~Move 
        .search-engine-optimization, .online-reputation-management, .social-media-marketing, 
        .search-engine-optimization img, .online-reputation-management img, .social-media-marketing img, 
        .search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2 classes to the content styling section.~~

    Consolidated .benefit-lead, .benefit-brand, .benefit-cost classes.
    
    Consolidated .benefit-lead h3, .benefit-brand h3, .benefit-cost h3 classes.

    Consolidated .benefit-lead img, .benefit-brand img, .benefit-cost img classes.

    Consolidated .search-engine-optimization, .online-reputation-management, .social-media-marketing classes.

    Consolidated .search-engine-optimization img, .online-reputation-management img, .social-media-marketing img classes.

    Consolidated .search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2 classes.~~