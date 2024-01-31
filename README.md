# Jekyll TUM I8 Theme

Use this repository as template for your TUM i8 pages (using [jekyll-remote-theme](https://github.com/benbalter/jekyll-remote-theme)).

    remote_theme: tumi8/tumi8-theme

If you want the legacy look, use

    remote_theme: tumi8/tumi8-theme@legacy

An example is available under https://tumi8.github.io/tumi8-theme. 
If you want so see how to use the theme as remote-theme, have a look at https://github.com/tumi8/active-tls-fingerprinting/tree/gh-pages

To create your own pages:
1. create a new file under /pages
2. Set the `page` or `main` layout
   - `main` will have the menu on top and is for main pages
   - `page` has the menu on the left side and is for sub pages
   - See https://portal.mytum.de/corporatedesign/stylesweb/living_styleguide for allowed usage
3. If the page should appear in the menu:
    - Add a title `toc` and the order in which it should appear `order`

A full page front matter could look like this:

    ---
    layout: page
    title: My Page Title
    permalink: /mypage/
    order: 2
    toc: 'My Page'
    ---

## Styles

CSS is from 

    https://www.tum.de/typo3conf/ext/in2template/Resources/Public/JavaScripts/Static/basic-1.0.0.js
    https://www.tum.de/typo3conf/ext/in2template/Resources/Public/Css/Static/style-1.0.0.css 
    https://www.tum.de/typo3conf/ext/in2template/Resources/Public/JavaScripts/Static/jquery-3.2.1.min.js 

