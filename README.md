# input-elements
Elements built for improving or replacing native inputs. The aim is to style them easier and have valid values.

Current elements include:
* `text-input`: An input for text or else, that will size automatically and can be validated.
* `number-input`: An input for numeric values, that can display a unit, be in percent, pad the number, size automatically and have localized number format.
* `color-input`: An input field for color. It will display the color, support different formats and convert automatically.
* `datetime-input`: An input for datetime values. It will use the local format, clamp and can use a minimum and a maximum.
* `date-input`: An input for date values. It will use the local format, clamp and can use a minimum and a maximum.
* `time-input`: An input for time values. It will use the local format, clamp and can use a minimum and a maximum.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../text-input/text-input.html">
    <link rel="import" href="../number-input/number-input.html">
    <link rel="import" href="../color-input/color-input.html">
    <link rel="import" href="../datetime-input/datetime-input.html">

    <dom-bind>
      <template is="dom-bind">
        <custom-style>
          <style is="custom-style">
            html {
              font-family: 'Roboto', 'Noto', 'Source Sans Pro', sans-serif;
            }
          </style>
        </custom-style>

        <next-code-block></next-code-block>
      </template>
    </dom-bind>
  </template>
</custom-element-demo>
```
-->
```html
&lt;text-input&gt;<text-input placeholder="type your text here..."></text-input><br><br>
&lt;number-input&gt;<number-input min="0" max="1000000" step="1000" default="12345" pad-length="8"></number-input><br><br>
&lt;color-input&gt;<color-input format="hsl"></color-input><br><br>
&lt;datetime-input&gt;<datetime-input></datetime-input><br><br>
&lt;date-input&gt;<date-input year="1950" month="8" min="1950-08-12"></date-input><br><br>
&lt;time-input&gt;<time-input hours="8"></time-input>
```
