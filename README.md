# input-elements
Elements built for enhancing or replacing native inputs.

Current elements include:
* `text-input`: An input for text or else, that will size automatically and can be validated.
* `number-input`: An input for numeric values, that can display a unit, be in percent, pad the number, size automatically and have localized number format.
* `color-input`: An input field for color. It will display the color, support different formats and convert automatically.
* `datetime-input`: An input for datetime values. It will use the local format, clamp and can use a minimum and a maximum.
* `date-input`: An input for date values. It will use the local format, clamp and can use a minimum and a maximum.
* `time-input`: An input for time values. It will use the local format, clamp and can use a minimum and a maximum.

```html
text-input: <text-input placeholder="type your text here..."></text-input><br><br>
number-input: <number-input min="0" max="1000000" step="1000" default="12345" pad-length="8"></number-input><br><br>
color-input: <color-input format="hsl"></color-input><br><br>
datetime-input: <datetime-input></datetime-input><br><br>
date-input: <date-input year="1950" month="8" min="1950-08-12"></date-input><br><br>
time-input: <time-input hours="8"></time-input>
```
