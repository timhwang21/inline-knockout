Knockout-Text
=======

### [Live Demo](http://timhwang21.github.io/knockout-text/index.html)

![Screenshot][screenshot]

CSS classes for knockout text. Uses pseudo-classes to keep required code to a minimum.

## Usage

Copy `sass/knockout-text.sass` to your project, and compile the SASS into CSS:

```bash
sudo gem install sass # if you do not have sass installed
sass sass/knockout-text.sass css/knockout-text.css
```

To add the knockout text element, add the following into your HTML:

```html
<content class="knockout-text">
  <div class="knockout-between"></div>
</content>
```

To customize the element, change the settings at the start of `knockout-text.sass`.

[screenshot]: images/screenshot.png
