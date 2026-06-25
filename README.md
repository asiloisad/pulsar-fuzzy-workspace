# fuzzy-workspace

Quickly find and focus any open item across the workspace.

## Features

- **Fast fuzzy search**: Uses a smart scoring algorithm to rank open items by match quality.
- **Full workspace coverage**: Lists every open pane item in the workspace center and the left, right, and bottom docks.
- **Focus on confirm**: Selecting an item reveals its dock (if hidden), activates its pane, and focuses it.
- **Item actions**: Close an item or copy its path without leaving the keyboard.
- **Icons**: Display an icon per item, derived from the item icon name or its file path.

## Installation

To install `fuzzy-workspace` search for [fuzzy-workspace](https://web.pulsar-edit.dev/packages/fuzzy-workspace) in the Install pane of the Pulsar settings or run `ppm install fuzzy-workspace`. Alternatively, you can run `ppm install asiloisad/pulsar-fuzzy-workspace` to install a package directly from the GitHub repository.

## Commands

Commands available in `atom-workspace`:

- `fuzzy-workspace:toggle`: toggle the fuzzy workspace panel.

Commands available in `.fuzzy-workspace`:

- `select-list:focus`: focus the selected item,
- `select-list:close-item`: close the selected item,
- `select-list:copy-path`: copy the path of the selected item,
- `select-list:query-selection`: set query from editor selection.

## Contributing

Got ideas to make this package better, found a bug, or want to help add new features? Just drop your thoughts on GitHub. Any feedback is welcome!
