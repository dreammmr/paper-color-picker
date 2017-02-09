##&lt;paper-color-picker&gt;

`paper-color-picker` is a Polymer 1.0 form element for the color picker. It opens a default system color picker and immediately updates his own value when the value is changing. It has a small bar in the bottom of it, which is showing you the current color you've selected.

[Live Example](http://spacee.xyz/polymer-components/paper-color-picker/demo.html)

##Installing with Bower

To install the component with the Bower, just run:

`bower install --save papercolorpicker`


Example:

```html
<link href="path/to/paper-color-picker/paper-color-picker.html" rel="import">

<paper-color-picker value="{{color}}" label="Pick the Color"></paper-color-picker>
```

###&lt;paper-color-picker&gt; - Properties

The following properties are available:

| Property Name | Description | Default |
| --- | --- | --- |
| `label` | The floating label of the input | `Color` |
| `value` | Immediate value of the color picker. | `` |
