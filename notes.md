# flex-grow: by default is 0; Will never grow

# flex-basis: Default is 0 /

- Is working on width on the main axis ..

-On the cross axis is looking for the height.

With a (min-width, max-width, min-height or max-height) that will prevent the flex-basis completely.

# flex: grow shrink basis; This is the shorthand for flex-grow, flex-shrink and flex-basis combined. The second and third parameters (flex-shrink and flex-basis) are optional.

- flex: 0 1 auto; Value by default
- flex: 1; = flex-grow: 1, flex-basis: 0,
- flex: auto; = flex: 1 1 auto
- flex: 400px; will assume it's flex-basis: 400px
