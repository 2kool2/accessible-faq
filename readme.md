
#FAQ using <abbr title="Accessible Rich Internet Applications">ARIA</abbr> roles to meet <abbr title="Web Content Accessibility Guidelines">WCAG</abbr> 2 level AA

<strong>Demo: <a href="https://codepen.io/2kool2/pen/ZOkojB">FAQ using ARIA roles to meet WCAG 2 level AA</a></strong>


<br>
##Features

* Lightweight vanilla JavaScript with zero dependencies.
* Meets WCAG 2 level AA and uses ARIA roles.
* Answers may be open by default using a class.
* Answers may be open by URI fragment.


<br>
##Basic usage

Link to styles
```html
<link rel="stylesheet" href="css/styles.css">
```

A definition list <code>dl</code> is used in the HTML.
Definition title <code>dt</code> for the question, and definition data <code>dd</code> for the answer.
Add the data attribute <code>data-pab</code> to the <code>dt</code> which has the value of the
```html
<dl class="dl-faq pab_container">

  <dt data-pab=faq_1><span>Question</span></dt>
  <dd id=faq_1>
    <div>
      <p>Answer</p>
    </div>
  </dd>

  &hellip;
</dl>
```

Include the JavaScript
```html
<script src="js/accessible-faq.1.0.js"></script>
```



CodePen demo: <a href="https://codepen.io/2kool2/pen/ZOkojB">FAQ using ARIA roles to meet WCAG 2 level AA</a>

<hr>
Mike Foskett @ <a href="https://websemantics.uk/">webSemantics</a>
