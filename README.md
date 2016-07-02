# Font Awesome SVG Starter-pack

### A _starter-pack_ for your favourite icon package.

## Use

1. Include the defs.

    ```
    <div style="display; none"> {{ SVG CONTENTS HERE }} </div>
    ```

1. Make an xlink ref.

    ```
    <svg class="icon icon-phone">
            <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-phone"></use>
    </svg>
    ```         

1. Add some stylez.

    ```
    .icon {
        display: inline-block;
        width: 1em;
        height: 1em;
        stroke-width: 0;
        stroke: currentColor;
        fill: currentColor;
    }     
    ```

## Credits

Cheers to [Icomoon](https://icomoon.io/) and [Font Awesome](https://fortawesome.github.io/Font-Awesome/).