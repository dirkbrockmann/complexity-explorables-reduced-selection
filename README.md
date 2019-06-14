# ce-reduced-double-pendulum

## Reduced version of Complexity Explorable **Double Trouble**.

For the original version of the system check out:

http://www.complexity-explorables.org/explorables/double-trouble/

Some of the controls are removed. 

## How to embed

The explorable's main code is in `double-pendulum.js`.

The code fills the two div tags in index.html with the display and the controls names

- `double-pendulum_display`
- `double-pendulum_controls`

```html
<div id="double-pendulum_display" class="display-panel"></div>
<div id="double-pendulum_controls" class="control-panel"></div>
```
It's a good idea to add a wrapper `<div>` around these elements for more control.

The display and control divs have independent elements in the `explorables.css`.


