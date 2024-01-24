# Jekyll TUM I8 Theme

Use this repository as template for your TUM i8 pages (using [jekyll-remote-theme](https://github.com/benbalter/jekyll-remote-theme)).

    remote_theme: tumi8/tumi8-theme

An example is available under https://tumi8.github.io/tumi8-theme. If you want so see how to use the theme as remote-theme, have a look at https://active-tls-fingerprinting.github.io

To create your own pages:
1. create a new file under /pages
2. Set the `page` layout
3. If the page should appear in the sidebar:
    - Add a title `toc` and the order in which it should appear `order`

A full page front matter could look like this:

    ---
    layout: page
    title: My Page Title
    permalink: /mypage/
    order: 2
    toc: 'My Page'
    ---

