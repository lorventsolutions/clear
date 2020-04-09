# Leftmenu structure

It has the following structure:

The links in left menu has the following structure:

```text
  <router-link to="/user" tag="li" exact>
     <a class="logo"><i class="menu-icon ti-desktop"></i><span class="mm-text">Dashboard 1</span></a>
  </router-link>
```

this will render to:

```text
<li class="">
  <a href="#/user" class="logo">
    <i class="menu-icon ti-desktop"></i><span class="mm-text">Dashboard 1</span>
  </a>
</li>
```

