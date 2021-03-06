# Orientation

Change the orientation of your image, by either flipping along its axes or rotating around the center.

## Flip <Parameter text="&flip"/><Badge text="New!" type="warn" vertical="middle"/>

Flip the image about the vertical Y axis. This always occurs after rotation, if any.

<code-group>
<code-block title="HTML" active>
```html
<img src="//images.weserv.nl/?url=images.weserv.nl/lichtenstein.jpg&h=300&flip">
```
</code-block>

<code-block title="Markdown">
```md
![Flip](https://images.weserv.nl/?url=images.weserv.nl/lichtenstein.jpg&h=300&flip)
```
</code-block>
</code-group>

[![Flip](/static/lichtenstein.jpg?h=300&flip)](/?url=images.weserv.nl/lichtenstein.jpg&h=300&flip)

## Flop <Parameter text="&flop"/><Badge text="New!" type="warn" vertical="middle"/>

Flop the image about the horizontal X axis. This always occurs after rotation, if any.

<code-group>
<code-block title="HTML" active>
```html
<img src="//images.weserv.nl/?url=images.weserv.nl/lichtenstein.jpg&h=300&flop">
```
</code-block>

<code-block title="Markdown">
```md
![Flop](https://images.weserv.nl/?url=images.weserv.nl/lichtenstein.jpg&h=300&flop)
```
</code-block>
</code-group>

[![Flop](/static/lichtenstein.jpg?h=300&flop)](/?url=images.weserv.nl/lichtenstein.jpg&h=300&flop)

## Rotation <Parameter text="&ro="/>

Rotates the image by either an explicit angle or auto-orient based on the EXIF `Orientation` tag.

If an angle is specified, it is converted to a valid positive degree rotation. For example, `-450` will
produce a `270` degree rotation. When rotating by an angle other than a multiple of 90, the background
color can be provided with the `&rbg=` parameter. See [here](adjustment.md#background) for the supported color formats.

If no angle is provided, it is determined from the EXIF data.

<code-group>
<code-block title="HTML" active>
```html
<img src="//images.weserv.nl/?url=images.weserv.nl/lichtenstein.jpg&h=300&ro=45&rbg=red">
```
</code-block>

<code-block title="Markdown">
```md
![Rotation](https://images.weserv.nl/?url=images.weserv.nl/lichtenstein.jpg&h=300&ro=45&rbg=red)
```
</code-block>
</code-group>

[![Rotation](/static/lichtenstein.jpg?h=300&ro=45&rbg=red)](/?url=images.weserv.nl/lichtenstein.jpg&h=300&ro=45&rbg=red)
