Packaging Keypress for [Meteor.js](http://meteor.com), the most popular full-stack JavaScript
framework on GitHub.

# Usage

Note that for Meteor, you must access Keypress via the `Keypress` global, rather than via
`window.keypress` as advised in [the documentation](http://dmauro.github.io/Keypress/). Do this:

    var listener = new Keypress.Listener();

Everything else is the same.


# Meteor

If you're new to Meteor, here's what the excitement is all about -
[watch the first two minutes](https://www.youtube.com/watch?v=fsi0aJ9yr2o); you'll be hooked by 1:28.

That screencast is from 2012. In the meantime, Meteor has become a mature JavaScript-everywhere web
development framework with numerous [advantages](http://www.meteorpedia.com/read/Why_Meteor) over all
other single-page application frameworks.


# Issues

If you encounter an issue while using this package, please CC @dandv when you file it in this repo.


# DONE

* Instantiation and basic functionality test


# TODO

* Test to ensure bindings are preserved when re-rendering templates
