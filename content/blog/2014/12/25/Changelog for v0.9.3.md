Now with full-featured templating! Powered by [Swig](href="http://paularmstrong.github.io/swig/")

<pre>{% raw %}{% for user in users %}<br>&nbsp;&nbsp;&nbsp;&nbsp;&lt;h2&gt;Thanks {{ user.name|capitalize }}!&lt;h2&gt;<br>{% endfor %}{% raw %}</pre>

### Noteworthy

- added help screen for keyboard shortcut to settings dropdown
- use <a href="http://paularmstrong.github.io/swig/">Swig Templating</a>
- use <a href="http://paularmstrong.github.io/swig/docs/filters">Swig Filters</a>

### Fixes

- editor wasn't updating when hidden
- response headers weren't persisting properly

### Minor Changes

- environment editor now uses monospace font
- improved sidebar dragging appearance
- added filter <code>{% raw %}{{ 10|random }}{% endraw %}</code> (random 10-digits)
- added default variable <code>_timestamp</code> (current timestamp)
- added default variable <code>_date</code> (current date string)
- added contact link

