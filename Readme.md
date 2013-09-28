
# magazine-layout

  some helper styles for magazine.js

## Installation

  Install with [component(1)](http://component.io):

    $ component install bmcmahen/magazine-layout

## Example

  This provides a basic absolutely positioned 12-node grid system that helps create basic magazine layouts.

```html
<li class='swipe-pane'>
  <div class='left-0 width-4 height-12'>
    <div>
      <h1> A title </h1>
      <p> This css create a left-hand column. </p>
  </div>
  <div class='left-8 width-4 height-6'>
    <div>
     <p> I will appear in the top right corner. </p>
    </div>
  </div>
</li>
```

  If you want a subgrid within a grid, you need to wrap it within a `.grid-container` class.

  More examples to come... including the use of `.fixed-block`.


## License

  MIT
