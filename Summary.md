## What's in it ?

The directories beginning with an underscore contain materials defining the basic layout and style for the site. 

The __assets/ directory__ contains any non-Markdown materials for the site (e.g., images or example code). These files won’t be touched in the conversion but will be just copied over as-is.

The __pages/ directory__ contains Markdown files that will become html pages on your site.

The ___config.yml file__ contains all sorts of configuration parameters (some of which you’ll need to modify). 

The Rakefile contains instructions for the conversion; you won’t modify this file.

If you build the site locally (for testing purposes), there will also be a _site/ directory containing the actual site (with Markdown files converted to html). You don’t want the _site/ directory in your repository, so include that in the __.gitignore file__.

It’s best to always include License.md and ReadMe.md files. But you wouldn’t need these to be placed on the website; they’d just be viewed in the repository on GitHub. 