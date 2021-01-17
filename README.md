# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  SOFTWARE ENGINEERING IMMERSIVE

# Manipulating the DOM using JavaScript

## Set up

1. Clone this repo and `cd js-dom-quotes-lab`
1. Open the index page in your browser: `chrome index.html`
1. Open Chrome's developer tools: <kbd>command + option + i</kbd>
1. Select and inspect the "elements" from top ribbon

## Exercise

This is an exercise in finding elements on the page (in the DOM).

Your task is to write javascript, in the `script.js` file to retrieve the objects which represent these elements.

Start with these:

1. Select the `<body>`
1. Select the `<header>`
1. Select all of the elements with class "quote"
1. Select all of the subject elements
1. Select the navigation links
1. Select all the quotes in the "life" section.
1. Using **relative** selection (i.e., don't use `querySelector`, `getElementBy...` etc.), select the `<p>` element containing the second Mark Twain quote
1. Do the same using a query selector
1. Select the 'Quotes About Motivation' heading
1. The first section has a class 'subject', preserve it, and add a class 'simplicity' as well.


### Bonus

- Create an element with the text of your favorite quote.
- Add the element that you created in the previous step to the layout by appending it to a corresponding subject section.
- Add the author's last name, as a class name, to one of the quotes.
