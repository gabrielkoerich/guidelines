Guidelines
=================

## General

* Contributions must follow the [GitHub Flow](https://guides.github.com/introduction/flow) with slight modifications. Create a new branch and pull request it to **develop**. Never directly to **master**.
* Use the present tense ("Add feature" not "Added feature") and the imperative mood ("Move class to..." not "Moves class to...") on commits and pull requests.
* Pull requests must be reviewed before merged.
* All classes, functions and variables names must be in english. Avoid abbreviations.
* Use 2 spaces indentation for HTML, CSS and Javascript. 4 spaces for PHP. You should install the [EditorConfig Plugin](https://github.com/sindresorhus/editorconfig-sublime) to configure automatically your Sublime Text.

## PHP Coding Style

We must follow the [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) coding standard and the [PSR-4](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md) autoloading standard.

You also should read the [PHP The Right Way](http://www.phptherightway.com).

### PHPDoc

Below is an example of a valid documentation block. Note that the `@param` attribute is followed by two spaces, the argument type, two more spaces, and finally the variable name:

```php
/**
 * Register a binding with the container.
 *
 * @param  string|array  $abstract
 * @param  \Closure|string|null  $concrete
 * @param  bool  $shared
 * @return void
 */
public function bind($abstract, $concrete = null, $shared = false)
{
    //
}
```

## HTML Coding Style

- Keep white space to a minimum.
- Use 2 spaces for indentation
- Do not use XHTML closing syntax `<br />` - just use standard syntax `<br>` instead
- Lowercase all elements and attributes (it just looks so much neater).
- Indent main 'sections' - for example:

  ```html
    <html>
      <head>
        <meta>
      </head>
      <body>
        Content
      </body>
    </html>
  ```
- Keep `<head>` section in the following order…
    1. `<title>` element
    2. `<meta>` elements
    2. Any ***required*** scripts (e.g. [Modernizr](http://modernizr.com/) or the [HTML5 Shiv](https://github.com/aFarkas/html5shiv), scripts that must be loaded **before** page render)
    3. Style sheets
- Keep HTML structure simple and not too deeply nested.
- Use styles up top in the `<head>` and scripts at the bottom before `</body>`.
- Compress your styles and scripts.
- Avoid making
- Use HTML5 form controls when **applicable** to trigger the right keyboard on mobile (`url`, `email`…)

### Example

Here follows is a basic boilerplate of an HTML page…

```html
  <!doctype html>
  <html dir="ltr" lang="pt-br">
    <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <title></title>
      <link rel="author" href="/humans.txt" type="text/plain">
      <link rel="stylesheet" href="styles.min.css">
    </head>
    <body>
      <!-- ... -->
      <script type="text/javascript" src="scripts.min.js"></script>
    </body>
  </html>
```

## CSS Coding Style
Just follow the [Airbnb CSS Style Guide](https://github.com/airbnb/css).

## Javascript Coding Style
Just follow the [Airbnb Javascript Style Guide](https://github.com/airbnb/javascript).

## Links
- Github Flow: https://guides.github.com/introduction/flow/
- PHP The Right Way: http://www.phptherightway.com/
- PSR-2: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
- PSR-4: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md
- PSR-4 Examples: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader-examples.md
- Google HTML / CSS Style Guide: https://google.github.io/styleguide/htmlcssguide.xml
- Browser Diet: https://browserdiet.com/
- Airbnb Javascript Style Guide: https://github.com/airbnb/javascript
- Oh, shit, git: http://ohshitgit.com/

## Sublime Text Plugins
- EditorConfig - https://github.com/sindresorhus/editorconfig-sublime
- DocBlockr - https://github.com/spadgos/sublime-jsdocs
- CheatSheet - https://github.com/vrachieru/cheatsheet
- Git Gutter - https://github.com/jisaacks/GitGutter
- Markdown Preview - https://github.com/revolunet/sublimetext-markdown-preview
- SASS - https://github.com/nathos/sass-textmate-bundle
- Sublime Linter - https://github.com/SublimeLinter/SublimeLinter3
- Sublime Linter PHP - https://github.com/SublimeLinter/SublimeLinter-php
- Sublime Linter Javascript - https://github.com/SublimeLinter/SublimeLinter-jshint
- JavascriptNext - ES6 Syntax - https://github.com/Benvie/JavaScriptNext.tmLanguage
- GoToClass - https://github.com/lazyguru/GoToClass
- PHP Companion - https://github.com/erichard/SublimePHPCompanion
- SublimeCodeIntel - https://github.com/SublimeCodeIntel/SublimeCodeIntel
- Sublime Pug - https://github.com/davidrios/pug-tmbundle

## Sublime Text Color Schemes / Themes
- Material Theme - https://github.com/equinusocio/material-theme
- Github Theme - https://github.com/AlexanderEkdahl/github-sublime-theme
- Afterglow Theme - https://github.com/YabataDesign/afterglow-theme
