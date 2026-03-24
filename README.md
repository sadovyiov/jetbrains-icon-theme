# JetBrains Icon Theme for Zed

A clean and familiar icon theme for the **Zed editor**, inspired by the iconography used in JetBrains IDEs (such as IntelliJ IDEA, WebStorm, GoLand, etc.).

This extension brings a recognizable development experience to Zed by reusing well-known file and folder icons, helping you quickly navigate projects with visual clarity.

## Features

- 109 JetBrains-style file and folder icons
- Supports both **Dark** and **Light** UI themes

## Screenshots

### Dark
![dark](https://github.com/user-attachments/assets/52dada52-fcdf-46b2-b190-3ca127a8b0aa)

### Light
![light](https://github.com/user-attachments/assets/6628b85c-f352-4974-8481-a3f763115e4d)

## Installation

### From Dev (local setup)

1.  Clone the repository:

``` bash
git clone https://github.com/sadovyiov/zed-jetbrains-icons.git
```

2.  Open Zed

3.  Go to:
    **Extensions → Install Dev Extension**

4.  Select the cloned folder

> Requires **Rust** installed on your system

## Usage

After installation:

1.  Open Zed settings
2.  Find **Icon Theme**
3.  Select:
    -   `JetBrains Dark`
    -   `JetBrains Light`

## Customization

You can modify icons or extend support for additional file types:

-   Update icon mappings in the extension config
-   Add new SVG icons
-   Override existing associations

## Contributing

Contributions are welcome!

### Steps:

1.  Fork the repository

2.  Clone your fork:

``` bash
git clone https://github.com/your-username/zed-jetbrains-icon.git
```

3.  Create a new branch:

``` bash
git checkout -b feature/your-feature
```

4.  Make your changes

5.  Test locally in Zed:

-   `Extensions → Install Dev Extension`

6.  Commit and push:

``` bash
git commit -m "Add: your feature"
git push origin feature/your-feature
```

7.  Open a Pull Request

## Motivation

Zed is a fast and modern editor, but many developers are used to JetBrains-style icons.
This project aims to combine the speed of Zed with the familiar visual language of JetBrains IDEs.

## License

MIT License
