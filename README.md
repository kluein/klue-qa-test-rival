# Deployed to
https://test-rival.qa.klue.io/

# About
This repo is to host a static page for QA testing purposes. This is based off the [Clean Blog Template](https://startbootstrap.com/themes/clean-blog-jekyll/) is a stylish, responsive blog theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/). 

## Run Locally
```
# Install Ruby 3+

bundle install
jekyll serve

```

## Generate a quick Lorem Ipsum Post via Github Actions and Deploy
1. Go to https://github.com/kluein/klue-qa-test-rival/actions/workflows/generate-new-page.yml
2. Click on 'Run Workflow' and dispatch from `main`

## Create a new Post Manually
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

## Create a new Random Lorem Ipsum Post
```
yarn install
npm run generate_random_post

# Verify it worked locally
bundle exec jekyll serve 

git add *
git commit -m 'New <date> Random Post'
git push origin main
```
