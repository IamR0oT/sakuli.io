# NEW SAKULI HOMEPAGE TEMPLATE
created with [hugo]()

## add pages
In case of new sections in html add to layouts/partials/. In case you want to create an md for content simply with 
    hugo new pathto/foo.md

## known issues
### Internet Explorer
The page might not load the color-scheme as the stylesheet (style.css) uses css variables which is not supported by IE. See [this Issue](https://github.com/elrumordelaluz/reactour/issues/6).