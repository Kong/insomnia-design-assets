Insomnia provides powerful request templating via the
[Swig](http://paularmstrong.github.io/swig/) template language. You can use templating anywhere
you can enter text. Here are some common use cases for templating API requests.

{% raw %}
- get the current timestamp with `{{ Date.now() }}`
- define a `base_url` variable and use it in every request `{{ base_url }}/my/unique/path`
- generate a 5-digit random number with `{{ 5 | random }}`
{% endraw %}


### How to Disable Templating

You can disable templating in specific cases by using Swig's
[raw](http://paularmstrong.github.io/swig/docs/tags/#raw) tag. Anything inside these tags will be
ignored by Swig.
