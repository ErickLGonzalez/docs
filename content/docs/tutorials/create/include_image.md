---
$title: Include an Image
$order: 1
---

Most HTML tags can be used directly in AMP HTML, but certain tags, such as the `<img>` tag, are replaced with equivalent or slightly enhanced custom AMP HTML tags (and a few problematic tags are outright banned, see [HTML Tags in the specification](/docs/reference/spec.html#html-tags)).

To demonstrate what additional markup could look like, here’s the code required to embed an image into the page:

[sourcecode:html]
<amp-img src="welcome.jpg" alt="Welcome" height="400" width="800"></amp-img>
[/sourcecode]

{% call callout('Read on', type='read') %}
To learn why we’re replacing tags like `<img>` with `<amp-img>`, and how many are available, visit [Include Images & Video](/docs/guides/amp_replacements.html).
{% endcall %}

<a class="go-button button" href="/docs/tutorials/create/presentation_layout.html">Continue to Step 3</a>
