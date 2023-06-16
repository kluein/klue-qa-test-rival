# About
This repo is to host a static page for QA testing purposes. This is based off the [Clean Blog Template](https://startbootstrap.com/themes/clean-blog-jekyll/) is a stylish, responsive blog theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/). 

## Run Locally
```
# Install Ruby 3+

bundle install
jekyll serve

```

## Create a new Post
1. Create a new file in /_posts following the pattern of the templates
2. For each post in the `_posts` directory, update the front matter. Example:

    ```markdown
    ---
    layout: post
    title: "Post Title"
    subtitle: "This is the post subtitle."
    date: YYYY-MM-DD HH:MM:SS # Make sure this date is in the past or else it won't show
    background: '/PATH_TO_IMAGE'
    ---
    ```
3. Build your site: `bundle exec jekyll serve`

