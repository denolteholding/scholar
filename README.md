# Scholar
+++ STILL WORK IN PROGRESS +++  
The Hugo theme "Scholar" is my personal approach to providing a great theme for your personal website.

## Installation
1. Install dependencies
Install the following tools
    - Hugo (if not already installed)
    - Go (if not already installed)
2. Create a new Hugo site and initialize git module
    ```bash
    hugo new site quickstart
    cd quickstart
    # Future repository of your website: yourname.github.io/sitename
    # If you do not have a remote GIT repository yet, leave it out 
    hugo mod init yourname.github.io/sitename
    ```
4. Add the following to your `config.toml`. If the variable `theme = ...` is set,
   remove that section out of the file.
    ```toml
    [module]
      [[module.imports]]
        path = "github.com/denolteholding/scholar"
        disable=false
    ```

## Supported languages
I plan to support the following languages:
- English
- German
- Chinese (simplified)

## Credit
While I did create "Scholar" myself, I was heavily influenced by [Wowchemy's Academic theme](https://github.com/wowchemy/starter-academic). If you are looking for a professional, feature-rich theme that offers frequent updates and - in my opinion - great code quality, I suggest you to look into their theme before considering this one.
I decided to build my own theme as a learning experience and to custom-tailor it to my needs, but this theme will not reach the feature-richness and matureness that Wowchemy provides.
