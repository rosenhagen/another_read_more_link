##Pelican-plugins: Another Read More Link

 - Inspired by [Octopress](http://octopress.org/docs/blogging/)
 - Reference to [read_more_link](https://github.com/getpelican/pelican-plugins/tree/master/read_more_link)

"
Inserting a `<!-- more -->` comment into your post will prevent the post content below this mark from being displayed on the index page for the blog posts, a "Continue →" button links to the full post.
"

demo: [fangpeishi.com](http://fangpeishi.com)

```css
.another-read-more-link {
    background: #eee;
    display: inline-block;
    padding: .4em .4em;
    margin-right: .5em;
    text-decoration: none;
    color: #737373;
    transition: background-color 0.5s;
}
```

![demo](http://fangpeishi.com/images/2016/another_read_more_link_demo.jpg)

###Settings

```

ANOTHER_READ_MORE_LINK = "Read more"
ANOTHER_READ_MORE_LINK_FORMAT = "<a class="another-read-more-link" href="{url}" >{text}</a>"
```
