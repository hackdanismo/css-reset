# CSS Reset
A lightweight and modern `CSS reset` for consistent styling across browsers. Released under the `MIT License`.

+ [HTML](#html)
+ [Project Structure](#project-structure)

## HTML
This is a general `HTML` page template that can be used for the initial page layout and structure. Add the minified CSS file - `css-reset.min.css` - to the `HTML` template to apply `CSS Reset`.

Open the code editor and save the following file as: `index.html`:

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="utf-8">
    <!-- Allows the page to be responsive and scales on mobile devices -->
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Helps SEO (Search Engine Optimisation) and sharing of previews -->
    <meta name="description" content="A brief description of what this page or site is about.">
    <!-- Optional but useful in collaborative projects -->
    <meta name="author" content="Your Name or Organization">
    <!-- Set the color of the browser's top bar on mobile devices -->
    <meta name="theme-color" content="#fff">

    <title>CSS Reset</title>

    <!-- Preload the main CSS stylesheet, not the reset here -->
    <!-- <link rel="preload" href="styles/main.css" as="style"> -->

    <!-- Reset and any additional CSS stylesheets (load after preload) -->
    <link rel="stylesheet" href="styles/css-reset.min.css">
</head>
<body>
    <header role="banner">
        <!-- Website header -->
    </header>
    <main role="main">
        <!-- Page content here -->
    </main>
    <footer role="contentinfo">
        <!-- Website footer -->
    </footer>

    <noscript>
        <p>This website works best with JavaScript enabled.</p>
    </noscript>
</body>
</html>
```

## Project Structure
On `macOS` the project structure/folder can be created in the terminal (optional). Alternatively, create the folders and files manually and copy/paste the code where needed.

 ```shell
# Create the folder and give it a name. Replace project-root with a suitable name for the website/project
$ mkdir project-root
# Change directory into the project folder
$ cd project-root
# Create the folder for styles where the CSS stylesheets will be placed
$ mkdir styles
# Create empty index.html where the HTML code can be pasted
$ touch index.html
# Change directory into the styles folder
$ cd styles
# Create empty css-reset.min.css file where the CSS code can be pasted
$ touch css-reset.min.css
```

The project structure should look something like this:

```
project-root/
│
├── index.html
│
├── styles/
│   ├── css-reset.css
│   ├── css-reset.min.css
```
