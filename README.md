# \<app-double-drawer-layout\>

A wrapper element for layouts with two drawers. Use it if all you ever wanted was creating a layout that looks like the one used in Google Inbox. Issues and pull requests welcome, as always!

This layout supports populating it with drawers on-demand. Example: You are using an iron-pages selector and only few of the subpages have app drawers. You should then make sure in the route-changed method to dynamically add (and remove) drawers. Always use the property: app-double-drawer-layout.leftDrawer or .rightDrawer.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing the Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

The element is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run the element's test suite locally.
