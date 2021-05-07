# Eclipse Classic color theme for Rust and Go

This extension is a light theme that uses the classic Eclipse colors. Nothing special. This theme supports Rust and Go tokens.

![screenshot](https://github.com/growingspaghetti/rust-go-classic-eclipse-color-theme/raw/master/screenshot.png)

I recommend you to use another plugin called **indent-rainbow**(oderwat.indent-rainbow) with this theme. The following color settings fit well together.
```
    "indentRainbow.colors": [
        "rgba(254,254,198,0.6)",
        "rgba(216,254,216,0.6)",
        "rgba(254,216,254,0.6)",
        "rgba(202,249,249,0.6)"
    ],
```

The colors can be overwritten by adding items in settings.json.
```
"editor.tokenColorCustomizations": {
    "textMateRules": [
        ~~ for example,
        {
            //"match": "<\\-",
            "scope": "keyword.operator.channel.go",
            "settings": {
                "foreground": "#323232",
                "fontStyle": ""
            }
        },
    ]
},
```
The scopes are found in this file. https://github.com/growingspaghetti/rust-go-classic-eclipse-color-theme/blob/master/themes/rust-go-classic-eclipse-color-theme-color-theme.json

## My personal font recommendation
 - https://github.com/i-tu/Hasklig
 - http://ftp.gnu.org/gnu/freefont/

```
    "editor.fontFamily": "Hasklig",
    "editor.fontLigatures": true,
    "terminal.integrated.fontFamily": "FreeMono",
```

![screenshot-let](https://github.com/growingspaghetti/rust-go-classic-eclipse-color-theme/raw/master/let-independent.png)

```
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": [
                "punctuation.brackets.curly.rust",
                "keyword.other.let.rust",
                "keyword.other.pub.rust"
            ],
            "settings": {
                "foreground": "#ffe600",
                "fontStyle": ""
            }
        },
        {
            "scope": [
                "constant.numeric",
                "constant.numeric.decimal.go",
            ],
            "settings": {
                "foreground": "#ba4f37"
            }
        },
    ]
},
```

For other languages, [uloco.theme-bluloco-light](https://marketplace.visualstudio.com/items?itemName=uloco.theme-bluloco-light) looks amazing for me.
