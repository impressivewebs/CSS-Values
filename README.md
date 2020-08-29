# [CSS Values](https://cssvalues.com)

CSS Values is a simple single page web app (SPA) that lets you search for almost any CSS property and get a simple list of possible values.

This GitHub repo does not have the code from the app, but will be used to report bugs, errors, omissions, incomplete info, etc. Below you'll find a description of how to use the app:

* Type a CSS property name into the box. The page will automatically update as you type.
* Add a space after the full property name to avoid multiple results for certain keywords (e.g. "width ").
* Each property has a "Load Browser Support" button. The loaded [caniuse.com](https://caniuse.com/) data represents basic support for the property itself and doesn't include each possible value or context (e.g. flex vs. grid context). No support data? That means there is no MDN article (feel free to create one!).
* Try some of the pre-defined filters in the navigation. All selected or typed filters will display the filtered properties in a menu on the right.
* CSS Values is now installable as a Progressive Web App (PWA) with offline capability on Chromium-based browsers. iOS also allows installing, but the offline capability doesn't seem to work on there.
* The first value listed for each property is the initial/default value for that property.
* Values in angle brackets (e.g. `<length>`) are linked to the spec, where it describes how they're written.
* The generic keyword values `inherit`, `initial`, and `unset` are omitted to avoid repetition.
