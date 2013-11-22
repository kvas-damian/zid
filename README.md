jQuery zid
===
https://github.com/kvas-damian/zid/
Version: 0.8

Dependencies:
jQuery throttle plugin: http://benalman.com/projects/jquery-throttle-debounce-plugin/

jQuery zid allows you to create column based laouyt with dynamic number of columns, depending on their with. Main goal of this lib is to add new items in a column that is currently shortest.
Code is binded to onreasize event but debounce is used to gain performance.

Why zid?
===
// TODO

Params
===
* selector - jquery selector for items that can should be distributed into columns.
* minColumnWidth - minimal column width in px
* gutter - gutter in px
* throttleThreshold - delay time in ms for debounce plugin

Example usage
===
````
$('#someId').zid({
  minColumnWidth: 350, 
  selector: '.class, .classTwo',
  gutter: 30,
  throttleThreshold: 100
});
````

Licence
===
MIT (http://www.opensource.org/licenses/mit-license.php) License.
