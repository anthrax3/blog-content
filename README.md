# CSSconf Blog

[![build status](https://secure.travis-ci.org/cssconf/blog-content.png)](http://travis-ci.org/cssconf/blog-content)

## Conventions

### Folder names

The folder name consists of a datetime and the blog post title.
Spaces are replaced by a hyphen, datetime and post title by an underscore.
The filename will be used to generate a unique url for this blog post.
If a post is in the future, it can be previewed by adding `?preview` to the url.

* `2015-10-25_post-name.md`: Post will be published on _25.10.2015 at midnight_ with the url `.../post-name(.html)`
* `2015-10-25_08:15_post-name.md`: Post will be published on _25.10.2015 at 08:15_ with the url `.../post-name(.html)`
* `2015-10-25_16:15_post-name.md`: Post will be published on _25.10.2015 at 16:15_ with the url `.../post-name(.html)`
