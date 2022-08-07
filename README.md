# HTML Error Demo

This demo is deliberately written with some built-in errors that should be caught by HTML Validators. Use it to test your validators. 

You can use the MDN Learning link in the Resources section to understand what the errors are.

## HTML validate by oliverroick

The [netlify-plugin-html-validate](https://github.com/oliverroick/netlify-plugin-html-validate#readme) is a Netlify plugin that will validate your HTML when it is deployed to Netlify. If your HTML does not pass validation, the deploy fails.

## Instructions

1. Login to Netlify and create a new site using this repo.
1. Let it deploy and see what the page looks like. At first it will deploy because we are not doing any validation.
1. You can keep the funky sitename Netlify gives your page, but do take note of the name for the next step.
1. Now go to the plugins tab in Netlify, and add the netlify-plugin-html-validate to your site
1. After installing the plugin, go to the Deploy tab and Trigger Deploy.
1. The assignment is successful if your deploy fails.
1. The plugin outputs the errors it finds inside the Deploy Log. It gives you the line number and character position of each error found, along with the type of error.



## Sources

This assignment was copied from [MDN Learning](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)

[MDN's Original Source Code](https://github.com/mdn/learning-area/blob/main/html/introduction-to-html/debugging-html/debug-example.html) with CC0 license.
