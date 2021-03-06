---
filename: /src/Progress/CircularProgress.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# CircularProgress



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| classes | Object |  | Useful to extend the style applied to components. |
| color | union:&nbsp;'primary'&nbsp;&#124;<br>&nbsp;'accent'&nbsp;&#124;<br>&nbsp;'inherit'<br> | 'primary' | The color of the component. It's using the theme palette when that makes sense. |
| max | number | 100 | The max value of progress in determinate mode. |
| min | number | 0 | The min value of progress in determinate mode. |
| mode | union:&nbsp;'determinate'&nbsp;&#124;<br>&nbsp;'indeterminate'<br> | 'indeterminate' | The mode of show your progress. Indeterminate for when there is no value for progress. Determinate for controlled progress value. |
| size | number | 40 | The size of the circle. |
| thickness | number | 3.6 | The thickness of the circle. |
| value | number | 0 | The value of progress in determinate mode. |

Any other properties supplied will be [spread to the root element](/guides/api#spread).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:
- `root`
- `primaryColor`
- `accentColor`
- `svgIndeterminate`
- `svgDeterminate`
- `circle`
- `circleIndeterminate`

Have a look at [overriding with classes](/customization/overrides#overriding-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/tree/v1-beta/src/Progress/CircularProgress.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiCircularProgress`.

## Demos

- [Progress](/demos/progress)

