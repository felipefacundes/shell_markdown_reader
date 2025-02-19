# Shell Markdown Reader

Shell Markdown Reader is a powerful and enhanced Markdown reader designed for terminal users. This script processes and displays Markdown content with clean formatting, color highlights, and optional syntax highlighting for better readability. It is ideal for developers and content creators who prefer working in the terminal while maintaining structured and readable documentation.

## Features
- **Multi-level headers** with distinct colors for better visibility.
- **Syntax highlighting** for inline code and code blocks.
- **Formatted lists**, including bullet points and numbered lists.
- **Table rendering** with color differentiation for headers.
- **Hyperlink processing**, displaying links in cyan for quick identification.
- **Horizontal rule formatting** for improved readability.
- **Automatic removal of unwanted HTML tags** such as `<br>`, `<code>`, and `<pre>`.
- **Efficient processing of various Markdown syntaxes**.

## Installation
To install Shell Markdown Reader, clone the repository using:

```sh
git clone https://github.com/felipefacundes/shell_markdown_reader
cd shell_markdown_reader
chmod +x shell_markdown_reader.sh
```

## Usage
Run the script with a Markdown file as an argument:

```sh
./shell_markdown_reader.sh README.md
```

### Options:
- `-h`, `--help`: Show the help message.
- `-nl`, `--no-less`: Disable pagination mode.
- `-nh`, `--no-hl`: Disable syntax highlighting for code blocks.

Example usage:

```sh
./shell_markdown_reader.sh --no-hl document.md
```

## Dependencies
Ensure that the following dependencies are installed:
- `source-highlight`
- `less`

If they are missing, install them using:

```sh
sudo apt install source-highlight less  # For Debian-based systems
sudo dnf install source-highlight less  # For Fedora-based systems
```

## Part of Shell Utils Framework
Shell Markdown Reader is also part of the **Shell Utils** framework, an extensive collection of scripts and utilities designed to simplify terminal workflows. You can explore more at [Shell Utils Repository](https://github.com/felipefacundes/shell_utils).

## License
This project is licensed under the **GPLv3 License**.

## Author
Developed by **Felipe Facundes**.