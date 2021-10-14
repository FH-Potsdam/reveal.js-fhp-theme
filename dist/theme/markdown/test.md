# hello world
<a href="test.html">a link</a>
<img src="/dist/theme/images/fhp_logo-black.svg" />



# Simple long copy
This is a nice little long text in a slide. With more nice little long text in a slide. With more nice little long text in a slide. With more nice little long text in a slide.
<div class="source">Sources:<br />
[1] This is the source of this text<br />
[2] This is the source of this text</div>



# A list
- First item in the list
- Another item
- And another one



# A full size image
<img src="/dist/theme/images/test.png" class="img-full" />



# Multiple Images
<div class="img-row">
<div><img src="/dist/theme/images/test.png" /></div>
<div><img src="/dist/theme/images/test.png" /></div>
<div><img src="/dist/theme/images/test.png" /></div>
</div>
<div class="img-row">
<div><img src="/dist/theme/images/test.png" /></div>
<div><img src="/dist/theme/images/test.png" /></div>
<div><img src="/dist/theme/images/test.png" /></div>
</div>



# And a little code
<pre><code data-trim data-noescape class="language-css">
body, .img-full{
  width:100%;
  height: auto;
  color: #ff0000;
}
</code></pre>
<pre><code data-trim data-noescape class="language-javascript" data-line-numbers="3-5">
const slide = document.querySelector('.slide');
slide.innerHTML = 'HELLO WORLD';
function hello() {
  return 'Hello';
}
</code></pre>
