---
layout: default
---

## A Jekyll template for publishing single-page websites and articles that are incredibly readable and fully responsive

### Nice, clean, reading!

Good clean read is set up with readability first in mind. Whatever you want to communicate here can be read easily, and without distraction. Of course, it's fully responsive, which means people can read it naturally on any phone, or tablet. Write it in markdown in <code>index.md</code> and get a beautifully published piece.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

> "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### With footnotes too!

Back up your stuff with solid, clean citations. Footnotes can be written in markdown and appear like this.[^1] Use as many as you like.[^2]

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### Add social sharing buttons

Simply add the following line anywhere in you markdown:

<pre><code>{% raw  %}
{% include sharing.html %}
{% endraw %}
</code></pre>

and get a nice responsive sharing ribbon.

{% include sharing.html %}

Add this at the bottom, or the top, or between every other paragraph is you're desprate for social validation.

Just remember to customize the buttons to fit your url in the <code>_includes/sharing.html</code> file. These buttons are made available and customizable by the good folks at kni-labs. See the documentation at [https://github.com/kni-labs/rrssb](https://github.com/kni-labs/rrssb) for more information.

### Add images to make your point

Images play nicely with this as well. Add diagrams or charts to make your point, and the template will fit them in appropriately.

<img src="http://githube.com/adueck/good-clean-read/images/hello.svg" alt="hello">

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Thanks to [Shu Uesengi](https://github.com/chibicode) for inspiring and providing the base for this template with his excellent work, [solo](https://github.com/chibicode).

<hr>

##### Footnotes:

[^1]: This is a footnote. Click to return.

[^2]: Here is another.
