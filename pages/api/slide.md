---
filename: /packages/material-ui/src/Slide/Slide.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# Slide API

<p class="description">The API documentation of the Slide React component. Learn more about the properties and the CSS customization points.</p>

```js
import Slide from '@material-ui/core/Slide';
```

The Slide transition is used by the [Drawer](/demos/drawers/) component.
It uses [react-transition-group](https://github.com/reactjs/react-transition-group) internally.

## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">children</span> | <span class="prop-type">element</span> |  | A single child content element.<br>⚠️The component used as a child [must be able to hold a ref](/guides/composition/#children). |
| <span class="prop-name">direction</span> | <span class="prop-type">enum:&nbsp;'left'&nbsp;&#124;<br>&nbsp;'right'&nbsp;&#124;<br>&nbsp;'up'&nbsp;&#124;<br>&nbsp;'down'<br></span> | <span class="prop-default">'down'</span> | Direction the child node will enter from. |
| <span class="prop-name">in</span> | <span class="prop-type">bool</span> |  | If `true`, show the component; triggers the enter or exit animation. |
| <span class="prop-name">timeout</span> | <span class="prop-type">union:&nbsp;number&nbsp;&#124;<br>&nbsp;{ enter?: number, exit?: number }<br></span> | <span class="prop-default">{  enter: duration.enteringScreen,  exit: duration.leavingScreen,}</span> | The duration for the transition, in milliseconds. You may specify a single timeout for all transitions, or individually with an object. |

The `ref` is attached to a component class.

Any other properties supplied will be spread to the root element ([Transition](https://reactcommunity.org/react-transition-group/#Transition)).

## Inheritance

The properties of the [Transition](https://reactcommunity.org/react-transition-group/#Transition) component, from react-transition-group, are also available.
You can take advantage of this behavior to [target nested components](/guides/api/#spread).

## Demos

- [Dialogs](/demos/dialogs/)
- [Transitions](/utils/transitions/)

