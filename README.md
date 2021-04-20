[![Screenshot of the Website](screenshot.png)](https://jpnlwebinar.github.io/)

---

An HTML/CSS website template perfect for a small academic conference.
It's simple and easy to use, to contrast with something slicker but cumbersome like [hoverboard](https://github.com/gdg-x/hoverboard).
You can [explore it live here](https://mikepierce.github.io/conference-website-template/).

## Beautiful Math with MathJax

It may be helpful to include mathematical notation on this website,
especially in the abstracts of talks.
This can be done using [MathJax](https://github.com/mathjax/MathJax).
For an example see the [*programs* page](https://mikepierce.github.io/conference-website-template/program/) of the template site.
To include math in a page of this website, include the line

````HTML
<script type="text/javascript" async
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=default">
</script>
````

in the `<head>` of that page. Then math can by typeset by using LaTeX's math notation enclosed in `\(...\)` delimiters.

## Sitemap

The `sitemap.xml` helps search engines understand the structure of the site.
In this file, each instance of "WEBSITE" should be replaced
with the actual address where this website is being hosted.
See the [sitemaps protocol page](https://www.sitemaps.org/protocol.html) for more details.
