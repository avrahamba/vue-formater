# vue-format README

Format single file with '.vue' used in 'vscode' editor.
https://marketplace.visualstudio.com/items?itemName=febean.vue-format
> If you have some issue, just let me know https://github.com/avrahamba/vue-formatter

> Your issue is my force for this project.  `Welcome to STAR && FORK`

> Js-beautify is heavily dependent, so most of them are limited by js-beautify. In theory, the configuration of js-beautify can be applied.

<!-- ## Features
<img src="https://raw.githubusercontent.com/avrahamba/vue-formatter/master/images/command.gif" alt="command" width=600/> -->

## Requirements
- js-beautify: [https://github.com/beautify-web/js-beautify](https://github.com/beautify-web/js-beautify)
- pug-beautify: [https://github.com/vingorius/pug-beautify](https://github.com/vingorius/pug-beautify)

## Keyboard Shortcuts
- mac: `cmd+ctrl+f`
- win: `alt+ctrl+f`

## Extension Settings

- Use [js-beautify](https://github.com/beautify-web/js-beautify)'s config && [pug-beautify](https://github.com/vingorius/pug-beautify)'s config
- indent_size: default use the "editor.tabSize"

```jsonc
{
    "htmlIndentRoot": false, // If need to indent the root tag of template in ".vue" file
    "breakAttrLimit": -1, // when attributes.length > the value，break attributes force; keep inline when -1.
    "attrEndWithGt": true, // when "break_attr_limit" works, if don't use "\n" before tag's ">"，default "true"
    "formatNeed": ["html", "js", "css"], // the list of need to format, default ["html", "js", "css"]. delete anyone if you don't need format.
    "jsBeautify": {
        "indent_char": " ",
        "indent_with_tabs": false,
        "brace-style": "collapse",
        "space_after_anon_function": true,
    },
    "indent_size": "editor.tabSize",
    "css": {},
    "js": {},
    "html": {
        // "force_format": ["template"],
        "wrap_attributes": "auto"
    },
    "pugBeautify": {
        "fill_tab": false
    }
}

```

|Key|Example|Default|
|---|---|---|
|vue-format.html_indent_root|false|false|
|vue-format.break_attr_limit|2|-1|
|vue-format.attr_end_with_gt|true|true|
|vue-format.format_need|["html"]|["html", "js", "css"]
|vue-format.js-beautify|(See the config at front)|(See the config at front)
|vue-format.pug-beautify|{fill_tab: false}|{fill_tab: false}


## Changelog
U can see the changelog in [CHANGELOG.md](./CHANGELOG.md)

<!-- ## Todo List
Some things todo in [todo.md](./todo.md) -->