# debug.css

Utilities to make debug easier for CSS

Debugging CSS might be tricky sometimes. Although, Google Dev Tools are great, we may miss something. A human thing. Specially when project get larger and larger. In this case seeing outlines of your elements become very usefull. **debug.css** comes with a bunch of utility classes which make appear lines around elements and make easier to see how your CSS impacts.

```html
<div class="debug">Outlined div</div>

<ul class="debug-children">
  <li>Outlined child</li>
  <li>Outlined child</li>
  <li>Outlined child</li>
</ul>

<nav class="debug-siblings">
  <ul>
    <li>Outlined sibling</li>
    <li>Outlined sibling</li>
    <li>Outlined sibling</li>
  </ul>
</nav>

<p class="debug-all">
  Outlined root,
  <span>
    outlined child and <a href="">outlined sibling and <i>more</i></a>
  </span>
</p>
```

## Get started

```shell
git clone git@github.com:cooskun/debug.css.git
cd debug.css
rm -rf .git
```

Done. Both Sass and CSS version of file is available.
