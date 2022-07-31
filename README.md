# How to update the blog

1. Go to [prose.io](https://prose.io) and give permissions if necessary

2. Click 'view project' on 1924piecesofme 

3. Navigate to the **_posts** subfolder

4. Click **'new file'**

5. Title the post something appropriate in the ‘title’ box (Prose will intelligently handle the filename for you now, you no longer need to worry about it)

6. Write your post, using the formatting tools if necessary

7. Over to the right, click the **‘metadata’** button (the horizontal lines).

8. Check the **‘published’** checkbox (or leave it unpublished if you want to write and save it, then preview it -- it will only appear on the public site if the ‘published’ checkbox in metadata is ticked)

9. Click the **'save'** button over to the right. 

10. Click the **‘commit’** button. Wait a few minutes and the post will appear in the list of blog posts

---


# About the theme
Daktilo is a [Jekyll](jekyllrb.com) theme with a minimal design inspired from typewriters.

# More info and Live preview
[Click here](http://daktilo.github.io/) to see the theme in action.

# Features
- Fully responsive
- [Disqus](https://disqus.com/) integration for comments.
- Google Analytics integration.
- Syntax Highlighter (using [highlight.js](https://highlightjs.org/)).
- Support for categories.
- Font-Awesome Icons.
- Optimized for SEO.
- Coolest [404 page ever](http://kronik3r.github.io/daktilo/404.html).

# How to use it
Start by cloning the repository, then check the `_config.yml` file and change it accordingly.
Note that the `title` property is what will be displayed as logo.

Finally execute `jekyll serve --watch` and head to [localhost:4000](http://127.0.0.1:4000) to see the result.

# Using categories
Categories are little bit tricky. Please make sure to do the following for each category:

- Create a file within `categories` folder with the name of your category
For example let's say that we have a category called `An Awesome Category` you will need to add an `an-awesome-category.html` file with this content:

``` html
---
layout: category
category: an-awesome-category
permalink: /categories/an-awesome-category/
---

```

- Create an entry inside `_data/categories.yml`

``` html
- slug: an-awesome-category
  name: An Awesome Category
```

- Then you will see it in the footer in the `Explore` section.

# License

The contents of this repository is licensed under [The MIT License.](https://opensource.org/licenses/MIT)
