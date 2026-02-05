# B.Tech Electrical & Electronics Engineering - SRMIST

A comprehensive documentation website for the B.Tech Electrical and Electronics Engineering program at SRM Institute of Science and Technology.

## About

This documentation provides complete information about:
- Program overview and objectives
- Eligibility criteria
- Admission process
- Detailed curriculum for all 8 semesters
- Campus facilities and contact information

## Features

- 📚 Complete semester-wise curriculum
- 🎓 Detailed eligibility requirements
- 📝 Step-by-step admission guide
- 🏛️ Campus facilities information
- 📱 Fully responsive design
- 🔍 Advanced search functionality
- 🌙 Dark/Light mode toggle

## Built With

- [MkDocs](https://www.mkdocs.org/) - Documentation generator
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - Beautiful theme
- GitHub Pages - Hosting

## Local Development

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/srm-eee-docs.git
cd srm-eee-docs
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the development server:
```bash
mkdocs serve
```

4. Open your browser and visit: `http://127.0.0.1:8000`

### Building the Site

To build the static site:
```bash
mkdocs build
```

The site will be generated in the `site/` directory.

## Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions when changes are pushed to the `main` branch.

### Manual Deployment

To manually deploy to GitHub Pages:
```bash
mkdocs gh-deploy
```

## Project Structure

```
srm-eee-docs/
├── docs/
│   ├── index.md                 # Home page
│   ├── eligibility.md           # Eligibility criteria
│   ├── admission.md             # Admission process
│   ├── curriculum.md            # Complete curriculum
│   ├── contact.md               # Contact & facilities
│   ├── stylesheets/
│   │   └── extra.css           # Custom styles
│   ├── javascripts/
│   │   └── extra.js            # Custom scripts
│   └── assets/                  # Images and other assets
├── .github/
│   └── workflows/
│       └── deploy.yml           # GitHub Actions workflow
├── mkdocs.yml                   # MkDocs configuration
├── requirements.txt             # Python dependencies
└── README.md                    # This file
```

## Configuration

### MkDocs Configuration

The site configuration is in `mkdocs.yml`. Key settings:

- **Theme**: Material for MkDocs with custom colors
- **Features**: Navigation tabs, search, dark mode
- **Extensions**: Admonitions, tables, code highlighting

### Customization

- **Colors**: Edit `docs/stylesheets/extra.css` for custom colors
- **Logo**: Replace `docs/assets/logo.png` with your logo
- **Social Links**: Update in `mkdocs.yml` under `extra.social`

## Content Updates

### Adding New Pages

1. Create a new `.md` file in the `docs/` directory
2. Add the page to `nav` section in `mkdocs.yml`
3. Commit and push changes

### Updating Existing Content

1. Edit the relevant `.md` file in `docs/`
2. Preview changes with `mkdocs serve`
3. Commit and push changes

## Information Source

All information is sourced from the official SRMIST website:
- [Program Page](https://www.srmist.edu.in/program/b-tech-electrical-electronics-engineering/)
- [Department Website](https://www.srmist.edu.in/department/department-of-electrical-and-electronics-engineering/)

## License

This documentation is for educational purposes. All program information is property of SRM Institute of Science and Technology.

## Contact

For queries about the program, contact:
- **Email**: infodesk@srmist.edu.in
- **Phone**: +91 44 27417000

## Acknowledgments

- SRMIST Department of Electrical and Electronics Engineering
- Material for MkDocs theme creators
- All contributors

---

**Note**: This is an unofficial documentation site. For official information, always refer to [www.srmist.edu.in](https://www.srmist.edu.in)
