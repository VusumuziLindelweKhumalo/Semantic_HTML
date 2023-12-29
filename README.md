# Semantic HTML

Semantic HTML refers to the use of HTML markup to convey the meaning of the content on a web page, rather than just its appearance. Semantic helps search engines and other technologies understand the structure and purpose of the content on your site. It makes your content more accessible to people who use assistive technologies to navigate the web and also it makes your code easier to read and maintain, since the purpose of each element is clear.

## Header

The `<header>` tag is used to markup the top section of a webpage. which typically includes the main titles or logo, navigation links, and other elements that are common to every page on the title.

![Code sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/code.png)

## Navigation

The `<nav>` tag is used to mark up a section of web page that contains navigation links.

```html
<!-- Non-semantic navigation -->
<div class="navigation">
	<a href="#">Home</a>
	<a href="#">About</a>
	<a href="#">Contact</a>
</div>

<!-- Semantic navigation -->
<nav>
	<ul>
		<li><a href="#">Home</a><li>
		<li><a href="#">About</a><li>
		<li><a href="#">Contact</a><li>
		<li><a href="#">Help</a><li>
	</ul>
</nav>
```

## Main

The `<main>` tag is used to mark up the main content area of a web page. This tag makes it easy to know which part of your page contains the main content.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Main.png?raw=true)

## Article

The `<article>` can represent a standalone piece of content and as a container. Contents within this tag should be self-contained and meaningful, and can include headings, paragraphs, images, and other types of content.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Article.png?raw=true)

## Aside

The `<aside>` tag is used t mark up content that is related to the main content on a web page but is not an intergral part of it. This may include things like supplementary information, advertisement, or related articles.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Aside.png?raw=true)

## Section

The `<section>` element is used to mark up sections of as web page that are thematically grouped together. This might include things like chapters or sections of a long article, or different parts of a product page.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Section.png?raw=true)

## Footer

The `<footer>` tag is used to mark up the bottom section of web page, which might include things like copyright information, contact details, links to social medial profiles.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/footer.png?raw=true)

## Details and Summary

The `<details>` and `<summary>` tags are used to mark uP a collapsible section of content. The `<summary>` tag is used to mark up the title of the section, and the `<details>` tag is used to mark up the content itself.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Details.png?raw=true)

## Figure and Figcaption

The `<figure>` and `<figcaption>` tags are used to mark up a self contained piece of content that is reference from the main content of web page. The `<figure>` tag is used to mark up the content itself, and the `<figcaptio>` tag is used to mark up a caption or description for the content.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Figure.png?raw=true)

---

## Additional HTML5

### Mark

- This tag is used to mark up text that has been highlighted. This might include things like search results, or text that has been highlighted by a user.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Mark.png?raw=true)

### Time

- The `<time>` tag is used to mark up a date or time. `<time>` tag, can make it easier for search engines and other technologies to understand the meaning of the content on your page.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Time.png?raw=true)

### Progress

The `<progress>` tag is used to mark up a progress bar. By using this tag, you can make it easier for users to understand the progress of a task.

![Code Sample](https://github.com/VusumuziLindelweKhumalo/Semantic_HTML/blob/main/images/Progress.png?raw=true)

### `<div>` and `<span>`

The `<div>` and `<span>` tags are not semantic tags. They are used to mark up deneric content areas, and do not convey any specific meaning.

## Sources

- [Writing Semantic HTML](https://cs.fyi/guide/writing-semantic-html)
- [Semantic HTML5 elements](https://www.freecodecamp.org/news/semantic-html5-elements/#:~:text=Semantic%20HTML%20elements%20are%20those,content%20that%20is%20inside%20them)
