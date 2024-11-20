# robolab-docs

A comprehensive documentation site for NAO6 robot development, built with MkDocs and the Material theme. Features detailed guides for software installation, development environment setup, and programming tutorials.

## Features

- Clean, responsive documentation layout
- Dark/light mode support
- Searchable content
- Code syntax highlighting
- Tabbed content sections
- Navigation breadcrumbs
- Mobile-friendly design

## Tech Stack

- [MkDocs](https://www.mkdocs.org/) - Documentation site generator
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - Modern documentation theme
- [Python-Markdown](https://python-markdown.github.io/) - Markdown processing
- [PyMdown Extensions](https://facelessuser.github.io/pymdown-extensions/) - Extended Markdown features

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/soconnor0919/robolab-docs.git
```

2. Install dependencies:
```bash
pip install mkdocs mkdocs-material
```

3. Start the development server:
```bash
mkdocs serve
```

4. Open [http://localhost:8000](http://localhost:8000) in your browser

## Project Structure

```
.
├── docs/                    # Documentation source files
│   ├── assets/             # Images and other static files
│   ├── getting-started/    # Getting started guides
│   ├── cpp-sdk/            # C++ SDK documentation
│   └── index.md           # Home page
├── mkdocs.yml             # MkDocs configuration
└── .gitignore            # Git ignore rules
```

## Configuration

The site configuration is managed through `mkdocs.yml`. Key features include:

- Material theme customization
- Navigation structure
- Search functionality
- Markdown extensions
- Color scheme toggles

## Documentation Sections

- Getting Started
  - Software Installation
  - Using robolab-installer
  - Manual Installation
- NAOqi C++ SDK
  - First C++ Project Setup
- References

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

Documentation by Sean O'Connor at Bucknell University, 2023

## Contact

Sean O'Connor
- Institution: Bucknell University
- Project: CSCI 278 Independent Study, Spring 2023

## References

This documentation site combines the work of many, specifically:

- Ryan Mosenkis, '22
- Cole Hausman, '23
- The Aldebaran Developers

The page was generated using [MkDocs](https://www.mkdocs.org/), with the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

## Special Thanks

None of this work would be possible without the support of Professor Perrone. Thank you for all your help and guidance throughout my first year here at Bucknell.