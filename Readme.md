##Pelican-plugins: Another Read More Link

 - Inspired by [Octopress](http://octopress.org/docs/blogging/)
 - Reference to [read_more_link](https://github.com/getpelican/pelican-plugins/tree/master/read_more_link)

"
Inserting a <!-- more --> comment into your post will prevent the post content below this mark from being displayed on the index page for the blog posts, a "Continue →" button links to the full post.
"

demo: [fangpeishi.com](http://fangpeishi.com)


###Settings

```

ANOTHER_READ_MORE_LINK = "Read more"
ANOTHER_READ_MORE_LINK_FORMAT = "<a class="another-read-more-link" href="/{url}" >{text}</a>
"
```
