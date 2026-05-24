# CV Builder

A professional, browser-based CV/Resume builder with live preview, multiple templates, and PDF export. No server required — runs entirely in your browser.

**Live Demo:** [github.com/Aizondy](https://github.com/Aizondy)

---

## Features

- **Interactive Form** — Fill in personal info, work experience, education, skills, and languages through an intuitive form interface.
- **Live Preview** — See your CV update in real time as you type. No need to refresh or rebuild.
- **3 Professional Templates** — Choose between Modern, Classic, and Minimal designs to match your style.
- **PDF Export** — Download your finished CV as a high-quality A4 PDF with one click.
- **LocalStorage Persistence** — Your data is automatically saved in the browser. Come back anytime and pick up where you left off.
- **Fully Responsive** — Works on desktop, tablet, and mobile screens.
- **No Dependencies** — Pure HTML, CSS, and vanilla JavaScript. The only external library is `html2pdf.js` for PDF generation.

## How to Use

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/Aizondy/cv-builder.git
   cd cv-builder
   ```

2. **Open `index.html`** in your browser — no build step or server needed.

3. **Fill in your details** using the form on the left side:
   - Add your name, job title, contact information, and professional summary.
   - Click **"+ Add Experience"** to add work history entries.
   - Click **"+ Add Education"** to add your academic background.
   - Type a skill and press **Enter** to add it as a tag.
   - Click **"+ Add Language"** to list your language proficiencies.

4. **Choose a template** from the dropdown in the top-right corner.

5. **Export to PDF** by clicking the "Export PDF" button.

## Project Structure

```
cv-builder/
├── index.html        # Main HTML file
├── css/
│   └── style.css     # All styles and template themes
├── js/
│   └── app.js        # Application logic, state management, PDF export
└── README.md
```

## Technologies

- HTML5 / CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (ES6+)
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) — client-side PDF generation
- Google Fonts (Inter, Merriweather, Roboto Slab)

## License

MIT

---

Built by **Aizondy** | [github.com/Aizondy](https://github.com/Aizondy)
