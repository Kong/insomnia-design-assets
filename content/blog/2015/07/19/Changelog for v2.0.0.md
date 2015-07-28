**v2.0 Brings Querystring Editing and More!**

I've been hard at work refactoring the entire Insomnia codebase. What does that mean for you? Not much, but it makes me happy.

There are also a few highly-requested features in this update, including query param generation, the ability to preview HTML responses, and the ability to repeat requests on a timed interval. 
I even made a getting started video to demonstrate some of the more advanced features of Insomnia. Check it out below.

<div style="text-align: center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/lPFOEufD6mQ" frameborder="0" allowfullscreen></iframe>
</div>

### Noteworthy

- friendly editor for query string parameters (similar to header editor)
- new option to toggle between raw and rendered for HTML responses
- cmd (or ctrl) click the purple submit button twice to make automatically repeating requests. The time between your clicks will be used as the delay between requests. Click a third time to stop the timer.

### Fixes

- fixed edits resetting when editing certain things
- fixed minor bug related to the Quick Switcher
- fixed highlight (:focus) color on HTTP method chooser
- fixed multi-workspace state sync bug
- fixed loading spinner not showing on shorter requests
- fixed launch count being specific to your workspace. This meant you would see the "please rate Insomia" dialog more than once.

### Minor Changes

- better first-user experience
- changed the default request format to JSON
- only show format chooser when not a GET request
- added "view changelog" button to main dropdown
- response body editor is now more apparently "read-only"
