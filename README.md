# CourtNotes

This is a simple and customizable Notes App Template built using [Eleventy (11ty)](https://www.11ty.dev/). The project serves as a learning exercise while I explore 11ty's features and functionalities, with the goal of later implementing it in my portfolio.

## 🚀 Features

- 📝 Static site generation with **Eleventy**
- 📄 Templating with **Nunjucks**
- 🗂️ **Netlify CMS** for easy content management
- 🎨 Minimal and responsive design
- ⚡ Fast and optimized for performance

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/notes-app-template.git
   cd notes-app-template
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the Development Server

To start the development server, run:

```sh
npm run dev
```

This will launch the app at `http://localhost:8080/`.

### Building for Production

To generate a production-ready build, run:

```sh
npm run build
```

The output will be in the `_site` directory.

## Folder Structure

```
notes-app-template/
├── src/
│   ├── _data/      # Data files
│   ├── _includes/  # Reusable templates
│   ├── notes/      # Markdown notes
│   ├── styles/     # CSS files
│   ├── scripts/    # JavaScript files
│   ├── index.njk   # Homepage template
│   └── ...
├── .eleventy.js    # 11ty configuration
├── package.json    # Project dependencies
├── README.md       # Project documentation
└── ...
```

## Customization

- Modify `_data/` for global site data.
- Update `_includes/` to change the UI components.
- Add new Markdown files in `notes/` to create new notes.
- Customize styles in `styles/` to match your preferred design.

## Roadmap

- Implement search functionality
- Add tagging and categorization for notes
- Support for dark mode
- Improve accessibility and performance

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- [Eleventy](https://www.11ty.dev/) for the static site generator
- Open-source community for inspiration and guidance

## Author

[Courtney Fradreck](https://courtney.codes)
