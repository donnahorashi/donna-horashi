---
layout: article
category: article
title: Search Engine Optimisation
subtitle: Stolen from edith.riesen
topic: Computers
date: 
tags: computers web
---

## [Principles](https://edith.reisen/computers/web_design/seo.html#principles)

Search engine optimization is the practice of adjusting your site’s code to increase readability and prominence for search engine algorithms, thus increasing its likelihood to appear higher in search listings.

Well-structured semantic HTML and filled out and descriptive meta tags are essential for your site’s content to be readable and relevant to a search engine. Site popularity and content quality is also estimated by the number of external links and unique domains directed to your site, weighted by those domains’ own ranking. Attempting to trick or game the search engines with tag spam, etc. is counter-productive due to their [advanced counter measures.](https://support.google.com/webmasters/topic/6001971?hl=en)

This article is a comprehensive list of the HTML content parsed by search engine algorithms with best practices for readability and visibility. Excepting [sitemaps](https://edith.reisen/computers/web_design/seo.html#sitemap) and [canonical urls](https://edith.reisen/computers/web_design/seo.html#canonical) covered in [the Appendix](https://edith.reisen/computers/web_design/seo.html#appendix) (special use cases), this is the whole of SEO.

## [Meta Tags: Keywords, Title, Description](https://edith.reisen/computers/web_design/seo.html#meta)

These tags belong in the <head> at the beginning of an HTML document. They are read by search engines to evaluate the content of the page and generate listings.

Attempts to [keyword stuff](https://archive.is/iZAdI) the meta tags or body content will be caught by the search engine's anti-spam algorithms and lower your search ranking. Focus on information-rich content and the keywords will naturally result in the content.

### Keyword

`<meta name="keyword" content="keyword, keyword keyword">`

List the keywords present in the article. You should look through your content and identify a primary keyword, and then list secondary keywords. Keywords are separated by commas. Feature the primary keyword prominently in the title and description meta tags.

Ensure consistency with your keywords. Secondary keywords can be included but there should be one primary keyword that is present across the three meta tags.

_E.g. if the primary keyword is UX Design, don’t alternate between "UX Design," "User Interface," and "web design" in the title and description and tags._

### Title

`<meta name="title" content="Title of Article">`

One line, under 60 characters. Clear and descriptive, containing your primary keyword

_Note: It's bad practice to prepend anything to the title, such as the name of your domain, e.g. "Edith: Search Engine Optimization," because it makes pages hard to distinguish for users with many tabs, whose browsers might truncate the title and lower the character cap._

### Description

`<meta name="description" content="Description of article">`

One paragraph description, attempt to include keywords.

Detailed analysis: https://blog.spotibo.com/meta-description/

## [Anchor](https://edith.reisen/computers/web_design/seo.html#anchor)

Anchor tags are what form hyperlinks in HTML.

`<a href="https://www.url.com">Example Hyperlink</a>`

It's important the words that are turned into a hyperlink are descriptive of the content they are linking to, especially for raising your Page Rank for external links directed to your site or internal links within your site.

e.g. [This](https://edith.reisen/computers/web_design/seo.html#) is a bad practice hyperlink.

This is a [good practice hyperlink.](https://edith.reisen/computers/web_design/seo.html#)

## [Images: Alt Attribute, Filename](https://edith.reisen/computers/web_design/seo.html#image)

When a search engine displays image results, they don't actually parse the visual content of the image. Instead they look at the images descriptive tags. If you want an image on your site to appear on image search results, you will need to include textual descriptions for the search engine's algorithms to read.

### Alt

`<img src="dog.jgp" alt="Photograph of a Golden Retriever">`

The alt attribute defines an alternative text description of an image in the case that it cannot be loaded by a browser (e.g. non graphical browser, screen reader, due to a missing file or images turned off).

An alt description should always be defined as per W3C standards to maintain accessibility, allowing the content of the website to be universally retained.

It is also, however, important as parsable information for a search engine. A web crawler will ignore images without alt text to reference. The more accurate and key-word containing the image, the more likely it is to appear highly in search results.

### Filename

Search engines will also analyze the filename of the image for information. Using a generated filename like "1545066239.jpg" or "Screen Shot 2018-06-11 at 10.56.51 PM" will reveal less usable information than a descriptive one like golden\_retriever.jpg.

___

___

↑ Return ↑