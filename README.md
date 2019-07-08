# Well-Formed HTML Document Lab

## Learning Goals

- Add an appropriate `DOCTYPE` tag to the top of an HTML file
- Add opening and closing `html` tags
- Add opening and closing `head` and `body` tags
- Add `title` tags

## Introduction

How do we keep all of our HTML in the right places? By making sure we build the
structure correctly from the very first line. Let's construct an entire HTML
document to practice putting the necessary elements where they belong.

Every HTML document requires a few specific tags that enable your browser to
correctly interpret and display the content. A good way to think about this is
that we need to build a solid structure for the content we want to put in our
page, and each tag has a function in building that structure. If we forget a
tag, our structure will weaken and the browser might not be able to display our
page at all. So it's important we put every piece in its place at the beginning.

To get started, open `index.html` in your text editor.

## Add an Appropriate `DOCTYPE` Tag to the Top of an HTML File

The first step is always to add a `DOCTYPE` declaration at the top of the file
indicating to the browser how the HTML should be handled, and, in particular,
what
[_mode_](https://developer.mozilla.org/en-US/docs/Web/HTML/Quirks_Mode_and_Standards_Mode)
of HTML the page should be in. In modern web development, we can simply put
`html` within the `DOCTYPE` declaration:

```html
<!DOCTYPE html>
```

## Add Opening and Closing `html` Tags

Secondly, we need to define where the HTML content is on the page by creating
opening and closing `html` tags to enclose _all_ of your page's HTML content.

## Add Opening and Closing `head` and `body` Tags

Within the `html` tags, there are two main sections that are required: `head`
and `body`. The `head` section generally contains data intended for the web
browser, including information about the page that is useful to search engines.
The `body` section contains all the content our users will see and interact with
on the page.

## Add a `title` Tag

The `head` section contains the `title`, which will show up at the top of a
browser window, typically in the _tab_. As the web developer, you get to decide
what the title will be — whatever text you type in between the `title` tags will
show up as the page title.

You can run the tests for this lab via `learn`. Make sure you save the file
before running this command. Failing tests will provide helpful error messages
that you can use to debug your code — read them closely for hints!

### View Your Work in the Browser

While working through these assignments, your general workflow should center on
writing code in the text editor and periodically running `learn` in the terminal
to check your work.

Another great way to track your progress is to open up the HTML document in your
browser and watch how each change you make in the text editor affects the visual
layout in the browser. For reference, here's a guide to [viewing HTML pages in the Learn IDE][help].

Once you have the HTML document open in your browser, you can make changes to it
in the text editor, save the file, refresh the page in the browser, and see the
changes instantly.

## Conclusion

We've figured out how to construct a solid structure for the HTML document. Now,
as you pick up new HTML tags, you'll be able to add more elements to build out
the rest of the page.

## Resources

* [W3S — HTML `<!DOCTYPE>` Declaration](https://www.w3schools.com/tags/tag_doctype.asp)

[help]: http://help.learn.co/the-learn-ide/common-ide-questions/viewing-html-pages-in-the-learn-ide



