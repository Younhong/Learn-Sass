# Learn-Sass

* How to use sass?

  1. Install sass
  ```
  npm install -g sass
  ```

  2. Convert sass to css
  ```
  sass --watch scss/style.scss css/style.css
  ```

  Or

  try "Live Sass Compiler" Extension in VS Code

  By installing and clicking sass watch, it automatically converts scss file to css file.

  You can customize setting in settings.json(in vscode) like below
  ```
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/css"
        }
    ],
    "liveSassCompile.settings.generateMap": false
  ```

* Benefit of using sass

  When you write css code, you might have to write same decoration for multiple times.  
  By using sass, you can seperate design into specific variable and reuse it in another tag.
