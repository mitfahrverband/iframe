# iframe
An `<iframe>` displaying aggregated carpool offers from differenct sources to and from a place on a given day.

A demo of the `<iframe>` is running at [https://ridewithukraine.eu/iframe-beispiel.html](https://ridewithukraine.eu/iframe-beispiel.html).
(The `<iframe>` can't be embedded here due to a restriction of [GitHub Flavored Markdown](https://github.github.com/gfm/#disallowed-raw-html-extension-).)

The code for embedding the `<iframe>` is:

```html
<iframe src="https://ridewithukraine.eu/iframedemo.php" height="850" ></iframe>
```
It is recommened not to include an constant width attribute value. 
If omitted to defined as width="100%" the iframe content will scale to the available width as good as possible.

A minimum value for height="840" should be specified to avoid vertical scrollbars for the iframe content.

The following URL parameters are available to define a behavior different from the default:
- go =  [ to | from ]  (default: to)
  - to specify the direction of travel to or from the event location
- showdate = [ on | off ]  (default: off)
  - to show or hide the date information for each entry
