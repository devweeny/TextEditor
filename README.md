# Kilo Text Editor

Kilo is a small, simple text editor written in C. This project follows the tutorial from [viewsourcecode.org](https://viewsourcecode.org/snaptoken/kilo/index.html). With future plans to add more features, Kilo aims to be a lightweight and easy-to-use text editor.

## Features

- Basic text editing capabilities
- Syntax highlighting for C/C++ files
- Line numbers and status bar
- Search functionality
- File saving

## Getting Started

### Prerequisites

To build and run Kilo, you need:

- A C compiler (e.g., `gcc`)
- `make`

### Building

To build the project, run:

```sh
make
```

### Running

To start the editor, run:

```sh
./kilo <filename>
```

Replace `<filename>` with the name of the file you want to edit or create.

### Usage

- Use arrow keys to navigate.
- Press `Ctrl-S` to save the file.
- Press `Ctrl-Q` to quit the editor.
- Press `Ctrl-F` to search within the file.
- Use arrow keys to navigate search results, `Esc` to exit search mode.
- Use `Home` and `End` keys to move to the beginning and end of the line.
- Use `Page Up` and `Page Down` keys to move up and down by a page.
- Use `Backspace` and `Delete` keys to delete characters.

## Acknowledgements

This project follows the tutorial from [viewsourcecode.org](https://viewsourcecode.org/snaptoken/kilo/index.html). Special thanks to the author for the detailed guide.

## Future Plans

- Add support for more file types.
- Add support for multiple buffers.
- Add support for undo/redo functionality.
- Add support for copy/paste functionality.
