
<h1>FAQ using WAI-<abbr title="Accessible Rich Internet Applications">ARIA</abbr> roles to meet <abbr title="Web Content Accessibility Guidelines">WCAG</abbr> 2 level AA</h1>

<strong>Demo: <a href="https://codepen.io/2kool2/pen/ZOkojB">FAQ using WAI-ARIA roles to meet WCAG 2 level AA</a></strong>


<br>
<h2>Features</h2>

* Lightweight vanilla JavaScript with zero dependencies.
* Meets WCAG 2 level AA and uses WAI-ARIA roles.
* Answers may be expanded by default.
* Answers may be expanded by URI fragment.
* Answer heights are resolved via JavaScript.
* Animations are CSS controlled.


<br>
<h2>Basic usage</h2>

Link to styles
```html
<link rel="stylesheet" href="css/styles.css">
```

A definition list <code>dl</code> is used for the <abbr title="Frequently Asked Questions">FAQ</abbr>.<br>
Definition title <code>dt</code> for the question, and definition data <code>dd</code> for the answer.<br>
Add the data attribute <code>data-pab</code> to the <code>dt</code> with the <code>id</code> value of the <code>dd</code> to control.<br>
Add the data attribute <code>data-pab-expand</code> to a <code>dt</code> for it to be expanded by default.<br>
To expand an answer via URI fragment, reference the <code>dd</code> <code>id</code>.

```html
<dl class="dl-faq pab_container">

  <dt data-pab=faq_1><span>Question</span></dt>
  <dd id=faq_1>
    <div>
      <p>Answer</p>
    </div>
  </dd>

  ...

</dl>
```

Include the JavaScript
```html
<script src="js/accessible-faq.1.0.js"></script>
```



CodePen demo: <a href="https://codepen.io/2kool2/pen/ZOkojB">FAQ using ARIA roles to meet WCAG 2 level AA</a>

<hr>
Mike Foskett @ <a href="https://websemantics.uk/">webSemantics</a>
