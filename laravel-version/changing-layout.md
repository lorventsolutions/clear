# Changing Layouts

To change any layout you just go through your file and in that you find the code

```text
@extends('layouts/defalut')
```

Modify the above line as

```text
@extends('layouts.menubarfold')
```

or

```text
@extends('layouts.mini_sidebar')
```

or

```text
@extends('layouts.layout_movable_header'
```

or

```text
@extends('layouts.layout_fixed')
```

or

```text
@extends('layouts.layout_boxed_fixed_header')
```

or

```text
@extends('layouts.horizontal_menu')
```

or

```text
@extends('layouts.boxed_movable_header')
```

**Note:** There are different styles of header and menu layout files are available.

* Default Layout
* Menubarfold Layout
* Mini Sidebar Layout
* Movable Header Layout
* Fixed Layout
* Boxed and Fixed Header Layout
* Horizontal Menu Layout
* Boxed Movable Header Layout

