This style guide contains styles for fonts, text styles, modals, buttons and forms for relay.edu.<br>

Missing Fonts: 
* 
These fonts will need to be replaced with a close replicate

## Local Installation

`npm install`

## Running the app
You can run the application with PHP's built in web server. Run the following command:

`php -S localhost:8000`

Now, browse to [http://localhost:8000](http://localhost:8000) to see the website.

## SASS

`gulp`

This will build sass files in `sass/` directory to `css/` directory

## Instructions of how to update styleguide:

### Create custom patterns
To create custom patterns like buttons, breadcrumbs, alert messages, etc., create a new .html file and add your HTML markup into the file.

Save the file as `pattern-name.html` into the `markup/patterns` directory.

### Create personalized documentation
You can use markdown or html to create personalized documentation for your examples. Create a new .md or .html file and name it whatever your markup snippet file is named.

Save the file as `markup-name.md` or `markup-name.html` into the `doc/base` or `doc/patterns` directory.

For example, if you want to create doc for `markup/patterns/breadcrumbs.html`, create a file called `breadcrumbs.md` or `breadcrumbs.html` and save it into `doc/patterns`.

## Generating static HTML style guide
You can generate a static index.html version of style guide boilerplate by running the following command:

`php index.php > index.html`


Original project: <a href="https://github.com/bjankord/Style-Guide-Boilerplate/tree/main">Style-Guide-Boilerplate<a>