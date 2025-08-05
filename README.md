# Angular Theme Switcher
## Easy Theme Switcher for Angular-Material
A simple angular app with an atomic theme switcher component. The theme switcher adds/replaces a theme class and light/dark class in the <body> tag of the app. The theme class contains all the css color variables, typography values, and the material-icons fonts.

to create a custom color scheme based on Google's Material Design spec you can use Angular Material's built-in generator:

`    ng generate @angular/material:m3-theme`

You must supply a hex 'primary' color and optionally hex colors for 'secondary', 'tertiary', and 'neutral' palettes. This yields a 'custom-theme.scss' file.