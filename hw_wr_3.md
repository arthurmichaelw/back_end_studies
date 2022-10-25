## Written HW 3 ##

## Explain what Index, New, Create, and Show Routes markdown code block.

Index, New, and Show routes are all expressions of the HTTP verb GET.

## Index Routes ##

An Index route lists all of the files available to the viewer. This is represented as a table of contents that lists all the options.

An index route uses the GET HTTP verb and mongoose .find method and renders a view: Index.jsx

## New Routes ##

The New route, is a GET HTTP Verb, used for displaying the HTML of creating a new item. This doesnt rely on database so there is no mongoose method. It will read in the url from fruits like /fruits/new and will be rendered as New.jsx.

## Show Routes ##

The show route is rendered as a page brought from the index. It used the GET HTTP method and uses the .findOne or .findById mongoose method. It is displayed on the Show.jsx page.