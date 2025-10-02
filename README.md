# CV Repository

This repository contains a professional LaTeX CV template with modern, ATS-friendly formatting. Built with clean design principles and professional typography for software engineering positions.

## 🚀 Quick Start

### Prerequisites

- **LaTeX distribution**: BasicTeX, TeX Live, MiKTeX, or MacTeX
  - On macOS: `brew install --cask basictex`
- **Git** for version control
- **VS Code** with LaTeX Workshop extension (recommended)

### Basic Usage

```bash
# Clone repository
git clone <repository-url>
cd cv

# Compile CV using latexmk (recommended)
latexmk -pdf cv_diomidis_anadiotis_2025_v1.tex

# Or use pdflatex directly
pdflatex cv_diomidis_anadiotis_2025_v1.tex

# View generated PDF
open cv_diomidis_anadiotis_2025_v1.pdf
```

## 📁 Repository Structure

```
├── cv_diomidis_anadiotis_2025_v1.tex    # Main LaTeX CV source
├── cv_diomidis_anadiotis_2025_v1.pdf    # Compiled PDF output
├── .gitignore                           # LaTeX build files exclusion
└── README.md                            # This documentation
```

### Build Artifacts (Git-ignored)

```
├── *.aux                    # LaTeX auxiliary files
├── *.fdb_latexmk           # Latexmk database
├── *.fls                   # File list
├── *.log                   # Compilation logs
├── *.out                   # Hyperref outputs
└── *.synctex.gz            # SyncTeX files
```

## 📄 CV Features

### Professional Sections

- **Professional Summary**: Concise value proposition with quantified achievements
- **Areas of Expertise**: Visual skill matrix for quick scanning
- **Key Achievements**: Quantified business impact and technical accomplishments
- **Experience**: Detailed work history with leadership and technical depth
- **Education & Certifications**: Academic background and professional development
- **Technical Skills**: Categorized technical competencies

### Design Features

- ✅ **ATS-Friendly**: Machine-readable formatting for applicant tracking systems
- ✅ **Modern Layout**: Clean, professional design with clear visual hierarchy
- ✅ **Responsive Text**: Optimized for both digital and print formats
- ✅ **FontAwesome Icons**: Professional contact information presentation
- ✅ **Quantified Metrics**: Data-driven achievement presentation

## 🛠️ Development Workflow

### LaTeX Compilation

```bash
# Using latexmk (recommended)
latexmk -pdf cv_diomidis_anadiotis_2025_v1.tex

# Using pdflatex (manual)
pdflatex cv_diomidis_anadiotis_2025_v1.tex
# Run twice if you have references/links
pdflatex cv_diomidis_anadiotis_2025_v1.tex
```

### VS Code Integration

1. Install LaTeX Workshop extension
2. Open `.tex` file in VS Code
3. Use `Ctrl+Alt+B` (or `Cmd+Alt+B` on Mac) to build
4. Use `Ctrl+Alt+V` (or `Cmd+Alt+V` on Mac) to view PDF

### Version Control Workflow

```bash
# Create feature branch for CV updates
git checkout -b update-experience-section

# Edit CV content
# (VS Code LaTeX Workshop provides syntax highlighting and live preview)
vim cv_diomidis_anadiotis_2025_v1.tex

# Compile and review
latexmk -pdf cv_diomidis_anadiotis_2025_v1.tex
open cv_diomidis_anadiotis_2025_v1.pdf

# Commit changes
git add cv_diomidis_anadiotis_2025_v1.tex cv_diomidis_anadiotis_2025_v1.pdf
git commit -m "feat: Update experience section with latest role"

# Merge to main
git checkout main
git merge update-experience-section
```

## 🎯 Template Features

### Technical Specifications

- **Document Class**: Article with 11pt font
- **Page Layout**: Letter paper with optimized margins
- **Typography**: Linux Libertine font family for professional appearance
- **Colors**: Custom blue theme (`#005b96`) for section headers
- **Icons**: FontAwesome integration for contact information
- **Encoding**: UTF-8 with Unicode support for ATS compatibility

### LaTeX Packages Used

- `fullpage`, `titlesec`, `enumitem` - Layout and formatting
- `hyperref` - Clickable links and PDF metadata
- `fontawesome` - Professional icons
- `xcolor`, `geometry` - Color and page layout
- `libertine` - Professional typography
- `ragged2e` - Text justification

## 📄 License

[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](http://creativecommons.org/licenses/by-nc-nd/4.0/)

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

---

**Last Updated**: October 2, 2025  
