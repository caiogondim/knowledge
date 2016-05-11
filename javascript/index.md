## Event targets

- `event.target`: the element that dispatched the event.
- `event.currentTarget`: always refer to the element the event handler has been attached.
- `event.relatedTarget`:
  - For `mouseover` it holds reference to the node the mouse was previously over.
  - For `mouseout` it holds reference to the node the mouse moved to.

More info on [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Event/Comparison_of_Event_Targets)
