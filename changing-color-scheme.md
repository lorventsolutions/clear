# Changing Color Scheme

The default color scheme is dark, to change it to white scheme, we need to perform the following steps:

1\) ln src/layout.vue, change the following lines

```text
@import ./assets/sass/custom.scss
```

to

```text
@import ./assets/sass/custom_white.scss
```

And

```text
import right_side from "./components/layout/right-side";
```

to

```text
import right_side from "./components/layout/right-side_white";
```

To, change the logo of your site, you can edit the img tag in **clear\_header.vue**

```text
<img src="../../assets/img/logo.png" alt="logo" />
```

