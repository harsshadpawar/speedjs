There are many event types (parameters) you can use with `addEventListener()` instead of "input". Here are the most commonly used ones grouped by category:

### Mouse Events

- `click` - Fires when an element is clicked
- `dblclick` - Fires when an element is double-clicked
- `mousedown` - Fires when a mouse button is pressed down on an element
- `mouseup` - Fires when a mouse button is released over an element
- `mouseover` - Fires when the mouse pointer enters an element
- `mouseout` - Fires when the mouse pointer leaves an element
- `mousemove` - Fires when the mouse pointer moves while over an element
- `contextmenu` - Fires when the right mouse button is clicked (before the context menu appears)

### Keyboard Events

- `keydown` - Fires when a key is pressed down
- `keyup` - Fires when a key is released
- `keypress` - Fires when a key is pressed (deprecated, use keydown instead)

### Form Events

- `input` - Fires when the value of an input element changes (what we used)
- `change` - Fires when the value of an element changes and loses focus (less immediate than input)
- `submit` - Fires when a form is submitted
- `reset` - Fires when a form is reset
- `focus` - Fires when an element receives focus
- `blur` - Fires when an element loses focus
- `select` - Fires when text in a text field is selected

### Document/Window Events

- `load` - Fires when a resource and its dependencies have finished loading
- `unload` - Fires when a page is being unloaded
- `resize` - Fires when the document view is resized
- `scroll` - Fires when the document or element is scrolled

### Drag and Drop Events

- `dragstart` - Fires when the user starts dragging an element
- `drag` - Fires when an element is being dragged
- `dragend` - Fires when the user has finished dragging an element
- `dragenter` - Fires when a dragged element enters a valid drop target
- `dragover` - Fires when a dragged element is over a valid drop target
- `dragleave` - Fires when a dragged element leaves a valid drop target
- `drop` - Fires when a dragged element is dropped on a valid target

### Touch Events

- `touchstart` - Fires when a touch point is placed on the touch surface
- `touchmove` - Fires when a touch point is moved along the touch surface
- `touchend` - Fires when a touch point is removed from the touch surface
- `touchcancel` - Fires when a touch point has been disrupted

### Animation and Transition Events

- `animationstart` - Fires when a CSS animation starts
- `animationend` - Fires when a CSS animation completes
- `animationiteration` - Fires when a CSS animation repeats
- `transitionend` - Fires when a CSS transition completes

In our profile form example, "input" was the best choice because we wanted to update the preview in real-time as the user types. If we had used "change" instead, the preview would only update when the user moved to another field (lost focus).
