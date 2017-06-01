# \<app-page\>

`app-page`
Is a component that show a structure of page

__Example__

```html
<app-page title-page="blog" subtitle-page="Marked publications" fade-in></app-page>
```

__Responsive example__

```html
<app-page title-page="Contact" subtitle-page="contact with us" responsive fade-in></app-page>
```

## Styling
The following custom properties and mixins are available for styling:

Custom property                           | Description                                         | Default       |
------------------------------------------|-----------------------------------------------------|---------------|
--app-header-bg-color                     | background color for host                           | transaparent  |
--app-header                              | empty mixin for host                                | {}            |
--app-header-panel-left-color             | color for panel-left                                | #666          |
--app-header-panel-left                   | empty mixin for panel-left                          | {}            |
--app-header-title-color                  | color for title                                     | #212121       |
--app-header-title                        | empty mixin for title                               | {}            |
--app-header-subtitle-color               | color for subtitle                                  | #666          |
--app-header-subtitle                     | empty mixin for sutitle                             | {}            |
--app-header-title-left-content           | empty mixin for left content                        | {}            |
--app-header-panel-right-color            | color for panel right                               | #666          |
--app-page-panel-right-b-l                | border left for panel-right                         | #e5e5e5       |
--app-page-panel-right                    | empty mixin for panel-right                         | {}            |
--app-header-title-right-content          | empty mixin for right-content                       | {}            |
--app-header-hide-panel-right             | empty mixin for host([hide-panel-right])            | {}            |
--app-header-hide-panel-right-panel-left  | empty mixin for host([hide-panel-right]) panel-left | {}            |
--app-header-responsive                   | empty mixin for host([responsive])                  | {}            |
--app-header-responsive-panel-left        | empty mixin for host([responsive]) panel-left       | {}            |
--app-page-responsive-panel-right-b-t     | border top for host([hide-panel-right]) panel-right | #e5e5e5       |
--app-header-hide-panel-right-panel-left  | empty mixin for host([hide-panel-right]) panel-left | {}            |
--app-header-responsive-panel-right       | empty mixin for host([responsive]) panel-right      | {}            |

## Serving your Application

You can serve your application with:

    $ gulp serve

## Building Your Application

The application goes building while you build your application, you can check your application in `dist` folder.
