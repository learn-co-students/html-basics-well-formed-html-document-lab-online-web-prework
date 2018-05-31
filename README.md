# Well-Formed HTML Document Lab

How do we keep all of our HTML in the right places? By making sure we build the
structure correctly from the very first line. Let's construct an entire HTML
document to practice putting the necessary elements where they belong.

## Students will be able to ...

1. Add an appropriate `doctype` tag at the top of an HTML file
2. Enclose the HTML contents of a site inside `html` tags
3. Structure an HTML document with `head` and `body` tags
4. Add `title` tags to give the page a title that will show up in the browser
   tab

## Adding the HTML Tags

There are some parts to every HTML document that are always necessary in order
for your browser to correctly interpret and display the content. To get started, open
`index.html` in your text editor.

First, we need to add a `doctype` declaration at the top of the file indicating
how the HTML should be handled, and in particular what
[_mode_](https://developer.mozilla.org/en-US/docs/Web/HTML/Quirks_Mode_and_Standards_Mode)
of HTML the page should be in. In modern web development, using HTML5, we can
simply put `html` within the `doctype` declaration, which will work for all
current browsers. This should always be placed at the top of your HTML
documents:

```html
<!DOCTYPE html>
```

Second, we need to define where the HTML content is on the page by creating
opening and closing `html` tags to enclose all your page's HTML content.

Within the `html` tags, there are two main sections that are required, `head`
and `body`. Add opening and closing `head` and `body` tags within the outer
`html` tags to break your HTML document up into two sections.

The `head` section generally contains data intended for the web browser,
including information about the page that is useful to search engines, and also
contains the `title`, which will show up at the top of a browser window,
typically in the _tab_. The `body` section contains all the content our users
will see and interact with on the page.

In order to pass this lab, your task is to create a well formed document using
the tags we've discussed. You can run the tests for this lab via `learn`. Make
sure you save the file before running the test suite. Failing tests will provide
helpful error messages that you can use to debug your code — read them closely
for hints!

## Viewing Your Work in the Browser

While working through these assignments, your general workflow should center on
writing code in the text editor and periodically running the test suite in the
terminal to check your work.

Another great way to track your progress is to open up the HTML document in your
browser and watch how each change you make in the text editor affects the visual
layout in the browser. For reference, here's a guide to [viewing HTML pages in
the Learn IDE](http://help.learn.co/the-learn-ide/common-ide-questions/viewing-
html-pages-in-the-learn-ide).

Once you have the HTML document open in your browser, you can make changes to it
in the text editor, save the file, refresh the page in the browser, and see the
changes instantly.

## Resources

* [W3S — HTML `<!DOCTYPE>` Declaration](https://www.w3schools.com/tags/tag_doctype.asp)

## Conclusion

We've figured out how to construct a solid structure for the HTML document. Now,
as you pick up new HTML tags, you'll be able to add more elements to build out
the rest of the page.
