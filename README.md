# my-sublime-settings

## Preferences.sublime-settings
```JSON
{
  "bold_folder_labels": true,
  "caret_style": "phase",
  "color_scheme": "Packages/User/SublimeLinter/Monokai JSON+ (SL).tmTheme",
  "fade_fold_buttons": false,
  "folder_exclude_patterns": [".svn", ".git", ".hg", "CVS", "node_modules"],
  "font_size": 11,
  "highlight_line": true,
  "highlight_modified_tabs": true,
  "ignored_packages": ["Vintage"],
  "line_padding_bottom": 1,
  "line_padding_top": 1,
  "open_files_in_new_window": false,
  "tab_size": 2,
  "translate_tabs_to_spaces": true
}
```
## Default (Windows).sublime-keymap
```JSON
[
  {
    "keys": ["ctrl+,"],
    "command": "insert_snippet",
    "args": {
      "contents": "console.log('${1:}$SELECTION');${0}"
    }
  },
  {
    "keys": ["ctrl+shift+,"],
    "command": "insert_snippet",
    "args": {
      "contents": "console.log(${1:}$SELECTION);${0}"
    }
  },
  {
    "keys": ["ctrl+shift+."],
    "command": "insert_snippet",
    "args": {
      "contents": "function(req, res) {\n\t${1:}$SELECTION\n}${0}"
    }
  },
  {
    "keys": ["ctrl+."],
    "command": "insert_snippet",
    "args": {
      "contents": "function() {\n\t${1:}$SELECTION\n}${0}"
    }
  },
  {
    "keys": ["alt+left"],
    "command": "jump_back"
  },
  {
    "keys": ["alt+right"],
    "command": "jump_forward"
  },
  {
    "keys": ["ctrl+shift+d"],
    "command": "delete_line"
  },
  {
    "keys": ["ctrl+alt+down"],
    "command": "duplicate_line"
  },
  {
    "keys": ["alt+down"],
    "command": "swap_line_down"
  },
  {
    "keys": ["alt+up"],
    "command": "swap_line_up"
  },
  { "keys": ["ctrl++"], "command": "unfold" },
  { "keys": ["ctrl+keypad_plus"], "command": "unfold" },
  { "keys": ["ctrl+-"], "command": "fold" },
  { "keys": ["ctrl+keypad_minus"], "command": "fold" },
  { "keys": ["ctrl+alt+shift+b"], "command": "reindent", "args": { "single_line": false } },
  { "keys": ["ctrl+alt+f"], "command": "esformatter" },
  { "keys": ["ctrl+shift+w"], "command": "toggle_setting", "args": { "setting": "word_wrap" } }
]
```
## Default (OSX).sublime-keymap
```JSON
[
  {
    "keys": ["super+,"],
    "command": "insert_snippet",
    "args": {
      "contents": "console.log('${1:}$SELECTION');${0}"
    }
  },
  {
    "keys": ["super+alt+e"],
    "command": "insert_snippet",
    "args": {
      "contents": "/* eslint-disable ${1:}$SELECTION*/${0}\n"
    }
  },
  {
    "keys": ["super+shift+,"],
    "command": "insert_snippet",
    "args": {
      "contents": "console.log(${1:}$SELECTION);${0}"
    }
  },
  {
    "keys": ["super+shift+."],
    "command": "insert_snippet",
    "args": {
      "contents": "function(req, res) {\n\t${1:}$SELECTION\n}${0}"
    }
  },
  {
    "keys": ["super+."],
    "command": "insert_snippet",
    "args": {
      "contents": "function() {\n\t${1:}$SELECTION\n}${0}"
    }
  },
  {
    "keys": ["super+left"],
    "command": "jump_back"
  },
  {
    "keys": ["super+right"],
    "command": "jump_forward"
  },
  {
    "keys": ["super+shift+d"],
    "command": "delete_line"
  },
  {
    "keys": ["super+alt+down"],
    "command": "duplicate_line"
  },
  {
    "keys": ["alt+down"],
    "command": "swap_line_down"
  },
  {
    "keys": ["alt+up"],
    "command": "swap_line_up"
  },
  { "keys": ["super++"], "command": "unfold" },
  { "keys": ["super+keypad_plus"], "command": "unfold" },
  { "keys": ["super+-"], "command": "fold" },
  { "keys": ["super+keypad_minus"], "command": "fold" },
  { "keys": ["super+alt+shift+b"], "command": "reindent", "args": { "single_line": false } },
  { "keys": ["super+shift+w"], "command": "toggle_setting", "args": { "setting": "word_wrap" } },
  { "keys": ["super+alt+up"], "command": "select_lines", "args": { "forward": false } },
  { "keys": ["super+shift+;"], "command": "format_javascript" },
  { "keys": ["f3"], "command": "goto_definition" }
]
```
