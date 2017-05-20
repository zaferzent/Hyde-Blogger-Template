# Hyde Blogger Template

Hyde adapted into the Blogger from Jekyll. The Jekyll version is [here](https://github.com/poole/hyde). 


Hyde is a brazen two-column [Blogger](http://blogger.com) template that pairs a prominent sidebar with uncomplicated content.

![Hyde screenshot](https://3.bp.blogspot.com/-DFxQYS5Of-g/WSCaKbv_-FI/AAAAAAAAGEE/3sjeS38qsmYIDicil3PSDdKxmA4RRiLlACPcB/s1600/hyde-blogger-template.png)


## Contents

- [Usage](#usage)
- [Options](#options)
  - [Sidebar menu](#sidebar-menu)
  - [Sticky sidebar content](#sticky-sidebar-content)
  - [Themes](#themes)
  - [Jquery Cookie Theme Switcher](#jquery-cookie-theme-switcher)
  - [Reverse layout](#reverse-layout)
- [Development](#development)
- [Author](#author)
- [License](#license)


## Usage

Only available on Blogger / Blogspot based blogs. Install `Blogger dashboard > Template > Edit HTML` or `Blogger dashboard > Template > Backup / Restore`

## Options

Hyde includes some customizable options, typically applied via classes on the `<body>` element.


### Sidebar menu

Create a list of links in the sidebar.

```html
<nav class='sidebar-nav'>
    <a class='sidebar-nav-item active' href='/'>Home</a>
    <a class='sidebar-nav-item' href='/p/example-page.html'>Example Page</a>
    <a class='sidebar-nav-item' href=''>Download</a>
    <a class='sidebar-nav-item' href=''>GitHub project</a>
</nav>
```

### Sticky sidebar content

By default Hyde ships with a sidebar that affixes it's content to the bottom of the sidebar. You can optionally disable this by removing the `.sidebar-sticky` class from the sidebar's `.container`. Sidebar content will then normally flow from top to bottom.

```html
<!-- Default sidebar -->
<div class="sidebar">
  <div class="container sidebar-sticky">
    ...
  </div>
</div>

<!-- Modified sidebar -->
<div class="sidebar">
  <div class="container">
    ...
  </div>
</div>
```


### Themes

Hyde ships with eight optional themes based on the [base16 color scheme](https://github.com/chriskempson/base16). Apply a theme to change the color scheme (mostly applies to sidebar and links).

![Hyde in red](https://3.bp.blogspot.com/-ozes_qXvKRI/WSCfgfbQ8gI/AAAAAAAAGEU/i3zlhQv6t6MRx7WmPR0u1NeVJW9hU-AfwCLcB/s1600/hyde-other-theme.png)

There are eight themes available at this time.

![Hyde theme classes](https://f.cloud.github.com/assets/98681/1817044/e5b0ec06-6f68-11e3-83d7-acd1942797a1.png)

To use a theme, add anyone of the available theme classes to the `<body>` element.

```html
<body class="theme-base-08">
  ...
</body>
```

### Jquery Cookie Theme Switcher

Use the jQuery Cookie Theme Switcher on Blogger. *Does not change when the page is refreshed

![Jquery Theme Switcher](https://1.bp.blogspot.com/-XAa7vuTEeB0/WSCh2ir-p0I/AAAAAAAAGEo/XP-SIE-J158OEtoHgHW33puZUh5tEdJNgCLcB/s1600/jquery-theme-switcher.png)

If you want to remove.
```html
<ul class='cscheme'>
    <li class='default' id='default'><a href=''/></li>
    <li class='red' id='orange'><a href=''/></li>
    <li class='yellow' id='blue'><a href=''/></li>
    <li class='orange' id='green'><a href=''/></li>
    <li class='green' id='rosse'><a href=''/></li>
    <li class='cyan' id='dark'><a href=''/></li>
    <li class='blue' id='mavi'><a href=''/></li>
    <li class='magenta' id='mor'><a href=''/></li>
    <li class='brown' id='kahve'><a href=''/></li>
</ul>
<a class='color-div' id='sright' value='s'>Sidebar Right</a>
```

Using together optional theme and reverse layout.

```html
<body class="theme-base-08 layout-reverse">
...
</body>
```

### Reverse layout

![Hyde with reverse layout](https://3.bp.blogspot.com/-x5_0S9nCk5s/WSCfqUFac5I/AAAAAAAAGEc/77-W0EBjlzkjwGcg_j9bfnpQAvY31D6zQCLcB/s1600/hyde-sidebar-right.png)

Hyde's page orientation can be reversed with a single class.

```html
<body class="layout-reverse">
  ...
</body>
```



## Development

Hyde has two branches, but only one is used for active development.

- `master` for development.  **All pull requests should be submitted against `master`.**
- `gh-pages` for our hosted site, which includes our analytics tracking code. **Please avoid using this branch.**


## Author

**Zafer Zent**
- <https://github.com/zaferzent>
- <https://twitter.com/zaferzent>


## License

Open sourced under the [MIT license](LICENSE.md).

<3
