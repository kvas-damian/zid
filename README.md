jQuery zid
===
https://github.com/kvas-damian/zid/

Version: 0.8

Dependencies:
jQuery throttle plugin: http://benalman.com/projects/jquery-throttle-debounce-plugin/

jQuery zid allows you to create column based layout with dynamic number of columns, depending on their with. Main goal of this lib is to add new items in a column that is currently shortest.
Code is binded to onreasize event but throttle is used to gain performance.

Why zid?
===
When we add containers to the shortest column in looks like brick wall and 'zid' means brick wall in Bulgarian language.

References:
* http://bg.wiktionary.org/wiki/%D0%B7%D0%B8%D0%B4 - I hope you can understand that, I can't :)
* http://en.wiktionary.org/wiki/%D0%B7%D0%B8%D0%B4 - more readable version but not exactly precise

Params
===
* selector - jQuery selector for items that can should be distributed into columns.
* minColumnWidth - minimal column width in px
* gutter - gutter in px
* throttleThreshold - delay time in ms for throttle plugin

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

License
===
MIT (http://www.opensource.org/licenses/mit-license.php) License.
