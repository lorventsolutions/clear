# Changing layouts

To change the layouts to your desired one involves changing names in the routes.js file

## 1.Default Layout

To get the default layout modify line as below.

```text
const routes = [{
    path: '/',
        component: resolve => require(['./default.vue'], resolve),
        ]}
```

## 2.Fixed Header Layout

To get the fixed header layout modify line as below.

```text
const routes = [{
    path: '/',
        component: resolve => require(['./fixed_header.vue'], resolve),
        ]}
```

## 3.Fixed Header and Fixed Menu Layout

To get the fixed header and fixed menu layout modify line as below.

```text
const routes = [{
    path: '/',
        component: resolve => require(['./fixed_header_fixed_menu.vue'], resolve),
        ]}
```

## 4.Fixed Menu Layout

To get fixed menu layout modify line as below.

```text
const routes = [{
    path: '/',
        component: resolve => require(['./fixed_menu.vue'], resolve),
        ]}
```

## 5.Horizontal Layout

To get Horizontal menu layout modify line as below.

```text
const routes = [{
    path: '/',
        component: resolve => require(['./horizontal.vue'], resolve),
        ]}
```

## 6.Menu Bar Folded Layout

To get Folded menu bar layout modify line as below.

```text
const routes = [{
    path: '/',
        component: resolve => require(['./menubar_fold.vue'], resolve),
        ]}
```

## 7.Boxed Layout

To get boxed layout modify line as below.

```text
const routes = [{
    path: '/',
        component: resolve => require(['./boxed.vue'], resolve),
        ]}
```

**Note:** There are different styles of header and menu layout files are available.

* Default layout
* Fixed Header layout
* Fixed Header and menu layout 
* Fixed menu
* Horizontal layout 
* Menu bar folded layout 
* Boxed layout

