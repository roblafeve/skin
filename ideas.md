
# Skin

A Skin is a group of styles that represent the non-dimensional aesthetic of an element. 

A Skin is typically based on a color from which contrasting variations are derived. These variations are usually applied to borders and typography.

```CSS
$skin-fire_engine
  background-color skin-color
  border-color darken(skin-color, 10)
  color lighten(skin-color, 50)
```

## Attributes

A Skin MAY consist of:
- Background
- Border
- Color
- Misc. (Shadow, etc.)

A Skin MAY NOT consist of:
- Padding
- Margin
- Width
- Height
- Position
- Etc.

## Base

When two or more skins share a common attribute, this attribute should be represented in the *Skin Base*.
